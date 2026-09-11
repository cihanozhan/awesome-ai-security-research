# Contributing

Contributions must be written in English and support the archive's knowledge-focused scope.

## Propose a source

1. Search `data/resources.json` for the title, DOI, manuscript identifier, and alternate versions.
2. Provide a primary source link and its official English title.
3. Explain the threat model, research contribution, or learning value in one original sentence.
4. Select the narrowest relevant categories. Cross-list only when the source materially serves each category.
5. Identify its document type and confirmed source year. Do not infer peer review from an arXiv record.
6. Record the link-check date, evidence method, and any access restriction.
7. Update the central registry, affected reading lists, expanded README sections, and category counts together.

## Required entry fields

- `id`: stable, descriptive identifier.
- `title`: official English title.
- `url`: primary source URL.
- `type`: paper, survey, report, standard, guidance, dataset paper, benchmark paper, competition archive, or educational application as appropriate.
- `year` and `date_basis`: confirmed source year and what it represents; otherwise null.
- `reading_focus`: original English explanation of why the source is useful.
- `category_ids`: relevant category identifiers, with no repeats.
- `access_note`: any material restriction on reading the source.
- `verification`: check date, evidence URL, method, and direct retrieval result when tested.

## Review checklist

- The entry is knowledge-focused and comes from a primary source.
- The title, identifier, and link refer to the same work.
- A preprint, published version, PDF mirror, and code repository are not counted as separate papers.
- Each category contains each source only once.
- Every knowledge category still has at least 25 sources.
- Counts distinguish unique sources from cross-listed category entries.
- Descriptions state what to study without treating reported results as universal guarantees.
- Standards identify their editions; frameworks and community guidance are labeled accurately.
- Markdown links resolve to the intended local file or external source.
- All repository prose is in English.

Stand-alone security tools, commercial product lists, promotional content, and copied full-text documents are outside the scope. See [CURATION.md](CURATION.md) for detailed selection rules.
