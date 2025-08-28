# Debating Capability for a Conversational Agent Overview: 

### Students
Mohamad Faraj Makkawi, Hassan Khan

### Supervisors
Mihai Andries, Christophe Lohr

### Institution
IMT Atlantique, France

---

## Context Description
Dialogue is a fundamental aspect of our social lives. Beyond its role in transmitting information, it significantly contributes to our mental health by stimulating our minds and helping us structure ideas into convincing arguments. To support socially isolated individuals in maintaining good mental health, we are developing a conversational agent capable of engaging in debates with humans.

## Objective
Our objective is to analyze the available literature on creating conversational agents capable of debating topics with humans.

## Requested Work
We require a comprehensive review of the state-of-the-art in conversational agents capable of debating. The review should cover the following subjects:

- **What is a debate? What constitutes a good debate?**
- **What debating techniques exist, and how can they be employed in a conversational agent?**
- **What are the existing types of conversational agents capable of debating a subject?**


# Debating Capability for a Conversational Agent Paper Content: 

## Abstract
This article explores the evolving capabilities of conversational agents to engage in sophisticated debates using structured argumentation and symbolic reasoning. We review computational approaches such as **Argument Graphs**, **ASPIC+**, and **Multi-Attribute Argumentation Frameworks**, evaluating their impact on logical consistency, comprehensibility, and rhetorical power in AI debates. By comparing debating architectures—rule-based, retrieval-based, hybrid, hierarchical, and explainable—we highlight their benefits and trade-offs. Symbolic approaches are emphasized for their user trust and verifiability. Despite progress, challenges like uncertainty management, knowledge acquisition bottlenecks, and real-time adaptability persist. This work underscores the need to balance formal rigor with adaptive methods to unlock the full potential of AI debaters.

**Keywords:** Debate Systems, Argumentation, Conversational Agents, ASPIC, Retrieval-Augmented Generation (RAG), Large Language Model (LLM)

---

