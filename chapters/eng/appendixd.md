[📚 Back to Table of Contents](../../README.md)

## Appendix D. List of Meta-Problems and How to Solve Them

| # | Meta-Problem | How It Manifests | Why It Happens | Solution |
|---|--------------|------------------|----------------|----------|
| 1 | **Switching Communication Frame** | Was academic style, became casual or colloquial (and vice versa) | The model adapts to the tone of the prompt; the user’s style may change mid-dialogue | 🔹 Explicitly state the desired style (*“Stay in academic tone”*)<br>🔹 Track such shifts as a signal of losing the logical thread |
| 2 | **Ignoring Hidden Address to the Model** | Hints or indirect references to the model in the middle of reasoning, loss of context | The instruction gets lost in the general text flow | 🔹 Structure the prompt: separate reasoning and instructions<br>🔹 Use markers (`---`) or highlight with **TASK:** |
| 3 | **Ignoring Some Questions in Multi-Question Prompts** | Out of several questions, the model answers only a few | The model focuses on the most prominent or last requests, skipping others | 🔹 Break questions into bullet points<br>🔹 At the end say: *“Answer all questions point by point”*<br>🔹 Or split into a series of prompts |
| 4 | **Smooth Style Without Substance** | The answer is pleasant but misses key meaning, logic is blurred | The model prioritizes coherence and friendliness over analytical depth | 🔹 Use another model for cross-analysis<br>🔹 Ask follow-up: *“What was missed? What are the weak points?”* |
| 5 | **Paraphrasing Without Insight** | The response looks different but simply repeats the request without new info | The model doesn’t realize the user needs novelty, not rewording | 🔹 Clarify the goal: *“Find something unexpected”*, *“Show contradictions”*<br>🔹 Ask to identify hidden ideas, weaknesses, distortions |

[⬅️ Appendix C](appendixc_eng.md) | [Table of Contents ➡️](../../README_eng.md)
