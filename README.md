# Hi, I'm Hugh 👋

Statistics PhD by training, tool builder by compulsion. My research focuses on combinatorial problems and structured data, where I design new statistical methods and Bayesian methods, prove their properties, and implement them in open-source software. My side projects are tools I build to help other people get their work done faster. I find it hard to leave a solvable problem alone, and whenever I run into repetitive work, I'd rather automate it than let it eat into my time.

---

## Tools I built because I needed them

### [latex2arxiv](https://github.com/YuZh98/latex2arxiv): Submit to arXiv without the headache. One command cleans your LaTeX project, catches rejection-causing errors, and walks you through the upload.

[![PyPI](https://img.shields.io/pypi/v/latex2arxiv?style=flat-square&color=blue)](https://pypi.org/project/latex2arxiv/)
[![Downloads](https://static.pepy.tech/badge/latex2arxiv?style=flat-square)](https://pepy.tech/project/latex2arxiv)
[![Homebrew](https://img.shields.io/badge/Homebrew-tap-orange?style=flat-square&logo=homebrew&logoColor=white)](https://github.com/YuZh98/homebrew-latex2arxiv)
[![VS Code](https://vsmarketplacebadges.dev/version-short/YuZh98.latex2arxiv.svg?style=flat-square&label=VS%20Code&logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=YuZh98.latex2arxiv)
[![MCP](https://img.shields.io/badge/MCP-server-8A2BE2?style=flat-square)](https://github.com/YuZh98/latex2arxiv/blob/main/docs/mcp.md)
[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/oeaoajmhcmlgdbeacnpkcofodekkpeab?style=flat-square&label=Chrome&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/latex2arxiv-for-overleaf/oeaoajmhcmlgdbeacnpkcofodekkpeab)
[![Stars](https://img.shields.io/github/stars/YuZh98/latex2arxiv?style=flat-square&logo=github)](https://github.com/YuZh98/latex2arxiv)

Takes any LaTeX project (zip, directory, or git URL) and outputs a submission-ready zip. Prunes unreachable files, strips draft markup and revision commands, normalizes BibTeX, and runs pre-flight checks that surface errors arXiv silently fails on. Pass `--guide` and it writes a step-by-step upload walkthrough with copy-paste title/authors/abstract. Gate your paper repo on compliance with `--dry-run` in CI. Same pipeline runs in **five surfaces**: terminal, **[Chrome extension for Overleaf](https://chromewebstore.google.com/detail/latex2arxiv-for-overleaf/oeaoajmhcmlgdbeacnpkcofodekkpeab)**, VS Code extension, MCP server (Claude/Cursor/Copilot/Windsurf/Zed), and GitHub Action.


### [latex2ufdissertation](https://github.com/YuZh98/latex2ufdissertation): 

A safety-net validator for UF doctoral dissertations submission using the University of Florida LaTeX template. Given a project archive, project directory, git URL, or compiled PDF, it produces a severity-tiered report citing the originating UF rule for each finding. 


### [academic-application-tracker](https://github.com/YuZh98/academic-application-tracker): 

Local Streamlit dashboard that answers "what do I do today?" for academics juggling dozens of applications, deadlines, and recommendation letters. [**Try the live demo**](https://academic-application-tracker.streamlit.app): no install, each session gets its own sandbox.



### [quant-prep-terminal](https://github.com/YuZh98/quant-prep-terminal):
An offline, single-file study cockpit for quant-finance interviews — learn, drill, and simulate in one HTML file. [**Open the live app**](https://yuzh98.github.io/quant-prep-terminal/).


---

## Research code

I am drawn to statistical problems that are at once mathematically challenging and scientifically motivated. In particular, I am interested in both methodology and theory related to **combinatorial problems and structured data**, such as clustering, variable selection, and integer-valued data under combinatorial constraints (e.g. matching data). I am deeply interested in both method innovation as well as asymptotic theory for statistical and machine learning methods. Below are some of my research code repositories. For more on my research and useful resources, see my [personal website](https://yuzh98.github.io/).

### [combreg](https://github.com/YuZh98/combreg):
An R package for Bayesian regression for response data that are integer-valued vectors constrained to an integral polytope. The package implements the MH-Within-Gibbs sampler of [Zheng, Ghosh & Duan (2026+)](https://arxiv.org/abs/2504.11630), with hit-and-run dual updates in C++ (OpenMP-parallel across observations), an unconstrained probit baseline, one-call benchmarking, MCMC and regression diagnostics, and utilities for constraint validation and data simulation. 

### [combinatorial-regression](https://github.com/YuZh98/combinatorial-regression):
A multi-language reproducibility pipeline for [Zheng, Ghosh & Duan (2026+)](https://arxiv.org/abs/2504.11630), with R + Rcpp inner loops, JAX/NumPyro baselines, and Makefile-orchestrated. The pipeline reproduces the numerical results and figures in the paper.

### [Anti-correlation-Gaussian](https://github.com/YuZh98/Anti-correlation-Gaussian):
Code accompanying the paper [Zheng & Duan (2025)](https://arxiv.org/abs/2309.09371) for implementation of a blocked Gibbs sampler using anti-correlation Gaussian data augmentation on a variable selection example, plus extensions to sampling from truncated multivariate Gaussian distributions.

### [VAE-fMRI-Alzheimer](https://github.com/YuZh98/VAE-fMRI-Alzheimer):
A 3D-convolutional Variational Autoencoder for Alzheimer's fMRI with CUDA training on HiPerGator. The repository also contains a tutorial for implementing VAE. It is worth mentioning that I also have notes on VAE [here](https://github.com/YuZh98/Study_Notes/blob/main/ML/VAEs.pdf). 

---

## Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" alt="R">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Rust-CE422B?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/JAX-FF6F00?style=flat-square&logo=google&logoColor=white" alt="JAX">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi&logoColor=white" alt="PyPI">
  <img src="https://img.shields.io/badge/Homebrew-FBB040?style=flat-square&logo=homebrew&logoColor=white" alt="Homebrew">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Slurm%2FHPC-2C5BB4?style=flat-square" alt="Slurm/HPC">
</p>

---

📫 `hugh.stats@gmail.com` · [Google Scholar](https://scholar.google.com/citations?user=rJRLTmkAAAAJ) · [ORCID](https://orcid.org/0009-0001-2712-5044) · [LinkedIn](https://www.linkedin.com/in/yu-zheng-statistics/) · [Website](https://yuzh98.github.io/)
