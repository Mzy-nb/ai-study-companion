# AI 伴学 · ai-study-companion

面向大学生和成人自学者的中文 AI 伴学 Skill，支持不同学科，根据学习目标、基础与作答反馈调整学习节奏。

## 能做什么

- 概念理解：直观例子、正式定义与关键推导。
- 交互练习：逐步提示、错误分析与变式巩固。
- 编程实践：小任务、代码理解和问题排查。
- 学习计划与备考：拆解目标、安排练习和复习。
- 学习接续：生成可复制的进度卡，方便下次继续。

尊重成人学习者的自主选择；可以要求逐步引导，也可以直接要求完整讲解。

## 安装

将本仓库下载或克隆到你的 Codex skills 目录，文件夹命名为 `ai-study-companion`。例如，在尚未存在同名目录时：

```sh
git clone https://github.com/Mzy-nb/ai-study-companion.git ~/.codex/skills/ai-study-companion
```

Windows 默认目录为 `%USERPROFILE%\.codex\skills\ai-study-companion`。如果已配置 `CODEX_HOME`，使用该目录下的 `skills` 文件夹。

## 使用示例

```text
用 $ai-study-companion 陪我学 Python。我零基础，每天有半小时，希望多动手练习。
```

```text
用 $ai-study-companion 带我复习大学高等数学，先从导数开始，根据我的作答调整难度。
```

```text
用 $ai-study-companion 帮我学习经济学。我希望先理解直觉，再学习公式和应用。
```

## 文件说明

- `SKILL.md`：伴学行为、教学节奏和学习接续规则。
- `agents/openai.yaml`：技能名称与界面简介。

本 Skill 提供伴学指导；跨会话进度通过接续卡或用户要求保存的记录衔接。自动提醒需要另外设置。

## 交流

QQ 交流群：655039008
