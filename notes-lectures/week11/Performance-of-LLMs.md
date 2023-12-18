## Performance of LLMs

### [How to Evaluate LLMs: A Complete Metric Framework](https://www.microsoft.com/en-us/research/group/experimentation-platform-exp/articles/how-to-evaluate-llms-a-complete-metric-framework/)

#### focusing on estimating costs;

- Cost = GPU Utilization
- ChatGPT a token is about .75 words
- Prompt tokens + Completion tokens = total tokens (cost)

#### assessing customer risk and;

https://learn.microsoft.com/en-us/azure/machine-learning/concept-responsible-ai?view=azureml-api-2

"Microsoft has developed a Responsible AI Standard. It's a framework for building AI systems according to six principles: fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability. For Microsoft, these principles are the cornerstone of a responsible and trustworthy approach to AI, especially as intelligent technology becomes more prevalent in products and services that people use every day."

"A crucial part of transparency is interpretability: the useful explanation of the behavior of AI systems and their components. Improving interpretability requires stakeholders to comprehend how and why AI systems function the way they do. The stakeholders can then identify potential performance issues, fairness issues, exclusionary practices, or unintended outcomes."

#### quantifying the added user value.

### [The Guide To LLM Evals: How To Build and Benchmark Your Evals](https://towardsdatascience.com/llm-evals-setup-and-the-metrics-that-matter-2cc27e8e35f3)

#### LLM Model Evals

"focused on the overall performance of the foundational models."

LLM leaderboards

#### LLM System Evals

"hold the LLM constant and change the prompt template. Since prompts are more dynamic parts of your system, this evaluation makes a lot of sense throughout the lifetime of the project."

- Extracting structured information: You can look at how well the LLM extracts information. For example, you can look at completeness (is there information in the input that is not in the output?).
- Question answering: How well does the system answer the user's question? You can look at the accuracy, politeness, or brevity of the answer --- or all of the above.
- Retrieval Augmented Generation (RAG): Are the retrieved documents and final answer relevant?

#### How To Build An LLM Eval

Need a labeled dataset to test the LLM. This is the trickiest part.

### [Language Models are Changing AI: The Need for Holistic Evaluation](https://crfm.stanford.edu/2022/11/17/helm.html)

"We believe holistic evaluation involves three elements:

1.  Broad coverage and recognition of incompleteness. Given language models' vast surface of capabilities and risks, we need to evaluate language models over a broad range of scenarios. However, it is not possible to consider all the scenarios, so holistic evaluation should make explicit all the major scenarios and metrics that are missing.
2.  Multi-metric measurement. Societally beneficial systems are characterized by many desiderata, but benchmarking in AI often centers on one (usually accuracy). Holistic evaluation should represent these plural desiderata.
3.  Standardization. Our object of evaluation is the language model, not a scenario-specific system. Therefore, in order to meaningfully compare different LMs, the strategy for adapting an LM to a scenario should be controlled for. Further, we should evaluate all the major LMs on the same scenarios to the extent possible."

### [BLEU: a Method for Automatic Evaluation of Machine Translation](https://aclanthology.org/P02-1040.pdf)

"To judge the quality of a machine translation, one measures its closeness to one or more reference human translations according to a numerical metric. Thus, our MT evaluation system requires two ingredients:

1.  a numerical "translation closeness" metric
2.  a corpus of good quality human reference translations"

### [Evaluating Large Language Models: A Comprehensive Survey](https://arxiv.org/pdf/2310.19736.pdf)

- "They could suffer from private data leaks or yield inappropriate, harmful, or misleading content."

### [Training Socially Aligned Language Models in Simulated Human Society](https://arxiv.org/pdf/2305.16960.pdf)

- an alternative to "Reinforcement Learning from Human Feedback" (RLHF) train an LLM in a simulated human society

"In contrast to these methods (), humans acquire social norms and values through social interactions---we interact, receive feedback, and adjust our behaviors to create positive impressions."

"We create a simulated human society, SANDBOX, comprising numerous LM-based social agents interacting and we record their behaviors. The recorded interaction data is distinct from traditional alignment data; it includes not only aligned and misaligned demonstrations but also collective ratings, detailed feedback, and iteratively revised responses."
