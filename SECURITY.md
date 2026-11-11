# 安全说明 / Security Policy

## 中文

### 报告安全问题

请**不要**开公开 issue。改用 GitHub 的「Security → Report a vulnerability」（私密报告），或直接发邮件给仓库所有者（见 GitHub 个人主页的联系方式）。

请在报告里写清：受影响的文件与行号、复现步骤、可能的影响。

### 这个项目会碰到你机器上的什么

本 skill 的作用是**指导**（它自己不执行命令），但它会让你在自己的机器上执行文件操作。请注意这些边界：

- 它会让你**读取并可能覆盖**你自己 agent 的 skills 目录里的文件。**覆盖前务必备份或提交版本控制。**
- 它默认你**自己**执行所有写操作；本项目**不提供**任何自动安装脚本。
- 本项目**不收集**任何数据，**不联网**，**不含**任何密钥或令牌。

### 支持范围

这是个人项目，没有承诺的修复时限。安全问题的处理优先级最高。

## English

Please do **not** open a public issue for security problems. Use GitHub's "Security → Report a vulnerability" (private advisory) or email the repository owner.

Include: affected file and line, reproduction steps, and potential impact.

This skill is guidance only — it does not execute commands itself, but it instructs you to modify files under your own agent's skills directory. **Back up or version-control that directory before overwriting anything.** The project collects no data, makes no network calls, and contains no secrets.

Support is best-effort; security reports are prioritised.
