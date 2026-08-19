# Rafael Alves Cabral

**Lead AI & Machine Learning Engineer @ Klubi** · **B.Sc. in Computer Science @ Inteli** *(Full Merit Scholar)*  
São Paulo, Brazil · [LinkedIn](https://www.linkedin.com/in/rafael-alves-cabral/)

---

### About

I design, deploy, and scale **Machine Learning systems** and **autonomous AI agents** in mission-critical production.

At **Klubi**, I lead the multi-agent and real-time Voice AI platform that powers autonomous consultative sales and post-sales — now the company's **#1 sales channel** — alongside **2-stage conversion propensity & lead-ranking pipelines** (*candidate filtering + reranking*), leak-free temporal feature engineering, online A/B experimentation, and model distillation/fine-tuning (LoRA).

> **Note on commit activity:** My daily production commits run under my corporate GitHub account ([`@rafael-cabral-klubi`](https://github.com/rafael-cabral-klubi)) and private organization repositories. This profile hosts public reference implementations, academic R&D collaborations, and open-source engineering work.

---

### Production & Applied R&D Highlights

- **Klubi — Autonomous Multi-Agent, Voice AI & Conversion ML Platform *(Production)***  
  End-to-end orchestration, low-latency real-time voice (p50/p95 SLAs via LiveKit), 2-stage propensity & prioritization models evaluated via offline AUC and capacity curves, automated evals, and full observability on **Google Cloud (Vertex AI, GKE, Cloud Run, BigQuery)**, **Python**, and **TypeScript**.

- **SnackTrack — Computer Vision & Mathematical Diet Optimization *(Founder & ML Engineer)***  
  Instance segmentation and 3D food volume estimation (**YOLOv11**, **SLIC superpixels + BIC-selected Gaussian Mixture Models**, geometric pixel-to-cm calibration with IQR outlier filtering, evaluated via **mAP** and **MAPE**) paired with a real-time **Mixed-Integer Linear Programming (`PuLP`)** macro-nutrient solver, **FastAPI**, and **AWS / Terraform**.

- **BTG Pactual — Deep Reinforcement Learning for Cash & Carry Arbitrage *(R&D Partner Project)***  
  Custom **OpenAI Gym** financial environment and **Deep Q-Network (DQN)** in **TensorFlow/Keras** (`tf.GradientTape`, Target Q-Network with Polyak soft updates, 100k Experience Replay buffer, asymmetric CDI reward shaping) matching **565,000+ spot operations × 4,400+ forward contracts** toward ~100% CDI in ~10 minutes. *(Dataset/repo under partner NDA — see my [public DQN reference implementation](https://github.com/Rafael-Cabral/LUNAR-LANDER---ADALOVE)).*

- **Brastel Co., Ltd. (Tokyo) — Hybrid NLP, Intent Classification & LLM Fine-Tuning *(R&D Partner Project)***  
  Multilingual customer-support architecture (25k+ monthly users) benchmarking classical & deep classifiers (**BoW/Naive Bayes from scratch → Word2Vec + SVM → Keras LSTM → BERT**), **Llama 3.2 (3B) fine-tuning**, and **RAG** evaluation deployed on GPU microservices (**FastAPI + Docker**).

- **Stone — High-Throughput Distributed Payment Architecture *(R&D Partner Project)***  
  Queue-decoupled microservices (**Python/Flask**, **Node.js**, **AWS**) orchestrated with **Kubernetes** auto-scaling and validated under extreme national-broadcast traffic spikes via **k6** stress testing.

- **AEL Systems — High-Performance Avionics Graph Route Planner** · [`2023M5T1-Inteli/grupo2`](https://github.com/2023M5T1-Inteli/grupo2)  
  Low-altitude military trajectory optimization in **Java** implementing **A\*** search over real **DTED** terrain elevation matrices with **JGraphT**, **JHeaps**, **Neo4j**, **RabbitMQ**, **AWS S3**, and **JUnit 5**.

- **Klabin — Industrial Cutting-Stock Combinatorial Optimizer** · [`2023M6T1-Inteli/grupo3_publico`](https://github.com/2023M6T1-Inteli/grupo3_publico)  
  **Simplex** and **Knapsack** solvers built in **Java + Spring Boot 3** (JUnit 5) to minimize raw-paper waste and machine setup resets across jumbo rolls.

- **AACD — Custom Domain Compiler & Embedded IDE** · [`2023M8T1Inteli/grupo5`](https://github.com/2023M8T1Inteli/grupo5)  
  Full lexical, syntactic, and semantic analyzer + code generator built in **C# / .NET** and Docker for occupational-therapy sensory hardware.

- **Banco Pan — Supervised Churn & Propensity Modeling** · [`2022M3T1-Inteli/PanDevs`](https://github.com/2022M3T1-Inteli/PanDevs)  
  Feature engineering, hyperparameter tuning, and supervised classification over internal banking and Open Banking datasets in **Python / Scikit-Learn**.

---

### Core Stack

| Domain | Technologies |
| :--- | :--- |
| **Languages** | Python · TypeScript / Node.js · C# / .NET · Java · C++ · SQL |
| **Machine Learning & DL** | TensorFlow / Keras · PyTorch / YOLOv11 · Scikit-Learn · OpenAI Gym (RL / DQN) · PuLP (MILP) · LoRA / Distillation |
| **AI & Real-Time Voice** | Multi-Agent Systems · Mastra · Gemini / Vertex AI · LiveKit · RAG · Automated Evals & A/B Testing |
| **Data, Cloud & Infra** | Google Cloud (GKE, Cloud Run, BigQuery) · AWS · Kubernetes · Docker · Terraform · PostgreSQL · Redis / BullMQ · RabbitMQ · Neo4j |
