# Hi, I'm Hugh 👋

Statistics PhD by training, tool builder by compulsion. My papers propose scalable algorithms and prove theorems, and my side projects are tools I build to help other people get their work done faster. I find it hard to leave a solvable problem alone, and whenever I run into repetitive work, I'd rather automate it than let it eat into my time.

---

## Tools I built because I needed them

### [latex2arxiv](https://github.com/YuZh98/latex2arxiv): Submit to arXiv without the headache. One command cleans your LaTeX project, catches rejection-causing errors, and walks you through the upload.

[![PyPI](https://img.shields.io/pypi/v/latex2arxiv?style=flat-square&color=blue)](https://pypi.org/project/latex2arxiv/)
[![Downloads](https://static.pepy.tech/badge/latex2arxiv?style=flat-square)](https://pepy.tech/project/latex2arxiv)
[![Homebrew](https://img.shields.io/badge/Homebrew-tap-orange?style=flat-square&logo=homebrew&logoColor=white)](https://github.com/YuZh98/homebrew-latex2arxiv)
[![VS Code](https://img.shields.io/visual-studio-marketplace/v/YuZh98.latex2arxiv?style=flat-square&label=VS%20Code&logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=YuZh98.latex2arxiv)
[![MCP](https://img.shields.io/badge/MCP-server-8A2BE2?style=flat-square)](https://github.com/YuZh98/latex2arxiv/blob/main/docs/mcp.md)
<!-- UPDATE on CWS approval: replace with the Chrome Web Store badge -->
[![Chrome extension](https://img.shields.io/badge/Chrome%20extension-in%20review-orange?style=flat-square&logo=googlechrome&logoColor=white)](https://github.com/YuZh98/latex2arxiv/tree/main/browser-extension)
[![Stars](https://img.shields.io/github/stars/YuZh98/latex2arxiv?style=flat-square&logo=github)](https://github.com/YuZh98/latex2arxiv)

Takes any LaTeX project (zip, directory, or git URL) and outputs a submission-ready zip. Prunes unreachable files, strips draft markup and revision commands, normalizes BibTeX, and runs pre-flight checks that surface errors arXiv silently fails on. Pass `--guide` and it writes a step-by-step upload walkthrough with copy-paste title/authors/abstract. Gate your paper repo on compliance with `--dry-run` in CI. Same pipeline runs in **five surfaces** — terminal, **Chrome extension for Overleaf** (zero install, in Web Store review), VS Code, MCP server (Claude/Cursor/Copilot/Windsurf/Zed), and GitHub Action.

`Python` `CLI` `PyPI` `Homebrew` `Chrome extension` `VS Code` `GitHub Actions` `pre-commit` `MCP`

---

### [academic-application-tracker](https://github.com/YuZh98/academic-application-tracker): Local Streamlit dashboard that answers "what do I do today?" for academics juggling dozens of applications, deadlines, and recommendation letters.

[![CI](https://github.com/YuZh98/academic-application-tracker/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/YuZh98/academic-application-tracker/actions/workflows/ci.yml)
[![Live demo](https://img.shields.io/badge/demo-live-E63946?style=flat-square)](https://academic-application-tracker.streamlit.app)
[![Python](https://img.shields.io/badge/python-3.11%E2%80%933.14-blue?style=flat-square)](https://github.com/YuZh98/academic-application-tracker/blob/main/pyproject.toml)
[![Coverage](https://img.shields.io/badge/coverage-95%25-brightgreen?style=flat-square)](https://github.com/YuZh98/academic-application-tracker/blob/main/pyproject.toml)

Academic job searching is chaos. Overlapping deadlines, three recommenders per position, every institution wanting the materials checklist in a different shape. Halfway through last cycle I gave up on spreadsheets and built the Streamlit dashboard I actually needed — urgency-banded deadlines, recommender state per position, an interview log, and a daily action list auto-computed from what's still open. [**Try the live demo**](https://academic-application-tracker.streamlit.app): no install, each session gets its own sandbox. 1000+ tests at 95% coverage, because I'm running it against my own applications and I can't afford it eating a deadline.

`Python` `Streamlit` `SQLite` `pytest` `Plotly`

---

### [python-project-scaffold](https://github.com/YuZh98/python-project-scaffold): Skip the 30-minute setup ritual and start at your first feature commit.

Every new Python project starts with the same 30-minute ritual: wire up ruff, pyright, pytest, CI matrix, coverage gate, pre-commit, Dependabot, ADRs... I automated all of it. One click on *Use this template* + one `python3 scripts/init-project.py` and you have a green-CI repo ready for your first feature. Ships with a `/new-project` Claude Code skill that creates the GitHub repo and sets up branch protection, because even the setup should be one command.

`Python` `GitHub Actions` `Claude Code` `pre-commit`

---

## Research

I've always enjoyed working on statistical problems that are mathematically challenging and scientifically motivated. I am in particular intrigued by problems where the data or the quantity of interest is combinatorial: some or all coordinates of the observation take values in a discrete, structured set rather than in Euclidean space. The loss of Euclidean geometry brings
simultaneous challenges in probabilistic modeling, mathematical theory, and scalable computation. The central question organizing my research is: 
**How can we develop Bayesian methodology with theoretical guarantees for problems that are combinatorial in structure, and how do those methods behave on real scientific data?**

**Three first-author papers:**
- [JCGS 2025](https://www.tandfonline.com/doi/abs/10.1080/10618600.2025.2473932) *(published)*: blocked Gibbs sampler with anti-correlation Gaussian data augmentation; 23 to 67 times faster than NUTS (the industry-standard sampler) with a geometric ergodicity proof. [Code: Anti-correlation-Gaussian](https://github.com/YuZh98/Anti-correlation-Gaussian).
- [JASA](https://arxiv.org/abs/2504.11630) *(revision submitted)*: Bayesian regression over combinatorial response data via integer programming duality. [Code: combinatorial-regression](https://github.com/YuZh98/combinatorial-regression), a multi-language reproducibility pipeline (R + Rcpp inner loops, JAX/NumPyro baselines, Makefile-orchestrated).
- [Bernoulli](https://arxiv.org/abs/2409.19129) *(revision submitted)*: first consistency guarantee for graph-based clustering under model misspecification.

**More research code:** [VAE-fMRI-Alzheimer](https://github.com/YuZh98/VAE-fMRI-Alzheimer), a 3D-convolutional VAE for Alzheimer's fMRI. CUDA training on HiPerGator, 36 unit tests, 18 tutorial notebooks.

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
