[📚 Back to Table of Contents](../../README.md)

## 2.1.7. Technique: AI Confidence Estimation of User Query Understanding

One of the effective prompts for GPT that improves the quality of answers is:  

> **"Estimate the confidence in the accuracy of your answer. If it is lower than 90%, ask clarifying questions until confidence is 90% or higher."**  

### Why this works  

- When a chatbot is unsure of its knowledge, it often starts **guessing**, which can lead to mistakes.  
- This prompt activates a **self-checking mechanism**: GPT begins to evaluate the risk of error instead of producing an uncertain answer.  
- If confidence is below 90%, the model **requests additional context** from the user.  
- As a result, answers become more **precise, relevant, and useful**.  

👉 This approach is especially valuable in professional and research contexts, where accuracy is more important than speed.  

### Example  

**User:** What is the average temperature in Paris in December?  
**LLM:** My confidence in the accuracy of this answer is about 70%. Could you clarify if you mean the long-term climate average or the forecast for this year?  
**User:** I mean the long-term average.  
**LLM:** Thank you! Based on climate data, the long-term average temperature in Paris in December is around **5°C (41°F)**. My confidence is now 95%.  

[⬅️ Chapter 2.1.6.](chapter216.md)  |  [Chapter 2.2., 2.2.1. ➡️](chapter221.md)
