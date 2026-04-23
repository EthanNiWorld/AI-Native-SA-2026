# Qwen3.6 系列模型

> 最后更新: 2026-04-23
> 所属厂商: 阿里云
> 产品类别: MaaS

**定位**: Qwen3.6 系列是通义千问 2026 年旗舰模型家族，包含 Max（深度推理旗舰）和 Plus（Agentic Coding 均衡型）两条产品线
**当前主推**: Qwen3.6-Max-Preview、Qwen3.6-Plus
**适用**: 科研推理、AI Agent、自动编程、长文档分析、多模态理解
**不适用**: 低延迟实时推理、成本极度敏感场景

## 当前主推模型

| 模型 | 定位 | 上下文 | 特点 |
|------|------|--------|------|
| Qwen3.6-Max-Preview | 旗舰推理 | 256K tokens | 综合智能指数 #2/201，深度推理能力极强，MoE 架构 |
| Qwen3.6-Plus | 均衡型 | 1M tokens | Agentic Coding 接近 Claude Opus 4.5，支持多模态，性价比极高 |

### Qwen3.6-Max-Preview
- 模型：Qwen3.6-Max-Preview
- 公司：阿里云
- 时间：2026年4月
- 尺寸：未公开（MoE 旗舰架构）
- 上下文：256K tokens
- 场景：科研/数学/复杂逻辑推理
- 定价：Preview 期免费，正式版预计偏贵
- 特点：综合智能指数 52（全球 Top 3），倾向充分推理后给出答案（极度 verbose）

### Qwen3.6-Plus
- 模型：Qwen3.6-Plus
- 公司：阿里云
- 时间：2026年（已正式 GA）
- 尺寸：未公开
- 上下文：1M tokens
- 场景：AI Agent、自动编程、长文档分析、多模态理解
- 定价：¥2/1M input tokens（≤256K）
- 特点：Agentic Coding 极强，支持图像输入，成熟度高（GA 状态）

## 核心能力与限制

### 核心能力

| 能力 | 说明 |
|------|------|
| 深度推理（Max） | GPQA Diamond 科学推理、数学、逻辑等深度思考任务表现优异 |
| Agentic Coding（Plus） | SWE-bench、Terminal-Bench、NL2Repo 等真实编程任务接近 Claude Opus 4.5 |
| 超长上下文（Plus） | 1M tokens 上下文窗口，处理大型代码仓库和长文档 |
| 多模态理解（Plus） | 支持图像输入，适用于视觉理解场景 |
| 综合智能（Max） | AA Intelligence Index 得分 52，仅次于 Claude Opus 4.7 和 Gemini 3.1 Pro |

### 核心限制

| 限制项 | 具体值 | 说明 |
|--------|--------|------|
| Max 上下文窗口 | 256K tokens | 仅为 Plus 的 1/4，处理超长文档时受限 |
| Max 多模态 | 仅文本 | Preview 阶段不支持图像输入 |
| Max 稳定性 | Preview 状态 | 尚未正式 GA，生产环境建议使用 Plus |
| Max 推理成本 | 预计偏贵 | 正式版定价未公布，但 MoE 旗舰架构成本较高 |
| Plus 深度推理 | 稍弱于 Max | 在科学推理和数学任务上略逊于 Max |

## 适用场景

### ✅ 适用

| 场景 | 推荐模型 | 说明 |
|------|----------|------|
| AI Agent / 自动编程 | Plus | Agentic coding 能力更强，1M 上下文 |
| 科研/数学/复杂推理 | Max | 深度推理天花板更高 |
| 长文档分析 | Plus | 1M vs 256K |
| 多模态理解 | Plus | 支持图像输入 |
| 生产环境稳定性 | Plus | GA 状态，Max 仍为 Preview |
| 追求极致智能 | Max | 综合智能 Top 3 |

## 参考资料

- https://artificialanalysis.ai/models/qwen3-6-max （AA独立评测，Intelligence Index #2）
- https://artificialanalysis.ai/models/comparisons/qwen3-6-plus-vs-qwen3-max-thinking-preview
- https://hub.baai.ac.cn/view/53628 （智源社区评测文章）
- https://qwen.ai/blog?id=qwen3.6 （Qwen官方博客）

## Changelog
| 日期 | 变更内容 |
|------|----------|
| 2026-04-23 | 初始创建，基于 Qwen3.6-Max-Preview vs Plus 差异分析 |
