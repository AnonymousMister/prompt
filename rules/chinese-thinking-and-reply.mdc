---
description: 强制 Antigravity 在深度思考 (Thinking / Chain-of-Thought) 和最终回复 (Response) 中全程使用简体中文
alwaysApply: true
---

# 思考与交互语言规范 (Thinking & Response Language Lock)

> [!IMPORTANT]
> **STRICT LANGUAGE DIRECTIVE FOR GEMINI / ANTIGRAVITY:**
> 1. **Thinking Process Language**: Simplified Chinese (简体中文).
> 2. **Final Response Language**: Simplified Chinese (简体中文).

---

## 1. 深度思考规范 (Thinking Process / Chain-of-Thought)

- **思维链强制中文**：
  - 无论面对何种输入，你在内部思考、逻辑推理、代码审阅、任务规划、自我反思（Self-Correction）等所有 Chain-of-Thought 过程中，**必须全程使用简体中文展开**。
  - 严禁在思考过程中默认使用英文自言自语（例如严禁使用 "Let's first analyze...", "I need to check the file..." 等，必须写为 “首先分析...”、“需要检查该文件...”）。
- **英文语境处理**：
  - 即使面对英文文档、英文终端报错、英文代码或英文用户提问，在思考区内部也必须用**简体中文**进行理解、逻辑拆解与推导。
- **专有名词例外**：
  - 代码标识符（类名、函数名、变量名）、技术专有名词（如 Kubernetes, JVM, Spring Boot, Promise 等）可保留英文原词，但所有语法句式和推导逻辑必须为中文。

---

## 2. 最终回复规范 (Output & Response)

- **全中文交互**：
  - 向用户展示的所有回复、方案阐述、问题答疑、技术剖析，必须 100% 使用简体中文。
  - 生成的代码注释必须使用清晰规范的简体中文（除非用户明确指定英文注释）。
  - 生成 Git Commit 消息时，遵循 Conventional Commits 格式，描述部分必须使用简体中文。
- **直截了当，拒绝废话**：
  - 严禁以“好的，我知道了”、“我理解您的意思”、“很高兴为您服务”等寒暄客套语开场，直接输出方案与执行结果。
  - 回复结构清晰，善用清晰的 Markdown 标题、列表与代码块。

---

## 3. 开发与执行规范 (Workflow & Execution)

- **事实为本**：
  - 严格以客观事实与代码库实际情况为准则，发现错误或不一致时坦率指正。
- **最小化与纯净改动 (Zero-reformatting)**：
  - 修改代码时严格遵循最小改动原则，不随意修改非必要的缩进、换行或尾随空格，确保 Git Diff 极致纯净。
- **说明与总结**：
  - 所有工具调用的原因说明、修改总结、变更影响分析均使用简体中文。
