# EVA

This repository is set up as a training workspace for team collaboration and onboarding.

It is split into two main areas:

- `real-work/`: real tasks, delivery requirements, review flow, and archived results.
- `practice-lab/`: low-risk exercises for beginners to practice common GitHub workflows.

## When To Use It

- onboarding new team members
- practicing GitHub basics
- separating real work from beginner exercises
- giving maintainers a consistent issue and PR entry point

## Recommended Path

1. Start with the exercises in `practice-lab/`.
2. Complete at least one edit, one follow-up update, and one review fix through PRs.
3. After that, move into `real-work/backlog/` to pick up real tasks.

## Repository Structure

```text
.
├─ .github/
│  ├─ ISSUE_TEMPLATE/
│  └─ pull_request_template.md
├─ docs/
├─ real-work/
│  ├─ backlog/
│  ├─ in-progress/
│  ├─ review/
│  ├─ done/
│  └─ templates/
├─ practice-lab/
│  ├─ level-00-repo-tour/
│  ├─ level-01-first-edit/
│  ├─ level-02-branch-and-pr/
│  ├─ level-03-review-and-fix/
│  ├─ mentors/
│  └─ templates/
└─ CONTRIBUTING.md
```

## The Two Tracks

### `real-work/`

- for real delivery work
- uses task IDs, done criteria, and review records
- suggested flow: `backlog -> in-progress -> review -> done`

### `practice-lab/`

- for beginner practice and onboarding
- each level focuses on one core collaboration action
- safe to repeat and safe to make mistakes in

## Start Here

- contributors: [CONTRIBUTING.md](./CONTRIBUTING.md)
- workflow guide: [docs/workflow.md](./docs/workflow.md)
- beginner entry: [practice-lab/README.md](./practice-lab/README.md)
- maintainer guide: [docs/maintainer-guide.md](./docs/maintainer-guide.md)
