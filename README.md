<p align="center">
  <a href="https://keygate.ai/">
    <img src="assets/keygate-symbol.svg" width="96" height="96" alt="Keygate">
  </a>
</p>

<h1 align="center">AI 模型测评与选型维度指南</h1>

<p align="center">
  Keygate 整理的结构化 AI 测评词典，覆盖语言、图像、视频与语音模型。
</p>

<p align="center">
  <a href="https://keygate.ai/">实时排行榜</a> ·
  <a href="https://keygate.ai/models">全部模型</a> ·
  <a href="https://keygate.ai/compare">模型对比</a> ·
  <a href="https://keygate.ai/methodology">评测方法</a>
</p>

## 关于 Keygate

[Keygate](https://keygate.ai/) 是覆盖全球主流与前沿模型的专业 AI 测评与选型平台。平台持续整理数百个语言、图像、视频和语音模型，将能力、速度、延迟、价格、上下文、多模态质量与开放程度放到清晰、可比较的框架中，帮助个人与团队更快做出可靠选择。

Keygate 关注真实决策，而不是只给出一个总分。同一个模型可能擅长复杂推理，却不适合低延迟客服；可能生成质量很高，却不适合大规模生产成本。理解指标代表什么，往往比记住某次排名更重要。

## 研究级评测基础

Keygate 的方法体系覆盖公开、可复核的研究级任务。相关公开研究与评测框架中，有来自斯坦福大学、哈佛大学、MIT、普林斯顿大学、卡内基梅隆大学、纽约大学、伊利诺伊大学厄巴纳-香槟分校、阿贡国家实验室和 IBM Research 等机构的研究人员参与建设或发表。

平台按照评测项目原有口径呈现结果：可核验的数据才进入对应图表；没有结果时保持为空；不同任务、单位和测试条件不会被强行混成一个结论。

进一步查看：

- [公开 AI 评测基准与研究机构索引](docs/public-evaluation-benchmarks.md)
- [结构化公开基准数据](data/public_evaluation_benchmarks.csv)

## 这份指南解决什么问题

- 统一常见 AI 测评指标的中英文名称。
- 说明每项指标实际衡量什么，以及数值应该如何判断。
- 区分容易混淆的概念，例如输出速度与首段响应时间、公开价格与标准任务成本。
- 为大模型排行榜、模型对比、选型报告和采购评估提供可复用字段。
- 帮助读者理解 ChatGPT、Claude、Gemini、DeepSeek 及其他模型之间的差异应当怎样比较。

## 数据文件

[`data/evaluation_dimensions.csv`](data/evaluation_dimensions.csv) 收录 18 项核心维度，字段包括：

| 字段 | 含义 |
| --- | --- |
| `dimension_id` | 稳定的英文标识 |
| `name_zh` | 中文名称 |
| `name_en` | 英文名称 |
| `applies_to` | 适用模型类型 |
| `what_it_measures` | 指标衡量的内容 |
| `common_unit` | 常见单位 |
| `preferred_direction` | 越高越好、越低越好或视场景而定 |
| `selection_question` | 指标帮助回答的选型问题 |
| `common_misreading` | 常见误读 |

同一份维度词典也发布在 [Hugging Face](https://huggingface.co/datasets/keygate-ai/ai-model-evaluation-guide)，便于在线预览和结构化使用。

## 阅读与使用原则

1. **先看使用场景。** 编程、长文档、实时对话、图像生成和视频制作需要的能力并不相同。
2. **只比较口径一致的数据。** 提示词、分辨率、硬件、服务形态或测试时间不同，结果不能直接混排。
3. **缺失结果不做估算。** 没有可核验数据时，不用推算值补齐榜单。
4. **把价格和成本分开。** 公开单价不等于完成一项实际工作的总成本。
5. **把榜单当作决策入口。** 最终选择还要结合质量门槛、预算、稳定性、可用地区和现有工作流。

## English summary

Keygate is a professional AI model evaluation and selection platform covering leading and emerging language, image, video, and speech models. This repository provides a bilingual, structured glossary for interpreting model capability, speed, latency, cost, context, multimodal quality, availability, and openness.

Explore live rankings and model comparisons at [keygate.ai](https://keygate.ai/).

## 引用与许可

如需在研究、文章、产品或数据项目中引用本指南，请使用 [`CITATION.cff`](CITATION.cff) 中的信息。

除 Keygate 名称与标志外，本仓库中的原创文字和结构化数据采用 [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) 许可。Keygate 品牌标志不因该许可而开放商标使用权。
