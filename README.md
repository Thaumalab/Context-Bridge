# 🪄 Context Bridge by ThaumaLab

**Context Bridge** is a high-fidelity productivity utility designed to solve the "memory loss" problem that occurs when AI chat sessions hit context limits or message quotas. It acts as a vendor-agnostic "save state," allowing you to package the essential intelligence of a conversation and resume work across any model—including Claude, GPT-4o, and Gemini—without losing momentum.

## 🚀 Key Features

* **SmartTrim™ Truncation:** Instead of raw cutting, the engine intelligently extracts code structure—preserving imports, function signatures, and key comments—to save up to **30% in tokens** while maintaining logic.
* **Semantic Conflict Guard:** Protects your "source of truth" by explicitly flagging previously rejected paths or failed logic to the new AI, preventing redundant suggestions and "AI drift".
* **Privacy Vault:** A local-first security layer that automatically identifies and redacts sensitive data, such as emails or API keys, before the handoff ever leaves your machine.
* **Target AI Optimization:** Tailors the handoff prompt specifically for the receiving model (e.g., XML for Claude or Markdown for GPT) to ensure native-level instruction following.
* **Collaborative Relay:** Encodes the entire project state into a compressed "Relay Link," allowing you to share a stateful AI context with a teammate in one click.
* **Context Safety Gauge:** A live, color-coded bar (Green → Amber → Red) that alerts you when the handoff is approaching the specific context limit of your target AI.
* **Live Cost Estimator:** Real-time USD input cost estimates based on current provider rates (e.g., $0.003 per 1k tokens for Claude).

## 🛠️ Tech Stack

* **Logic:** Vanilla ES6+ JavaScript, Python, and Go.
* **Frontend:** Functional minimalism built with HTML5 and CSS3.
* **Deployment:** Optimized for desktop and mobile (**Pydroid/Android**) with full PWA support.

---
Developed by **ThaumaLab**
