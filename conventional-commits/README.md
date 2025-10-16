## Summary

This directory contains git hooks that I use in projects to enforce the [Conventional Commits](https://www.conventionalcommits.org) standard.

## Usage

1. In the root of your git repository, run:

```bash
cd .git/hooks/
```

2. Add the git hooks:

```bash
curl -H "Accept: application/vnd.github.v3.raw" -O -L https://api.github.com/repos/MofoJohnson/git-hooks/contents/conventional-commits/commit-msg
curl -H "Accept: application/vnd.github.v3.raw" -O -L https://api.github.com/repos/MofoJohnson/git-hooks/contents/conventional-commits/pre-push
curl -H "Accept: application/vnd.github.v3.raw" -O -L https://api.github.com/repos/MofoJohnson/git-hooks/contents/conventional-commits/prepare-commit-msg
```

3. The hooks are now added:

```bash
❯ ls
commit-msg
pre-push
prepare-commit-msg
```
