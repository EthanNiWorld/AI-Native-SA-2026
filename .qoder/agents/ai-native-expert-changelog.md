# ai-native-expert Changelog

| 日期 | 变更 | 解决的问题 |
|------|------|----------|
| 2026-04-20 | 新增「版本校验」规则：模型名精确到版本号，搜索加引号，数据跨源交叉确认 | 回答 Qwen3.6-Max-Preview vs Plus 时，混用了 Qwen3-Max（上一代）的数据，导致结论不准确 |
| 2026-04-20 | 从 Skill 精简为 Agent 定位，73行→42行 | 原 SKILL.md 包含大量 Skill 规范约束，与 Agent 开放式对话场景不匹配 |
| 2026-04-20 | 删除重复描述，加入 knowledge/ 路径引用 | 原文"不读知识库"与 Agent 定位矛盾，且缺少明确路径指向 |
| 2026-04-23 | 重构知识沉淀机制：inbox 文件名改为 ai-knowledge-by-qoder-ai-nativeagent-YYYYMMDD.md；回答结构改为"所以然+之所以然"双层；新增信源优先级规则；概念洞察用 ⭐ #ai-general-notes 标签标注 | 原文件名无区分度、回答只有结论没有底层逻辑、概念洞察无机制导向 ai-general-notes/ |
| 2026-04-23 | 新增「类型」字段机制（事实问答/概念洞察/选型分析），洞察自动导向 ai-general-notes/；新增「洞察提炼」必填区块；强化第一性原理行为准则表述 | inbox 分类只有 maas/ai-coding，概念性洞察（如 Harness 战略价值、Agent for循环等）无法回流 ai-general-notes/ |
| 2026-04-20 | 角色从"跨云AI架构师"转型为"AI Native Expert"，去除云基础设施内容，151行→70行 | 原角色覆盖范围过广（含云产品排错、IaC等），与 MaaS+AI Coding 聚焦不符 |
