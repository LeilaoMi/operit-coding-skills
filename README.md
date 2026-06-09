# Operit Coding Skills

一组面向 Operit / AI Agent 的中文编程工程增强 Skill，覆盖代码库阅读、代码审查、Bug 修复、测试生成、重构、安全审计、DevOps 部署和 Skill/MCP 开发。

## Skills

| Skill | 中文名 | 用途 |
|---|---|---|
| codebase-reader | 代码库阅读助手 | 分析项目结构、技术栈、入口文件、模块职责和代码阅读路线 |
| code-reviewer | 代码审查官 | 审查代码质量、逻辑漏洞、性能问题、安全风险和可维护性 |
| bug-fixer | Bug定位与修复助手 | 解析报错日志、定位根因、给出最小修复补丁和验证方案 |
| test-engineer | 测试工程师 | 生成单元测试、接口测试、边界用例、回归测试和验证方案 |
| refactor-architect | 重构架构师 | 在保持功能不变的前提下拆分模块、降低耦合、提升可维护性 |
| security-code-auditor | 安全代码审计员 | 检查注入、越权、XSS、路径穿越、命令执行、敏感信息泄露等风险 |
| devops-engineer | DevOps部署助手 | 处理 Docker、Nginx、systemd、CI/CD、服务部署和日志排查 |
| skill-mcp-developer | Skill/MCP开发助手 | 创建和调试 Operit Skill、MCP 工具、插件配置和工具参数 schema |

## Repository Structure

```text
skills/
  codebase-reader/
  code-reviewer/
  bug-fixer/
  test-engineer/
  refactor-architect/
  security-code-auditor/
  devops-engineer/
  skill-mcp-developer/
```

## Install

在 Operit 中导入对应 Skill 目录，或使用本项目中的 `SKILL.md` / `DISPLAY.json` 创建本地 Skill。

## License

MIT