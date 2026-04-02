# Maintainer Guide

这个仓库的重点不是“放很多内容”，而是“让不同熟练度的人都有清晰入口”。

## 如何新增真实任务

1. 用 `.github/ISSUE_TEMPLATE/real-task.yml` 建 issue。
2. 复制 `real-work/templates/task-template.md`。
3. 放到 `real-work/backlog/`，命名为 `RW-XXX-short-title.md`。
4. 写清楚目标、交付物、完成标准和风险。

## 如何新增练习任务

1. 复制 `practice-lab/templates/exercise-template.md`。
2. 放到对应等级目录中。
3. 保证练习只关注一个核心动作。
4. 最好提供一个明确的修改目标文件。

## 如何判断结构是否健康

- 新手知道先去哪里开始
- 真实任务不会和练习内容混在一起
- reviewer 能快速判断任务状态
- 任务完成后能归档，避免目录越来越乱

