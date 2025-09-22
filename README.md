# Conversational Agent Debating Capability

**Authors:** [Mohamad Faraj Makkawi](https://www.linkedin.com/in/momakkawi/), [Hassan Khan](https://www.linkedin.com/in/hassan-khan-37912b280/)

**Supervisors:** Mihai Andries, Christophe Lohr

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [What is a "Good" Debate?](#what-is-a-good-debate)
3. [Argumentation Techniques](#argumentation-techniques)
4. [Why Symbolic AI for Debates?](#why-symbolic-ai-for-debates)
5. [Conversational AI Agent Types](#conversational-ai-agent-types)
6. [Evaluation Metrics](#evaluation-metrics)
7. [Limitations of Existing Debating Agents](#limitations-of-existing-debating-agents)
8. [Conclusion](#conclusion)
9. [Future Directions](#future-directions)
10. [References](#references)

---

## Project Overview

### Objective
This project conducts **bibliographical research** on designing conversational agents capable of logical, persuasive debate. The primary goal is to **support the mental health of socially isolated individuals** by leveraging **symbolic reasoning** to enhance debating agents.

### Key Research Questions
- What defines a debate, and what constitutes a "good" debate?
- What debating techniques are effective for conversational agents?
- What types of conversational agents are currently capable of debating?

---

## What is a "Good" Debate?

### Definition
A structured exchange of arguments governed by:
- **Logical consistency**
- **Evidence-based reasoning**
- **Rebuttal mechanisms**

### Evaluation Criteria
| Criterion       | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| Logical Flow    | Coherence and progression of arguments                                     |
| Evidence Quality| Reliability and relevance of supporting data                                |
| Clarity         | Accessibility and understandability of arguments                           |
| Relevance       | Pertinence of arguments to the debate topic                                 |

---

## Argumentation Techniques

### Overview
Structured methods for constructing, analyzing, and evaluating arguments to reach logical conclusions and persuade audiences.

### Comparison of Techniques

<custom-element data-json="%7B%22type%22%3A%22table-metadata%22%2C%22attributes%22%3A%7B%22title%22%3A%22Argumentation%20Techniques%20Comparison%22%7D%7D" />

| Technique                | Pros                                      | Cons                                      |
|--------------------------|-------------------------------------------|-------------------------------------------|
| **ASPIC+**               | Logical rigor, explainability             | Manual rule encoding required             |
| **Multi-Attribute**      | Adapts to dynamic priorities              | Weightings may introduce bias             |
| **Argument Graphs**      | Clarity in argument dependencies          | Struggles with uncertainty                |

---

## Why Symbolic AI for Debates?

### Core Principles
- **Knowledge Representation:** Uses ordered, legible symbols derived from logical reasoning.
- **Advantages:**
  - **Logical Consistency:** Ensures arguments are free of contradictions.
  - **Explainability:** Transparent reasoning process.
  - **Verifiability:** Easier to validate and audit.
  - **Clear Communication:** Facilitates effective interaction with users.

---

## Conversational AI Agent Types

### Comparison

<custom-element data-json="%7B%22type%22%3A%22table-metadata%22%2C%22attributes%22%3A%7B%22title%22%3A%22Agent%20Types%20Comparison%22%7D%7D" />

| Agent Type               | Strengths                          | Weaknesses                        |
|--------------------------|------------------------------------|-----------------------------------|
| **Rule-Based**           | Predictable outcomes              | Rigid structure                   |
| **Retrieval-Based**      | Dynamic data handling             | Dependency on retrieval quality   |
| **Hybrid**               | Context-aware reasoning           | Complex setup                     |
| **Hierarchical**         | Personalized arguments            | Feedback latency                  |
| **Explainable**          | Transparent explanations          | Depth limitations                 |

---

## Evaluation Metrics

### Performance Benchmarks

<custom-element data-json="%7B%22type%22%3A%22table-metadata%22%2C%22attributes%22%3A%7B%22title%22%3A%22Evaluation%20Metrics%22%7D%7D" />

| Agent Type               | Accuracy | Response Time | Cost Efficiency | Scalability | Stability | User Satisfaction |
|--------------------------|----------|---------------|-----------------|-------------|-----------|-------------------|
| **Rule-Based**           | ↑        | ↑             | ↓               | ↓           | ↑         | ↓                 |
| **Retrieval-Based**      | —        | —             | —               | ↑           | —         | —                 |
| **Hybrid (Rule-Retrieval Based)** | —  | ↓             | ↑               | —           | ↑         | ↑                 |
| **Hierarchical**         | —        | ↓             | ↑               | ↑           | ↑         | —                 |
| **Explainable**          | —        | —             | —               | —           | —         | ↑                 |

**Legend:**
↑ High/Better
— Moderate
↓ Low/Worse

**References for Evaluation Metrics:**
- Bronsdon, G. **"Evaluating AI Agent Performance: Benchmarks for Real-World Tasks."** Accessed: Apr. 3, 2025. URL: [https://www.galileo.ai/blog/evaluating-ai-agent-performance-benchmarks-real-world-tasks](https://www.galileo.ai/blog/evaluating-ai-agent-performance-benchmarks-real-world-tasks).
- Smythos. **"AI Agent Performance Measurement."** Accessed: Apr. 3, 2025. URL: [https://smythos.com/ai-agents/agent-architectures/ai-agent-performance-measurement/](https://smythos.com/ai-agents/agent-architectures/ai-agent-performance-measurement/).
- SuperAnnotate. **"AI Agent Evaluation."** Accessed: Apr. 3, 2025. URL: [https://www.superannotate.com/blog/ai-agent-evaluation](https://www.superannotate.com/blog/ai-agent-evaluation).
- IBM. **"AI Agent Evaluation."** Accessed: Apr. 3, 2025. URL: [https://www.ibm.com/think/topics/ai-agent-evaluation](https://www.ibm.com/think/topics/ai-agent-evaluation).

---

## Limitations of Existing Debating Agents
- **Uncertainty and Big Data Management:** Difficulty handling ambiguous or large-scale data.
- **Knowledge Acquisition Bottleneck:** Manual encoding is time-consuming.
- **Real-Time Dynamic Assessments:** Limited adaptability in live debates.
- **Logical Inconsistencies:** Risk of contradictory arguments.

---

## Conclusion
### Recommended Agent Type
**Explainable Conversational Agent**
- **Why?** Balances transparency, user satisfaction, and logical consistency—ideal for mental health support through debate.

---

## Future Directions
- **Real-Time Dynamic Adaptation:** Enhance agents to respond fluidly to evolving debate contexts.

---

## References
1. Rakshit, G., et al. **"Debbie, the debate bot of the future."** *Advanced Social Interaction with Agents: 8th International Workshop on Spoken Dialog Systems.* Springer, 2019, pp. 45–52.
2. Tan, C., et al. **"Winning arguments: Interaction dynamics and persuasion strategies in good faith online discussions."** *Proceedings of the 25th International Conference on World Wide Web.* 2016, pp. 613–624.
3. Engelmann, D., et al. **"Argumentation as a method for explainable AI: A systematic literature review."** *17th IEEE Iberian Conference on Information Systems and Technologies (CISTI).* IEEE, 2022, pp. 1–6.
4. Kasif, S. **"A Trilogy of AI Safety Frameworks: Paths from Facts and Knowledge Gaps to Reliable Predictions and New Knowledge."** *arXiv preprint arXiv:2410.06946 (2024).* Department of Biomedical Engineering, Program in Bioinformatics, Department of Computer Science, Boston University. URL: [https://arxiv.org/abs/2410.06946](https://arxiv.org/abs/2410.06946).

---
**Note:** For further details, refer to the [full paper](https://hal.science/hal-05237874).
