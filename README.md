# 🔍 Agent Observability — Logs, Traces & Metrics  
**Day 4 — Kaggle 5-Day AI Agents Course**

Welcome to **Day 4** of the Kaggle Agentic Systems series!

Yesterday (Day 3), you learned how **Session** and **Memory** management give agents short-term, long-term, and shared state.

Today, we focus on:

- How to add **observability** to your agent  
- How to evaluate whether the agent is behaving correctly  

This notebook covers the first part: **Agent Observability**.

---

## 🧐 What Is Agent Observability?

Traditional software fails in predictable ways:  
**Null pointer, bad API call, missing file — easy to debug.**

AI Agents?  
They can fail silently, strangely, or irrationally.


You: **WHY?**

- Was the prompt wrong?  
- Missing tool?  
- Did the LLM hallucinate?  
- Did the tool return an error?  
- Was the context too large?

### 💡 Observability solves this.

With observability, you can see:

- The **exact prompts** sent to the LLM  
- All **tools** the agent had access to  
- **Which tool it selected** and why  
- **Tool inputs/outputs**  
- Where the chain broke  
- How the agent reasoned  

## Code Link
[Kaggle Link](https://www.kaggle.com/code/harsharachagiri/day-4a-agent-observability/edit)  

