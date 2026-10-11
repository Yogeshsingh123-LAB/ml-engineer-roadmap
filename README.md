# 18-Month ML Engineer Roadmap

**October 2026 → March 2028 · ~16 hours/week · Free-first**

**Goal:** Become a credible candidate for ML, AI, and software internships by proving you can **build, evaluate, deploy, and explain** real systems. Certificates alone don't count.

> GSoC, internships, and merged PRs are **targets, not promises**.

**Track your progress in [PROGRESS.md](PROGRESS.md)** and update it every Sunday.

---

## Contents

1. [Overview](#overview)
2. [Start here](#start-here)
3. [How to study](#how-to-study)
4. [The six phases](#the-six-phases)
5. [Portfolio projects](#portfolio-projects)
6. [Checkpoints](#checkpoints)
7. [Targets](#targets)
8. [Career and open source](#career-and-open-source)
9. [System design](#system-design)
10. [Resources](#resources)
11. [Rules](#rules)

---

## Overview

| | |
|---|---|
| **Duration** | 78 weeks · Oct 2026 – Mar 2028 |
| **Pace** | 15 h minimum · **16 h target** · 18 h stretch |
| **Starting point** | CS50SQL done · CS50P nearly done · Python/Flask basics · hackathon experience · SIH projects (GeM procurement, Watershed Insight) |
| **Finish line** | 5 evaluated projects, a deployed ML app, a RAG-to-agent system, steady DSA and SQL practice, and a polished GitHub, resume, and LinkedIn |
| **Total effort** | ~1,248 h at 16 h/week (1,170 h at 15 h · 1,404 h at 18 h). Real totals will be lower after exams and breaks. |

### Phases at a glance

| Phase | Months | Focus | Deliverable |
|---|---|---|---|
| 1. Foundations | Oct – Dec 2026 | Python, supervised ML, SQL, pandas | **P1** Tabular ML (Dec 2026) |
| 2. Applied ML | Jan – Mar 2027 | Model selection, APIs, deployment, Git | **P2** Deployed ML app (Mar 2027) |
| 3. Deep Learning | Apr – Jun 2027 | PyTorch, neural networks, CNNs | **P3** PyTorch model (Jun 2027) |
| 4. AI Foundations & Algorithms | Jul – Sep 2027 | Search, uncertainty, DSA interview prep | **P3.5** AI mini-project + mock interviews start |
| 5. LLMs & RAG | Oct – Dec 2027 | Transformers, embeddings, retrieval | **P4a** Deployed RAG app (Dec 2027) |
| 6. Agents & Portfolio | Jan – Mar 2028 | LangGraph, Docker, testing, portfolio | **P4b** Agent capstone (Mar 2028) |

---

## Start here

Your first 7 days:

- [ ] Finish CS50P and check your solutions.
- [ ] Start Andrew Ng's Machine Learning Specialization.
- [ ] Solve 10 SQL problems and review your mistakes.
- [ ] Clean up one GitHub repo (README, folder structure, requirements file).
- [ ] Block your 16 weekly hours around college.
- [ ] Create a tracker for learning, DSA, projects, and applications.
- [ ] Pick two GSoC organizations and read their contribution guides.

> **Until November, focus only on CS50P, Andrew Ng, and DSA.** Don't start every resource in this document.

---

## How to study

### Weekly schedule

| Activity | 15 h | **16 h** | 18 h |
|---|---:|---:|---:|
| Projects and implementation | 5 | **5** | 6 |
| Main learning track | 3 | **4** | 4 |
| DSA and problem solving | 3 | **3** | 4 |
| Math, statistics, and SQL | 2 | **2** | 2 |
| Testing, documentation, and review | 1 | **1** | 1 |
| Open source and career prep | 1 | **1** | 1 |
| **Total** | **15** | **16** | **18** |

**Example 16-hour week**

| Day | Study |
|---|---|
| Mon | Main course 1 h + DSA 1 h |
| Tue | Project 2 h |
| Wed | DSA 1 h + math/stats 1 h |
| Thu | Main course 1 h + project 1 h |
| Fri | Project 2 h + testing/docs 1 h |
| Sat | DSA 1 h + open source/career 1 h |
| Sun | Main course 2 h + math/stats 1 h |

Use **18 hours** only when college and sleep allow. Drop to **15** in lighter weeks.

### Sunday review (15 minutes)

1. What did I **build or solve independently** this week?
2. What concept can I explain without notes?
3. What is blocked, and what's the smallest next step?
4. Which **one** task matters most next week?
5. Did the plan fit around college and sleep?

### When life gets busy

| Situation | What to do |
|---|---|
| Exams, SIH, or hackathons | Drop to **3–8 hours/week**. Don't create a backlog. |
| Very busy week | Keep one DSA session, one course session, one project session. |
| Project running late | **Cut scope**, not testing, evaluation, or documentation. |
| Three weeks behind | Drop to **10 hours/week** for a while, then rebuild. |
| Exam months (May/June, December) | Treat as lighter. Move milestones instead of catching up. |
| Quarter-end weeks (Dec, Mar, Jun, Sep) | Buffer for catch-up, polish, or rest. |

### Study rules

- **One main course + one project at a time**, plus DSA. Don't run several courses in parallel.
- **Finishing a lecture isn't the goal.** A phase is done when its required output exists.
- **Add a new course only if all three are true:** it fills a named gap, you know the exact module you need, and you'll apply it to a project within two weeks.
- **Use Python** for DSA unless your placement requires C++.

---

## The six phases

Each phase has a goal, core resources, optional extras, a monthly checklist, and a milestone.

---

### Phase 1 — Foundations
**October – December 2026**

**Goal:** Build Python fluency, learn supervised ML, and refresh SQL, NumPy, pandas, and basic statistics.

**Core resources**
- [CS50P](https://cs50.harvard.edu/python/) — Python foundations
- [Andrew Ng's ML Specialization](https://www.deeplearning.ai/specializations/machine-learning/) — your main ML course
- [scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started.html)
- **DSA:** [DSA for AI (free Telegram channel)](https://t.me/DSAFORAI) + [NeetCode](https://neetcode.io/) — see the [DSA track](#dsa-track)

**Optional extras (pick one or two at most)**
- [Tech With Tim — Learn Python With This ONE Project!](https://www.youtube.com/@TechWithTim)
- [Karina Data Scientist — Clean Data in Minutes with Python](https://www.youtube.com/@KarinaDataScientist)
- [UCB CS70: Discrete Math and Probability](https://csdiy.wiki/数学进阶/CS70/) — ~60 h

**Monthly checklist**

- [ ] **Oct 2026** — Finish CS50P. Start Ng. Clean GitHub. Solve 20 SQL problems. Start DSA (complexity, arrays, hashing). Pick a small Python project.
- [ ] **Nov 2026** — Study regression, classification, gradient descent. Practice NumPy/pandas. Start Project 1. Read two GSoC guides. Make one useful open-source contribution.
- [ ] **Dec 2026** — **Finish Project 1.** Reach 75 cumulative SQL problems. Protect exam time.

**Milestone:** CS50P complete, Ng's course underway, baseline tabular ML project with honest evaluation.

---

### Phase 2 — Applied ML
**January – March 2027**

**Goal:** Move from notebooks to tested, deployable apps. Cover model selection, cross-validation, leakage prevention, Flask/FastAPI, Git, Linux, virtual environments, and experiment tracking.

**Core resources**
- [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
- [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/) — selected modules
- [Flask documentation](https://flask.palletsprojects.com/)

**Optional extras**
- [freeCodeCamp — Python API Development](https://www.youtube.com/@freecodecamp)
- [CS229 (Stanford)](https://csdiy.wiki/机器学习/CS229/) — ~100 h. Only if you want algorithm internals.
- [CMU 15-445 (Databases)](https://csdiy.wiki/数据库系统/15445/) — ~100 h, needs C++. Only for deep backend work.

**Monthly checklist**

- [ ] **Jan 2027** — Ensembles, cross-validation, leakage, tuning. Start Project 2. Continue timed DSA. Attempt a first small PR.
- [ ] **Feb 2027** — Build a Flask/FastAPI interface and add tests. Learn Git branches, PRs, Linux, virtual environments. Draft your resume. Reach 100 cumulative SQL problems.
- [ ] **Mar 2027** — Finish Ng. **Deploy Project 2.** Add a dashboard and a 20-minute walkthrough. Check official GSoC dates.

**Choose one experiment tracker:** MLflow or Weights & Biases.

**Milestone:** Ng's course complete. Project 2 tested, documented, deployed.

> **Career note:** Summer 2027 is a stretch. Aim for stronger summer 2028 applications. If no internship comes, use the break for a small project, hackathon, or open-source contribution.

---

### Phase 3 — Deep Learning
**April – June 2027**

**Goal:** Understand tensors, autograd, training loops, optimizers, and regularization. Train a CNN or text classifier.

**Core resources**
- [PyTorch Tutorials](https://pytorch.org/tutorials/) — main implementation track
- [fast.ai](https://course.fast.ai/) — practical, project-first deep learning

**Optional extras**
- [Karpathy — Neural Networks: Zero to Hero](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — build networks by hand
- Selected lectures from [MIT 6.S191](https://introtodeeplearning.com/)
- [CS231n (Stanford)](https://csdiy.wiki/深度学习/CS231/) — ~80 h. Good if Project 3 is image-based.

**Monthly checklist**

- [ ] **Apr 2027** — Tensors, autograd, `nn.Module`, training loops. Train a small network on your own. Start Project 3. Submit GSoC if applying.
- [ ] **May 2027** — Optimizers, regularization, CNNs or text classification. Build a baseline and log experiments.
- [ ] **Jun 2027** — **Finish Project 3.** Compare results, inspect errors, document reproducibility.

**Milestone:** PyTorch project with reproducible training, evaluation, and a short write-up.

**Notes**
- Ng's *Machine Learning* Specialization ≠ his *Deep Learning* Specialization. The Deep Learning one is optional and historically TensorFlow-based. Check the current syllabus before starting.
- **Compute:** Use Colab or Kaggle for free GPU. Save checkpoints. Keep datasets small. Don't make paid GPUs or APIs a requirement.

---

### Phase 4 — AI Foundations & Algorithms
**July – September 2027**

**Goal:** Learn search, knowledge representation, probabilistic reasoning, and optimization. Build DSA interview fluency. Ship one small AI project so this phase produces a portfolio piece, not just coursework.

**Core resources**
- [Harvard CS50AI](https://cs50.harvard.edu/ai/) — **priority topics only:** search, knowledge representation, uncertainty, optimization. Skip ML and neural-network sections that duplicate Ng/PyTorch.
- **DSA:** Continue with [DSA for AI (Telegram)](https://t.me/DSAFORAI) and [NeetCode](https://neetcode.io/) — trees, graphs, heaps, DP. See the [DSA track](#dsa-track).

**Optional extras**
- [MIT 6.006](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — extra depth on graphs and DP
- [CS285 (Berkeley Deep RL)](https://rail.eecs.berkeley.edu/deeprlcourse/) — only if you develop a specific RL interest

**Monthly checklist**

- [ ] **Jul 2027** — CS50AI search and knowledge representation. Probability and statistics review. Continue DSA. Pick your Phase 4 mini-project idea.
- [ ] **Aug 2027** — CS50AI uncertainty and optimization. Practice Python fluency (generators, decorators). Add tests to existing repos. Build the core of your mini-project.
- [ ] **Sep 2027** — Finish selected CS50AI projects. **Finish and document the mini-project.** Write up a documented technical contribution. **Start mock interviews.**

**Milestone:** Clean CS50AI repos, a documented AI mini-project, and first mock interviews.

**Phase 4 mini-project ideas (pick one, keep it small):**
- A constraint-satisfaction puzzle solver (Sudoku, map coloring) with a write-up on the search strategy used.
- A Bayesian spam filter built from scratch on a public dataset, with calibration analysis.
- An A* pathfinding visualizer with a short technical write-up.
- A small game-playing agent (minimax with alpha-beta pruning) for a simple board game.

> **Rule:** Consistent DSA matters more than finishing another course. Roughgarden's algorithms course and CS229 stay optional unless you're clearly ahead.

---

### Phase 5 — LLMs & RAG
**October – December 2027**

**Goal:** Understand tokenization, embeddings, transformers, and pretrained models. Build retrieval-augmented generation (RAG) that gives grounded, sourced answers and is **measured**.

**Core resources**
- [Hugging Face LLM Course](https://huggingface.co/learn/llm-course)
- [pguso/rag-from-scratch](https://github.com/pguso/rag-from-scratch) — step-by-step RAG, no black boxes
- [LangChain documentation](https://docs.langchain.com/oss/python/learn) — used after building RAG from scratch

**Optional extras**
- [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) — project-first RAG
- Selected lectures from [Stanford CS224N](https://web.stanford.edu/class/cs224n/) (~80–100 h full course)
- [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) — only when they support your project
- [Karpathy — Let's reproduce GPT-2 (124M)](https://www.youtube.com/@AndrejKarpathy) — advanced; watch last
- [CS336 (Stanford LLMs)](https://csdiy.wiki/深度生成模型/roadmap/) — advanced LLM internals
- [MIT 6.S184 (Diffusion)](https://csdiy.wiki/深度生成模型/MIT6.S184/) — only if interested in diffusion models

**Monthly checklist**

- [ ] **Oct 2027** — Study transformers, tokenization, embeddings, pretrained models. Run a small LLM experiment and explain the pipeline in writing.
- [ ] **Nov 2027** — Build raw RAG: parsing, chunking, embeddings, retrieval, grounded answers. Create your evaluation set. Reach 150 cumulative SQL problems.
- [ ] **Dec 2027** — Add LangChain where it helps. Add tests, API/UI, deployment. **Finish Project 4a.**

**Milestone:** Deployed RAG app with source citations and measured retrieval quality.

**RAG evaluation standard**
- Write **30–50 questions**, each paired with the expected source document or passage.
- Report a **retrieval hit rate**: how often the expected source appears in top results.
- Check **answer faithfulness and relevance** by hand. Log failure cases.
- RAGAS can be added later — it doesn't replace understanding your own test set.
- A working chatbot alone isn't a complete RAG project.

**Compute:** Prefer small open-weight models, local inference with [Ollama](https://ollama.com/) where possible, or free-tier services. Plan a fallback so API limits don't block you. **Never commit API keys.**

---

### Phase 6 — Agents, MLOps & Portfolio
**January – March 2028**

**Goal:** Turn the RAG app into a tested, documented, observable agent system. Polish the whole portfolio.

**Core resources**
- [LangGraph documentation](https://docs.langchain.com/oss/python/learn) — state, nodes, edges, routing, tool calls
- [Docker — Get Started](https://docs.docker.com/get-started/)
- [Made With ML](https://madewithml.com/) — testing, deployment, monitoring

**Optional extras**
- [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp)
- [FastAPI Tutorial](https://fastapi.tiangolo.com/tutorial/)
- [Full Stack Open](https://csdiy.wiki/Web开发/fullstackopen/) — React and Node.js for a full-stack agent interface
- [Kun Chen — Full Stack App with Agentic Engineering](https://www.youtube.com/@KunChen)
- Optional big capstone: **Autonomous Research Assistant** (React, FastAPI, PostgreSQL, LLM). Only after the core agent works.

**Monthly checklist**

- [ ] **Jan 2028** — Learn LangGraph basics. Build a small stateful agent with limited, well-defined tools. Learn Docker basics.
- [ ] **Feb 2028** — Upgrade RAG into an agent. Add tests, logging, basic monitoring. Document architecture and evaluation. Reach 10 cumulative mock interviews.
- [ ] **Mar 2028** — **Finish Project 4b.** Polish all four projects. Revise Python, ML, SQL, DSA. Update resume and tracker. Apply for summer 2028 internships.

**Milestone:** Tested, documented agent capstone and a polished portfolio.

**Agent rules**
- A reliable, evaluated agent beats a complicated multi-agent system.
- Restrict tool access. Require human approval for actions with real consequences.

> **If you consistently hit 18 hours:** Move the LangGraph capstone into December 2027. Use January–March for open source, interview prep, or optional depth. Don't add new courses.

---

## Portfolio projects

Existing SIH projects count if they meet the same standard. Don't create extra projects just to hit a number.

| # | Project | Due | What it proves |
|---|---|---|---|
| **P1** | Tabular ML | Dec 2026 | Baseline vs improved model, correct metrics, error analysis |
| **P2** | Deployed ML app | Mar 2027 | Predictions served via Flask/FastAPI with validation, tests, dashboard, walkthrough |
| **P3** | PyTorch model | Jun 2027 | Training from scratch, reproducibility, technical write-up |
| **P3.5** | AI mini-project | Sep 2027 | Search / probabilistic reasoning applied to a concrete problem |
| **P4** | RAG → agent | Dec 2027 – Mar 2028 | Retrieval evaluation, citations, tool-using agent, tests, Docker |

**P1 — Tabular ML.** Train a baseline and an improved model. Include data preparation, appropriate metrics, error analysis, and limitations.

**P2 — Deployed ML app.** Serve predictions through Flask or FastAPI with validation, tests, setup instructions, and a demo. Add a compact dashboard (Plotly, Streamlit, Power BI, or Tableau) and a **20-minute walkthrough**: the question, data, key insights, caveats, and decisions a stakeholder could make. Also supports data analyst applications.
*Optional idea:* customer segmentation pipeline served as a FastAPI endpoint.

**P3 — PyTorch deep learning.** Train and evaluate a neural network, compare with a sensible baseline, document reproducibility. Choose image classification if you want to pair it with CS231n.

**P3.5 — AI mini-project.** A small, well-documented application of classical AI: search, constraint satisfaction, or probabilistic reasoning. Must include a working implementation, a short write-up explaining the approach, and honest limitations. See [Phase 4](#phase-4--ai-foundations--algorithms) for ideas.

**P4 — RAG upgraded into an agent.** Build retrieval from first principles, measure retrieval and answer quality, add sources. Then add an agent workflow, tests, logging, and Docker.
*Optional idea:* modified GPT-2 (changed positional encoding or LR schedule), trained on a small dataset with a write-up. Only after Karpathy's Zero to Hero.

### Choosing a SIH project

Pick the SIH project where you can:
- explain the problem, your contribution, the data pipeline, the evaluation, and the limitations;
- reproduce it and demo it reliably.

A large team project isn't automatically a strong individual piece. Document clearly what **you** designed, implemented, tested, and maintained.

### Every core project should have

- [ ] A clearly stated problem and data source
- [ ] A baseline and an appropriate evaluation method
- [ ] Train / validation / test separation with no data leakage
- [ ] Error analysis and honest limitations
- [ ] Reproducible setup instructions and tests
- [ ] A working demo, or screenshots if deployment isn't practical
- [ ] A README and short technical write-up
- [ ] A clear note on your individual contribution

> **Visibility:** Publish one concise write-up per project (README plus a LinkedIn post or blog). By March 2028, have a simple portfolio page linking to demos, repos, and write-ups.

---

## Checkpoints

Use these to adjust scope. Don't silently carry unfinished work forward. Quarter-end weeks are buffers, not extra deadlines.

| By | Check | If not met |
|---|---|---|
| **Dec 2026** | P1 complete; Ng's course at least halfway | Drop optional reading. Protect the main course and P1. |
| **Mar 2027** | Ng complete; P2 deployed with dashboard | Delay PyTorch up to a month. Don't skip evaluation or tests. |
| **Jun 2027** | P3 complete and reproducible | Reduce CS50AI scope in Phase 4. Keep DSA steady. |
| **Sep 2027** | CS50AI work documented; mini-project shipped; mock interviews started | Narrow CS50AI to priority topics. Ship a simpler mini-project. Start mock interviews now. |
| **Dec 2027** | RAG deployed with a 30–50-question evaluation set | Keep the agent simple. Protect tests and RAG evaluation. |
| **Mar 2028** | Portfolio page, resume, tracker, agent capstone ready | Prioritize reliable demos, clear explanations, applications. |

---

## Targets

| Area | Target by March 2028 |
|---|---|
| **Projects** | 5 evaluated projects (tabular ML, deployed ML app, PyTorch model, AI mini-project, RAG → agent) |
| **DSA** | 300+ independently solved problems, tracked by topic and explanation quality |
| **SQL** | 150+ problems: joins, aggregation, subqueries, CTEs, window functions |
| **Open source** | 2–4 substantive PR attempts; at least one merged or meaningfully reviewed |
| **Mock interviews** | 10+, starting September 2027 |
| **System design** | 5+ practiced ML system design problems with written explanations |
| **Deployment** | Deployed RAG app with retrieval evaluation; agent with tests, logging, Docker |
| **GitHub** | Clean repos with README, tests, reproducible setup |
| **Career** | Updated resume, LinkedIn, portfolio page, application tracker, one write-up per project |

**Two tiers of success**
- **Core:** 4–5 strong projects you can explain and reproduce, steady DSA and SQL, at least one real contribution attempt, clear write-ups.
- **Stretch:** 300+ DSA problems, 150+ SQL problems, multiple substantive PRs, 10+ mock interviews, 5+ system design walkthroughs.

If college or SIH makes the stretch numbers unrealistic, protect project quality and interview-level understanding instead.

---

## Career and open source

| Period | Focus |
|---|---|
| **Oct – Dec 2026** | Improve GitHub. Explore relevant repositories. Learn the contribution workflow. |
| **Jan – Mar 2027** | Build resume. Practice applications. Attempt a first PR. |
| **Apr – Sep 2027** | Improve project quality, interview skills, and contribution depth. |
| **Oct – Dec 2027** | Show LLM and RAG ability through a tested, evaluated project. |
| **Jan – Mar 2028** | Polish portfolio. Target summer 2028 internships. |

> **About GSoC:** Selection isn't guaranteed. If you're not selected, the same work still counts — reading a real codebase, communicating with maintainers, reviewing code, making useful contributions.

> **Don't wait:** You don't need to finish all 18 months before applying.

---

## System design

ML engineer interviews increasingly include system design rounds. You don't need a full course — you need repeated practice explaining design decisions out loud and on paper.

**When:** Start lightly in Phase 4 (Jul–Sep 2027), practice consistently from October 2027 onward. One problem every two weeks is enough.

**Resources**
- [Made With ML — Design](https://madewithml.com/) — ML system design patterns
- [Chip Huyen — ML Interviews](https://huyenchip.com/ml-interviews-book/) — system design chapter and ML interview prep
- [Grokking the Machine Learning Interview](https://www.educative.io/courses/grokking-the-machine-learning-interview) — paid, but comprehensive; use only if you need structure
- [DataTalksClub — ML System Design interviews (YouTube)](https://www.youtube.com/@DataTalksClub) — free walkthroughs of real interview problems

**Practice problems (work through these progressively)**
1. Design a content recommendation system for a social media feed.
2. Design a model serving infrastructure for real-time predictions with latency constraints.
3. Design a fraud detection system for online payments.
4. Design a feature store for a machine learning platform.
5. Design an A/B testing framework for model rollouts.
6. Design a search ranking system for an e-commerce platform.
7. Design a data pipeline for training data collection and labeling.

**How to practice**
- Pick one problem. Set a 45-minute timer.
- Write out: requirements, data sources, model choices, training pipeline, serving architecture, monitoring, and failure modes.
- Explain it out loud as if to an interviewer.
- Compare your design against a reference solution or video walkthrough.
- Write a short summary of what you'd do differently next time.

> **Rule:** System design practice replaces DSA time, not project time. Never sacrifice project quality for interview prep.

---

## Resources

Links are references. Course versions and enrollment options change — check them before you start.

### DSA track

**Free (primary)**
- [DSA for AI (Telegram)](https://t.me/DSAFORAI) — a free DSA course shared via Telegram. Your main structured DSA source.
- [NeetCode](https://neetcode.io/) — free roadmap of interview problems grouped by pattern. Your main practice source.
- [LeetCode](https://leetcode.com/) — easy and medium problems for extra practice.
- [MIT 6.006 (OCW)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — algorithm theory when a pattern doesn't make sense.

**DSA rules**
- Attempt each problem before reading a solution. After reading one, close it and rewrite from memory.
- Track patterns and mistakes, not just the count.
- Don't turn DSA into a playlist collection.

**DSA topic sequence** (a guide — adjust to your progress)

| Quarter | Topics |
|---|---|
| Q4 2026 | Time complexity, arrays, strings, hashing, two pointers, basic sorting/searching |
| Q1 2027 | Recursion, stacks, queues, linked lists, binary search, basic trees |
| Q2 2027 | Trees, BSTs, heaps, priority queues, traversals |
| Q3 2027 | Graphs (BFS/DFS), heap review, intro DP |
| Q4 2027 | Mixed practice, sliding window, intervals, greedy, graphs, basic DP |
| Q1 2028 | Timed mixed sets, weak-topic revision, interview-style explanations |

### SQL and tools

> **Note:** LeetCode SQL 50 is only 50 questions. Use it as a starter, not the full 150+ target.

| Resource | Purpose |
|---|---|
| [SQLBolt](https://sqlbolt.com/) | SQL fundamentals refresher |
| [LeetCode SQL 50](https://leetcode.com/studyplan/top-sql-50/) | 50 curated core-pattern questions (starter only) |
| [LeetCode Database](https://leetcode.com/problemset/database/) | Extra Easy/Medium problems beyond SQL 50 |
| [DataLemur](https://datalemur.com/questions) | Real interview questions, company-tagged |
| [StrataScratch](https://www.stratascratch.com/) | Real-world data science SQL |
| [HackerRank SQL](https://www.hackerrank.com/domains/sql) | Fundamentals and volume practice |
| [SQLZoo](https://sqlzoo.net/) | Window functions, subqueries |
| [PostgreSQL Exercises](https://pgexercises.com/) | Joins and complex queries on one dataset |
| [Advanced SQL Practice Workbook](https://github.com/search?q=advanced+sql+practice+workbook&type=repositories) | Topic-wise volume (1,400+ questions available) |
| [Oracle Dev Gym](https://devgym.oracle.com/) | Quizzes and theory |
| [LearnSQL.com](https://learnsql.com/) | Structured paid path |
| [Kaggle Learn](https://www.kaggle.com/learn) | Short pandas and intro-to-ML exercises |
| [GitHub Skills](https://skills.github.com/) | Git and pull-request workflow |

#### How to reach 150+ SQL problems

| Source | Questions | Running total |
|---|---:|---:|
| LeetCode SQL 50 | 50 | 50 |
| LeetCode Database (extra Easy/Medium) | +40 | 90 |
| DataLemur (free tier) | +25 | 115 |
| StrataScratch (free tier) | +20 | 135 |
| HackerRank SQL | +20 | **155+** |
| SQLZoo / PGExercises | as needed | for weak topics |

**Pace:** 10–15 questions/week → 150+ in about 10–12 weeks.

**Focus patterns:** joins · GROUP BY / HAVING · window functions · CTEs · subqueries · date/time functions · self-joins · conditional aggregation.

**Rule:** Redo problems you got wrong after one week. Pattern recognition matters more than the raw count.

#### 12-week SQL sprint (optional)

Use this if you want to front-load SQL and hit 150+ early. If it clashes with CS50P or Ng, stretch it to 24 weeks at 6–7 questions/week instead.

| Week | Focus | Main sources | Questions | Cumulative |
|---|---|---:|---:|---:|
| 1 | SELECT, WHERE, ORDER BY, LIMIT | SQLBolt 1–6 · LeetCode SQL 50 | 12 | 12 |
| 2 | GROUP BY, HAVING, COUNT/SUM/AVG | SQLBolt 7–9 · LeetCode SQL 50 | 12 | 24 |
| 3 | Joins: INNER, LEFT, RIGHT, self-joins | SQLBolt 10–12 · LeetCode · PGExercises | 13 | 37 |
| 4 | Subqueries, CTEs, UNION | SQLBolt 13–15 · LeetCode SQL 50 | 13 | 50 |
| 5 | Window functions: ROW_NUMBER, RANK, LAG/LEAD | SQLZoo · LeetCode | 13 | 63 |
| 6 | Date/time, string, conditional logic | LeetCode · DataLemur | 13 | 76 |
| 7 | Advanced joins, multiple CTEs, complex aggregation | StrataScratch · HackerRank | 13 | 89 |
| 8 | Pivoting, conditional aggregation, self-joins | PGExercises · DataLemur | 13 | 102 |
| 9 | Interview-style mixed problems | DataLemur · StrataScratch | 13 | 115 |
| 10 | Timed practice, weak topics | LeetCode · HackerRank | 13 | 128 |
| 11 | Company-tagged questions | DataLemur · StrataScratch | 13 | 141 |
| 12 | Review, redo wrong problems, mock SQL interview | All sources | 13 | **154+** |

**How to use it**
- 10–15 questions/week. Split across 3–4 sessions.
- After each session, write one sentence on the pattern you used.
- At the end of each week, redo one problem you got wrong earlier.
- If you finish early, stop at 150+ and switch to maintenance: 2–3 problems/week.

### Mathematics and statistics (~2 hours/week)

| Period | Focus | Resource |
|---|---|---|
| Oct – Dec 2026 | Vectors, matrices, derivatives, basic probability | [Khan Academy](https://www.khanacademy.org/math) · [3Blue1Brown](https://www.3blue1brown.com/topics/linear-algebra) |
| Jan – Mar 2027 | Linear algebra and statistics for evaluation metrics | [MIT 18.06](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) (selected lectures) |
| Apr – Jun 2027 | Chain rule and gradients for backpropagation | Trace gradients by hand in a small network |
| Jul – Sep 2027 | Conditional probability and Bayes | [Harvard Stat 110](https://stat110.hsites.harvard.edu/youtube) |
| Oct – Dec 2027 | Dot products, cosine similarity, nearest neighbors | Your RAG project |
| Jan – Mar 2028 | Only what blocks your project or interview explanations | As needed |

**Reference only:** [MIT 18.065](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) · MIT 18.650 · MIT RES.6-012 — via [MIT OCW](https://ocw.mit.edu/).

**Optional depth:** [UCB CS70: Discrete Math and Probability](https://csdiy.wiki/数学进阶/CS70/) — ~60 h. Only start this if you've finished the primary resources for the current phase and have spare capacity. Don't run it in parallel with Khan Academy/3Blue1Brown.

Study only the lessons that address a current gap. Don't try to finish full university courses.

### Optional course catalog (CSDIY)

[CS自学指南 (CSDIY)](https://csdiy.wiki/) is a community guide to university courses, with prerequisites and estimated hours. Use it as a **reference catalog**, not a second roadmap. Pick **one** course for a named gap. Never run several at once.

| Course | Phase | Effort | Use when |
|---|---|---|---|
| [CS229 (Stanford)](https://csdiy.wiki/机器学习/CS229/) | 2 | ~100 h | You want algorithm-level ML depth |
| [CMU 15-445 (Databases)](https://csdiy.wiki/数据库系统/15445/) | 2 or 6 | ~100 h | You want database internals (needs C++) |
| [CS231n (Stanford)](https://csdiy.wiki/深度学习/CS231/) | 3 | ~80 h | Project 3 is image-based |
| [CS285 (Berkeley RL)](https://rail.eecs.berkeley.edu/deeprlcourse/) | Optional | ~100 h | You develop a specific RL interest |
| [CS224n (Stanford NLP)](https://web.stanford.edu/class/cs224n/) | 5 | ~80–100 h | Transformers and NLP depth (selected lectures) |
| [CS336 (Stanford LLMs)](https://csdiy.wiki/深度生成模型/roadmap/) | 5 | ~100 h+ | You want to write LLM training code yourself |
| [MIT 6.S184 (Diffusion)](https://csdiy.wiki/深度生成模型/MIT6.S184/) | 5 | ~60 h | You're interested in diffusion models |
| [MIT 6.006 (Algorithms)](https://csdiy.wiki/数据结构与算法/6.006/) | 4 | ~60 h | You want a deeper algorithms course |
| [Full Stack Open](https://csdiy.wiki/Web开发/fullstackopen/) | 6 | ~100 h | You want a React/Node.js interface for the agent |

### Supplements (use only for a specific gap)

- [MASTER ROADMAP 2026–2027](https://youtube.com/playlist?list=PLYMLIfEYAPgM) by Yogesh Kumar Singh — sequencing guide for project ideas. Don't watch in upload order.
- [CampusX — 100 Days of ML](https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH) — Hindi and English explanations
- [StatQuest](https://www.youtube.com/@statquest) — short statistics and ML explanations
- [freeCodeCamp](https://www.youtube.com/@freecodecamp) — API development and Python projects
- [Stanford Algorithms (Roughgarden)](https://www.coursera.org/learn/algorithms-part1) — only if DSA is stable
- [Fluent Python](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/) — reference for idiomatic Python
- [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) — deployment practice

---

## Rules

1. **One main course + one project at a time**, plus DSA.
2. **Protect college and sleep.** Exam and SIH weeks drop to 3–8 hours. No backlog.
3. **Keep DSA regular.** 3–4 hours a week, shorter sessions on busy days.
4. **Cut scope, not quality.** Remove features before you remove tests, evaluation, or documentation.
5. **Start open source early.** Read repositories from November 2026.
6. **Start mock interviews in September 2027.** Don't wait until the last month.
7. **Reset if unsustainable.** Three weeks behind → drop to 10 hours and rebuild.
8. **Apply on evidence.** You don't need to finish all 18 months before applying.
9. **Practice system design from Phase 4 onward.** One problem every two weeks. Replace DSA time, not project time.

---

*No plan can guarantee GSoC selection, an internship, or a top-10% ranking. This plan gives you real work and technical evidence to compete with.*
