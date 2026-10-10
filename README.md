# oi-memory

Memory subsystem for Oi — retrieval, extraction and pluggable storage for agent
long-term memory.

Part of [Oi](https://github.com/akankofik-dev/Oi); used via a git pin, not published on PyPI.

## Install

```bash
pip install "git+https://github.com/akankofik-dev/oi-memory.git@v1.0.0"
```

From the Oi checkout it is declared in `[tool.uv.sources]`, so `uv sync` resolves it.

## What's inside

| Module | Purpose |
|---|---|
| `oi_memory.ports` | Storage and LLM ports |
| `oi_memory.pipeline` | Extraction and retrieval pipeline |
| `oi_memory.operations` | Import, export and migration |

## Storage backends

Core installs no backend. Pick one via extras: `qdrant`, `chroma`, `postgres`,
`langgraph-postgres`, or `embeddings` for local sentence-transformers.

## Provenance

Modul `oi_memory` dari distribusi `oimemory`.
Wheel upstream tidak menyertakan file lisensi atau copyright header;
pemberitahuan MIT yang didistribusikan direproduksi di [LICENSE](LICENSE).

## License

MIT — see [LICENSE](LICENSE).