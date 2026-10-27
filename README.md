## Hi, I'm Mohammad 👋

**MSc Artificial Intelligence student** at the University of Surrey (77% average, Distinction level; completing Feb 2027), with an IEEE publication in medical image classification. Available for graduate and junior ML/AI engineering roles from February 2027.

I build models that are accurate, efficient and shippable: real-time computer vision deployed with C++ and TensorRT, self-supervised and compressed models for industrial sensing, LLM and NLP fine-tuning, and inference services with tests, CI/CD and monitoring.

🗣️ Arabic (native) · English (fluent) · Turkish (basic)

---

### Featured work
<p align="center">
<a href="https://github.com/mohammadabdalaziz241/drone-tracking-tensorrt">
<img src="https://raw.githubusercontent.com/mohammadabdalaziz241/drone-tracking-tensorrt/main/docs/media/demo.gif" width="560" alt="Multi-object tracking on drone video: boxes, track IDs and trajectories">
</a>
<br>
<sub>Real-time drone video tracking: YOLO11s served by a C++ TensorRT engine, with BoT-SORT tracking.</sub>
</p>

| Project | What it shows | Highlights |
|---|---|---|
| [**Real-Time Drone Detection and Tracking with TensorRT**](https://github.com/mohammadabdalaziz241/drone-tracking-tensorrt) | Small-object detection and multi-object tracking in drone video, deployed with a custom C++/CUDA TensorRT engine | **3.9 ms per frame** (257 FPS) · **+49% mAP** from 1280 px training · tracking score (HOTA) **41.0 → 53.7** with **89% fewer ID switches** on held-out data |
| [**RotorMamba / Lightweight PC-STE**](https://github.com/mohammadabdalaziz241/Lightweight-PCSTE) | Self-supervised Mamba encoder for machine fault diagnosis, compressed for deployment (MSc dissertation) | **95.5% Macro-F1** across 4 datasets · **1.9× faster** on CPU · **1.53 MiB** after INT8 quantisation |
| [**Review Classifier Service**](https://github.com/mohammadabdalaziz241/review-classifier-service) | Production ML: a RoBERTa API on AWS, end to end | FastAPI · Docker · Terraform · CI/CD · Prometheus/Grafana · **+79% throughput** with dynamic batching |
| [**Cross-Variety Sentiment and Sarcasm Classification**](https://github.com/mohammadabdalaziz241/cross-variety-sentiment-sarcasm) | Transformer and LLM fine-tuning across English varieties (group project) | RoBERTa **0.90 Macro-F1** · Gemma-2-2B 4-bit LoRA · Gradio demo |
| [**Few-Shot Prompt Learning for CLIP (CoOp)**](https://github.com/mohammadabdalaziz241/clip-coop-prompt-learning) | Few-shot vision-language adaptation (my component of a group project) | **64.9% → 83.5%** mean accuracy over 8 datasets · ensembles & Model Soups |

📄 **Publication:** [A Two-Stage Hierarchical Skin Lesion Classification Using Transfer Learning](https://doi.org/10.1109/ICIT64950.2025.11049224), IEEE ICIT 2025 (2nd author)

---

### Tools I use

- **ML:** Python · PyTorch · TensorFlow/Keras · Hugging Face Transformers · PEFT (LoRA/QLoRA) · scikit-learn
- **Computer vision:** YOLO · multi-object tracking (BoT-SORT, ByteTrack) · OpenCV · CLIP · ViT
- **Efficiency:** C++17 · CUDA · TensorRT (FP16/INT8) · ONNX · knowledge distillation · INT8 quantisation · latency profiling · dynamic batching
- **Deployment:** FastAPI · Docker · PostgreSQL · AWS (EC2, ECR, CloudWatch) · Terraform · GitHub Actions · Prometheus · Grafana

📫 [LinkedIn](https://www.linkedin.com/in/mohammad-abdalaziz) · [Google Scholar](https://scholar.google.com/citations?user=3Y3BcXcAAAAJ) · mohammmed.abdalaziz.24@gmail.com
