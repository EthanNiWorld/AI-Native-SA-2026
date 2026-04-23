# 通义千问 (Qwen)

> 最后更新: 2026-04-20
> 所属厂商: 阿里云
> 产品类别: MaaS

**定位**: 阿里云自研大语言模型系列，覆盖文本/代码/多模态，开源+商业双轨并行
**当前主推**: Qwen3.6 系列（Qwen3.6-Max / Qwen3.6-Plus / Qwen3.6-Flash）
**适用**: 企业级AI应用开发、智能对话、代码生成、多模态理解
**不适用**: 需要完全私有化且无网络的极端离线场景

## 当前主推模型

| 模型 | 定位 | 上下文 | 特点 |
|------|------|--------|------|
| Qwen3.6-Max | 旗舰 | 1M tokens | 最强推理，复杂任务 |
| Qwen3.6-Plus | 均衡 | 1M tokens | 性价比高，企业首选，Always-on CoT |
| Qwen3.6-Flash | 轻量 | 256K tokens | 速度快，成本低 |

### Qwen3.6-Plus
- 模型：Qwen3.6-Plus
- 公司：阿里云
- 时间：2026年4月
- 尺寸：未公开
- 上下文：1M tokens
- 场景：Agentic Coding/长文档分析/多模态推理
- 定价：¥2/1M input tokens（≤256K）
- 特点：1M上下文，Always-on CoT，Agentic Coding能力强

### Qwen3.6-Max
- 模型：Qwen3.6-Max
- 公司：阿里云
- 时间：2026年5月（预告未发布）
- 尺寸：未公开（MoE架构）
- 上下文：1M tokens
- 场景：复杂推理/科研/创作
- 定价：按量付费（百炼平台）
- 特点：旗舰推理能力，数学/代码/逻辑最强

## 核心能力与限制

### 核心能力

| 能力 | 说明 |
|------|------|
| 多语言 | 中英文及多语言能力领先 |
| 代码生成 | 编程能力对标 GPT-4 级别 |
| 长上下文 | 1M tokens 窗口（Qwen3.6系列） |
| 多模态 | Qwen-VL 系列支持图文理解 |
| 开源生态 | 多尺寸开源，社区活跃 |

### 核心限制

| 限制项 | 具体值 | 说明 |
|--------|--------|------|
| 最大上下文 | 1M tokens | Qwen3.6-Plus/Max |
| 并发限制 | 按账户等级 | 企业版更高 |
| 多模态 | 图文理解 | 视频/音频能力有限 |

## 适用场景

### ✅ 适用

| 场景 | 推荐模型 | 说明 |
|------|----------|------|
| 企业智能客服 | Qwen3.6-Plus | 性价比高，中文能力强 |
| 代码辅助 | Qwen3.6-Max | 复杂代码推理 |
| 高并发轻量调用 | Qwen3.6-Flash | 低延迟低成本 |
| 私有化部署 | Qwen3.6开源版 | 支持本地部署 |

## 接入方式

| 方式 | 说明 | 适用场景 |
|------|------|----------|
| API 直接调用 | DashScope API，兼容OpenAI格式 | 快速集成 |
| 平台托管 | 百炼平台，可视化编排 | 企业级应用 |

## 参考资料

- agentic LLM参考: https://artificialanalysis.ai/models?intelligence=coding-index
- [通义千问官网](https://tongyi.aliyun.com)
- [百炼平台](https://bailian.console.aliyun.com)
- [Qwen GitHub](https://github.com/QwenLM)

## Changelog
| 日期 | 变更内容 |
|------|----------|
| 2026-04-20 | 按_maas_template重构，对齐模板结构 |
