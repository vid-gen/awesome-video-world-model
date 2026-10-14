# Contributing

Thanks for helping improve **Awesome Video World Models**. We welcome relevant
papers, bibliographic corrections, and suggestions for clearer category placement.

## Suggest a paper

Search the [current list](README.md) first, then use the
[paper suggestion form](https://github.com/vid-gen/awesome-video-world-model/issues/new?template=new-paper.yml).
Provide the exact title, author information, venue and year, a stable source URL,
the best matching category, and a short explanation of the contribution. Include
official code, project, or dataset links when available.

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

Add a bullet directly to `README.md` under the appropriate category and year.
Use a plain-text title, separate resource links, and an 18-pixel venue badge:

```markdown
- Paper title. [[paper](<https://paper-url>)] [[code](<https://official-code-url>)] [[project](<https://official-project-url>)] <img src="assets/readme/venues/cvpr.svg" alt="CVPR" title="IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2026" height="18">
```

Replace the example URLs and venue/year with the work's actual metadata. Omit
unavailable resource links; never leave placeholders or guess a repository from a
model name. Add `[data]` only for an actual released dataset, not model weights.
Use `[source]` for official web reports and `[book]` for book landing pages. If the
only source is an official code repository, label that link `[code]`.

Keep entries ordered by year, newest first, and alphabetically by title within a
year. Preserve exact titles, and avoid an extra period after `?` or `!`. Full author
lists belong in the bibliographic data and BibTeX, rather than in the compact
README bullets. Update category/total counts, navigation-card counts, and year
anchors when adding or removing entries.

Reuse a matching SVG from `assets/readme/venues/`. Badge colors distinguish
conferences, journals, preprints, reports/official sources, and books; they do not
indicate quality or acceptance status. Use the verified publication venue, not
the site hosting a PDF. Do not replace a preprint label with a conference label
without publisher or author confirmation.

For source links, prefer a publisher landing page, DOI, ACL Anthology, OpenReview,
arXiv abstract page, or official project page. Use authoritative metadata for any
BibTeX entry added to `references.bib`. Avoid search-results URLs.

Keep the matching record in `data/references.json` synchronized with the bullet
and BibTeX entry. Supplemental links go in an optional `resources` object, with
`code`, `project`, and/or `data` URL fields. Verify these against the paper or an
author-maintained page, and link to the matching release when a repository hosts
several versions. The primary `url` field remains the paper's source link.

Keep the corresponding entry in `data/resource-verification.json` synchronized.
Record the author/paper source for each resource and any version-specific branch,
directory, or snapshot. A repository with only a release announcement, images,
or a “coming soon” README is not released code. Author-owned forks can be valid
when the paper explicitly links them; an unrelated fork or third-party
reimplementation is not an official resource. An unverified entry is left blank
in the reading list; it does not assert that no resource exists.

This is public bibliographic metadata only; do not add local
source paths, editorial notes, or unpublished manuscript files. Category keys are
`understanding`, `generation`, `unified`, `world-models`, `evaluation`, and
`background`, respectively.

The companion website lives in
[`vid-gen/video-world-model-survey`](https://github.com/vid-gen/video-world-model-survey).
Maintainers can update its catalog snapshot and bibliography with the sync command
documented there. Readers do not need to install or run anything.

Explain corrections in the pull-request description, especially if multiple
versions have different titles, dates, or publication venues.
