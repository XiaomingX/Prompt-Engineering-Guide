# Prompt 工程指南

Prompt 工程是一门新兴学科，用于开发和优化提示（Prompt），以高效使用大语言模型（LLM）完成各种任务和研究课题。掌握 Prompt 工程技能，有助于深入了解大语言模型的能力和局限性。

通过 Prompt 工程，可以提升 LLM 在以下方面的表现：

- **问答**：通过设计精准提示，获取准确的回答。
- **逻辑推理**：改进模型的数学和逻辑推理能力。
- **任务执行**：优化模型在常见任务（如文案生成、翻译、总结）中的表现。

## 主要用途

1. **研究者**：通过 Prompt 工程探索大语言模型的潜力，优化复杂任务的处理能力。
2. **开发者**：设计强大的 Prompt 技术，与 LLM 接口交互，实现高效工具开发。

### 学习资源

以下是推荐的学习资源：

- [Prompt Engineering Guide 官方网页](https://www.promptingguide.ai/)
- 详细教程、学习指南和工具集。

## 指南

以下内容为提示工程相关的精华内容，帮助快速掌握常用技术和应用。更多信息请访问 [提示工程指南](https://www.promptingguide.ai/)。

### 入门
- [提示工程基础](https://www.promptingguide.ai/introduction/basics)
- [提示工程设置参数](https://www.promptingguide.ai/introduction/settings)
- [提示设计要点](https://www.promptingguide.ai/introduction/elements)
- [提示设计技巧](https://www.promptingguide.ai/introduction/tips)
- [提示实例](https://www.promptingguide.ai/introduction/examples)

### 技术
- [零样本提示](https://www.promptingguide.ai/techniques/zeroshot)
- [少样本提示](https://www.promptingguide.ai/techniques/fewshot)
- [链式思维提示](https://www.promptingguide.ai/techniques/cot)
- [自洽性提示](https://www.promptingguide.ai/techniques/consistency)
- [生成知识提示](https://www.promptingguide.ai/techniques/knowledge)
- [提示链](https://www.promptingguide.ai/techniques/prompt_chaining)

### 应用
- [生成代码](https://www.promptingguide.ai/applications/coding)
- [生成数据](https://www.promptingguide.ai/applications/generating)
- [生成合成数据集](https://www.promptingguide.ai/applications/synthetic_rag)
- [文本总结](https://www.promptingguide.ai/prompts/text-summarization)
- [问答](https://www.promptingguide.ai/prompts/question-answering)

### 模型
- [ChatGPT](https://www.promptingguide.ai/models/chatgpt)
- [GPT-4](https://www.promptingguide.ai/models/gpt-4)
- [LLaMA](https://www.promptingguide.ai/models/llama)
- [Code Llama](https://www.promptingguide.ai/models/code-llama)

### 风险与误用
- [对抗性提示](https://www.promptingguide.ai/risks/adversarial)
- [事实性问题](https://www.promptingguide.ai/risks/factuality)
- [偏见问题](https://www.promptingguide.ai/risks/biases)

---

## 视频课程

我们发布了一小时提示工程的综合课程，涵盖技术、应用和工具：
- [课程视频](https://youtu.be/dOxUroR57xs)
- [代码笔记本](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/notebooks/pe-lecture.ipynb)
- [演讲幻灯片](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/lecture/Prompt-Engineering-Lecture-Elvis.pdf)

---

## 本地运行指南

如果需要在本地运行以进行自定义，请按以下步骤操作：

1. 安装 Node >=18.0.0。
2. 安装 `pnpm`（参考 [安装指南](https://pnpm.io/installation)）。
3. 安装依赖：`pnpm i next react react-dom nextra nextra-theme-docs`。
4. 启动服务：`pnpm dev`。
5. 访问 `http://localhost:3000/`。
