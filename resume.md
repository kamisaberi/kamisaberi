# Kamran Saberifard
**Visionary AI Architect, High-Performance Systems & AI Security Engineer**

📞 **Phone:** [+98 936-598-2333](tel:+989365982333) | ✉️ **Email:** [kamisaberi@gmail.com](mailto:kamisaberi@gmail.com)  
🆔 **ORCID:** [0009-0002-7822-6168](https://orcid.org/0009-0002-7822-6168) | 🐙 **GitHub:** [github.com/kamisaberi](https://github.com/kamisaberi) | 💼 **LinkedIn:** [linkedin.com/in/kamisaberi](https://linkedin.com/in/kamisaberi)

---

## Professional Summary

A distinguished AI architect and systems engineer with 25 years of experience building high-performance, mission-critical AI software from first principles. Research focuses on foundational improvements to deep learning acceleration, low-level kernel optimization, and AI security architecture. Creator of open-source C++, CUDA, and Triton platforms—including **xTorch**, **xInfer**, **alloy**, and **blackbox**—engineered to bridge the gap between high-level Python research and ultra-low-latency, memory-safe C++/vLLM inference deployment. Expert in auditing native C++ AI runtimes, adversarial machine learning defense, and securing AI infrastructure against remote execution vulnerabilities.

---

## Research & Publications

* **XTorch: A High-Performance C++ Framework for Deep Learning Training**  
  *Preprints.org* (2025). Authored research outlining the architectural design, memory allocators, and autograd mechanics of `xTorch`, restoring PyTorch-like developer productivity to native, secure C++ environments.  
  **DOI:** [10.20944/preprints202507.0540.v1](https://doi.org/10.20944/preprints202507.0540.v1)

* **xtorch: A High-Level C++ Deep Learning Framework for Simplicity and Performance**  
  *Preprints.org* (2025). Introduced a high-level C++ abstraction layer for deep learning model development, proving execution efficiency over Python baselines while enforcing memory safety.  
  **DOI:** [10.20944/preprints202507.0535.v1](https://doi.org/10.20944/preprints202507.0535.v1)

* **xTorch: A High-Level C++ Extension Library for PyTorch (LibTorch)**  
  *ResearchGate* (2025). Authored architectural specifications for extending PyTorch's native C++ library with automated memory allocators and high-level training pipelines.  
  **DOI:** [10.13140/RG.2.2.23235.31520](https://doi.org/10.13140/RG.2.2.23235.31520)

* **MoCAFT: A Framework for Composing and Rapidly Fine-Tuning Custom Models**  
  Published a novel framework unifying neural architecture search (NAS) and accelerated fine-tuning, enabling automated discovery and rapid C++ model training.

* **MoCA-NAS: Efficient Automated Discovery of Composable Neural Architectures**  
  Authored research on a NAS methodology for efficient discovery of composable, reusable neural blocks, directly informing the modular design of `xTorch` and `blackbox`.

* **CAFT: Accelerating Fine-Tuning by Caching Frozen Layer Activations**  
  Developed a technique to accelerate deep network fine-tuning by caching activations of frozen layers, drastically reducing redundant FLOPs in custom `xTorch` training loops.

* **Performance Comparison of CNNs Using PyTorch and xTorch**  
  Empirically validated that a single-GPU `xTorch` system achieves a **37% training speedup over a dual-GPU PyTorch baseline**.

---

## Core Projects: Open-Source AI & Security Ecosystem

* [**xTorch: High-Performance C++ Deep Learning Framework**](https://github.com/kamisaberi/xtorch)  
  Authored a native C++ deep learning library extending PyTorch's C++ API (LibTorch) with high-level abstractions, memory-safe custom allocators, automatic differentiation, and research-backed fine-tuning speedups (MoCAFT/CAFT).

* [**xInfer: Universal High-Performance C++ AI Runtime**](https://github.com/kamisaberi/xinfer)  
  Built a cross-platform C++ inference framework designed to run trained deep learning models with maximum throughput across NVIDIA TensorRT, OpenVINO, RKNN, and 15+ hardware architectures, featuring encrypted model weight ingestion and zero-copy C++20 memory execution.

* [**alloy: High-Performance GPU Kernel Acceleration & LLM Serving Engine**](https://github.com/kamisaberi/alloy)  
  Architected a high-throughput acceleration engine incorporating custom **CUDA** and **Triton** kernels alongside **vLLM**-inspired memory management (PagedAttention, KV-cache optimization) and kernel sandboxing to protect against VRAM buffer overflows and side-channel leakage.

* [**blackbox: Parallel Black-Box Optimization, NAS & Adversarial Robustness Engine**](https://github.com/kamisaberi/blackbox)  
  Developed a high-performance C++/Python engine for derivative-free black-box optimization, hyperparameter tuning, automated NAS, and adversarial robustness stress-testing across non-differentiable model landscapes.

* **Ignition Hub: Cloud-Native TensorRT Deployment Platform**  
  Architected a cloud service delivering pre-compiled, hardware-tailored, and cryptographically verified TensorRT engines on demand to eliminate enterprise build barriers.

---

## Professional Experience

### **Founder & Principal AI Architect**  
*Independent Research & Consulting (Aryorithm Group)* | Global  
*(Sep 2013 – Present)*

* Authored research papers on training acceleration, neural architecture search, and kernel-level GPU optimization (CAFT, MoCA-NAS, MoCAFT).
* Architected and developed the open-source **xTorch**, **xInfer**, **alloy**, and **blackbox** ecosystems, translating theoretical DL research into production-grade, secure C++, CUDA, and Triton acceleration libraries.
* Conducted native C++/CUDA security audits, fuzzing, and memory safety analyses on AI execution engines to prevent buffer overflows, race conditions, and remote code execution (RCE) vulnerabilities.
* Advised international technology leaders on high-throughput LLM deployment, custom CUDA kernel development, vLLM/TensorRT integration, and AI security:
  * **European Automotive Supplier Prototype:** Optimized perception stack latency by **40%** using custom C++ pipeline execution and TensorRT acceleration while hardening models against camera spoofing and adversarial physical attacks.
  * **US E-Commerce Personalization Firm:** Engineered a hybrid GNN recommender system improving accuracy by **15%** with privacy-preserving data isolation.
  * **LLM Serving & Security Optimization:** Implemented vLLM-compatible PagedAttention and Triton kernels to maximize token throughput while securing execution runtimes against prompt-driven code injection.

---

### **Founder, Lead Programmer & Technical Manager**  
*Various Companies (Arnahit Group, Pars Veda, Sibel Rayaneh)* | Iran & Russia  
*(Jan 2001 – Oct 2013)*

* Directed engineering teams to deliver mission-critical software, including high-concurrency sports betting platforms with secure transactional architectures.
* Implemented genetic algorithms and AI search solvers from scratch in C++, establishing a first-principles foundation in intelligent systems engineering and algorithmic defense.

---

## Technical Expertise

* **Languages & Low-Level Systems:** Modern C++ (Expert, C++17/20), Python (Expert), CUDA, Triton, Java, SQL, Rust.
* **Cybersecurity & AI Hardening:** AI Threat Modeling, Adversarial Machine Learning Defense, Native Memory Auditing (ASan/Valgrind/GDB), Fuzzing (AFL++), Reverse Engineering (Ghidra), Confidential Computing (TEEs), Cryptography, Privacy-Preserving AI, Secure C++ Coding Guidelines.
* **High-Performance AI & Serving:** vLLM, NVIDIA TensorRT, LibTorch (Expert), ONNX Runtime, Custom CUDA/Triton Kernels, PagedAttention, KV-Cache Optimization, FlashAttention, Quantization (FP8/AWQ).
* **AI Frameworks & Ecosystems:** xTorch, xInfer, alloy, blackbox (Author), PyTorch, Scikit-learn, OpenCV.
* **Architectures & Domains:** LLM Serving & Security, Cybersecurity, Transformers, Mamba, Diffusion Models, GNNs, CNNs, Computer Vision, NLP, Recommender Systems, Neural Architecture Search (NAS).

---

## Education

**M.S. in Computer Engineering – Cybersecurity**  
*MehrAstan University* | Guilan, Iran  
*(Sep 2024 – Present)*

**B.S. in Pure Mathematics**  
*Sistan & Baluchistan University* | Zahedan, Iran  
*(Mar 2000 – Aug 2003)*
