# ADSP Query History

Upload plain text query-history files here with names that start with `질의내역_` and end with `.txt`.

Examples:

- `질의내역_2026-06-14.txt`
- `질의내역_ADSP_오답노트.txt`

The daily ADSP Process Map updater imports these files, deduplicates them by file name and content hash, stages the questions from foundation to review, and stores the results in `data/adsp_query_history_db.json`.
