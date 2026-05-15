# Hi, I'm Hugh 👋

I'm a Statistics PhD who can't stop shipping tools. My papers prove theorems; my side projects solve the daily annoyances that slow researchers down. I find it genuinely hard to leave a solvable problem unsolved.

---

## Tools I built because I needed them

**[latex2arxiv](https://github.com/YuZh98/latex2arxiv)** — arXiv rejected my paper because of a stray `\usepackage{minted}`. I couldn't find a tool that caught every submission-blocking error *before* upload, so I built one. One command turns a messy LaTeX project into a clean, submission-ready zip — it prunes unreachable files, strips draft markup, validates the bibliography, and tells you exactly what will get desk-rejected. Now on PyPI, Homebrew, GitHub Actions, pre-commit, and there's an **MCP server** so AI agents can submit papers too. *(14 releases, 292 commits)*

**[academic-application-tracker](https://github.com/YuZh98/academic-application-tracker)** — I had 47 job applications, 12 recommenders, and deadlines stacking up like a queue with no consumer. I built the dashboard I needed: everything in one place, deadline urgency banded by color, recommender alerts, interview logs, daily action items auto-computed. 800+ tests at 97% coverage — because I actually trust it with my real job search.

**[python-project-scaffold](https://github.com/YuZh98/python-project-scaffold)** — Every new Python project starts with the same 3-hour ritual: wire up ruff, pyright, pytest, CI matrix, coverage gate, pre-commit, Dependabot, ADRs... I got annoyed and automated all of it. One click on *Use this template* and you're writing real code. The scaffold even ships with a `/new-project` Claude Code skill that creates the GitHub repo and sets up branch protection for you.

---

## Research

I find Bayesian inference for structured data genuinely beautiful. When your data is a ranking, a graph partition, an integer array under hard constraints — standard inference breaks. My work builds algorithms that don't: I prove they converge, derive the conditions under which they're consistent, and ship the code to show they run fast.

**Three first-author papers:**
- [JCGS 2025](https://www.tandfonline.com/doi/abs/10.1080/10618600.2025.2473932) *(published)* — blocked Gibbs sampler with anti-correlation Gaussian data augmentation; 23–67× faster than NUTS with a geometric ergodicity proof
- [JASA](https://arxiv.org/abs/2504.11630) *(major revision)* — Bayesian regression over combinatorial response data via integer programming duality
- [Bernoulli](https://arxiv.org/abs/2409.19129) *(major revision, 2nd round)* — first consistency guarantee for graph-based clustering under model misspecification

---

## Currently building

🦀 **[itch-tools](https://github.com/YuZh98/itch-tools)** — NASDAQ ITCH 5.0 parser in Rust. Raw binary → L1 order book → NBBO timeline. Targeting 1M+ msgs/sec.

📝 Writing up dissertation (UF Statistics, Aug 2026)

---

## Stack

`Python` · `R` · `C++` · `Rust` *(learning)* · `JAX` · `NumPyro` · `PyTorch`
`GitHub Actions` · `Slurm/HiPerGator` · `PyPI` · `Homebrew` · `pre-commit`

---

📫 `seanzhengyu1@gmail.com` · [Google Scholar](https://scholar.google.com/citations?user=rJRLTmkAAAAJ) · [ORCID](https://orcid.org/0009-0001-2712-5044) · [LinkedIn](https://www.linkedin.com/in/yu-zheng-statistics/) · [Website](https://yuzh98.github.io/)
