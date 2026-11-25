## Hi, I'm Rishikesh

B.Tech CSE (Data Science) student at **NMIMS STME Hyderabad**. I build machine-learning systems and measure where they work and where they don't: calibrated confidence, statistical guarantees, honest evaluation. I also build the full-stack software that turns them into usable products.

- **Focus:** reliable AI, including conformal prediction, risk-controlled automation, retrieval-grounded LLMs and computer vision
- **Also build:** FastAPI and React applications, PostgreSQL / PostGIS / pgvector backends, and AWS deployments
- **How I work:** frozen splits, pre-registered hypotheses, reproducible figures, and results reported even when they are negative

---

### Featured projects

**[Certus](https://github.com/Rishikesh10925/Certus)** · *Computer vision · Uncertainty quantification*<br>
A conformal risk-control layer over frozen vision-language models (CLIP, Qwen2-VL, OWLv2) that decides which building-defect images can skip human review, with a finite-sample bound on missed defects. It also measures how that bound breaks under site shift (2–3× ε) and which corrections repair it. 100-seed experiments, 220 tests, FastAPI triage service at 98 ms p95.
`PyTorch` `conformal prediction` `FastAPI` `Streamlit` `DVC`

**[TicketSense](https://github.com/Rishikesh10925/Ticket_Sense)** · *LLMs · RAG · Full-stack* · team of 3<br>
Routes IT and HR tickets, drafts cited replies from a department-scoped knowledge base with a local LLM, checks every claim against its evidence with NLI, then uses a calibrated 31-signal confidence gate with Learn-then-Test thresholds to decide whether an engineer sees the draft. Routing macro-F1 0.91, 0 of 40 prompt-injection attacks reach an engineer, and a sealed test run once.
`LangGraph` `Ollama` `pgvector` `FastAPI` `React + TypeScript`

**[PRISM](https://github.com/Rishikesh10925/PRISM)** · *Computer vision · Geospatial · Full-stack*<br>
Pothole segmentation (YOLOv8n-seg, test mask mAP@0.5 0.685) with interpretable severity scoring (area, MiDaS depth, irregularity) and a repair-priority ranking that combines OpenStreetMap road type and PostGIS recurrence. Includes a citizen upload portal, an admin map with live priority sliders, PDF reports and 203 tests.
`YOLOv8` `SAM` `FastAPI` `PostGIS` `React + Leaflet`

**[Signal](https://github.com/Rishikesh10925/Sentiment_Analysis)** · *NLP · Data engineering · Explainability*<br>
A sentiment analytics workbench over 1.65 M real X/Twitter and Reddit posts: curation pipeline, TF-IDF and DistilBERT baselines, aspect-based sentiment, SHAP/LIME explanations with a faithfulness test, and a three-arm PySpark benchmark behind a React dashboard.
`scikit-learn` `PySpark` `SHAP` `FastAPI` `React + TypeScript`

**[ResultCloud](https://github.com/Rishikesh10925/Result_management)** · *Cloud · Full-stack*<br>
A student result management system on AWS (EC2, RDS, S3, IAM, CloudWatch) with Student, Faculty and Admin roles, PDF marksheets and Terraform for the whole stack. Its tests check the GPA engine against the reference implementation's outputs.
`Flask` `React` `Terraform` `AWS`

<details>
<summary><b>More projects</b></summary>
<br>

| Project | What it is | Stack |
|---|---|---|
| [Hackathon Platform](https://github.com/Rishikesh10925/hackathon-platform) | Event, team and judge management with event-scoped judging and live leaderboards | React, Cognito, Lambda, API Gateway, DynamoDB |
| [Real vs. Fake Face Detector](https://github.com/Rishikesh10925/Real-vs-Fake-image-detector) | MobileNetV2 transfer learning with Grad-CAM explanations, with its overfitting analysed openly | TensorFlow, Streamlit |
| [Password Security Auditor](https://github.com/Rishikesh10925/Adsa_password) | Client-side batch password auditing using hash maps, pattern normalisation and entropy | React, Vite |
| [Dijkstra Routing Visualizer](https://github.com/Rishikesh10925/Dijkstra-and-Link-State-Routing-Visualizer) | Step-through Dijkstra that builds a link-state routing table | Python, Pygame |
| [Xpot](https://github.com/Rishikesh10925/Xpot) | Three-sided parking booking app for drivers, owners and admins | Android, Java, SQLite |
| [REMA](https://github.com/Rishikesh10925/Dbms_Project) | Real-estate listing and transaction system on a relational schema | PHP, MySQL, Docker |

</details>

---

### Skills

| Area | Tools |
|---|---|
| **Languages** | Python · TypeScript · JavaScript · SQL · Java · PHP |
| **ML & AI** | PyTorch · TensorFlow/Keras · scikit-learn · XGBoost · Ultralytics YOLO · sentence-transformers · vision-language models (CLIP, Qwen2-VL, OWLv2) |
| **LLM systems** | LangGraph · Ollama · retrieval (pgvector, rerankers) · NLI claim checking |
| **Reliability & evaluation** | Conformal prediction · risk control (CRC, Learn-then-Test) · calibration · bootstrap CIs · SHAP / LIME |
| **Data** | PostgreSQL · pgvector · PostGIS · MySQL · SQLite · PySpark · DVC |
| **Backend** | FastAPI · Flask · SQLAlchemy · Alembic · REST · JWT auth |
| **Frontend & mobile** | React · Vite · Tailwind CSS · Leaflet · Streamlit · Android |
| **Cloud & DevOps** | AWS (EC2, RDS, S3, IAM, CloudWatch, Lambda, API Gateway, DynamoDB, Cognito) · Terraform · Docker · GitHub Actions · Nginx |

---

### Contact

[rishikeshtalpalikar@gmail.com](mailto:rishikeshtalpalikar@gmail.com) · [github.com/Rishikesh10925](https://github.com/Rishikesh10925)
