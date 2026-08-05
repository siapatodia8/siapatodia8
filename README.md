# Hi, I'm Sia

**Data Science + Math @ UC San Diego**

I build ML systems and AI agents.

📫 patodiasia8@gmail.com · 🔗 [LinkedIn](https://www.linkedin.com/in/sia-patodia/)

---

## Selected Projects

### [Personalized Supplement Recommender](https://github.com/kevinkchen1/Personalized-Supplement-Recommender) · 4-person team, 2 Deloitte mentors

Multi-agent system that flags dangerous supplement–medication interactions and recommends supplements, grounded in a 330K-node biomedical knowledge graph built from biomedical data.

**I owned** the data → knowledge graph layer (data collection, ingestion, Neo4j schema) and the LangGraph agent workflow — supervisor routing, entity extraction and normalization, deficiency agent, and the LLM-based safety-check tool. → [my commits](https://github.com/kevinkchen1/Personalized-Supplement-Recommender/commits?author=siapatodia8)

### [Stock Market Decoder](https://github.com/siapatodia8/stock-market-decoder) · solo

Dashboard that explains *why* a stock moved: monthly price history mapped to the SEC filings and press releases behind it, with a grounded chat that answers questions using only retrieved source passages.

FastAPI backend over a HydraDB knowledge graph, three-stage retrieval-and-synthesis chat pipeline, and a React/D3 frontend. Built as a hands-on evaluation of HydraDB, so the repo also documents where the SDK and retrieval broke down.

### [FinanceMyths](https://github.com/ShaheerAlamKhan/FinanceMyths) · 3-person course project (DSC 148)

Scrollable data-journalism site testing three common personal-finance beliefs against 20+ years of income and wealth data from SWIID, the BEA, and the Fed's Survey of Consumer Finances.

**I owned** the redistribution analysis: paired t-test and OLS on market vs. disposable Gini across countries, derived absolute and relative redistribution metrics, and shipped it as a D3 choropleth plus a written report. → [my commits](https://github.com/ShaheerAlamKhan/FinanceMyths/commits?author=siapatodia8)

### [Team TBD](https://github.com/acmucsd-projects/Team-TBD) · ACM AI quarterly project, 6-person team

NLP model that predicts Myers-Briggs personality type from free text, packaged into a Streamlit app.

**I built** the V0 classification pipeline — BERT tokenization and the initial training loop the team iterated on from there.

### [Credit Card Fraud Detection](https://github.com/siapatodia8/credit_card_fraud) · 2-person course project (DSC 148)

Fraud classifier on a heavily imbalanced transaction dataset (0.17% positive class), tuned for catching fraud without drowning analysts in false positives.

**I owned** the class-imbalance work and modeling — SMOTE, undersampling, and SMOTEENN comparisons, then logistic regression and LinearSVC with grid-searched hyperparameters, evaluated on precision-recall rather than accuracy.

---

*Currently interested in: AI agents, retrieval systems, and applied ML. Always happy to talk!*
