# Hi, I'm Hugh 👋

Statistics PhD by training, tool builder by compulsion. My papers prove theorems and my side projects automate the things that were making me miserable. I find it genuinely hard to leave a solvable problem unsolved — and I've made peace with that.

---

## Tools I built because I needed them

### [latex2arxiv](https://github.com/YuZh98/latex2arxiv) — arXiv rejected my submission. I automated my revenge.

[![PyPI](https://img.shields.io/pypi/v/latex2arxiv?style=flat-square&color=blue)](https://pypi.org/project/latex2arxiv/)
[![PyPI Downloads](https://img.shields.io/pypi/dm/latex2arxiv?style=flat-square&label=PyPI%20installs)](https://pypi.org/project/latex2arxiv/)
[![Homebrew](https://img.shields.io/badge/Homebrew-available-orange?style=flat-square&logo=homebrew&logoColor=white)](https://formulae.brew.sh/formula/latex2arxiv)
[![Stars](https://img.shields.io/github/stars/YuZh98/latex2arxiv?style=flat-square&logo=github)](https://github.com/YuZh98/latex2arxiv)

arXiv rejected my paper because of a stray `\usepackage{minted}`. I couldn't find a tool that caught every submission-blocking error *before* upload, so I built one. One command turns a messy LaTeX project into a clean, submission-ready zip — it prunes unreachable files, strips draft markup, validates the bibliography, and tells you exactly what will get desk-rejected. There's even an **MCP server** so AI agents can submit papers without leaving their workflow.

`Python` `CLI` `PyPI` `Homebrew` `GitHub Actions` `pre-commit` `MCP`

---

### [academic-application-tracker](https://github.com/YuZh98/academic-application-tracker) — 47 applications, 12 recommenders, zero missed deadlines.

[![Stars](https://img.shields.io/github/stars/YuZh98/academic-application-tracker?style=flat-square&logo=github)](https://github.com/YuZh98/academic-application-tracker)

I had 47 job applications, 12 recommenders, and deadlines stacking up like a queue with no consumer. I built the dashboard I needed: everything in one place, deadline urgency banded by color, recommender alerts, interview logs, daily action items auto-computed. 800+ tests at 97% coverage — because I actually trust it with my real job search.

`Python` `CLI` `pytest`

---

### [python-project-scaffold](https://github.com/YuZh98/python-project-scaffold) — because I was tired of spending hour one of every project not writing code.

[![Stars](https://img.shields.io/github/stars/YuZh98/python-project-scaffold?style=flat-square&logo=github)](https://github.com/YuZh98/python-project-scaffold)

Every new Python project starts with the same 3-hour ritual: wire up ruff, pyright, pytest, CI matrix, coverage gate, pre-commit, Dependabot, ADRs... I got annoyed and automated all of it. One click on *Use this template* and you're writing real code. Ships with a `/new-project` Claude Code skill that creates the GitHub repo and sets up branch protection — because even the setup should be one command.

`Python` `GitHub Actions` `Claude Code` `pre-commit`

---

## Research

Bayesian inference for structured data is my obsession. When your data is a ranking, a graph partition, or an integer array under hard constraints, standard inference breaks. My work builds algorithms that don't: I prove they converge, derive consistency conditions, and ship the code to show they run fast.

**Three first-author papers:**
- [JCGS 2025](https://www.tandfonline.com/doi/abs/10.1080/10618600.2025.2473932) *(published)* — blocked Gibbs sampler with anti-correlation Gaussian data augmentation; 23–67× faster than NUTS (the industry-standard sampler) with a geometric ergodicity proof
- [JASA](https://arxiv.org/abs/2504.11630) *(major revision — strong acceptance signal)* — Bayesian regression over combinatorial response data via integer programming duality
- [Bernoulli](https://arxiv.org/abs/2409.19129) *(major revision, 2nd round)* — first consistency guarantee for graph-based clustering under model misspecification

---

## Currently building

🦀 **[itch-tools](https://github.com/YuZh98/itch-tools)** — NASDAQ ITCH 5.0 parser in Rust. Raw binary → L1 order book → NBBO timeline. Built for 1M+ messages/sec throughput.

📝 Writing up dissertation (UF Statistics, Aug 2026)

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
  <img src="https://img.shields.io/badge/HiPerGator-Slurm-blue?style=flat-square" alt="HiPerGator/Slurm">
</p>

---

📫 Open to quant research, AI lab, and SWE roles starting Fall 2026 — reach out: `hugh.stats@gmail.com` · [Google Scholar](https://scholar.google.com/citations?user=rJRLTmkAAAAJ) · [ORCID](https://orcid.org/0009-0001-2712-5044) · [LinkedIn](https://www.linkedin.com/in/yu-zheng-statistics/) · [Website](https://yuzh98.github.io/)
