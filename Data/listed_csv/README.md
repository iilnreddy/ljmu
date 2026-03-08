# Data

This folder is intended for storing CSV files used by the project.

Guidelines
- File types: .csv (plain comma-separated values).  
- Naming convention (recommended): `description_YYYYMMDD.csv` or `description_v1.csv` (use lowercase and underscores). Example: `sales_20251227.csv`.
- Sensitive data: Do NOT commit CSVs that contain secrets, personally identifiable information (PII), or confidential records. If you must keep such files, store them outside the repository or use a secure data store.
- Large files: If CSVs are large (>50 MB), consider using Git LFS or an external data store (S3, Google Cloud Storage, etc.) rather than committing them to the repo.
- If you prefer CSVs not to be versioned in Git, add `Data/*.csv` to `.gitignore`.

If you want the repository to track CSVs, do not add `Data/*.csv` to `.gitignore`.
If you want CSVs ignored, add the following to `.gitignore`:

```
# Ignore CSVs in Data folder
Data/*.csv
```
