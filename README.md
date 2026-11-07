# Engineering Talks Catalog

This repository holds the research digest team's curated engineering talks
collection. Each talk is stored as one catalog record (a GitHub issue) and
carries a long abstract, a topic label and a reference to an open-source project.

## Layout

- `catalog/collection.json` — the collection record. Its `item_count` field is
  the authoritative number of entries in the collection.
- Issues in this repository — one catalog record per talk. Each record starts
  with the `[T-xxx]` catalog identifier and includes `Catalog position`,
  `Topic` and `Referenced project` fields.
- `digests/` — published digests produced from the collection.

## Notes for digest authors

- The collection is larger than a single listing call can comfortably return;
  walk it to the end before filtering.
- Topics are labels on the records, but the `Topic` field in the body is the
  authoritative value.
- Some referenced projects have moved or been renamed since the talk was
  recorded. Resolve each reference through the code-hosting service and use the
  current canonical repository URL.
- When a talk mentions its project only in the abstract prose, use that
  reference.
