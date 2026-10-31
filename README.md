<p align="center">
  <a href="https://arnabsanyal.com/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="logo-on-dark.svg">
      <img src="logo-on-light.svg" alt="Arnab Sanyal" width="72">
    </picture>
  </a>
</p>

<h1 align="center">Hello, I am Arnab <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"></h1>

<p align="center">
  Senior ML Engineer II · <a href="https://getcruise.com/">Cruise LLC, General Motors</a><br>
  Ph.D. student · <a href="https://www.ece.utexas.edu/">ECE, The University of Texas at Austin</a> · Austin, Texas
</p>

<p align="center">
  <a href="https://arnabsanyal.com/"><b>arnabsanyal.com</b></a> ·
  <a href="https://scholar.google.com/citations?user=D9ebkwoAAAAJ">Google Scholar</a> ·
  <a href="https://orcid.org/0000-0001-6365-6769">ORCID</a> ·
  <a href="https://www.linkedin.com/in/arnabsanyal17/">LinkedIn</a> ·
  <a href="https://stackoverflow.com/users/7517511/senior-mle">Stack Overflow</a> ·
  <a href="https://medium.com/@arnabsanyal_15738">Medium</a> ·
  <a href="https://drive.google.com/open?id=1qmr7uleFa0IoCncOq6VHd0Pkg9Zh6q0o">CV</a> ·
  <a href="mailto:mail@arnabsanyal.com">Email</a>
</p>

---

<img hspace="20" align="right" src="coding.gif" width="400"/>

