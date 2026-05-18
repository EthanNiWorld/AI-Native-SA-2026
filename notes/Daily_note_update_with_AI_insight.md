# Daily Notes with AI Insight

## 2025-05-18
-  Claude Platform on AWS 与 Claude on Amazon Bedrock 之间的差异，Claude Platform on AWS的身份验证由 AWS IAM 负责处理，审计日志通过 CloudTrail 来记录，计费则通过标准 AWS 发票结算。Anthropic 自行运营该服务，这意味着客户数据会在 AWS 基础设施边界之外完成处理，这与通过 Amazon Bedrock 访问 Claude 模型的模式有所不同，后者由 AWS 作为数据处理方。前者的优势是day0体验和claude原生API功能一致。

- Kiro的前身为AWS CodeWhisperer (停服)，演进路线AWS CodeWhisperer--> Amazon Q Developer（过渡期） -->升级为升级Kiro（新一代 AI IDE）