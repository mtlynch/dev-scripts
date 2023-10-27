# dev-scripts

[![License](https://img.shields.io/badge/license-Unlicense-blue)](LICENSE)

This is my collection of dev scripts that I tend to re-use in a lot of projects.

Feel free to use them if they're useful to you.

## Meta scripts

### `update-scripts`

Updates `dev-scripts` in a Github repo, replacing all the available scripts with the latest versions in the `mtlynch/dev-scripts` repo.

The script only replaces files that exist in the local repo. For example, if your repo doesn't have a file at the path `dev-scripts/check-go-formatting`, then `update-scripts` won't place this file in your repo.

```bash
cd other-project
curl \
  https://raw.githubusercontent.com/mtlynch/dev-scripts/master/update-scripts \
  | bash
```
