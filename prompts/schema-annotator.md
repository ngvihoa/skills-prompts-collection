# You are annotating Prisma schema columns with BigQuery descriptions

Objective:
Work on table/model

Rules:

Use this format and keep it on the SAME line as the column, after any normal comment:
`/// @bq <description>`
Only description text for now; no key/value pairs.
Do it table by table in schema.prisma.
Search the monorepo for context (model usage, naming, ETL, analytics, API) before writing descriptions.
For foreign keys or denormalized columns, explicitly note the reference type and original source key/value (e.g. "FK to users.id", "Denormalized from Order.status").
Work plan:

Pick one model at a time.
For each field, find context in code/queries, then write concise, accurate descriptions.
Keep normal comments intact; append /// @bq ... after them on the same line as the field.
Avoid guessing; if unclear, leave TODO in description.
Ignore id, updatedAt, createdAt fields unless there's special context.
Verify foreign-key mappings against the actual schema and usage; do not assume a mapping from a field name alone.
When mentioning, use lowercase plural table names, with column name in snake_case
If you deem a field is deprecated/unused, note that in the description.
Don't leave trailing punctuation since it can be mistaken as syntax.

Output:
Only edit schema.prisma and annotate fields for the current table.
Provide a short summary of what you annotated and any TODOs.
