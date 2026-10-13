18-Month ML Engineer Roadmap
============================

**October 13, 2026 → April 10, 2028 · 78 weeks · ~16 hours/week · Free-first**

**Goal:** Become a credible candidate for ML, AI, and software internships by proving you can **build, evaluate, deploy, and explain** real systems. Certificates alone don't count.

> GSoC, internships, and merged PRs are **targets, not promises**.

**Track your progress in PROGRESS.md** and update it every Sunday.

Contents
--------

1.  [Overview](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#overview)
    
2.  [Start here](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#start-here)
    
3.  [How to study](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#how-to-study)
    
4.  [The six phases](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#the-six-phases)
    
5.  [Portfolio projects](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#portfolio-projects)
    
6.  [Checkpoints](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#checkpoints)
    
7.  [Targets](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#targets)
    
8.  [Career and open source](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#career-and-open-source)
    
9.  [System design](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#system-design)
    
10.  [Resources](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#resources)
    
11.  [Rules](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#rules)
    

Overview
--------

**Duration**78 weeks · Oct 13, 2026 – Apr 10, 2028 (assuming Week 1 starts Oct 13)**Pace**15 h minimum · **16 h target** · 18 h stretch**Starting point**CS50SQL done · CS50P nearly done · Python/Flask basics · hackathon experience · SIH projects (GeM procurement, Watershed Insight)**Finish line**6 evaluated phase releases across 5 portfolio entries, a deployed ML app, a RAG-to-agent system, steady DSA and SQL practice, and a polished GitHub, resume, and LinkedIn**Total effort**1,248 planned hours at 16 h/week (1,170 at 15 h · 1,404 at 18 h) before exam, break, and life weeks. These are planning totals, not hours to make up later.

### Phases at a glance

**PhasePlanning window (13 weeks each)FocusRelease gate**1\. FoundationsOct 13, 2026 – Jan 11, 2027Python, supervised ML, SQL, pandas**P1** Tabular ML · Jan 11, 20272. Applied MLJan 12 – Apr 12, 2027Model selection, APIs, deployment, Git**P2** Deployed ML app · Apr 12, 20273. Deep LearningApr 13 – Jul 12, 2027PyTorch, neural networks, CNNs**P3** PyTorch model · Jul 12, 20274. AI Foundations & AlgorithmsJul 13 – Oct 11, 2027Search, uncertainty, DSA interview prep**P3.5** AI mini-project · Oct 11, 20275. LLMs & RAGOct 12, 2027 – Jan 10, 2028Transformers, embeddings, retrieval**P4a** Evaluated RAG app · Jan 10, 20286. Agents, MLOps & PortfolioJan 11 – Apr 10, 2028LangGraph, Docker, testing, portfolio**P4b** Agent capstone · Apr 10, 2028

**Date convention:** Week 1 starts Oct 13, 2026. Six 13-week phases end Apr 10, 2028. The former March 2028 finish was one phase short under the six-cycles-plus-buffer structure, so release gates move; don't compress them. Month names below are planning windows. Start monitoring summer 2028 internships during Phase 5 and apply as roles open rather than waiting for the final capstone.

Start here
----------

### First week (starting Oct 13, 2026)

*   Confirm the actual first study date and block up to 16 hours around college.
    
*   Freeze P1's two-sentence success/failure contract, dataset provenance, split protocol, duplicate policy, metric, and evaluation command before modeling.
    
*   Finish CS50P and check solutions; start only the Andrew Ng module needed to unblock P1.
    
*   Solve 3–5 SQL problems and review mistakes; aim for 10–20 cumulative by Oct 31 (20 is stretch).
    
*   Start DSA with complexity, arrays, and hashing.
    
*   Ship P1 v0 by Oct 26: data checks, frozen split, dummy baseline, validation script, and saved measured result.
    
*   Defer repo polish and GSoC guide reading if they threaten P1 v0; they are useful, not blockers.
    

> The first two weeks are for a measured baseline, not for finishing every setup task. Keep the 16-hour ceiling; reduce optional tasks rather than borrowing from sleep or exams.

How to study
------------

### Weekly schedule

**Activity15 h16 h18 h**Projects and implementation5**6**7Main learning track3**3**3DSA and problem solving3**3**4Math, statistics, and SQL2**2**2Testing, documentation, and review1**1**1Open source and career prep1**1**1**Total151618**

**Example 16-hour week**

**DayStudy**MonMain course 1 h + DSA 1 hTueProject 2 hWedDSA 1 h + math/stats 1 hThuMain course 1 h + project 1 hFriProject 2 h + testing/docs 1 hSatDSA 1 h + open source/career 1 hSunProject 1 h + main course 1 h + math/stats 1 h

Use **18 hours** only when college and sleep allow. Drop to **15** in lighter weeks.

### Durable and perishable skills: 30 / 70

This is a second view of the same hours, not extra work. At 16 h/week, aim for approximately 11 h of technical/tool practice and 5 h of durable practice: statistics/SQL reasoning, systematic debugging and experiment design, tests and clear writing, and explaining trade-offs. Treat this as a monthly average, not a weekly quota.

### Two-week experiment rhythm

Each 13-week phase contains six two-week cycles plus one buffer week. Before coding, write exactly two sentences: “Success means \[metric, threshold, dataset/split, protocol, budget\].” “Failure means \[quality or safety violation\], in which case I will \[first diagnostic/action\].”

*   **Week A:** freeze the question and evaluation protocol, implement the smallest baseline, and save the initial measurement.
    
*   **Week B:** change one thing, rerun the same evaluation, inspect failures, and publish a runnable commit with results and a short decision note.
    
*   Use development data for iteration and run the sealed test only at the release gate. If you inspect test errors and then tune, disclose that the set is spent and obtain a new holdout when feasible.
    
*   Keep a flat list of at most 4–5 active failure modes; link each fix to evidence or a regression test.
    
*   Every cycle ends with a runnable commit and machine-readable result. Publish an interim evaluation snapshot around weeks 7–8, then the full phase release. This yields public evidence every 6–8 weeks without starting another project.
    

### Sunday review (15 minutes)

1.  What did I ship and measure? Link the commit and evaluation output.
    
2.  What did I learn, and which failure or experiment comes next?
    
3.  What is blocked, and what's the smallest next step?
    
4.  Which one task matters most next week?
    
5.  Did I preserve project/evaluation time and fit the plan around college and sleep?
    

### When life gets busy

**SituationWhat to do**Exams, SIH, or hackathonsDrop to **3–8 hours/week**. Don't create a backlog.Very busy weekKeep one DSA session, one course session, one project session.Project running late**Cut scope**, not testing, evaluation, or documentation.Three weeks behindDrop to **10 hours/week** for a while, then rebuild.Exam months (May/June, December)Treat as lighter. Move milestones instead of catching up.Quarter-end weeks (Dec, Mar, Jun, Sep)Buffer for catch-up, polish, or rest.

### Study rules

*   **One main course + one project at a time**, plus DSA. Don't run several courses in parallel.
    
*   **Finishing a lecture isn't the goal.** A phase is done when its required output exists.
    
*   **Add a new course only if all three are true:** it fills a named gap, you know the exact module you need, and you'll apply it to a project within two weeks.
    
*   **Use Python** for DSA unless your placement requires C++.
    

The six phases
--------------

Each phase has a goal, core resources, optional extras, a monthly checklist, and a milestone.

### Phase 1 — Foundations

**October 13, 2026 – January 11, 2027**

**Goal:** Build Python fluency, learn supervised ML, and refresh SQL, NumPy, pandas, and basic statistics.

**Core resources**

*   [CS50P](https://cs50.harvard.edu/python/) — Python foundations
    
*   [Andrew Ng's ML Specialization](https://www.deeplearning.ai/specializations/machine-learning/) — your main ML course
    
*   [scikit-learn Getting Started](https://scikit-learn.org/stable/getting_started.html)
    
*   **DSA:** [DSA for AI (free Telegram channel)](https://t.me/DSAFORAI) + [NeetCode](https://neetcode.io/) — see the [DSA track](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#dsa-track)
    

**Optional extras (pick one or two at most)**

*   [Tech With Tim — Learn Python With This ONE Project!](https://www.youtube.com/@TechWithTim)
    
*   [Karina Data Scientist — Clean Data in Minutes with Python](https://www.youtube.com/@KarinaDataScientist)
    
*   [UCB CS70: Discrete Math and Probability](https://csdiy.wiki/数学进阶/CS70/) — ~60 h
    

**Monthly checklist**

*   **Oct 13–31, 2026** — Finish CS50P. Start Ng. Freeze P1 contract and split. Ship P1 v0 by Oct 26. Aim for 10–20 cumulative SQL problems (20 is stretch). Start DSA (complexity, arrays, hashing).
    
*   **Nov–Dec 2026** — Study regression, classification, gradient descent. Practice NumPy/pandas. Improve P1 against its frozen baseline. Read GSoC guides and attempt one useful contribution only if project time remains. Protect exam time.
    
*   **Jan 1–11, 2027** — Freeze the model, run the official held-out test once, publish error analysis and a pass/miss decision. Aim for 35–50 cumulative SQL problems by the phase gate; 75 is a stretch sprint, not the default.
    

**Milestone:** CS50P complete, Ng's course underway, and P1 released with reproducible evaluation and honest limitations.

**One phase artifact — P1 tabular classifier:** Use the public UCI Adult dataset for educational use only, not hiring or credit decisions. Preserve the official test partition; split the official training data 80/20 with a fixed seed and stratification. Fit preprocessing only on training data. Freeze an exact-duplicate policy before splitting: prevent identical feature rows crossing the internal train/validation boundary, record counts and IDs, and disclose any overlap across the official train/test boundary without using test labels to tune.

**Pre-code contract (two sentences):** Success means validation macro-F1 beats the most-frequent dummy baseline by at least 0.10 absolute on the frozen validation split, and a clean checkout reproduces the score within 0.01. Failure means leakage, non-reproducibility, or missing the target; first audit duplicate handling, split construction, and preprocessing, then inspect the largest validation errors, and publish a clearly labeled miss if the target remains unmet.

**CycleVerifiable output**1 (weeks 1–2)Freeze provenance/contract; ship split manifest, dummy baseline, validation script, and measured P1 v0 by Oct 26.2–3 (weeks 3–6)Compare logistic regression and one tree-based model under the same protocol.4 (weeks 7–8)Inspect false positives/negatives and subgroup slices; publish an interim evaluation snapshot.5 (weeks 9–10)Add schema/leakage checks and clean-environment reproduction.6 (weeks 11–12)Freeze model, run official held-out test once, publish failures and the release decision.Buffer (week 13)Peer reproduction, rest, or scope recovery; no second project.

### Phase 2 — Applied ML

**January 12 – April 12, 2027**

**Goal:** Move from notebooks to tested, deployable apps. Cover model selection, cross-validation, leakage prevention, Flask/FastAPI, Git, Linux, virtual environments, and experiment tracking.

**Core resources**

*   [scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
    
*   [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course/) — selected modules
    
*   [Flask documentation](https://flask.palletsprojects.com/)
    

**Optional extras**

*   [freeCodeCamp — Python API Development](https://www.youtube.com/@freecodecamp)
    
*   [CS229 (Stanford)](https://csdiy.wiki/机器学习/CS229/) — ~100 h. Only if you want algorithm internals.
    
*   [CMU 15-445 (Databases)](https://csdiy.wiki/数据库系统/15445/) — ~100 h, needs C++. Only for deep backend work.
    

**Monthly checklist**

*   **Jan 12–Mar 2027** — Ensembles, cross-validation, leakage, tuning. Reuse P1's frozen model and preprocessing as Project 2. Continue timed DSA and attempt a first small PR.
    
*   **Feb–Mar 2027** — Build and test a Flask/FastAPI interface; learn Git branches, PRs, Linux, and virtual environments. Draft your resume. Continue at 2–3 reviewed SQL problems/week; 100 cumulative is a stretch, not a deadline.
    
*   **Apr 1–12, 2027** — Deploy P2, publish the API evaluation report and short walkthrough, and check official GSoC dates.
    

**Choose one experiment tracker:** MLflow or Weights & Biases.

**Milestone:** Ng's course complete. P2 tested, documented, deployed, and evaluated.

**One phase artifact — P2: P1 behind an API.** Compare API predictions with offline predictions on 100 fixed valid requests; reject 20 invalid-input cases correctly; measure p95 latency over 500 warmed requests at concurrency 1 on documented hardware. Measure cold start separately.

**Pre-code contract (two sentences):** Success means 100% offline/API prediction agreement, all 20 invalid inputs rejected correctly, and p95 latency below 200 ms over 500 warm requests on the stated hardware. Failure means prediction disagreement, validation bypass, or a missed latency budget; profile and simplify before adding UI features.

> **Career note:** Summer 2027 is a stretch. Aim for stronger summer 2028 applications. If no internship comes, use the break for a small project, hackathon, or open-source contribution.

### Phase 3 — Deep Learning

**April 13 – July 12, 2027**

**Goal:** Understand tensors, autograd, training loops, optimizers, and regularization. Train a CNN or text classifier.

**Core resources**

*   [PyTorch Tutorials](https://pytorch.org/tutorials/) — main implementation track
    
*   [fast.ai](https://course.fast.ai/) — practical, project-first deep learning
    

**Optional extras**

*   [Karpathy — Neural Networks: Zero to Hero](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) — build networks by hand
    
*   Selected lectures from [MIT 6.S191](https://introtodeeplearning.com/)
    
*   [CS231n (Stanford)](https://csdiy.wiki/深度学习/CS231/) — ~80 h. Good if Project 3 is image-based.
    

**Monthly checklist**

*   **Apr–May 2027** — Tensors, autograd, nn.Module, training loops, optimizers, regularization, CNNs or text classification. Start P3, train the baseline, and log experiments. Submit GSoC if applying.
    
*   **Jun–Jul 12, 2027** — Run three training seeds, inspect class-level errors, freeze the model, evaluate held-out test once, and publish reproducibility details.
    

**Milestone:** PyTorch project with reproducible training, evaluation, and a short write-up.

**One phase artifact — P3 PyTorch classifier.** Choose one small licensed public image or text dataset; freeze split IDs and check duplicate/source-group overlap. Compare a small neural model to a simple baseline under identical splits.

**Pre-code contract (two sentences):** Success means validation macro-F1 improves by at least 0.03 absolute over the declared simple baseline, with mean and range reported across three training seeds. Failure means split contamination, a missing baseline, or an unmet target; inspect learning curves and failure examples before increasing compute.

**Notes**

*   Ng's _Machine Learning_ Specialization ≠ his _Deep Learning_ Specialization. The Deep Learning one is optional and historically TensorFlow-based. Check the current syllabus before starting.
    
*   **Compute:** Use Colab or Kaggle for free GPU. Save checkpoints. Keep datasets small. Don't make paid GPUs or APIs a requirement.
    

### Phase 4 — AI Foundations & Algorithms

**July 13 – October 11, 2027**

**Goal:** Learn search, knowledge representation, probabilistic reasoning, and optimization. Build DSA interview fluency. Ship one small AI project so this phase produces a portfolio piece, not just coursework.

**Core resources**

*   [Harvard CS50AI](https://cs50.harvard.edu/ai/) — **priority topics only:** search, knowledge representation, uncertainty, optimization. Skip ML and neural-network sections that duplicate Ng/PyTorch.
    
*   **DSA:** Continue with [DSA for AI (Telegram)](https://t.me/DSAFORAI) and [NeetCode](https://neetcode.io/) — trees, graphs, heaps, DP. See the [DSA track](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#dsa-track).
    

**Optional extras**

*   [MIT 6.006](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — extra depth on graphs and DP
    
*   [CS285 (Berkeley Deep RL)](https://rail.eecs.berkeley.edu/deeprlcourse/) — only if you develop a specific RL interest
    

**Monthly checklist**

*   **Jul–Aug 2027** — CS50AI search, knowledge representation, uncertainty, and optimization. Review probability, continue DSA, and build the selected mini-project.
    
*   **Sep–Oct 11, 2027** — Finish selected CS50AI projects, document the mini-project and a technical contribution, and start mock interviews. Start light system-design practice by replacing a DSA session every other week.
    

**Milestone:** Clean CS50AI repos, an evaluated AI mini-project, and first mock interviews.

_One phase artifact — P3.5 A pathfinder._\* Use unit-cost four-neighbor grids and Manhattan distance; compare A\* with BFS on 100 development and 100 held-out seeded maps, including unreachable goals.

**Pre-code contract (two sentences):** Success means A\* matches BFS reachability and optimal path length on every evaluation map, and reduces median expanded nodes by at least 20% on reachable development maps. Failure means an invalid/non-optimal path, incorrect unreachable result, or no efficiency gain; debug the heuristic and report counterexamples.

**Phase 4 mini-project ideas (pick one, keep it small):**

*   A constraint-satisfaction puzzle solver (Sudoku, map coloring) with a write-up on the search strategy used.
    
*   A Bayesian spam filter built from scratch on a public dataset, with calibration analysis.
    
*   An A\* pathfinding visualizer with a short technical write-up.
    
*   A small game-playing agent (minimax with alpha-beta pruning) for a simple board game.
    

> **Rule:** Consistent DSA matters more than finishing another course. Roughgarden's algorithms course and CS229 stay optional unless you're clearly ahead.

### Phase 5 — LLMs & RAG

**October 12, 2027 – January 10, 2028**

**Goal:** Understand tokenization, embeddings, transformers, and pretrained models. Build retrieval-augmented generation (RAG) that gives grounded, sourced answers and is **measured**.

**Core resources**

*   [Hugging Face LLM Course](https://huggingface.co/learn/llm-course)
    
*   [pguso/rag-from-scratch](https://github.com/pguso/rag-from-scratch) — step-by-step RAG, no black boxes
    
*   [LangChain documentation](https://docs.langchain.com/oss/python/learn) — used after building RAG from scratch
    

**Optional extras**

*   [LLM Zoomcamp](https://github.com/DataTalksClub/llm-zoomcamp) — project-first RAG
    
*   Selected lectures from [Stanford CS224N](https://web.stanford.edu/class/cs224n/) (~80–100 h full course)
    
*   [DeepLearning.AI short courses](https://www.deeplearning.ai/short-courses/) — only when they support your project
    
*   [Karpathy — Let's reproduce GPT-2 (124M)](https://www.youtube.com/@AndrejKarpathy) — advanced; watch last
    
*   [CS336 (Stanford LLMs)](https://csdiy.wiki/深度生成模型/roadmap/) — advanced LLM internals
    
*   [MIT 6.S184 (Diffusion)](https://csdiy.wiki/深度生成模型/MIT6.S184/) — only if interested in diffusion models
    

**Monthly checklist**

*   **Oct–Nov 2027** — Study transformers, tokenization, embeddings, and pretrained models. Freeze a licensed/public corpus, 50 questions (30 development / 20 sealed test), rubric, and numeric latency/cost budgets; ship a lexical baseline.
    
*   **Nov–Dec 2027** — Build raw RAG: parsing, chunking, embeddings, retrieval, grounded answers, and abstention. Reach 130–150 cumulative SQL problems by the January release gate; 150 remains a goal, not a reason to skip evaluation.
    
*   **Jan 1–10, 2028** — Add LangChain only where useful, add tests/API/deployment, run the sealed test once, publish every failure, and ship P4a.
    

**Milestone:** Deployed RAG app with source citations and measured retrieval quality.

**RAG evaluation standard**

*   Author 50 realistic questions before tuning: 30 development and 20 sealed test; include at least 5 unanswerable questions in each split and expected evidence for answerable questions.
    
*   Report retrieval hit@5 on answerable questions, with numerator/denominator. Hand-label answer relevance, faithfulness, citation resolution, and explicit abstention; report all denominators and failure examples.
    
*   Freeze the held-out pass rule and numeric latency/cost budget before cycle 1. Do not tune on sealed-test errors; if you do, mark the set spent and get a new holdout when feasible.
    
*   A working chatbot or judge-model score alone is not a complete evaluation. RAGAS can supplement—not replace—the human rubric.
    

**Pre-code contract (two sentences):** Success means development hit@5 is at least 80% on answerable questions, at least 80% of all development items pass the human answer/citation rubric, every unanswerable development item is explicitly abstained, and the sealed test meets the same predeclared thresholds within frozen budgets. Failure means a failed gate, unsupported claim, fabricated/unresolved citation, or budget breach; fix retrieval and grounding using development data only and report the sealed result as a miss.

**Compute:** Prefer small open-weight models, local inference with [Ollama](https://ollama.com/) where possible, or free-tier services. Plan a fallback so API limits don't block you. **Never commit API keys.**

### Phase 6 — Agents, MLOps & Portfolio

**January 11 – April 10, 2028**

**Goal:** Turn the RAG app into a tested, documented, observable agent system. Polish the whole portfolio.

**Core resources**

*   [LangGraph documentation](https://docs.langchain.com/oss/python/learn) — state, nodes, edges, routing, tool calls
    
*   [Docker — Get Started](https://docs.docker.com/get-started/)
    
*   [Made With ML](https://madewithml.com/) — testing, deployment, monitoring
    

**Optional extras**

*   [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp)
    
*   [FastAPI Tutorial](https://fastapi.tiangolo.com/tutorial/)
    
*   [Full Stack Open](https://csdiy.wiki/Web开发/fullstackopen/) — React and Node.js for a full-stack agent interface
    
*   [Kun Chen — Full Stack App with Agentic Engineering](https://www.youtube.com/@KunChen)
    
*   Optional big capstone: **Autonomous Research Assistant** (React, FastAPI, PostgreSQL, LLM). Only after the core agent works.
    

**Monthly checklist**

*   **Jan–Feb 2028** — Learn LangGraph basics; extend P4a with one bounded stateful workflow and read-only tools by default. Add tests, logs, basic monitoring, Docker, and a rollback path. Begin/continue applications as relevant openings appear.
    
*   **Mar–Apr 10, 2028** — Run held-out tasks once, publish the P4b report and write-up, polish portfolio/resume, revise interview fundamentals, and continue applications. Do not delay applications until the capstone is finished.
    

**Milestone:** Tested, documented, observable agent capstone and polished portfolio.

**One phase artifact — P4b observable agent.** Extend P4a rather than starting a new capstone. Freeze 30 development tasks and 20 held-out tasks with expected outcomes, including prompt injection, tool failure, and unanswerable cases; compare agent and non-agent RAG on identical tasks.

**Pre-code contract (two sentences):** Success means at least 24/30 development tasks and 16/20 held-out tasks succeed, the agent is not worse than the non-agent baseline on the same tasks, 100% of tool-permission and step-limit checks pass, and latency/cost stays within frozen budgets. Failure means any unauthorized action, failed tool-permission or step-limit check, unbounded loop, result below either threshold or baseline, or budget breach; disable agent routing and retain the simpler pipeline.

**Agent rules**

*   A reliable, evaluated agent beats a complicated multi-agent system.
    
*   Restrict tool access; keep tools read-only by default and require human approval for consequential actions.
    
*   Report paired outcomes on the same tasks. One held-out task changes the 20-task success rate by five percentage points; do not imply production reliability from this small benchmark.
    

> **If you consistently hit 18 hours:** Use the extra capacity to improve tests, documentation, reproducibility, and open-source contributions. Do not expand the agent scope or compress the sealed evaluation. Keep applications moving while the capstone is in progress.

Portfolio projects
------------------

Existing SIH projects count if they meet the same standard. Don't create extra projects just to hit a number.

**#ProjectDueWhat it provesP1**Tabular MLJan 11, 2027Baseline vs improved model, correct metrics, error analysis**P2**Deployed ML appApr 12, 2027API parity, validation, latency measurement, tests, demo**P3**PyTorch modelJul 12, 2027Training, baseline comparison, reproducibility, failure analysis**P3.5**AI mini-projectOct 11, 2027Search / probabilistic reasoning with correctness and efficiency evaluation**P4**RAG → agentJan–Apr 2028Retrieval evaluation, citations, held-out tasks, tools, tests, Docker

**P1 — Tabular ML.** Train a baseline and an improved model. Include data preparation, appropriate metrics, error analysis, and limitations.

**P2 — Deployed ML app.** Serve predictions through Flask or FastAPI with validation, tests, setup instructions, and a demo. Add a compact dashboard (Plotly, Streamlit, Power BI, or Tableau) and a **20-minute walkthrough**: the question, data, key insights, caveats, and decisions a stakeholder could make. Also supports data analyst applications._Optional idea:_ customer segmentation pipeline served as a FastAPI endpoint.

**P3 — PyTorch deep learning.** Train and evaluate a neural network, compare with a sensible baseline, document reproducibility. Choose image classification if you want to pair it with CS231n.

**P3.5 — AI mini-project.** A small, well-documented application of classical AI: search, constraint satisfaction, or probabilistic reasoning. Must include a working implementation, a short write-up explaining the approach, and honest limitations. See [Phase 4](https://arena.ai/agent/01a13621-6ec8-7f0a-9616-823c9bad5fdd#phase-4--ai-foundations--algorithms) for ideas.

**P4 — RAG upgraded into an agent.** Build retrieval from first principles, measure retrieval and answer quality, add sources. Then add an agent workflow, tests, logging, and Docker._Optional idea:_ modified GPT-2 (changed positional encoding or LR schedule), trained on a small dataset with a write-up. Only after Karpathy's Zero to Hero.

### Choosing a SIH project

Pick the SIH project where you can:

*   explain the problem, your contribution, the data pipeline, the evaluation, and the limitations;
    
*   reproduce it and demo it reliably.
    

A large team project isn't automatically a strong individual piece. Document clearly what **you** designed, implemented, tested, and maintained.

### Every core project should have

*   A clearly stated question, intended user, licensed data source, and pre-code success/failure contract
    
*   A baseline, frozen split/evaluation protocol, and appropriate metric
    
*   Train / validation / test separation with no data leakage; sealed test data used only at the release gate
    
*   Machine-readable evaluation output, baseline comparison, and explicit pass/miss decision
    
*   Error analysis with concrete failures, a flat top-4–5 failure list, and honest limitations
    
*   Reproducible setup instructions, tests, and a clean-checkout evaluation command
    
*   A working demo or screenshots if deployment isn't practical
    
*   A README, short technical write-up, and clear note on individual contribution
    

> **Visibility:** Each two-week cycle gets a runnable commit and measurement. Publish an interim snapshot around weeks 7–8 and one concise public write-up per phase release. By April 2028, have a simple portfolio page linking to demos, repos, and write-ups.

Checkpoints
-----------

Use these to adjust scope. Don't silently carry unfinished work forward. Quarter-end weeks are buffers, not extra deadlines.

**ByCheckIf not metOct 26, 2026**P1 v0: split, dummy baseline, validation script, saved resultCut dataset/model scope; defer optional lectures, not measurement.**Jan 11, 2027**P1 release; Ng at least halfway; sealed test evaluated onceDrop optional reading; move dates, not testing or documentation.**Apr 12, 2027**Ng complete; P2 deployed with API evaluation reportDelay PyTorch up to a month. Don't skip evaluation or tests.**Jul 12, 2027**P3 reproducible with baseline, three-seed validation, and held-out reportReduce CS50AI scope; keep DSA steady.**Oct 11, 2027**CS50AI work documented; P3.5 shipped; mock interviews startedNarrow CS50AI and ship the smallest correct mini-project.**Jan 10, 2028**P4a deployed with 50-question split and sealed evaluationKeep agent scope small; protect RAG evaluation.**Apr 10, 2028**P4b released, portfolio/resume ready; applications already underwayPrioritize reliable demos, clear explanations, and applications.

Targets
-------

**AreaTarget by April 2028Projects**6 evaluated phase releases across 5 portfolio entries (P1, P2, P3, P3.5, P4a → P4b)**DSA**300+ independently solved problems, tracked by topic and explanation quality**SQL**150+ problems: joins, aggregation, subqueries, CTEs, window functions**Open source**2–4 substantive PR attempts; at least one merged or meaningfully reviewed**Mock interviews**10+, starting September 2027**System design**5+ practiced ML system design problems with written explanations**Deployment**Deployed RAG app with retrieval evaluation; agent with tests, logging, Docker**GitHub**Clean repos with README, tests, reproducible setup**Career**Updated resume, LinkedIn, portfolio page, application tracker, one public write-up per phase release

**Two tiers of success**

*   **Core:** 4–5 strong projects you can explain and reproduce, steady DSA and SQL, at least one real contribution attempt, clear write-ups.
    
*   **Stretch:** 300+ DSA problems, 150+ SQL problems, multiple substantive PRs, 10+ mock interviews, 5+ system design walkthroughs.
    

If college or SIH makes the stretch numbers unrealistic, protect project quality and interview-level understanding instead.

Career and open source
----------------------

**PeriodFocusOct – Dec 2026**Improve GitHub. Explore relevant repositories. Learn the contribution workflow.**Jan – Mar 2027**Build resume. Practice applications. Attempt a first PR.**Apr – Sep 2027**Improve project quality, interview skills, and contribution depth.**Oct – Dec 2027**Show LLM and RAG ability through a tested, evaluated project.**Jan – Apr 2028**Polish portfolio while applying as suitable summer 2028 roles open; do not wait for the P4b release.

> **About GSoC:** Selection isn't guaranteed. If you're not selected, the same work still counts — reading a real codebase, communicating with maintainers, reviewing code, making useful contributions.

> **Don't wait:** You don't need to finish all 18 months before applying.

System design
-------------

ML engineer interviews increasingly include system design rounds. You don't need a full course — you need repeated practice explaining design decisions out loud and on paper.

**When:** Start lightly in Phase 4 (Jul–Oct 2027), practice consistently from October 2027 onward. One 45–60-minute problem every two weeks is enough; it replaces a DSA session that week, never project/evaluation time.

**Resources**

*   [Made With ML — Design](https://madewithml.com/) — ML system design patterns
    
*   [Chip Huyen — ML Interviews](https://huyenchip.com/ml-interviews-book/) — system design chapter and ML interview prep
    
*   [Grokking the Machine Learning Interview](https://www.educative.io/courses/grokking-the-machine-learning-interview) — paid, but comprehensive; use only if you need structure
    
*   [DataTalksClub — ML System Design interviews (YouTube)](https://www.youtube.com/@DataTalksClub) — free walkthroughs of real interview problems
    

**Practice problems (work through these progressively)**

1.  Design a content recommendation system for a social media feed.
    
2.  Design a model serving infrastructure for real-time predictions with latency constraints.
    
3.  Design a fraud detection system for online payments.
    
4.  Design a feature store for a machine learning platform.
    
5.  Design an A/B testing framework for model rollouts.
    
6.  Design a search ranking system for an e-commerce platform.
    
7.  Design a data pipeline for training data collection and labeling.
    

**How to practice**

*   Pick one problem. Set a 45-minute timer.
    
*   Write out: requirements, data sources, model choices, training pipeline, serving architecture, monitoring, and failure modes.
    
*   Explain it out loud as if to an interviewer.
    
*   Compare your design against a reference solution or video walkthrough.
    
*   Write a short summary of what you'd do differently next time.
    

> **Rule:** System design practice replaces DSA time, not project time. Never sacrifice project quality for interview prep.

Resources
---------

Links are references. Course versions and enrollment options change — check them before you start.

### DSA track

**Free (primary)**

*   [DSA for AI (Telegram)](https://t.me/DSAFORAI) — a free DSA course shared via Telegram. Your main structured DSA source.
    
*   [NeetCode](https://neetcode.io/) — free roadmap of interview problems grouped by pattern. Your main practice source.
    
*   [LeetCode](https://leetcode.com/) — easy and medium problems for extra practice.
    
*   [MIT 6.006 (OCW)](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-fall-2011/) — algorithm theory when a pattern doesn't make sense.
    

**DSA rules**

*   Attempt each problem before reading a solution. After reading one, close it and rewrite from memory.
    
*   Track patterns and mistakes, not just the count.
    
*   Don't turn DSA into a playlist collection.
    

**DSA topic sequence** (a guide — adjust to your progress)

**QuarterTopics**Q4 2026Time complexity, arrays, strings, hashing, two pointers, basic sorting/searchingQ1 2027Recursion, stacks, queues, linked lists, binary search, basic treesQ2 2027Trees, BSTs, heaps, priority queues, traversalsQ3 2027Graphs (BFS/DFS), heap review, intro DPQ4 2027Mixed practice, sliding window, intervals, greedy, graphs, basic DPQ1–Q2 2028Timed mixed sets, weak-topic revision, interview-style explanations

### SQL and tools

> **Note:** LeetCode SQL 50 is only 50 questions. Use it as a starter, not the full 150+ target.

**ResourcePurpose**[SQLBolt](https://sqlbolt.com/)SQL fundamentals refresher[LeetCode SQL 50](https://leetcode.com/studyplan/top-sql-50/)50 curated core-pattern questions (starter only)[LeetCode Database](https://leetcode.com/problemset/database/)Extra Easy/Medium problems beyond SQL 50[DataLemur](https://datalemur.com/questions)Real interview questions, company-tagged[StrataScratch](https://www.stratascratch.com/)Real-world data science SQL[HackerRank SQL](https://www.hackerrank.com/domains/sql)Fundamentals and volume practice[SQLZoo](https://sqlzoo.net/)Window functions, subqueries[PostgreSQL Exercises](https://pgexercises.com/)Joins and complex queries on one dataset[Advanced SQL Practice Workbook](https://github.com/search?q=advanced+sql+practice+workbook&type=repositories)Topic-wise volume (1,400+ questions available)[Oracle Dev Gym](https://devgym.oracle.com/)Quizzes and theory[LearnSQL.com](https://learnsql.com/)Structured paid path[Kaggle Learn](https://www.kaggle.com/learn)Short pandas and intro-to-ML exercises[GitHub Skills](https://skills.github.com/)Git and pull-request workflow

#### How to reach 150+ SQL problems

**SourceQuestionsRunning total**LeetCode SQL 505050LeetCode Database (extra Easy/Medium)+4090DataLemur (free tier)+25115StrataScratch (free tier)+20135HackerRank SQL+20**155+**SQLZoo / PGExercisesas neededfor weak topics

**Default pace:** 2–3 deliberate, reviewed questions/week within the existing shared math/statistics/SQL budget. A 10–15/week sprint is optional and must replace other study time; do not treat it as the normal pace.

**Focus patterns:** joins · GROUP BY / HAVING · window functions · CTEs · subqueries · date/time functions · self-joins · conditional aggregation.

**Rule:** Redo problems you got wrong after one week. Pattern recognition matters more than the raw count.

#### 12-week SQL sprint (optional)

Use this if you want to front-load SQL and hit 150+ early. If it clashes with CS50P or Ng, stretch it to 24 weeks at 6–7 questions/week instead.

**WeekFocusMain sourcesQuestionsCumulative**1SELECT, WHERE, ORDER BY, LIMITSQLBolt 1–6 · LeetCode SQL 5012122GROUP BY, HAVING, COUNT/SUM/AVGSQLBolt 7–9 · LeetCode SQL 5012243Joins: INNER, LEFT, RIGHT, self-joinsSQLBolt 10–12 · LeetCode · PGExercises13374Subqueries, CTEs, UNIONSQLBolt 13–15 · LeetCode SQL 5013505Window functions: ROW\_NUMBER, RANK, LAG/LEADSQLZoo · LeetCode13636Date/time, string, conditional logicLeetCode · DataLemur13767Advanced joins, multiple CTEs, complex aggregationStrataScratch · HackerRank13898Pivoting, conditional aggregation, self-joinsPGExercises · DataLemur131029Interview-style mixed problemsDataLemur · StrataScratch1311510Timed practice, weak topicsLeetCode · HackerRank1312811Company-tagged questionsDataLemur · StrataScratch1314112Review, redo wrong problems, mock SQL interviewAll sources13**154+**

**How to use it**

*   Default to 2–3 deliberate problems/week; this pace is already included in the shared math/statistics/SQL hours.
    
*   Use the 12-week sprint only by replacing other practice time, never by adding hours.
    
*   After each session, write one sentence on the pattern you used.
    
*   At the end of each week, redo one problem you got wrong earlier.
    
*   After 150+, switch to maintenance: 2–3 problems/week.
    

### Mathematics and statistics (~2 hours/week)

**PeriodFocusResource**Oct – Dec 2026Vectors, matrices, derivatives, basic probability[Khan Academy](https://www.khanacademy.org/math) · [3Blue1Brown](https://www.3blue1brown.com/topics/linear-algebra)Jan – Mar 2027Linear algebra and statistics for evaluation metrics[MIT 18.06](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/) (selected lectures)Apr – Jun 2027Chain rule and gradients for backpropagationTrace gradients by hand in a small networkJul – Sep 2027Conditional probability and Bayes[Harvard Stat 110](https://stat110.hsites.harvard.edu/youtube)Oct – Dec 2027Dot products, cosine similarity, nearest neighborsYour RAG projectJan – Apr 2028Only what blocks your project or interview explanationsAs needed

**Reference only:** [MIT 18.065](https://ocw.mit.edu/courses/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) · MIT 18.650 · MIT RES.6-012 — via [MIT OCW](https://ocw.mit.edu/).

**Optional depth:** [UCB CS70: Discrete Math and Probability](https://csdiy.wiki/数学进阶/CS70/) — ~60 h. Only start this if you've finished the primary resources for the current phase and have spare capacity. Don't run it in parallel with Khan Academy/3Blue1Brown.

Study only the lessons that address a current gap. Don't try to finish full university courses.

### Optional course catalog (CSDIY)

[CS自学指南 (CSDIY)](https://csdiy.wiki/) is a community guide to university courses, with prerequisites and estimated hours. Use it as a **reference catalog**, not a second roadmap. Pick **one** course for a named gap. Never run several at once.

**CoursePhaseEffortUse when**[CS229 (Stanford)](https://csdiy.wiki/机器学习/CS229/)2~100 hYou want algorithm-level ML depth[CMU 15-445 (Databases)](https://csdiy.wiki/数据库系统/15445/)2 or 6~100 hYou want database internals (needs C++)[CS231n (Stanford)](https://csdiy.wiki/深度学习/CS231/)3~80 hProject 3 is image-based[CS285 (Berkeley RL)](https://rail.eecs.berkeley.edu/deeprlcourse/)Optional~100 hYou develop a specific RL interest[CS224n (Stanford NLP)](https://web.stanford.edu/class/cs224n/)5~80–100 hTransformers and NLP depth (selected lectures)[CS336 (Stanford LLMs)](https://csdiy.wiki/深度生成模型/roadmap/)5~100 h+You want to write LLM training code yourself[MIT 6.S184 (Diffusion)](https://csdiy.wiki/深度生成模型/MIT6.S184/)5~60 hYou're interested in diffusion models[MIT 6.006 (Algorithms)](https://csdiy.wiki/数据结构与算法/6.006/)4~60 hYou want a deeper algorithms course[Full Stack Open](https://csdiy.wiki/Web开发/fullstackopen/)6~100 hYou want a React/Node.js interface for the agent

### Supplements (use only for a specific gap)

*   [MASTER ROADMAP 2026–2027](https://youtube.com/playlist?list=PLYMLIfEYAPgM) by Yogesh Kumar Singh — sequencing guide for project ideas. Don't watch in upload order.
    
*   [CampusX — 100 Days of ML](https://www.youtube.com/playlist?list=PLKnIA16_Rmvbr7zKYQuBfsVkjoLcJgxHH) — Hindi and English explanations
    
*   [StatQuest](https://www.youtube.com/@statquest) — short statistics and ML explanations
    
*   [freeCodeCamp](https://www.youtube.com/@freecodecamp) — API development and Python projects
    
*   [Stanford Algorithms (Roughgarden)](https://www.coursera.org/learn/algorithms-part1) — only if DSA is stable
    
*   [Fluent Python](https://www.oreilly.com/library/view/fluent-python-2nd/9781492056348/) — reference for idiomatic Python
    
*   [MLOps Zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp) — deployment practice
    

Rules
-----

1.  **One main course + one project at a time**, plus DSA.
    
2.  **Protect college and sleep.** Exam and SIH weeks drop to 3–8 hours. No backlog.
    
3.  **Keep DSA regular.** 3–4 hours a week, shorter sessions on busy days.
    
4.  **Cut scope, not quality.** Remove features before you remove tests, evaluation, or documentation.
    
5.  **Start open source early.** Read repositories from November 2026.
    
6.  **Start mock interviews in September 2027.** Don't wait until the last month.
    
7.  **Reset if unsustainable.** Three weeks behind → drop to 10 hours and rebuild.
    
8.  **Apply on evidence.** You don't need to finish all 18 months before applying.
    
9.  **Practice system design from Phase 4 onward.** One problem every two weeks. Replace DSA time, not project time.
    

_No plan can guarantee GSoC selection, an internship, or a top-10% ranking. This plan gives you real work and technical evidence to compete with._
