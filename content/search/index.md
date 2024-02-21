---
title: Search
hidden: true
versions:
  fpt: '*'
  ghec: '*'
  ghes: '*'
---

# Search all versions available on your platform:
mamba repoquery search gh --channel conda-forge

# List packages depending on `gh`:
mamba repoquery whoneeds gh --channel conda-forge

# List dependencies of `gh`:
mamba repoquery depends gh --channel conda-forge![Screen Shot 2016-12-01 at 20 10 39](https://github.com/github/docs/assets/116414081/e79e2839-ff77-46d4-afa5-d5f11811bb7b)
