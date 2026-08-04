# Minsun Park

**Data Scientist — Recommendation, Ranking & ML Systems** at Kakao Style (AI Search & Recommendation)

🌐 **[minsun-park.github.io](https://minsun-park.github.io)** — full resume (KR / EN)

I build recommendation and search systems end to end — candidate retrieval, embedding-based ranking, and production serving at scale — and I'm currently extending into ads-facing ranking and user representation learning.

> 💡 My day-to-day work ships through my company's private org, so the commit graph here doesn't reflect it. This account hosts my research and selected personal work.

## 🚀 Production highlights

- **User size prediction system** serving millions of users daily — recommendation coverage 80% → 90%, ~91% top-3 accuracy validated on 10M+ purchase records
- **Similar-store recommendation engine** blending text, SVD, and Fashion-CLIP embeddings in an OpenSearch kNN stack — batch runtime cut 80%
- **Recommender pipeline migration** from SageMaker to LightGCN on MLflow — training time −74%, embedding API cost −67%; KServe (Kubernetes) serving with a Kafka real-time pipeline
- Earlier: **CTR-prediction personalization**, product-to-query retrieval (BERT, DPR, ColBERT), and demand forecasting shipped at an e-commerce company

## 🔬 Research

M.S. student in Applied Artificial Intelligence, Korea University. Thesis in progress on **filtered approximate nearest neighbor search over HNSW indexes** — a problem I also operate against in production vector search.

| Repo | What it is |
|---|---|
| [filtered-ann-hnsw](https://github.com/minsun-park/filtered-ann-hnsw) | **Active thesis work** — quantifying HNSW recall collapse and cost inversion under metadata filtering (SIFT-128, ann-benchmarks) |
| [csrec-fashion-exploration](https://github.com/minsun-park/csrec-fashion-exploration) | Archived exploration — causal sequential recommendation (CSRec, SIGIR 2025) for fashion; superseded after finding synthetic interventional data inflates offline metrics |

The two repos together are the research trail: explored causal recommendation, hit a data-validity wall, and pivoted to a benchmark-reproducible retrieval problem.

## 🛠 What I work with

`Python` `SQL` `Spark/PySpark` `TensorFlow` `MLflow` `OpenSearch (kNN)` `Airflow` `Databricks` `Kafka` `Kubernetes (KServe)` `GCP (BigQuery)` `AWS`

## 📫 Contact

[minsun-park.github.io](https://minsun-park.github.io) · parkminsun0508@gmail.com · [LinkedIn](https://www.linkedin.com/in/%EB%AF%BC%EC%84%A0-%EB%B0%95-467333237/)