I am currently employed at [Cruise LLC](https://getcruise.com/) as a **Senior Machine Learning Engineer II**, where I focus on building ML compilers to optimize machine learning models for General Motors' [advanced driver assistance and full autonomous vehicle systems](https://news.gm.com/home.detail.html/Pages/topic/us/en/2025/feb/0225-supercruise.html?evar25=gm_com_autonomous_driving). Previously, I have worked at [Advanced Micro Devices, Inc.](https://www.amd.com/en.html) as a Member of Technical Staff, [Qualcomm AI Research](https://www.qualcomm.com/research/artificial-intelligence/ai-research) as a Senior ML Engineer and [Amazon Lab126](https://amazon.jobs/en/teams/lab126/) Hardware Compute Group as a SysDE ML Compiler Engineer.

I graduated with two research-focused master's degrees from the [University of Southern California](https://viterbischool.usc.edu/) in 2020 and an integrated dual degree from the [Indian Institute of Technology, Kharagpur](http://www.ee.iitkgp.ac.in/) in 2017. At present, I am finishing up my doctorate at the [University of Texas at Austin](https://www.ece.utexas.edu/), where my research focus is designing energy-efficient, robust machine learning algorithms for generative AI edge applications.

I have a pet cat, Oliver. He is quite chonky &#128516; and a very good boy. Check out his [Instagram](https://www.instagram.com/ollie.bear___/).

<br clear="right"/>

## Research

I work on making generative AI cheap enough to run where it is needed: on phones, cars, image sensors and microcontrollers. My papers sit where number formats, compression and hardware meet.

| Thread | Focus | Papers |
|---|---|---|
| **Post-training quantization & number formats** | Choosing the format, not just the scale: INT, FP8, MX and NF4 formats picked per weight channel and per diffusion timestep, with no retraining. | Chameleon, EntroLLM |
| **Entropy-coded model compression** | Bits that are cheaper to move: entropy-reducing quantization, Huffman coding and parallel decoding for bandwidth-starved devices. | EntroLLM, EntroMCU, OASIS, in-sensor compression |
| **Hardware–algorithm co-design** | From kernels to microcontrollers: ternary GEMM kernels, KV-aware SRAM/Flash management for LLMs on Cortex-M, and multiplication-free log-domain training. | EntroMCU, log-domain training |
| **Efficient perception: in-sensor & video** | Compute where the data is born: in-sensor encoders that compress representations on-chip, and real-time neuro-symbolic video understanding. | OASIS, in-sensor compression, RT-NeuS |

## Publications

- **Chameleon: Dynamic Format Adapter for Efficient Diffusion**<br>
  Arnab Sanyal, Sandeep Chinchali · *Preprint, under review*, 2026<br>
  [Project page](https://arnabsanyal.com/preprint/chameleon.html) · [arXiv](https://arxiv.org/abs/2609.33496) · [Code](https://github.com/arnabsanyal/Chameleon)
- **EntroLLM: Entropy Encoded Weight Compression for Efficient Large Language Model Inference on Edge Devices**<br>
  Arnab Sanyal, Gourav Datta, Prithwish Mukherjee, Sandeep P. Chinchali, Michael Orshansky · *ICASSP 2026*<br>
  [Project page](https://arnabsanyal.com/icassp2026/entrollm.html) · [Paper](https://doi.org/10.1109/ICASSP55912.2026.11464777) · [arXiv](https://arxiv.org/abs/2505.02380) · [Code](https://github.com/arnabsanyal/entrollm)
- **EntroMCU: A Hardware-Algorithm Vision for LLM Inference on Microcontrollers** (invited)<br>
  Arnab Sanyal, Sandeep P. Chinchali, Gourav Datta · *ISVLSI 2026*<br>
  [Paper](https://repositories.lib.utexas.edu/items/027c9158-e8fb-45f2-b590-8cacf7ad1cc3) · [PDF](https://repositories.lib.utexas.edu/server/api/core/bitstreams/91bdaeb0-b8bc-4a1c-aa30-9f433f2ffbf0/content)
- **OASIS: Optimized Lightweight Autoencoder System for Distributed In-Sensor Computing**<br>
  Chengwei Zhou, Sreetama Sarkar, Yuming Li, Arnab Sanyal, Md Abdullah-Al Kaiser, Sercan Aygun, Hassan Najafi, Gourav Datta · *ISVLSI 2026*<br>
  [arXiv](https://arxiv.org/abs/2505.02256)
- **RT-NeuS: Towards Real-Time Neuro-Symbolic Video Understanding via Adaptive Temporal Verification**<br>
  Shawn Liang, Sahil Shah, Chengwei Zhou, S P Sharan, Harsh Goel, Arnab Sanyal, Sandeep Chinchali, Gourav Datta · *NeuS 2026*<br>
  [arXiv](https://arxiv.org/abs/2602.23553)
- **Hardware-Aware Learned Representation Compression for Distributed In-Sensor Vision**<br>
  Chengwei Zhou, Abu Masum, Xuming Chen, Mehran Moghadam, Sreetama Sarkar, Arnab Sanyal, Md Abdullah-Al Kaiser, M. Hassan Najafi, Sercan Aygun, Gourav Datta · *IEEE TETC, under review*<br>
  [arXiv](https://arxiv.org/abs/2609.13947)
- **Neural Network Training with Approximate Logarithmic Computations**<br>
  Arnab Sanyal, Peter A. Beerel, Keith M. Chugg · *ICASSP 2020*<br>
  [Project page](https://arnabsanyal.com/icassp2020/lnsdnn.html) · [Paper](https://doi.org/10.1109/ICASSP40776.2020.9053015) · [arXiv](https://arxiv.org/abs/1910.09876) · [Code](https://github.com/arnabsanyal/lnsdnn) · [Talk](https://youtu.be/MN7_Jar0DSM)

## Experience

| | Role | Highlights |
|---|---|---|
| **[Cruise LLC, General Motors](https://getcruise.com/)**<br>Nov 2025 – present | Senior ML Engineer II | Build, enhance and deploy the ML compiler pipeline for autonomous-vehicle hardware accelerators, [enabling full self-driving](https://www.gm.com/innovation/autonomous-driving#future). |
| **[Xilinx, AMD Inc.](https://www.amd.com/)**<br>Feb 2024 – Sep 2025 | Member of Technical Staff | Scalable, robust kernels for generative AI models on AMD's [AI Engine](https://www.xilinx.com/products/technology/ai-engine.html); ONNX graph optimizations and MLIR generation. |
| **[Qualcomm AI Research](https://www.qualcomm.com/research/artificial-intelligence/ai-research)**<br>Feb 2023 – Feb 2024 | Senior ML Engineer | Compiler stack for the Hexagon Tensor Processor, bringing [generative AI to the edge](https://www.qualcomm.com/news/onq/2023/02/worlds-first-on-device-demonstration-of-stable-diffusion-on-android). |
| **[Amazon Lab126](https://www.amazon.jobs/en/teams/lab126/)**<br>Sep 2020 – Nov 2022 | SysDE ML Compiler Engineer I | Founding team of the [AZ1 Neural Edge Processor](https://www.mediatek.com/blog/amazon-az1-neural-edge-processor-powered-by-mediatek); software stack for on-device inference such as [local voice processing](https://techcrunch.com/2021/09/28/new-amazon-echo-devices-will-have-local-voice-processing-giving-users-more-privacy/). |
| **[MediaTek Research](https://www.mediatek.com/mediatekresearch)**<br>May 2020 – Aug 2020 | Research Intern | Reduced training and inference complexity for RNNs/LSTMs on accelerator architectures. |

## Skills

- **Efficient AI:** post-training quantization, FP8 / MX / INT4 / NF4 formats, quantization-aware training, GPTQ · AWQ · SmoothQuant, mixed precision, entropy & Huffman coding, pruning, distillation, KV-cache optimization, logarithmic number systems
- **ML compilers:** MLIR, StableHLO, LLVM, TVM, XLA, torch.compile / Dynamo / Inductor, torch.fx, ONNX graph optimization, ExecuTorch
- **Kernels & accelerators:** CUDA, Triton, AMD AI Engine, Qualcomm Hexagon HTP / HVX, Amazon AZ1 NPU, Arm Cortex-M (CMSIS-NN, Helium), NVIDIA Jetson, FPGA (Verilog, HLS)
- **Frameworks:** PyTorch, TensorFlow, ONNX Runtime, TensorRT, Hugging Face Transformers & Diffusers
- **Languages:** Python, C++, C, CUDA, Shell, MATLAB, Java, Assembly (AVR, ARM, MIPS), LaTeX

## Academic service

- **Website Chair**, [IEEE Workshop on Signal Processing Systems (SiPS 2027)](https://sips2027.github.io/)
- **Reviewer:** CVPR, ICML (2026) · ICASSP, WACV, ISLPED (2025) · VLSID (2023) · PATMOS (2019) · RAW, FCCM (2018) · H2RC, IA3 (2017)
- **Judge (chair)**, USC ECE Deep Learning Symposium, 2019 and 2020

<p align="center"><sub>More on <a href="https://arnabsanyal.com/">arnabsanyal.com</a>: talks, education, affiliations, honors and awards.</sub></p>
