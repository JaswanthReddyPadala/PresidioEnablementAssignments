# AI Models Comparision

# Models considered for comparision

- GPT-4o
- Claude 4 Sonnet
- Gemini 2.5 Flash
- DeepSeek-R1:7B — Ollama

---

# Comparision Chat

|                           | **GPT-4o** | **Claude 4 Sonnet** | **Gemini 2.5 Flash** | **DeepSeek-R1 7B (Ollama)** |
| ------------------------- | ---------- | ------------------- | -------------------- | --------------------------- |
| **Code Quality (AppDev)** | Excellent  | Good                | Limited              | Limited                     |
| **SQL Generation (Data)** | Excellent  | Good                | Limited              | Basic                       |
| **Infra (DevOps)**        | Good       | Good                | Limited              | Basic                       |
| **Ease of Use**           | Excellent  | Excellent           | Good                 | Good                        |
| **Speed**                 | Excellent  | Excellent           | Excellent            | Good                        |

---

## Comments

### GPT-4o

- **Code Quality**: Generates high-quality code across various programming languages. And good at debugging the error, But immediatly jump to code implementation (relavent) without comepletly understanding the context.
- **SQL Generation**: Generates complex SQL Queries when proper context is given.
- **Infra**: Generates automation code, sample terraform for infra automation, Couldn't test due to lack of complete knowledge.
- **Ease of Use**: Easily used, with web app and also using via API.
- **Speed**: Speed, and offers very good performance with less responses times.

### Claude 4 Sonnet

- **Code Quality**: Generates high-quality code across various programming languages. And good at debugging the error, But immediatly jump to code implementation (relavent) without comepletly understanding the context.
- **SQL Generation**: Generates complex SQL Queries when proper context is given.
- **Infra**: Generates automation code, sample terraform for infra automation, Couldn't test due to lack of complete knowledge.
- **Ease of Use**: Easily used, with web app and also using via API.
- **Speed/Latency**: Speed, and offers very good performance with less responses times.

### Gemini 2.5 Flash

- **Code Quality**: Generates okayish code across various programming languages. But missing the context sometimes, even though clearly explained.
- **SQL Generation**: Can handle basic SQL generation tasks but may require detailed prompt refinement for accuracy.
- **Infra**: Limited capabilities in generating infrastructure scripts; better suited for template-driven tasks.
- **Ease of Use**: Can be used through API and web app
- **Speed**: Excellent response times.

### DeepSeek-R1 7B (Ollama)

- **Code Quality**: Generates okayish code across various programming languages. But missing the context sometimes, even though clearly explained.
- **SQL Generation**: Limited support; may require custom prompts and adjustments for accurate SQL generation.
- **Infra**: Not much good.
- **Ease of Use**: Runs locally via Ollama with REST API support; setup is easy.
- **Speed/Latency**: Offers good performance on local machine.

