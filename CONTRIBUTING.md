# 参与贡献 / Contributing

## 中文

这是一个把「skill 变更流程」写成可执行步骤的小项目。欢迎提 issue 和 PR。

**提 issue 前**，请先说明三件事：

1. 你用的是哪个 agent（Claude Code / Codex / Cursor / pi / 其他），版本是多少；
2. 你按 README 走到第几步出的问题，**贴出命令与原始报错**（截图或文字都行）；
3. 你期望看到什么、实际看到了什么。

**提 PR 时**：

- 保持正文里的**通用性**：不要写死任何人的本机路径、内网地址、组织名称。用 `<你的 skills 目录>` 这类占位符。
- 如果你的改动只适用于你自己的环境，请写在 `local/` 下并确认它在 `.gitignore` 里，不要改进正文。
- 改了正文，请同时在 `CHANGELOG.md` 加一行，写清「改了什么、为什么」。

**我不保证响应时间**。这是个人项目，不是商业支持。

## English

Issues and pull requests are welcome.

Before opening an issue, please include: (1) which agent you use and its version; (2) the exact step in the README where it broke, with the command and raw error output; (3) what you expected vs. what happened.

When opening a PR: keep the text generic — no personal paths, internal hostnames, or organization names (use placeholders such as `<your skills directory>`). Machine-specific tweaks belong in `local/` (git-ignored), not in the main text. Add a line to `CHANGELOG.md` describing what changed and why.

This is a personal project; responses are best-effort.
