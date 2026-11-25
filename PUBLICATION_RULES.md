# Publication and CV Panel Rules

This file defines how to add or update publications in this Jekyll website. Follow these rules whenever a new paper is provided.

## Files and panels

- Add one Markdown record for each paper under `_publications/`.
- The Publications panel is rendered by `_pages/publications.html`.
- The CV panel is rendered by `_pages/cv.md`.
- Publication entries must use `_includes/archive-single.html`. This preserves the title, citation, paper, slides, and BibTeX links.
- CV publication entries must use `_includes/archive-single-cv-citation.html`, which displays the citation without a duplicate standalone title.
- The title inside the CV citation links to the publication page by default. Set `cv_title_url` when the title must link directly to a supplied PDF.
- Do not replace `archive-single.html` with `archive-single-cv.html` in the Publications panel; doing so removes download functions.

## Required publication metadata

Every publication record must contain:

```yaml
title: "Exact paper title"
collection: publications
category: manuscripts
cv_section: methodology       # methodology or collaboration
cv_status: published          # see status order below
permalink: /publication/unique-slug
date: YYYY-MM-DD
venue: 'Journal or publication venue'
paperurl: 'URL to the paper PDF'
citation: 'Complete citation with HTML formatting where needed'
```

Use the exact title and complete author wording supplied in the paper or citation source. Preserve special characters, capitalization, accents, en dashes, and the paper's punctuation.

For published papers, write every author in the citation; do not use `et al.`. Mark each confirmed corresponding author with `*`. Do not infer corresponding authors from author order. The CV panel includes the note `* denotes corresponding author`.

Add `excerpt` when a concise description is available. Add `bibtexurl` and `slidesurl` only when valid resources exist. Do not invent missing links.

## CV section assignment

Use exactly one of these values for `cv_section`:

- `methodology`: statistical methodology, modeling, algorithms, clustering, semiparametric methods, change-point methods, or related methodological work.
- `collaboration`: public health, epidemiology, infectious disease, long COVID, influenza, schistosomiasis applications, or other primarily applied health research.

In the CV panel, the visible subsection names are:

- `First-author publications & Manuscripts under review`
- `Statistics & Methodology (Co-authored)`
- `Public Health & Epidemiology (Co-authored)`

The underlying `cv_section` values remain `methodology` and `collaboration`.

## First-author publications

The first CV subsection is `First-author publications & Manuscripts under review`.

Set:

```yaml
cv_selected: true
```

only when Yewen Chen is the first author in the citation. These papers are displayed in the first-author subsection and excluded from the other two CV subsections, so they do not appear twice.

Do not set `cv_selected: true` when Chen Y is a middle author or a coauthor who is not first author. Papers without `cv_selected: true` remain in their assigned `cv_section`.

## Status and ordering

Set exactly one `cv_status` value. The CV and Publications panels use this order:

1. `peer_review`
2. `third_round_revision`
3. `second_round_revision`
4. `first_round_revision`
5. `accepted`
6. `published`

Use the status stated in the source paper or supplied publication information. Do not infer acceptance or publication status from the filename alone.

Within the `published` group, papers are displayed by publication year in descending order, newest first. Use the actual publication year in `date`; do not use the year of submission, revision, or online manuscript preparation unless that is the supplied publication date.

If a status group has no papers, leave it empty; do not create a placeholder entry.

## Panel layout and spacing

The Publications panel must retain its original download and citation behavior. Its entries use the original publication template and must not be converted to CV-only entries.

The CV panel currently uses these spacing rules:

```css
.cv-subsection-title {
  margin-top: 3em !important;
  margin-bottom: 0em !important;
}

.publication-item {
  margin-bottom: -1em !important;
}
```

The first subsection title uses `margin-top: 0.5em`; later subsection titles use `margin-top: 3em`. All subsection titles use `margin-bottom: 0em`, and `.cv-publications` uses zero top margin and padding.

Do not change article-to-article spacing when adding a paper unless explicitly requested. Do not add extra list wrappers or nested list elements that create large gaps or overlapping entries.

## Adding a paper checklist

1. Read the supplied PDF, BibTeX, or publisher information.
2. Confirm the exact title, complete author list, status, venue, publication year, DOI or paper URL, and first author.
3. Create one `_publications/*.md` record with all required metadata.
4. Assign `cv_section` and `cv_status`.
5. Add `cv_selected: true` only if Chen Y is first author.
6. Verify that `paperurl` points to the supplied paper and that optional links are real.
7. Confirm that the paper appears in the correct Publications subsection and CV subsection.
8. Confirm that a selected paper is not duplicated in Statistics & Methodology or Public health & Epidemiology.
9. Run `git diff --check`.
10. If Jekyll/Bundler is available, run `bundle exec jekyll build --trace`. If it is unavailable, report that the full build could not be run and perform structural metadata checks instead.

## Do not

- Do not remove `paperurl`, `bibtexurl`, or `slidesurl` when they are already present.
- Do not remove citation text or download links from existing records.
- Do not use `Papers Under Review` as a visible subsection.
- Do not use literal Markdown `###` headings inside `_pages/publications.html`; use HTML headings there.
- Do not modify unrelated biography, publication titles, author names, or existing paper metadata.
