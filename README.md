# AI Knowledge Base

本项目是一个 AI 知识库，主要通过两个专门的 agent 来沉淀和整理 AI 相关知识：

## Agent 说明

### 1. ai-knowledge-miner
负责将 `inbox/` 原始素材与 `notes/` 长期笔记提炼为脱敏、结构化的知识文档，写入 `knowledge/` 对应目录。优先合并到现有文档避免重复创建。当提到"提炼"、"沉淀"、"处理 inbox"、"knowledge miner"时自动适用。

### 2. ai-native-expert
AI Native 领域专家，聚焦 MaaS（Qwen/Wan/Claude/Gemini/GPT/DeepSeek）和 AI Coding（Qoder/Kiro/Claude Code）。对于模型对比、benchmark、产品集成关系等事实问题必须基于官方文档 / 技术报告等一手来源回答，禁止仅凭知识库交付。回答后自动产出 inbox 素材。

## 目录结构

- `inbox/` - 原始素材存放目录（一次性，提炼后自动归档）
- `notes/` - 长期维护的个人笔记目录（如 Daily note，提炼后保留原文件）
- `archive/` - 原始素材备份目录
- `knowledge/` - 结构化的知识文档目录，按不同 AI 领域和组织分类整理
- `index.md` - 知识库全局索引（Skill 必读）
