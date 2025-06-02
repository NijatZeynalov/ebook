**Introduction**
**Why This Guide?**
The world of AI is growing fast. As models get bigger and more powerful, we also need better ways to run them quickly, use less memory, and serve them in real-world systems. Models like large language models (LLMs), image-text models, and transformers are now used in many areas—such as language tasks, computer vision, and generative AI.

But using these models in real applications is not just about building them. To get good performance, you also need to understand how GPUs work, how to write efficient code, how to use the right tools for running models, and how to manage systems that use many GPUs or machines.

This guide helps you learn all of that.

Whether you're an ML engineer working on model serving, a researcher trying to make training faster, or a system builder creating tools for large models—this guide will teach you the key skills you need.

From the basics of CUDA to advanced tools for compiling and deploying models, it covers everything step by step.

---

**Program Overview**
The program is divided into three progressive phases:

**Phase 1: Foundations**
Introduction to GPU architecture, CUDA, PyTorch profiling, quantization, and model compression.

**Phase 2: Advanced Inference**
Learn real-time deployment with vLLM, TGI, Triton Server, and kernel-level optimization using CUDA and Triton.

**Phase 3: Distributed Systems**
Scale training and inference across multiple GPUs/nodes, implement distributed inference, MLOps, and deploy on edge/cloud hardware.

---

**Who This Is For**
This guide is designed for:

* Machine learning engineers working on model optimization or serving.
* Systems engineers deploying models in production.
* Researchers implementing efficient training/inference techniques.
* Technical leaders building infrastructure for scalable AI workloads.

**Prerequisites:**

* Strong Python and PyTorch fundamentals.
* Familiarity with Linux-based GPU environments.
* A working knowledge of deep learning models and training pipelines.

---

**Tools & Frameworks You'll Use**
CUDA, Nsight, Triton, TensorRT
PyTorch, ONNX, torch.compile
vLLM, TGI, FlashAttention-2
Torch-MLIR, IREE, bitsandbytes
Prometheus, Grafana, TLS & Auth

---

**Environment Recommendations**
Before you begin, ensure you have:

* Access to a machine with NVIDIA GPU(s) and CUDA support
* Python 3.10+ and PyTorch installed
* Docker (optional but recommended for container-based labs)

---

**Repositories & Assets**
We provide:

* Lab notebooks per lesson
* Scripts for profiling and model optimization
* Pretrained models (BERT, ResNet, ViT, LLaMA, etc.)
* Example configs for ONNX, TensorRT, vLLM, Triton

All code is hosted in a companion GitHub repository linked at the top of each lab section.

---

**Next Steps**
Head over to Phase 1: Foundations to begin your deep dive into modern GPU architecture, CUDA programming, and PyTorch model profiling.