## Table of Contents
1. [Introduction](#introduction)
2. [Debate Definition and Criteria](#debate-definition-and-criteria)
3. [Debating Techniques and Applications](#debating-techniques-and-applications)
4. [Comparative Analysis of Debate Agents](#comparative-analysis-of-debate-agents)
5. [Symbolic Methods: Explainability and Validity](#symbolic-methods-explainability-and-validity)
6. [Limitations](#limitations)
7. [Discussion](#discussion)
8. [Conclusion](#conclusion)
9. [Acknowledgments](#acknowledgments)
10. [References](#references)

---

## Introduction
Dialogue systems capable of sophisticated debate are a burgeoning research area in AI. These systems must understand and generate arguments while adhering to principles of logic and persuasion. Creating agents that can present justified positions, resolve controversies, and rebut counterarguments is technically challenging but holds immense potential for applications like educational software and decision support systems.

### Approaches
- **Rule-based agents:** Use predefined templates and logical rules. Predictable but limited in domain flexibility.
- **Retrieval-based agents:** Leverage databases or corpora (e.g., RAG) for dynamic responses, but face challenges in ensuring factual and logical consistency.
- **Hybrid agents:** Combine logical rules with data-driven responses for flexible, coherent arguments.
- **Hierarchical agents:** Adapt arguments based on dialogue context or user feedback, enhancing persuasiveness.
- **Explainable agents:** Prioritize transparency, justifying claims and reasoning steps to build user trust.

This paper focuses on **symbolic reasoning** approaches (Argument Graphs, ASPIC+, Multi-Attribute Frameworks) for their logical consistency, validity, and explainability—critical for designing effective debating agents.

---

## Debate Definition and Criteria
**Debate** is a structured exchange of arguments and counterarguments, governed by rules such as timing, alternation, and rebuttal formats. A "good" debate depends on context:
- **Academic debates:** Emphasize logical consistency and evidence.
- **Political debates:** Prioritize clarity and public persuasion.

**Effective arguments** are:
- Empirically supported
- Clearly explained
- Aware of counterarguments
- Logically coherent

Judges evaluate debates based on:
- Structured argumentation
- Evidence quality
- Successful refutations
- Avoidance of fallacies (e.g., ad hominem attacks)

---

## Debating Techniques and Applications

### 1. Argument Graphs
- **Visual representations** of argument relationships (nodes = arguments, edges = support/attack).
- **Strengths:** Clarity, readability.
- **Weakness:** Persuasiveness depends on argument quality.

### 2. ASPIC+ Framework
- **Formal structure** for logical argumentation:
  - **Strict rules:** Deductive inferences (e.g., "If X is a square, then it is a rectangle").
  - **Defeasible rules:** Common-sense reasoning (e.g., "Birds typically fly").
- **Attack relations:** Challenge premises or rebut conclusions.
- **Advantages:** Transparent reasoning, logical rigor.

### 3. Multi-Attribute Argumentation Framework
- **Ranks arguments** on criteria like logical soundness, relevance, and clarity.
- **Strengths:** Accommodates heterogeneous preferences, enhances persuasiveness.

---

## Comparative Analysis of Debate Agents

### Overview of Agent Types

<custom-element data-json="%7B%22type%22%3A%22table-metadata%22%2C%22attributes%22%3A%7B%22title%22%3A%22Comparison%20of%20Conversational%20Agent%20Types%20for%20Debate%22%7D%7D" />

|  Attribute       | Rule-Based               | Retrieval-Based         | Hybrid                     | Hierarchical               | Explainable                |
|------------------|--------------------------|-------------------------|----------------------------|-----------------------------|-----------------------------|
| **Approach**     | Predefined logical templates | DB queries + RAG        | Rule-retrieval integration | Feedback-driven adaptation  | Justification chains        |
| **Use Cases**    | Compliance systems        | Customer support        | Legal argumentation        | Policy negotiation         | Diagnostics, Legal          |
| **Strengths**   | Predictable outcomes      | Dynamic data handling    | Context-aware reasoning     | Personalized arguments      | Transparent explanations    |
| **Weaknesses**  | Rigid structure           | Retrieval dependency    | Complex setup              | Feedback latency            | Depth limitations          |


### Evaluation Metrics
<custom-element data-json="%7B%22type%22%3A%22table-metadata%22%2C%22attributes%22%3A%7B%22title%22%3A%22Evaluation%20Metrics%20for%20Debate%20Agents%22%7D%7D" />

| Criteria          | Rule-Based | Retrieval | Hybrid      | Hierarchical | Explainable |
|-------------------|------------|-----------|-------------|--------------|-------------|
| **Accuracy**      | High       | Moderate  | Balanced    | Varies       | Moderate    |
| **Response Time** | Fast       | Moderate  | Slow        | Slowest      | Moderate    |
| **Cost Efficiency**| Low        | Moderate  | High        | High         | Moderate    |
| **Scalability**   | Poor       | High      | Moderate    | Best         | Limited     |
| **Stability**     | High       | Moderate  | High        | High         | Moderate    |
| **User Satisfaction**| Low    | Moderate  | High        | Moderate     | Highest     |

---

## Symbolic Methods: Explainability and Validity
Symbolic techniques use formal logic, rule systems, and knowledge graphs to ensure:
- **Explainability:** Defends selected arguments, enhancing user trust.
- **Soundness:** Logical consistency via formal entailment tests (e.g., truth tables).

**Advantages:**
- Transparent reasoning chains.
- Verifiable against logical constraints.

---

## Limitations
1. **Uncertainty and Big Data:** Handling noisy or inconsistent data.
2. **Knowledge Acquisition:** High human effort for hand-coded rules.
3. **Real-Time Adaptability:** Challenges in dynamic contexts.
4. **Logical Inconsistencies:** Risk of internal contradictions.

---

## Discussion
The development of AI debaters requires balancing **flexibility** (retrieval/hybrid systems) with **logical rigor** (symbolic methods). While symbolic approaches ensure explainability and consistency, they often lag in scalability and adaptability. Future research should explore hybrid architectures that combine formal rigor with data-driven plasticity.

---

## Conclusion
This paper highlights the potential of **structured argumentation** and **symbolic reasoning** in AI debate systems. Techniques like Argument Graphs, ASPIC+, and Multi-Attribute Frameworks are vital for logical consistency and explainability. However, challenges in data management, knowledge acquisition, and real-time responsiveness remain. Addressing these will pave the way for AI agents capable of high-level, logical, and coherent debate.

---

## Acknowledgments
We thank John Puentes, Mihai Andries, and Christophe Lohr for their supervision and guidance.

---

## References
1- Monte-Alto, H. H. L. C., Possebom, A. T., Morveli-Espinoza, M. M. M., & Tacla, C. A. (2021). A rule-based argumentation framework for distributed contextual reasoning in dynamic environments. *DYNA, 88*(217), 120–130. [DOI:10.15446/dyna.v88n217.90858](https://doi.org/10.15446/dyna.v88n217.90858)].
2- Kulatska, I. (2019). *ArgueBot: Enabling debates through a hybrid retrieval-generation-based chatbot* [Master's thesis, University of Twente].
3- Sakai, K., Higashinaka, R., Yoshikawa, Y., Ishiguro, H., & Tomita, J. (2020). Hierarchical argumentation structure for persuasive argumentative dialogue generation. *IEICE Transactions on Information and Systems, 103*(2), 424–434.
4- Ali, B., Pawar, S., Palshikar, G. K., & Singh, R. (2022). Constructing a dataset of support and attack relations in legal arguments in court judgements using linguistic rules. In *Proceedings of the 13th Conference on Language Resources and Evaluation (LREC 2022)* (pp. 491–500). European Language Resources Association (ELRA). Retrieved from [https://www.elra.info](https://www.elra.info).
5- Kasif, S. (2024). A Trilogy of AI Safety Frameworks: Paths from Facts and Knowledge Gaps to Reliable Predictions and New Knowledge. *arXiv preprint arXiv:2410.06946*. Department of Biomedical Engineering, Program in Bioinformatics, Department of Computer Science, Boston University. [https://arxiv.org/abs/2410.06946](https://arxiv.org/abs/2410.06946).
6- Rakshit, G., Bowden, K. K., Reed, L., Misra, A., & Walker, M. (2019). Debbie, the debate bot of the future. In *Advanced Social Interaction with Agents: 8th International Workshop on Spoken Dialog Systems* (pp. 45–52). Springer.
7- Tan, C., Niculae, V., Danescu-Niculescu-Mizil, C., & Lee, L. (2016). Winning arguments: Interaction dynamics and persuasion strategies in good-faith online discussions. In *Proceedings of the 25th International Conference on World Wide Web* (pp. 613–624).
8- Engelmann, D., Damasio, J., Panisson, A. R., Mascardi, V., & Bordini, R. H. (2022). Argumentation as a method for explainable AI: A systematic literature review. In *17th IEEE Iberian Conference on Information Systems and Technologies (CISTI)* (pp. 1–6). IEEE.
9- Chalaguine, L. A., & Hunter, A. (2020). A persuasive chatbot using a crowdsourced argument graph and concerns. In *Computational Models of Argument* (pp. 9–20). IOS Press.
10- Ilkou, E., & Koutraki, M. (2020). Symbolic vs Sub-symbolic AI Methods: Friends or Enemies? In *Proceedings of the CIKM 2020 Workshops*. CEUR Workshop Proceedings. [http://ceur-ws.org](http://ceur-ws.org).
