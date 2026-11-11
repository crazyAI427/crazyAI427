<h1 align="center">Hi, I'm crazyAI 👋</h1>
<h3 align="center">AI Engineer · LLM Engineer · MLOps<br/>I build LLM systems and ML platforms that run in production: RAG assistants, agentic workflows, search ranking, and RL post-training.</h3>

<p align="center">
  <img src="https://img.shields.io/badge/LLM-RAG%20%7C%20Agents%20%7C%20Guardrails-6E40C9?style=flat-square" />
  <img src="https://img.shields.io/badge/Post--Training-SFT%20%7C%20DPO%20%7C%20GRPO-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/MLOps-SageMaker%20%7C%20Databricks%20%7C%20K8s%20%2B%20Ray-1F883D?style=flat-square" />
  <img src="https://img.shields.io/badge/Bittensor-Miner-000000?style=flat-square" />
</p>

---

## 🧠 About me

I'm an AI/LLM engineer who works across the whole lifecycle: data pipelines, model training, serving, monitoring and infrastructure as code.

- 🤖 **LLM applications:** production RAG shopping assistants, multi-agent data-science workflows, guardrails and LLM tracing/evaluation
- 🎯 **LLM post-training:** SFT, DPO and GRPO with TRL + LoRA, vLLM, DeepSpeed, and RL environments for multi-turn game-playing agents
- 🔎 **Search & ranking:** BERT/mBERT relevance scoring, CLIP visual similarity and popularity sorting for e-commerce search
- ⚙️ **MLOps:** SageMaker Pipelines and endpoints, Databricks/Spark, Terraform/Terragrunt, Jenkins CI/CD, Docker, GKE + Ray, DVC, load testing

---

## 💼 Experience

### 🛍️ Nike: Search, Ranking & GenAI (AWS)

- **AI shopping assistant:** a LangChain/LangGraph RAG assistant with tool calling, on AWS Bedrock and OpenAI models. It has a knowledge base, guardrails, follow-up prompt generation, Arize Phoenix tracing and an evaluation setup, served through FastAPI with a React/Next.js frontend and deployed with Terraform, Lambda and Jenkins.
- **Search relevance (SCORE) models:** BERT and sentence-transformer relevance models trained in SageMaker and Databricks pipelines. Deployment is event-driven: an S3 trigger runs Lambda, which starts an ECS task that deploys SageMaker endpoints. Includes Terraform, Jenkins rollback and Locust load tests.
- **Multilingual search (mBERT):** end-to-end SageMaker Pipelines covering ETL, Feature Store ingestion, training, evaluation, model registration, batch inference and model cards.
- **Visual similarity search:** CLIP image embeddings and product recommendations, with scheduled data refresh and SageMaker inference behind API Gateway.
- **Popularity sort service:** Spark feature pipelines, SageMaker serving and DynamoDB lookups, with infrastructure managed in Terragrunt.

### 📊 Avaloka AI: Multi-Agent Data Analyst

- **Datagent:** a YAML-defined, graph-based multi-agent framework (planner, data-processor, training-planner and trainer agents, plus routers). It streams events over FastAPI SSE to a React frontend.
- **Training jobs:** the agents launch model training on GKE + Ray clusters with Kubernetes manifests and store artifacts in GCS. LLM backends are OpenAI and Groq.

### 🧪 Oddity (Voyage81): AI Product Pipelines

- Production ML pipelines for hyperspectral and color imaging products: multi-camera ingestion, ETL, triage, and per-brand product models.
- Engineering practices: DVC for data versioning, CircleCI with coverage gates, and pytest.

### 👄 LiRA: Visual Speech Recognition

- A lip-reading phrase classifier: face and mouth-ROI cropping, a ResNet-based video model in PyTorch Lightning, and a Flask inference API.

---

## ⛏️ Bittensor: Decentralized AI Mining

I compete as a miner on Bittensor subnets, where models are trained, evaluated and rewarded on chain.

- **Gradients / G.O.D:** I compete in the text, image and environment tournaments. That covers SFT, DPO and GRPO training pipelines in Docker under hard time limits, and per-model hyperparameter tables.
  → [Merged_env_tourn_13-20](https://github.com/crazyAI427/Merged_env_tourn_13-20) · [env release 1](https://github.com/crazyAI427/Gradients_RL_tournament-4_20_env_release_1) · [env release 2](https://github.com/crazyAI427/Gradients_RL_tournament-4_20_env_release_2)
- **Affine:** an OpenSpiel game environment that scores LLM agents against MCTS opponents.
  → [mcts-api](https://github.com/crazyAI427/mcts-api)
- **RL for game-playing LLMs:** GRPO with curriculum learning and opponent modeling across Gin Rummy, Liar's Dice, Leduc Poker, Goofspiel and ALFWorld.
  → [grpo-simple](https://github.com/crazyAI427/grpo-simple)
- **Swarm:** autonomous drone-navigation policy submissions.

---

## 🚀 Open-source projects

| Project | What it does | Stack |
|---|---|---|
| [**grpo-simple**](https://github.com/crazyAI427/grpo-simple) | Teaches Qwen3-0.6B to play Liar's Dice and Gin Rummy with GRPO, step by step | TRL · LoRA · PyTorch |
| [**Merged_env_tourn_13-20**](https://github.com/crazyAI427/Merged_env_tourn_13-20) | A containerized GRPO trainer with live game-environment rollouts | TRL · vLLM · DeepSpeed · Docker |
| [**mcts-api**](https://github.com/crazyAI427/mcts-api) | OpenSpiel evaluation of LLM strategic play | OpenSpiel · Docker |
| [**Vision_Path_Planning**](https://github.com/crazyAI427/Vision_Path_Planning) | SegFormer drivable-road segmentation and waypoint planning | Transformers · OpenCV |
| [**Segment_based_path_planning**](https://github.com/crazyAI427/Segment_based_path_planning) | Cityscapes segmentation for dashcam scenes | SegFormer · PyTorch |
| [**custom_AI_chunking**](https://github.com/crazyAI427/custom_AI_chunking) | Semantic document chunking for RAG | Python · Flask |

---

## 🛠️ Tech stack

**LLM & GenAI**

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/TRL-FF9D00?style=flat-square" />
  <img src="https://img.shields.io/badge/PEFT%20%2F%20LoRA-8A2BE2?style=flat-square" />
  <img src="https://img.shields.io/badge/vLLM-30A2FF?style=flat-square" />
  <img src="https://img.shields.io/badge/DeepSpeed-0A66C2?style=flat-square" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square" />
  <img src="https://img.shields.io/badge/AWS%20Bedrock-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
  <img src="https://img.shields.io/badge/Arize%20Phoenix-6E40C9?style=flat-square" />
</p>

**MLOps & Cloud**

<p>
  <img src="https://img.shields.io/badge/SageMaker-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Ray-028CF0?style=flat-square&logo=ray&logoColor=white" />
  <img src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/DVC-13ADC7?style=flat-square&logo=dvc&logoColor=white" />
  <img src="https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black" />
</p>

**Languages & Tooling**

<p>
  <img src="https://skillicons.dev/icons?i=python,bash,docker,aws,gcp,linux,git,githubactions,jenkins,fastapi,react&perline=11" />
</p>

**Computer Vision**

<p>
  <img src="https://img.shields.io/badge/YOLO-00FFFF?style=flat-square&logoColor=black" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/CLIP-412991?style=flat-square" />
  <img src="https://img.shields.io/badge/SegFormer-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/PyTorch%20Lightning-792EE5?style=flat-square&logo=lightning&logoColor=white" />
</p>
