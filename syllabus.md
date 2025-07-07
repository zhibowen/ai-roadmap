# 12-Month AI Learning Syllabus  
*A free-only playlist roadmap with check-boxes so you can tick things off each week.*

---

## 📜 How to use this file
* Do your study session → check the box `- [x]`.  
* Edit freely—add links, dates, or extra resources you discover.  
* Each “Search:” line is a **YouTube search string** (safer than hard-coding URLs, which break).

---

## Phase 0 – Boot-up  *(Weeks 1-2)*  
> Goal: Refresh Python, math & git workflow before diving into ML.

- [x] **Search:** `Learn Python for Data Science freeCodeCamp full course`  
- [ ] **Search:** `Mathematics for Machine Learning Imperial Linear Algebra`  
- [ ] Re-implement softmax and cross-entropy in pure Python  
- [ ] Set up `ai-roadmap` conda env + push first notebook to GitHub  

---

## Phase 1 – Core Machine Learning  *(Weeks 3-8)*  
> Goal: Classical algorithms, overfitting intuition, first Kaggle submission.

| Week | Watch | Do |
|------|-------|----|
| 3 | **Search:** `Stanford CS229 Machine Learning Andrew Ng playlist` | Logistic-regression assignment |
| 4 | (continued CS229) | Implement k-NN & decision-tree from scratch |
| 5 | **Search:** `StatQuest Machine Learning playlist` (use as concept refreshers) | Kaggle *Titanic* EDA |
| 6 | CS229 SVM lecture | Ship *Titanic* model & hit top 25 % |
| 7 | Ensemble methods video | Mini-project: gradient-boost on your own dataset |
| 8 | Wrap-up & review | Mid-phase reflection blog-post |

---

## Phase 2 – Deep-Learning Foundations  *(Weeks 9-16)*  
> Goal: CNNs, optimisation tricks, regularisation.

- [ ] **Search:** `MIT 6.S191 Introduction to Deep Learning 2025` (7 lectures)  
- [ ] **Search:** `Practical Deep Learning for Coders 2025 fast.ai Lesson 1+`  
- [ ] Train ResNet-34 on CIFAR-10 with 1-cycle scheduler  
- [ ] Write a blogpost: “What I learned training my first CNN”  

---

## Phase 3 – NLP & Transformers  *(Weeks 17-28)*  
> Goal: Word embeddings → attention → build a mini-Transformer.

| Block | Watch | Build |
|-------|-------|-------|
| 17-20 | **Search:** `Stanford CS224n Spring 2024 playlist` | Word2Vec & GloVe notebook |
| 21-24 | (CS224n transformer lectures) | **Mini-Transformer (<150 lines)** |
| 25-26 | **Search:** `Hugging Face LLM crash-course` | Fine-tune 7 B Llama-3 with LoRA |
| 27-28 | **Search:** `Stanford CS25 Transformers United V5 playlist` (pick 2 talks) | Paper-style report on your fine-tune |

---

## Phase 4 – Advanced LLMs & Gen-AI Apps  *(Weeks 29-40)*  
> Goal: Retrieval-augmented generation (RAG), evaluation & cost dashboards.

- [ ] **Search:** `LLM Bootcamp The Full Stack Spring 2023`  
- [ ] **Search:** `Local Retrieval-Augmented Generation from Scratch tutorial`  
- [ ] Build an end-to-end RAG chatbot (vector DB + RTX 4070 inference)  
- [ ] Instrument latency, cost and hallucination metrics – export Grafana board  

---

## Phase 5 – MLOps & Production  *(Weeks 41-48)*  
> Goal: Containerise, deploy, monitor; compare on-prem vs cloud TCO.

| Task | Tick |
|------|------|
| **Search:** `MLOps Community playlist` |
| **Search:** `Google Cloud Generative AI for Developers playlist` |
| Build Dockerfile with `nvidia-container-toolkit` |
| Deploy Phase-4 chatbot on GCP Vertex AI or AWS EKS |
| Set up Prometheus + Grafana GPU dashboards |
| Write cost-of-ownership memo (local 4070 vs rented A100) |

---

## Phase 6 – Strategy & Leadership  *(Weeks 49-52)*  
> Goal: Translate tech depth into business strategy & org design.

- [ ] **Search:** `MIT Sloan Artificial Intelligence Implications for Business Strategy`  
- [ ] **Search:** `Wharton AI and the Future of Work conference`  
- [ ] Draft a 12-page AI adoption roadmap for an automotive subsidiary  
- [ ] Present findings at a local Berlin MLOps meet-up  

---

## 📚 Weekly Paper Club (standing item)
1. Read **one** seminal or SOTA paper each Tuesday.  
2. Capture a 5-minute summary (bullet-point or voice note).  
3. Tick below:

```text
- [ ] Week 1  Attention Is All You Need (2017)
- [ ] Week 2  BERT (2018)
- [ ] Week 3  Scaling
