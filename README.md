# 研究前置协议

![GitHub stars](https://img.shields.io/github/stars/ninggui/research-first-protocol)
![License](https://img.shields.io/github/license/ninggui/research-first-protocol)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/research-first-protocol)

触发词"你研究一下/学习一下/联网搜索一下"时，先通盘研究再给方法论。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| 触发词识别 |
| 全量信息获取与提炼 |
| 方法论框架输出 |
| 落地动作沉淀 |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/research-first-protocol

## 优势

- 防止拍脑袋回答
- 与自主学习/定时任务兼容
- 研究产出文档化

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
