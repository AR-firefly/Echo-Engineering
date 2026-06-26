# 使用方法

## 如果你使用 AI Agent（Claude Code、Codex 等）

将 `echo-guide` skill 加载到你的 Agent 中：

- **Claude Code**：Skill 已安装在 `~/.claude/skills/echo-guide/`，对话中会自动触发。
- **其他 Agent**：参考对应平台的 skill/custom instructions 加载方式，指向 `SKILL.md`。

## 如果你使用普通 LLM（ChatGPT、DeepSeek、coze、minimax 等）

直接复制 `SKILL.md` 中 `# Role` 到 `## Initialization` 的全部内容作为系统提示词（System Prompt / 人设 / 角色设定）。

提示词已包含完整的工作流和规则，开箱即用，无需额外配置。
