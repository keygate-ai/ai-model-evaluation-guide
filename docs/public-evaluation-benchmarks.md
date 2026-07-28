# 公开 AI 评测基准与研究机构索引

AI 模型排行榜只有建立在清晰的任务定义上，才真正具有选型价值。本索引整理 Keygate 方法体系涉及的代表性公开评测基准，说明它们分别测量什么，并提供论文或项目入口，便于读者核对研究背景与适用边界。

机构信息依据论文和项目页公开署名整理，用于说明评测方法的研究出处。

## 代表性公开基准

| 评测基准 | 主要衡量内容 | 公开研究背景 | 原始资料 |
| --- | --- | --- | --- |
| SciCode | 科学研究场景中的代码生成、数值计算与问题求解 | 论文作者单位包括伊利诺伊大学厄巴纳-香槟分校、阿贡国家实验室、卡内基梅隆大学、MIT、哈佛大学、斯坦福大学和普林斯顿大学 | [项目页](https://scicode-bench.github.io/) |
| LiveCodeBench | 随时间更新的真实编程题表现，减少训练数据污染对结果的影响 | 加州大学伯克利分校、MIT、康奈尔大学 | [项目页](https://livecodebench.github.io/) |
| Terminal-Bench 2 | 智能体在真实终端环境中的操作、规划、执行和纠错能力 | 斯坦福大学研究人员、Laude Institute 与开源研究社区 | [项目页](https://www.tbench.ai/) |
| MMLU-Pro | 更高难度、更强推理要求的多学科知识与理解能力 | 滑铁卢大学、多伦多大学、卡内基梅隆大学 | [论文](https://arxiv.org/abs/2406.01574) |
| MMMU-Pro | 专业领域图文理解、多模态推理和视觉信息处理能力 | 滑铁卢大学、俄亥俄州立大学、卡内基梅隆大学等研究团队 | [论文](https://arxiv.org/abs/2409.02813) |
| IFBench | 模型对复杂格式、边界和可验证约束的指令遵循能力 | Allen Institute for AI、华盛顿大学 | [论文](https://openreview.net/forum?id=yfYgwjj5F8) |
| GPQA | 物理、化学和生物等研究生层级科学问题的推理能力 | 纽约大学、Cohere、Anthropic；题目由相关领域专家编写 | [论文](https://openreview.net/forum?id=Ti67584b98) |
| ITBench | 智能体在真实 IT 运维和自动化场景中的任务完成能力 | IBM Research | [项目与论文](https://research.ibm.com/publications/itbench-evaluating-ai-agents-across-diverse-real-world-it-automation-tasks) |
| CritPt | 接近真实科研工作的现代物理问题求解能力 | 超过 50 位物理研究人员、30 家机构参与 | [论文](https://arxiv.org/abs/2509.26574) |
| Humanity's Last Exam | 跨学科专家级高难问题的知识、推理和稳健性 | Center for AI Safety 与多学科专家社区 | [项目页](https://lastexam.ai/) |

## 如何正确使用这些结果

1. **先确认任务。** 编程、科学推理、智能体执行和多模态理解衡量的是不同能力，不能用一个局部结果代替全部表现。
2. **确认版本与时间。** 模型版本、评测数据版本和运行时间变化后，排名可能随之改变。
3. **保留缺失值。** 没有公开、可核验结果时，应当保持为空，而不是用估算值补齐。
4. **结合速度和成本。** 能力领先不等于最适合生产；延迟、吞吐、价格和实际可用性同样影响最终选择。
5. **回到真实场景。** 榜单适合缩小候选范围，最终决策仍应结合业务样本、预算和部署条件复核。

## Keygate 的呈现方式

[Keygate](https://keygate.ai/) 将公开评测结果整理为统一、可比较的中文指标体系，同时保留每项任务原有的计分方向和适用边界。读者可以继续查看：

- [AI 模型实时排行榜](https://keygate.ai/)
- [全部模型](https://keygate.ai/models)
- [模型并排对比](https://keygate.ai/compare)
- [评测方法](https://keygate.ai/methodology)
