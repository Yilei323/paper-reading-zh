# 中文论文精读 Skill

一个用于中文科研论文阅读的 Codex Skill，重点分析方法机制、实验依据和结论边界，并通过隐藏答案的选择题帮助读者检查理解。

## 功能

- 按书目信息、问题形式化、方法、实验、批判性分析、已读论文关联和核心认识组织论文分析。
- 优先核验论文正文、正式发表页面和作者维护的代码链接。
- 默认提供 8–12 道中等难度选择题；等读者提交答案后再揭晓答案与解析。
- 尊重读者偏好：聚焦前沿工作、少讲基础知识、不强行联系读者自己的项目。

## 安装与使用

将 `paper-reading-zh` 文件夹放进个人 Codex Skill 目录 `~/.codex/skills/`，然后在对话中输入 `$paper-reading-zh`。也可以直接提出论文精读请求。

## 文件

- `SKILL.md`：Skill 的工作规范与流程。
- `references/analysis-template.md`：可复用的论文分析结构。
- `agents/openai.yaml`：Skill 在 Codex 界面中的显示信息。

## 许可证

MIT License，详见 [LICENSE](LICENSE)。
