# Contributing

Thanks for helping improve **Awesome Video World Models**. We welcome relevant
papers, bibliographic corrections, and suggestions for clearer category placement.

## Suggest a paper

Search the [current list](README.md) first, then use the
[paper suggestion form](https://github.com/vid-gen/awesome-video-world-model/issues/new?template=new-paper.yml).
Provide the exact title, author information, venue and year, a stable source URL,
the best matching category, and a short explanation of the contribution.

The collection is curated rather than exhaustive. Prefer substantive work on video
foundation models, world models, or closely related datasets and evaluation. List
the most complete or authoritative version of a work once.

## Categories

- **Reading the World** — video comprehension, perception, representations,
  video-language models, long-video reasoning, streaming, and video agents.
- **Writing the World** — video generation, synthesis, tokenizers, controllability,
  editing, and audio-video generation.
- **Sharing the World** — unified understanding, generation, and editing.
- **Interacting with the World** — predictive dynamics, action-conditioned and
  interactive environments, memory, planning, robotics, and driving.
- **Datasets, Benchmarks and Evaluation** — training data, task benchmarks,
  quality metrics, and world-model or decision evaluation.
- **Surveys and Foundations** — surveys, conceptual foundations, and general
  modeling methods.

Choose a work's main contribution when it spans multiple areas.

## Submit a pull request

Add a bullet directly to `README.md`, using the existing format:

```markdown
- [Paper title](https://paper-or-official-project-url) — First Author et al. *Venue, year*.
```

Keep entries ordered by year, newest first, and alphabetically by title within a
year. Update the category and total counts when adding or removing entries.

For source links, prefer a publisher landing page, DOI, ACL Anthology, OpenReview,
arXiv abstract page, or official project page. Use authoritative metadata for any
BibTeX entry added to `references.bib`. Avoid search-results URLs.

Keep the matching record in `data/references.json` synchronized with the bullet
and BibTeX entry. This is public bibliographic metadata only; do not add local
source paths, editorial notes, or unpublished manuscript files. Category keys are
`understanding`, `generation`, `unified`, `world-models`, `evaluation`, and
`background`, respectively.

The companion website lives in
[`vid-gen/video-world-model-survey`](https://github.com/vid-gen/video-world-model-survey).
Maintainers can update its catalog snapshot and bibliography with the sync command
documented there. Readers do not need to install or run anything.

Explain corrections in the pull-request description, especially if multiple
versions have different titles, dates, or publication venues.
