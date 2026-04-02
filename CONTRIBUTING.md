# Contributing Guide

这个仓库把“练习”和“真实任务”拆开管理，请按对应流程参与。

## 分支命名建议

- 练习任务：`practice/<your-name>-<level>`
- 真实任务：`task/<task-id>-<short-name>`
- 文档修订：`docs/<short-name>`

## Commit 建议

尽量让 commit 一次只表达一件事，例如：

- `docs: add self introduction for level 01`
- `practice: finish level 02 team skills update`
- `task: start RW-001 onboarding cleanup`

## Pull Request 基本要求

- 说明本次属于 `practice-lab` 还是 `real-work`
- 写清楚改了什么
- 写清楚怎么验证
- 如果有未完成项，直接写出来

## 真实任务认领规则

1. 先从 `real-work/backlog/` 选择任务。
2. 把任务移到 `real-work/in-progress/` 或在任务文件里注明认领人。
3. 完成后进入评审，再归档到 `real-work/done/`。

## 新手练习规则

1. 按 `practice-lab` 的关卡顺序做。
2. 每次练习只聚焦一个动作，不要一次改太多文件。
3. 收到 review 后，至少完成一次修正再合并。

## 不建议的做法

- 在 `practice-lab` 里直接改真实任务文件
- 跳过 PR 直接提交到主分支
- 同时认领多个真实任务但没有交付计划
- 修改他人的进行中文件而没有提前沟通

