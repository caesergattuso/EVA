# EVA

这是一个面向中文团队的 GitHub 训练仓库。

它把“真实工作”和“新手练习”拆成两条线，方便团队一边做正式任务，一边做低风险训练，不会互相打扰。

## 这个仓库适合做什么

- 新成员入组训练
- GitHub 基础协作练习
- 测试、文档、流程类任务演练
- 让维护者统一管理任务、评审和归档

## 新人从哪里开始

1. 先看 [docs/newcomer-start.md](./docs/newcomer-start.md)
2. 再看 [CONTRIBUTING.md](./CONTRIBUTING.md)
3. 从 [practice-lab/README.md](./practice-lab/README.md) 开始做练习
4. 熟悉流程后，再去 [real-work/README.md](./real-work/README.md) 领取真实任务

## 仓库结构

```text
.
|- .github/
|  |- ISSUE_TEMPLATE/
|  `- pull_request_template.md
|- docs/
|  |- newcomer-start.md
|  |- workflow.md
|  `- maintainer-guide.md
|- real-work/
|  |- backlog/
|  |- in-progress/
|  |- review/
|  |- done/
|  `- templates/
|- practice-lab/
|  |- level-00-repo-tour/
|  |- level-01-first-edit/
|  |- level-02-branch-and-pr/
|  |- level-03-review-and-fix/
|  |- mentors/
|  `- templates/
|- CONTRIBUTING.md
`- SECURITY.md
```

## 两条线分别做什么

### `real-work/`

- 用于真实任务和实际交付
- 强调任务编号、完成标准、评审记录
- 推荐流转顺序：`backlog -> in-progress -> review -> done`

### `practice-lab/`

- 用于新人练习和带教训练
- 每一关只练一个核心动作
- 出错成本低，适合反复练习

## 重要入口

- 协作规则：[CONTRIBUTING.md](./CONTRIBUTING.md)
- 工作流说明：[docs/workflow.md](./docs/workflow.md)
- 维护者指南：[docs/maintainer-guide.md](./docs/maintainer-guide.md)
- 漏洞提报说明：[SECURITY.md](./SECURITY.md)

## 中文体验约定

- 目录名和文件名保持英文，方便协作和兼容工具
- 页面标题、步骤说明、模板字段尽量使用中文
- 术语统一使用：分支、提交、PR、评审、漏洞报告
- 文档统一保存为 UTF-8，减少乱码风险
