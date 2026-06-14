# MegaMind Working Paper Guide

## Naming Conventions

Store public research PDFs in:

`papers/`

Use lowercase, hyphenated filenames for both HTML Working Paper pages and PDF files:

- `stop-rediscovering-texas.html`
- `stop-rediscovering-texas.pdf`
- `the-earl-problem.pdf`
- `powerpoint-as-critical-infrastructure.pdf`
- `executive-confidence-as-a-leading-indicator-of-unknown-problems.pdf`
- `everything-is-a-graph-an-introductory-apology.pdf`

Do not use spaces, dates, draft numbers, or punctuation in filenames unless there is a strong archival reason.

## Adding New Working Papers

1. Create a dedicated HTML Working Paper page at the site root.
2. Preserve the Working Paper text in semantic HTML.
3. Export the matching PDF.
4. Place the PDF in `papers/`.
5. Add one Working Paper card to `papers.html`.
6. Include title, status, abstract, Working Paper date, primary read action, PDF download action, and related concepts.
7. If the Working Paper is not yet available, show `Working Paper Pending`.

## Linking Working Papers

When a Working Paper exists, use the HTML page as the primary action and the PDF as the secondary action:

```html
<a class="button button-primary" href="example-working-paper.html">Read Working Paper</a>
<a class="button button-secondary" href="papers/example-paper.pdf" download>Download PDF</a>
```

When the Working Paper does not exist, use:

```html
<span class="paper-pending">Working Paper Pending</span>
```

## Working Paper Workflow

Recommended status values:

- Draft
- Working Paper
- Field Report
- Published
- Archive
- Candidate Formalism

Workflow:

1. Field Notes identify recurring observations.
2. Case Files reconstruct evidence.
3. Working Papers preserve generalized lessons in hosted HTML form.
4. PDFs remain available as downloadable versions of the Working Paper record.

## Maintenance Notes

Keep `papers.html` as a Working Papers archive, not a commentary page.

Field Notes may remain more informal. Case Files should remain evidence-focused. Working Papers should stay professional, readable in the browser, downloadable, and citation-friendly.
