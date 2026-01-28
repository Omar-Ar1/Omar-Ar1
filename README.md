# Hi, I'm Omar Arbi 👋

### AI Research • ENS Paris-Saclay (MVA) & CentraleSupélec • Generative Models • Representation Learning • HPC


## 🚀 About Me

I like building models that **push boundaries**, stress-test assumptions, and reveal what really drives performance. My work sits where:

* **Generative models break symmetry**,
* **Representations become interpretable**, and
* **GPU constraints force creativity**.

I enjoy turning complex ML systems into **clean, efficient, and rigorous experiments**. No fluff—just models, math, and good engineering.



## 🔬 What I’m Researching

### **🌀 Diffusion Models & Noise Geometry**

* Exploring **non-Gaussian noise** (Simplex, rank-based Gaussianization) and how noise structure shifts denoising difficulty.
* Building anomaly scoring pipelines using reconstruction spectra + latent statistics.
* Designing structured latents (FiLM conditioning, spatial Z-maps, capacity annealing).

### **📐 Representation Learning & Structure Prediction**

* Vision Transformers + GNNs for structured reasoning.
* Latent geometry analysis using **t‑SNE, PPCA, KL trajectories**, and internal feature probing.


## 🧠 Highlight Projects

### **1. Adaptive Diffusion for Anomaly Detection**

🔹 Swapped Gaussian noise with **Simplex noise**, Gaussianized-by-rank to preserve structure.

🔹 Saw **significant AUROC gains** with identical architecture.

🔹 Developed diagnostics to verify no data leakage + no artifact-induced shortcuts.

🔹 Focus on *why* noise geometry changes anomaly separability.

### **2. GPT‑2 Interpretability — Tuned Lens vs Logit Lens**

🔹 Trained a **Tuned Lens** to study token-level representation flow.

🔹 Compared KL divergence trajectories to detect prompt injection patterns.

🔹 Tuned Lens consistently outperformed Logit Lens in decoding stability & injection detection.

### **3. PPCA at Scale (GPU, Missing Data)**

🔹 Implemented a full EM loop for PPCA with missing values, fully vectorized for GPUs.

🔹 Benchmarked PCA vs PPCA vs mini-batch variants on massive synthetic datasets.

### **4. Low‑VRAM LLaVA Fine‑Tuning**

🔹 Fine‑tuned LLaVA with **LoRA + quantization** under strict memory budgets.

🔹 Evaluated through LLM judges (DeepSeek R1 / MedAlpaca).

🔹 Improved reasoning structure with deliberate prompting.

### **5. Online NMF for Time Series**

🔹 Designed a sliding-window factorization model for financial-market signals.

🔹 Integrated hyperparameter search to stabilize dictionary evolution.

🔹Applied the approach to financial time‑series forecasting, supported by rigorous preprocessing and benchmarking against baseline models.



## 🛠️ Skills

**Models:** Diffusion, VAEs, Transformers, GNNs 

**Training:** LoRA, quantization, pruning, EMA, DDP, gradient checkpointing

**Math:** ELBO, variational inference, spectral analysis, latent-variable modeling

**HPC:** Slurm, A100 GPUs, CUDA profiling, memory debugging

**Frameworks:** PyTorch, timm, MONAI, PyTorch-Geometric, vLLM, Flash-Attention



## 📌 What I'm Focusing on Next

* Understanding how **noise geometry** reshapes generative-model learning.
* Pushing more efficient training pipelines for large models.
* Strengthening my research engineering profile for roles involving **foundation models, interpretability, and generative modeling**.



## 📫 Contact

* **LinkedIn:** linkedin.com/in/omar-arbi

Thanks for stopping by! 🚀
