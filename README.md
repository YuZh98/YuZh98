# Hi, I'm Hugh 👋

Statistics PhD by training, tool builder by compulsion. My papers prove theorems and my side projects automate the things that were making me miserable. I find it genuinely hard to leave a solvable problem unsolved — and I've made peace with that.

---

## Tools I built because I needed them

### [latex2arxiv](https://github.com/YuZh98/latex2arxiv) — Overleaf gave me 934 files and 80.6 MB. arXiv wanted a clean zip. I wrote the tool.

[![PyPI](https://img.shields.io/pypi/v/latex2arxiv?style=flat-square&color=blue)](https://pypi.org/project/latex2arxiv/)
[![PyPI Downloads](https://img.shields.io/pypi/dm/latex2arxiv?style=flat-square&label=PyPI%20installs)](https://pypi.org/project/latex2arxiv/)
[![Homebrew](https://img.shields.io/badge/Homebrew-available-orange?style=flat-square&logo=homebrew&logoColor=white)](https://formulae.brew.sh/formula/latex2arxiv)
[![Stars](https://img.shields.io/github/stars/YuZh98/latex2arxiv?style=flat-square&logo=github)](https://github.com/YuZh98/latex2arxiv)

One command takes any LaTeX project — zip, directory, or git URL — and outputs a clean, arXiv-ready zip. It prunes unreachable files (934 → 40 on my own JASA paper), strips draft markup and revision commands, normalizes BibTeX, and runs pre-flight checks that catch rejection-causing errors *before* you upload: `\usepackage{minted}`, stray `.eps` images, broken `\printindex` — things arXiv silently fails on. Pass `--guide` and it writes a step-by-step upload walkthrough with copy-paste metadata. There's also an **MCP server** so AI agents can trigger the whole pipeline without leaving the chat.

`Python` `CLI` `PyPI` `Homebrew` `GitHub Actions` `pre-commit` `MCP`

---

### [academic-application-tracker](https://github.com/YuZh98/academic-application-tracker) — answers one question every morning: *what do I do today?*

[![Stars](https://img.shields.io/github/stars/YuZh98/academic-application-tracker?style=flat-square&logo=github)](https://github.com/YuZh98/academic-application-tracker)

Academic job searching is chaos: overlapping deadlines, multiple recommenders per position, materials checklists that differ by institution. I built the Streamlit dashboard that cuts through it — urgency-banded deadlines, per-position recommender state, materials readiness panel, interview log, and daily action items auto-computed. The database auto-exports plaintext markdown backups on every write. 800+ tests at 97% coverage — because I actually trust it with my real job search.

`Python` `Streamlit` `SQLite` `pytest`

---

### [python-project-scaffold](https://github.com/YuZh98/python-project-scaffold) — skip the 30-minute setup ritual and start at your first feature commit.

[![Stars](https://img.shields.io/github/stars/YuZh98/python-project-scaffold?style=flat-square&logo=github)](https://github.com/YuZh98/python-project-scaffold)

Every new Python project starts with the same 30-minute ritual: wire up ruff, pyright, pytest, CI matrix, coverage gate, pre-commit, Dependabot, ADRs... I automated all of it. One click on *Use this template* + one `python3 scripts/init-project.py` and you have a green-CI repo ready for your first feature. Ships with a `/new-project` Claude Code skill that creates the GitHub repo and sets up branch protection — because even the setup should be one command.

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
