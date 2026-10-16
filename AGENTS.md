# Agent guide

This repository is a curated collection of quantitative research papers. Keep the PDFs easy to find and preserve their original contents.

## Adding or organizing papers

1. Read the first page to confirm the paper's actual title. Do not rely on the downloaded filename or PDF metadata alone.
2. Put each PDF in the folder matching its primary topic. Reuse an existing folder when appropriate.
3. Name the file with the full title in uppercase ASCII letters, using underscores between words and a lowercase `.pdf` extension. Remove punctuation that is unsafe or awkward in paths.
4. If two PDFs share a title, append `__` and a short uppercase source or version label before `.pdf`. Preserve both versions.
5. Add or update the paper's entry in `README.md`. Keep its link relative and record the original filename in the `Tên gốc` column.

## Checks before committing

- Confirm every PDF opens and every README link resolves.
- Confirm PDF stems are uppercase and no two files share a path.
- Preserve PDF bytes when only renaming or moving files. Compare SHA-256 hashes before and after such moves.
- Keep `*.pdf binary` in `.gitattributes` so Git treats PDFs as binary files.
- Do not change a paper's content or embedded metadata solely to make its filename consistent.
