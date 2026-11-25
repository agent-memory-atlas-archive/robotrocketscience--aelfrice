### Documentation

- **Transcript ingest doesn't use the triple extractor ([#112](https://github.com/robotrocketscience/aelfrice/issues/112)).** `docs/concepts/ARCHITECTURE.md` said that both the commit-ingest lane and the transcript-ingest lane use `triple_extractor.py`. Only the commit-ingest hook and the context rebuilder's query enrichment call it, and the module's docstring says that transcript ingest doesn't. The page now says that the commit-ingest lane uses it and transcript ingest doesn't.
