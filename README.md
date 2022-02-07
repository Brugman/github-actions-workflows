# GitHub Actions Workflows

A collection of tested workflows that you can customize and combine.

This repo is about `/.github/workflows/`, all other files are for testing.

Task | Method | Avg Duration (s)
:--- |:--- |---:
Build | npm | 32
Build | yarn | 37
Build | pnpm | 27

Task | Method | Avg Duration (s) | Auth
:--- |:--- |---: |:---
Deploy | ftp | 19 | ftp pass
Deploy | ftps | 19 | ftp pass
Deploy | scp | 27 | ssh pass
Deploy | rsync | 16 | ssh key

Avg Duration was measured by taking the average of 5 runs. Much science.

