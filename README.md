# Brandon Walters
### Applied AI Engineer | AI Security & Mission Systems

I build AI systems for environments where **reliability, security, and governance matter** — retrieval-grounded LLM applications, production ML services, human-in-the-loop decision systems, distributed machine learning, and deep-learning experiments with measurable evaluation.

My work combines hands-on AI/ML engineering with 20+ years across cybersecurity, intelligence, and secure mission systems. I focus on moving AI beyond the demo: explicit failure handling, reproducible evaluation, secure deployment patterns, and human escalation when a system should not act autonomously.

![MSDA](https://img.shields.io/badge/M.S.-Data%20Analytics%20(AI%2FML)-3E6B8A)
![BA Cert](https://img.shields.io/badge/Grad%20Cert-Business%20Analytics-3E6B8A)
![Data+](https://img.shields.io/badge/CompTIA-Data%2B-3E6B8A)
![PMP](https://img.shields.io/badge/PMI-PMP%C2%AE-3E6B8A)

**Selected results:** 100% grounded-answer rate across a 17,880-entry RAG knowledge base · macro-F1 0.760 vs. 0.042 majority-class baseline on a nine-class NLP service · Spark LinearSVC training in ~3 minutes versus ~43 minutes for nonlinear RBF SVM with a substantial minority-recall tradeoff · 91.86% test accuracy across controlled CNN architecture experiments.

## Engineering focus
- Applied AI and retrieval-augmented generation
- AI security, reliable AI, and safe-failure design
- NLP, classical ML, distributed ML, and deep learning
- Model evaluation and human-in-the-loop workflows
- FastAPI · Docker · Kubernetes · CI/CD
- Apache Spark / PySpark · scikit-learn · TensorFlow / Keras
- Secure mission and regulated environments

## Featured engineering work

| Repo | Engineering signal |
|---|---|
| [rag-capstone-qa](https://github.com/brandonwaltersai/rag-capstone-qa) | Retrieval-grounded QA with hybrid retrieval, hard citation validation, pre-generation safety escalation, and reproducible evaluation — 100% grounded-answer rate, 96.7% retrieval coverage, 88.3% escalation appropriateness |
| [ai-service-delivery](https://github.com/brandonwaltersai/ai-service-delivery) | Nine-class complaint-triage service on public CFPB data, served through FastAPI with Docker, tests, PII handling, model governance, and low-confidence human review — macro-F1 0.760 vs. 0.042 baseline |
| [distributed-ml-svm-benchmark](https://github.com/brandonwaltersai/distributed-ml-svm-benchmark) | Spark MLlib LinearSVC versus nonlinear RBF SVM under class imbalance — ~3 min versus ~43 min training, exposing the tradeoff between distributed speed/raw accuracy and minority-class recall/balanced accuracy |
| [deep-learning-computer-vision](https://github.com/brandonwaltersai/deep-learning-computer-vision) | Controlled CNN architecture experiments plus a DCGAN trained from scratch on Fashion-MNIST — 91.86% best test accuracy with generated samples, loss curves, and limitations documented |
| [deepdream-experiment-runner](https://github.com/brandonwaltersai/deepdream-experiment-runner) | Config-driven InceptionV3 DeepDream experiments with tiled gradients, failure isolation, resume behavior, quantitative image-change metrics, and documented provenance |
| [ensemble-methods-benchmark](https://github.com/brandonwaltersai/ensemble-methods-benchmark) | Bagging vs. boosting vs. stacking under class imbalance, including ROC-based threshold tuning and model-comparison tradeoffs |

<details>
<summary><b>Supporting ML and reliability studies</b></summary>

| Repo | Demonstrates |
|---|---|
| [zero-shot-reliability](https://github.com/brandonwaltersai/zero-shot-reliability) | CLIP label-set sensitivity, confidence-gap/entropy analysis, and failure modes that simple confidence thresholds miss |
| [credit-default-classification](https://github.com/brandonwaltersai/credit-default-classification) | Class weighting, cross-validation, balanced accuracy, and ROC AUC on an imbalanced credit-risk dataset |
| [bank-marketing-decision-tree](https://github.com/brandonwaltersai/bank-marketing-decision-tree) | Decision-tree tuning under class imbalance and the operational cost of optimizing the wrong metric |
| [whas500-survival-analysis](https://github.com/brandonwaltersai/whas500-survival-analysis) | Kaplan-Meier, log-rank testing, Cox proportional hazards, and concordance evaluation |

</details>

*Portfolio lists above include Brandon-authored/refactored work only. Forked repositories on this account are retained as reference material and are not presented as original portfolio projects.*

## Design philosophy
The common thread across my AI work is **safe failure over confident failure**. Unsupported RAG answers are blocked by code-level citation checks, low-confidence classifier decisions are routed to human review, and evaluation artifacts document where systems are weak rather than hiding failure modes behind aggregate metrics.

## Connect
[LinkedIn](https://www.linkedin.com/in/bw172b29208/)
