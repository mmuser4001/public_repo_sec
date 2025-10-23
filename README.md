# test-secrets-github-20251023-072844

This repository intentionally contains **fake, non-sensitive** values that *look* like secrets, to help test secret scanners.
Do **not** add any real credentials. Rotate immediately if you accidentally do.

## Quick start (manual push)
```bash
git init
git add .
git commit -m "Add fake secret samples"
git branch -M main
git remote add origin https://github.com/<your-username>/test-secrets-github-20251023-072844.git
git push -u origin main
```
