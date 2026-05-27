# 知识库全局索引

> 本文件是知识库的全局索引，Skill 必读。
> 最后更新：2026-05-27（修复 ai-app 路径笔误为 ai-application）

## 道：AI 领域知识（跨厂商）

### AI General Notes

**🛠️ 技术概念类**（适合关键选型维度）：
- [Agent](ai-general-notes/agent-def.md) ⭐ — for循环本质、Model+Harness框架、Agent平台战略拐点、OpenAI三大优先级
- [Harness](ai-general-notes/harness.md) ⭐ — 企业战略级资产、约束治理层、Harness vs Prompt区别、调用层容量与限流治理（多账号扩 TPM、客户端拥塞拐点）
- [Prompt Engineering](ai-general-notes/prompt-engineering.md) ⭐ — 防幻觉四层机制、第一性原理、博弈论应用
- [RAG](ai-general-notes/rag.md) — 待填充
- [Fine-tuning](ai-general-notes/fine-tuning.md) — 待填充

**💡 概念洞察类**（适合关键认知框架）：
- [AI能力边界与迭代部署](ai-general-notes/ai-capability-and-deployment.md) ⭐ — 锯齿状能力边界、迭代部署哲学、Personal AGI终局

## 点：单产品知识

### 阿里云
- MaaS: [百炼平台](alibaba-cloud/maas/overview.md) — UID 级限流机制、多账号扩 TPM 方案（8.5× 实测验证）、deepseek-v4-flash 压测踩坑 | [Qwen](alibaba-cloud/maas/qwen.md) | [万相](alibaba-cloud/maas/wan.md) | [Qwen3.6](alibaba-cloud/maas/qwen3.6.md)
- AI Coding: [Qoder](alibaba-cloud/ai-coding/qoder.md)
- AI App: [QoderWork](alibaba-cloud/ai-application/qoder-work.md) | [龙虾家族（HiClaw/QwenPaw/百炼龙虾/PolarClaw/AgentBay）](alibaba-cloud/ai-application/claw-family.md) | [JVS Crew](alibaba-cloud/ai-application/jvs-crew.md)
- AI Platform: [PAI](alibaba-cloud/ai-platform/pai.md)
- AI Infra：[ECS GPU](alibaba-cloud/ai-infra/ecs-gpu.md) | [灵骏](alibaba-cloud/ai-infra/lingjun.md) | [GPU 产品线选型](alibaba-cloud/ai-infra/gpu-product-line.md) ⭐

### AWS
- MaaS: [Bedrock](aws/maas/overview.md) | [Claude](aws/maas/claude.md) | [Titan](aws/maas/titan.md)
- AI Coding: [Q Developer](aws/ai-coding/q-developer.md) | [Kiro](aws/ai-coding/kiro.md)
- AI App: [Q Business](aws/ai-application/q-business.md)
- AI Platform: [SageMaker](aws/ai-platform/sagemaker.md)
- AI Infra: [EC2 GPU](aws/ai-infra/ec2-gpu.md) | [Trainium](aws/ai-infra/trainium.md) | [Inferentia](aws/ai-infra/inferentia.md)

### GCP
- MaaS: [Model Garden](gcp/maas/overview.md) | [Gemini](gcp/maas/gemini.md) | [Imagen](gcp/maas/imagen.md)
- AI Coding: [Gemini Code Assist](gcp/ai-coding/gemini-code-assist.md)
- AI App: [Gemini for Workspace](gcp/ai-application/gemini-workspace.md)
- AI Platform: [Vertex AI](gcp/ai-platform/vertex-ai.md)
- AI Infra: [TPU](gcp/ai-infra/tpu.md)

### Anthropic
- MaaS: [Claude API](anthropic/maas/claude-api.md)（Opus / Sonnet / Haiku）
- AI Coding: [Claude Code](anthropic/ai-coding/claude-code.md)
- AI App: [Claude Teams](anthropic/ai-application/claude-teams.md) | [Claude Managed Agents](anthropic/ai-application/claude-managed-agents.md)

### MiniMax
- 公司分析: [MiniMax 公司分析报告](minimax/general_intro.md) — 2026.01 港股 IPO（00100.HK）、海螺 AI / Talkie 全球化、MiniMax-M1/M2 开源混合注意力

### 智谱 AI（Zhipu）
- 公司分析: [智谱 AI 公司分析报告](zhipu/general_intro.md) — 2026.01 港股 IPO（02513.HK，全球大模型第一股）、GLM-5 编程开源 SOTA、MaaS ARR 17 亿元

### DeepSeek（深度求索）
- 公司分析: [DeepSeek 公司分析报告](deepseek/general_intro.md) ⭐ — MLA+MoE 架构创新、R1 纯 RL 推理、V4 开源 SOTA、557万美元训练成本、“DeepSeek 时刻”

## 线：对比分析（阿里云视角）

- [阿里云 vs AWS](alibaba-cloud/competitive-analysis/alibaba-vs-aws/overview.md)
- [阿里云 vs 火山引擎](alibaba-cloud/competitive-analysis/alibaba-vs-volcengine/overview.md)
- [Qoder vs Kiro](alibaba-cloud/competitive-analysis/qoder-vs-kiro/overview.md)
- [Qoder vs Trae](alibaba-cloud/competitive-analysis/qoder-vs-trae/overview.md) ⭐ — 企业级 vs 个人开发者定位差异

## 体：行业解决方案

- [IPC 智能安防](solutions/vertical-ipc/overview.md)
- [短剧出海](solutions/vertical-short-drama/overview.md)
- [商业地产](solutions/commercial-real-estate/overview.md) — AI 应用规模化复制：AI 质检、合同审查、知识库、智能客服、Qoder 提效
- [企业自建 AI 推理平台](solutions/enterprise-ai-platform/overview.md) ⭐ — Higress AI 网关 + 灵骏 GPU + 百炼 Fallback；含 AWS 迁移案例、优化建议、销售策略

## 模板参考

- [AI 通用笔记模板](ai-general-notes/_template.md)
- [MaaS 产品模板](_maas_template.md)
- [产品模板](_product_template.md)
- [对比分析模板](alibaba-cloud/competitive-analysis/_template.md)
- [解决方案模板](solutions/_template.md)
