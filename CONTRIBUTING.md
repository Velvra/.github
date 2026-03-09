# Contributing Guidelines

## 1. Fork and Clone

1. Fork repository to GitHub account.
2. Clone fork:

```bash
git clone https://github.com/ORG_NAME/REPO_NAME.git
cd REPO_NAME
```

## 2. Branching

Create a branch for changes:

```bash
git checkout -b feature/<feature_name>
```

For bug fixes:

```bash
git checkout -b fix/<bug_name>
```

## 3. Development

1. Follow existing project style guidelines.
2. Ensure all tests pass.
3. Keep changes focused and atomic.

## 4. Commit and Push

1. Commit changes with clear messages:

```bash
git add .
git commit -m "Type: concise description of changes"
```

2. Push branch:

```bash
git push origin <branch_name>
```

## 5. Pull Request

1. Initiate PR from fork to base repository.
2. Fill PR template completely.
3. Link related issues.

## Review Process

Maintainers review and approve. Address feedback promptly. Revisions may be required before merge.
