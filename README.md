# AI Knowledge Base

本项目是一个AI知识库，主要通过两个专门的agent来沉淀和整理AI相关知识：

## Agent 说明

### 1. ai-knowledge-miner
负责将 inbox 中的原始素材提炼为脱敏、结构化的知识文档，写入 knowledge/ 对应目录。当提到"提炼"、"沉淀"、"处理 inbox"、"knowledge miner"时自动适用。

### 2. ai-native-expert
AI Native 领域专家，聚焦 MaaS（Qwen/Wan/Claude/Gemini/GPT）和 AI Coding（Qoder/Kiro/Claude Code）。当询问模型能力、选型、API问题、竞品分析时自动适用。回答后自动产出 inbox 素材。

## 目录结构

- `inbox/` - 原始素材存放目录
- `arhive/` - 原始素材备份目录
- `knowledge/` - 结构化的知识文档目录，按不同AI领域和组织分类整理