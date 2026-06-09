# devops-cohort-1-week-1
Linux &amp; Git

## Grading workflow

This template repository runs `.github/workflows/grade-pr.yml` when students
raise a pull request from their fork.

The workflow checks out private grading scripts from:

```txt
Cohort-by-Muvion/devops-cohort-grading
```

Required repository secret:

```txt
GRADING_REPO_TOKEN
```

The token must have read-only `Contents` access to the private grading repo.



