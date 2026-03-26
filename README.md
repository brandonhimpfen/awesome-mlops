# Awesome MLOps [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of tools, frameworks, platforms, and resources for Machine Learning Operations (MLOps).

MLOps stands at the intersection of machine learning, DevOps, and data engineering. This list is intended for ML engineers, data scientists, DevOps practitioners, and anyone building, deploying, monitoring, and scaling machine learning systems.

## Contents

- [General Resources](#general-resources)
- [Model Development & Experiment Tracking](#model-development--experiment-tracking)
- [Model Deployment](#model-deployment)
- [Model Monitoring](#model-monitoring)
- [Model Governance & Fairness](#model-governance--fairness)
- [Data Versioning & Management](#data-versioning--management)
- [CI/CD for ML](#cicd-for-ml)
- [Frameworks & Platforms](#frameworks--platforms)
- [Courses & Learning](#courses--learning)
- [Related Awesome Lists](#related-awesome-lists)

## General Resources

- [MLOps Guide by Google](https://cloud.google.com/architecture/mlops-continuous-delivery-and-automation-pipelines-in-machine-learning) – Google's foundational guide to implementing MLOps.
- [ml-ops.org](https://ml-ops.org/) – Open source resource defining MLOps best practices.
- [Hidden Technical Debt in Machine Learning Systems (paper)](https://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.pdf) – Seminal research on operational complexity in ML.

## Model Development & Experiment Tracking

- [MLflow](https://mlflow.org/) – Open-source platform for managing the ML lifecycle, including experimentation and reproducibility.
- [Weights & Biases](https://wandb.ai/) – Experiment tracking, model management, and collaboration tools.
- [Neptune.ai](https://neptune.ai/) – Metadata store for ML experiments.
- [Comet](https://www.comet.com/) – Experiment tracking, model optimization, and monitoring.
- [Sacred](https://github.com/IDSIA/sacred) – Lightweight experiment configuration and tracking tool.

## Model Deployment

- [Seldon Core](https://github.com/SeldonIO/seldon-core) – Deploy machine learning models on Kubernetes.
- [KFServing (KServe)](https://github.com/kserve/kserve) – Kubernetes-based model serving with autoscaling and inference graph support.
- [BentoML](https://github.com/bentoml/BentoML) – Framework for serving, optimizing, and deploying ML models.
- [MLServer](https://github.com/SeldonIO/MLServer) – Fast and lightweight inference server for deploying ML models.
- [Triton Inference Server](https://developer.nvidia.com/nvidia-triton-inference-server) – Scalable GPU/CPU inference server by NVIDIA.

## Model Monitoring

- [Evidently](https://github.com/evidentlyai/evidently) – Monitor data drift, model performance, and fairness.
- [WhyLabs](https://whylabs.ai/) – Observability for ML models and data.
- [Arize AI](https://arize.com/) – ML performance and drift monitoring platform.
- [Fiddler AI](https://www.fiddler.ai/) – Explainable AI and monitoring for production ML models.
- [Weco Observe](https://weco.ai) – AI-powered observability platform for monitoring and improving ML model performance in production.

## Model Governance & Fairness

- [AI Fairness 360](https://github.com/IBM/AIF360) – IBM's toolkit for detecting and mitigating bias in ML models.
- [Fairlearn](https://fairlearn.org/) – Python library for assessing and improving fairness.
- [Model Cards for Model Reporting](https://github.com/google/model-card-toolkit) – Framework for transparent model documentation.
- [Audit-AI](https://github.com/pymetrics/audit-ai) – Bias and discrimination auditing for models.

## Data Versioning & Management

- [DVC (Data Version Control)](https://dvc.org/) – Git-like version control for datasets and ML pipelines.
- [LakeFS](https://lakefs.io/) – Git-like operations for data lakes.
- [Delta Lake](https://delta.io/) – Reliable data lakes with ACID transactions and time travel.
- [Pachyderm](https://www.pachyderm.com/) – Data versioning and lineage for ML pipelines.
- [Feast](https://feast.dev/) – Feature store for production ML.

## CI/CD for ML

- [ZenML](https://zenml.io/) – MLOps framework for reproducible, production-ready pipelines.
- [Metaflow](https://metaflow.org/) – Netflix-developed tool for real-world ML pipelines.
- [Kubeflow Pipelines](https://www.kubeflow.org/) – End-to-end ML workflows on Kubernetes.
- [Flyte](https://flyte.org/) – Scalable and structured workflows for ML and data processing.
- [Dagster](https://dagster.io/) – Data orchestrator for machine learning, analytics, and ETL.

## Frameworks & Platforms

- [Tecton](https://www.tecton.ai/) – Enterprise-grade feature store.
- [Airflow](https://airflow.apache.org/) – Workflow orchestration for ETL and ML pipelines.
- [Dagster](https://dagster.io/) – Build and monitor data applications and ML systems.
- [Metaflow](https://metaflow.org/) – Human-centric workflow tool for ML.
- [Valohai](https://valohai.com/) – MLOps platform for managing reproducible machine learning workflows from experimentation to production, with support for pipeline orchestration, tracking, and deployment.
- [AIDE](https://github.com/WecoAI/aideml) – AI-driven automated machine learning agent that uses tree search to iteratively improve code and models for ML tasks.
  
## Courses & Learning

- [Coursera – MLOps Specialization by DeepLearning.AI](https://www.coursera.org/specializations/mlops) – Learn to build, deploy, and monitor ML systems at scale.
- [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) – Free course to learn MLOps from scratch.
- [Full Stack Deep Learning](https://fullstackdeeplearning.com/) – Covers the full lifecycle of deep learning projects.
- [Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning) – Companion list with tutorials and practical guides.

## Related Awesome Lists

- **[Awesome LLMOps](https://github.com/awesomelistsio/awesome-llmops)** – Resources focused on managing large language models in production.
- **[Awesome Prompt Engineering](https://github.com/awesomelistsio/awesome-prompt-engineering)** – Techniques and tools for prompt design.
- **[Awesome AI Infrastructure](https://github.com/awesomelistsio/awesome-ai-infrastructure)** – Tools for managing AI pipelines and infra.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
