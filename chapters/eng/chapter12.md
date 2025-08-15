[📚 Back to Table of Contents](../../README.md)

# 1.2. Handling Hallucinations and Distortions in AI Responses

One of the most dangerous yet subtle meta-problems is **AI hallucinations** — situations when a language model confidently makes up facts, terms, references, definitions, or logical connections that don’t exist.

This is not a bug in the code or an act of malice — it is a **fundamental feature** of how text generation works. The model doesn't “know” the truth; it simply generates the most statistically likely sequence of words based on the context and style of your prompt.

## 📊 Table 1 — Examples of AI Hallucinations

| Type                      | Example                                                             | Comment                                                                 |
|---------------------------|---------------------------------------------------------------------|-------------------------------------------------------------------------|
| Invented source           | “According to a 2021 Harvard study…”                                | Sounds authoritative, but no such study exists.                        |
| Fake quote                | “As Steve Jobs said: ‘Design is when beauty meets simplicity.’”     | Feels like Jobs, but he never said it.                                 |
| Illogical reasoning       | “Since water freezes at 0°C, that explains air behavior at -10°C.”  | Formally logical, but the connection is imaginary.                     |
| Distorted known facts     | “Unemployment rate in Germany in 2023 was 18%.”                     | The actual figure was around 5–6%.                                     |
| Fictional term or method  | “Reverse Cognitive Activation Method”                               | Not a real method, but sounds scientific.                              |

---

## 🤖 Why Does It Happen?

The model does **not access a database of facts**. It doesn’t search Wikipedia or books. Instead:
- It predicts the next likely word;
- If you ask for a “citation,” it mimics the appearance of citations;
- If you ask for reasoning, it follows common argumentative templates.

The main criterion is not **truth**, but **coherence and plausibility**.

---

## ⚠ Why Is This Dangerous?

- ❗ You might believe it — especially if you don’t double-check.
- ❗ You might use fake info in work, school, or publications.
- ❗ Errors are polished — hallucinations often look beautifully convincing.

---

## ✅ How to Work with This Issue

1. **Verify confident statements**
   - If the model says:  
     “According to WHO data...” or “It is well known that...” — ask yourself:  
     _Can I actually find this source online?_

2. **Ask meta-questions directly**
   - “What is this based on?”  
   - “Is there a source?”  
   - “What’s the likelihood of error here?”

3. **Use external verification**
   - Google, Wikipedia, or another AI model
   - This can:
     - prevent falsehoods from spreading;
     - bring real depth to your understanding;
     - train your skill to spot pseudo-knowledge.

4. **Rephrase your prompt**
   - “Provide verifiable sources on this topic.”  
   - “Are there any known studies that support this?”  
   - “Give an example — but warn me if it’s fictional.”

5. **Ask for a hypothesis — if that’s what you want**
   - “Create a possible version or fantasy about...”  
   - “Build a scenario, even if hypothetical.”

By framing your prompt explicitly, you avoid the illusion: “It sounds convincing, so it must be true.”

---

## 📋 Checklist: Spotting AI Hallucinations

| Question                                                        | Sign of Hallucination |
|------------------------------------------------------------------|------------------------|
| Does it sound too polished or too confident?                     | Yes                    |
| Is there no specific source?                                     | Yes                    |
| Is the citation or quote untraceable but sounds persuasive?      | Yes                    |
| Is the model certain, but gives no context or explanation?       | Yes                    |
| Is the topic complex and interdisciplinary?                      | Higher risk            |

[⬅️ Chapter 1.1.](chapter11.md)  |  [Chapter 1.3. ➡️](chapter13.md)
