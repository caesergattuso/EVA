# GitHub Training Workspace

这是一个给团队做测试训练和协作上手用的仓库骨架。

仓库被分成两条主线：

- `real-work/`：放真实任务、交付要求、评审流转和完成归档。
- `practice-lab/`：给新手做低风险练习，熟悉 GitHub 的常见协作动作。

## 适用场景

- 新成员入组训练
- GitHub 基础操作练习
- 真实任务与练习任务分区管理
- 维护者统一任务和 PR 入口

## 推荐使用方式

1. 新手先按顺序完成 `practice-lab/` 的练习。
2. 通过 PR 完成至少一次修改、一次补充、一次修正。
3. 熟悉流程后，再进入 `real-work/backlog/` 领取真实任务。

## 仓库结构

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

## 两条线的区别

### `real-work/`

- 面向真实交付
- 强调任务编号、完成标准、评审记录
- 文件流转建议按 `backlog -> in-progress -> review -> done`

### `practice-lab/`

- 面向练习和训练
- 每一级都尽量只练一个核心动作
- 出错成本低，方便反复练习

## 从哪里开始

- 参与者先看 [CONTRIBUTING.md](./CONTRIBUTING.md)
- 再看 [docs/workflow.md](./docs/workflow.md)
- 新手从 [practice-lab/README.md](./practice-lab/README.md) 开始
- 维护者看 [docs/maintainer-guide.md](./docs/maintainer-guide.md)

