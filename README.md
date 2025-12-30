```{=html}
<p align="center">
```
`<img src="https://img.shields.io/badge/ML-Production-green" />`{=html}
`<img src="https://img.shields.io/badge/DevOps-CI%2FCD-blue" />`{=html}
`<img src="https://img.shields.io/badge/Deep%20Learning-Transformers-orange" />`{=html}
```{=html}
</p>
```
```{=html}
<h1 align="center">
```
🚀 End‑to‑End ML & CI/CD Projects
```{=html}
</h1>
```
```{=html}
<p align="center">
```
Fun. Practical. Deployment‑Ready. 🎯
```{=html}
</p>
```

------------------------------------------------------------------------

## 🎒 What's inside?

  -----------------------------------------------------------------------
  Project              Tech              Highlights
  -------------------- ----------------- --------------------------------
  **CI/CD with Docker  Docker · GitHub   Fully automated build → push →
  --- From Code to     Actions · AWS     deploy ⚙️
  Deployment**         ECR/EC2           

  **Windmill Blade     PyTorch ·         Industrial‑grade segmentation
  Anomaly Detection    Transformers · CV for corrosion/cracks 🌬️
  (SegFormer)**                          
  -----------------------------------------------------------------------

------------------------------------------------------------------------

# 🔥 Project 1 --- CI/CD with Docker (Code → Cloud)

### 🧭 Overview

Containerize a Spring Boot app and automate everything from build to
deployment.

### ✨ Key Takeaways

✔ Docker image builds via `Dockerfile`\
✔ Multi‑container orchestration with **Docker Compose**\
✔ GitHub Actions CI to build & test images\
✔ Secure push to **AWS ECR**\
✔ EC2 pulls & runs containers automatically\
✔ CD pipeline deploys on each push 🎉

> 💡 Designed for real‑world DevOps learning --- simple, reproducible,
> production‑like.

### ▶️ Run locally

``` bash
docker-compose up --build
```

------------------------------------------------------------------------

# 🌬️ Project 2 --- Windmill Blade Anomaly Detection (SegFormer)

### 🎯 Goal

Detect anomalies like **corrosion, cracks, erosion, wear** on turbine
blades.

### 🧠 Model

SegFormer = Transformer encoders + lightweight decoder → fast +
accurate.

### 🏗️ Training

``` bash
python train_segformer.py --config configs/segformer.yaml
```

### 🔍 Inference

``` bash
python predict.py --image sample.jpg --weights checkpoints/best_model.pth
```

Outputs saved in `outputs/` 📁

------------------------------------------------------------------------

## 🧩 Suggested Structure

    .
    ├── ci-cd-docker/
    ├── segformer-windmill/
    ├── requirements.txt
    └── README.md

------------------------------------------------------------------------

## 🛠️ Requirements

``` bash
pip install -r requirements.txt
```

> ⚠️ For CI/CD: configure AWS CLI + GitHub Secrets (`AWS_ACCESS_KEY_ID`,
> `AWS_SECRET_ACCESS_KEY`, `EC2_SSH_KEY`).

------------------------------------------------------------------------

## 🌈 Roadmap

-   🔵 Blue‑green deployments
-   📊 Monitoring (Prometheus / Grafana)
-   ✂️ Model pruning + quantization
-   🤖 Active learning

------------------------------------------------------------------------

```{=html}
<p align="center">
```
Built with ❤️, containers 🐳, and transformers 🤖
```{=html}
</p>
```
