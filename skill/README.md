# COROS MCP Skills

[中文](../README.md) | [English](../README.en.md)

本目录用于存放将 AI Agent 或本地客户端连接到 COROS MCP 的 Agent Skill 模块。

This directory contains Agent Skill modules for connecting AI agents and local clients to COROS MCP.

## Available Skills / 可用 Skill

| Skill | 说明 / Description |
| --- | --- |
| [`coros_mcp_login_gateway`](coros_mcp_login_gateway/) | 通过 `mcp.coros.com` 网关完成 COROS MCP 登录、CN/EU/US 区域发现，并帮助配置 OpenClaw。<br>Enters through `mcp.coros.com`, completes COROS MCP login, discovers the selected CN/EU/US region, and helps configure OpenClaw. |

## Usage / 使用

打开具体 Skill 目录查看详细说明：

Open the skill directory for detailed instructions:

```text
skill/coros_mcp_login_gateway/
```

Agents that support skills can read the skill's `SKILL.md` file and use its helper script to log in, refresh local auth state, list tools, and configure OpenClaw.

支持 Skill 的 Agent 可以读取其中的 `SKILL.md`，并使用辅助脚本完成登录、刷新本地授权状态、列出工具以及配置 OpenClaw。
