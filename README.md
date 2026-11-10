# Yihan Wu

**AI/ML systems · Software engineering · Applied machine learning**

I'm an M.S. Electrical Engineering student at Columbia University, specializing in AI Engineering. I build LLM applications, inference systems, and data tools, with a background in data science and neurobiology from UW–Madison.

**Seeking Summer 2027 internships in AI/ML systems and software engineering.**  
[LinkedIn](https://www.linkedin.com/in/yihan-wu-205864263) · [Email](mailto:yw4756@columbia.edu)

## Open-source contribution

Contributed to **[terminal-mac](https://github.com/govijr/terminal-mac)**, a macOS terminal tool with **2.5k+ GitHub stars**. [Merged contribution →](https://github.com/govijr/terminal-mac/pull/21)

<br>

## Selected public work

### [FunnyLLM](https://github.com/yihan2588/FunnyLLM) — AI meme co-writer

Built a full-stack application that turns images or ideas into editable memes. Combined Gemini interpretation and generation with semantic retrieval, then added private drafts, explicit publication, a public gallery, and an operations console. Structured-output validation, idempotent requests, and revision checks support reliable editing.

**TypeScript · Next.js · React · Gemini · Supabase · pgvector · Zod**  
[Live gallery](https://funnyllm.vercel.app/) · [Architecture](https://github.com/yihan2588/FunnyLLM/blob/main/apps/web/docs/co-writer.md)

### [The Shape of Song Ci / 词之形](https://github.com/yihan2588/the-shape-of-song-ci) — Poetry through embeddings

Built a bilingual explorer for **240 Song Ci poems**, with t-SNE/UMAP maps, poet and text search, and three nearest neighbors computed in the original embedding space. Connected literary interpretation to reproducible data preparation, documented methods, and dataset integrity checks.

**Python · JavaScript · Plotly · Supabase · Vercel**  
[Live explorer](https://song-ci-atlas.vercel.app) · [Dataset and method](https://github.com/yihan2588/the-shape-of-song-ci/blob/main/docs/DATASET.md)

### EEG research tooling — Source reconstruction and slow-wave analysis

As a Research Developer at UW–Madison School of Medicine and Public Health, automated MATLAB source reconstruction for **approximately 30,000 EEG epochs**, reducing a months-long workflow to **under two days**. Public tools cover sLORETA reconstruction, group comparisons, and Python analysis of slow-wave origins and regional involvement.

**MATLAB · Python · Brainstorm · FieldTrip**  
[Source reconstruction](https://github.com/yihan2588/Scource_Recon) · [Slow-wave analysis](https://github.com/yihan2588/Source_Ana)

## Additional engineering work

Selected work from my résumé; source repositories are currently private.

- **AgentKV — LLM serving.** Built cost-aware KV-cache restoration and tenant isolation with Python and vLLM on NVIDIA L4. Reduced p95 time to first token by **20% versus tuned native vLLM at identical memory budgets**, and neighbor-induced p95 latency overhead by **30% under bursty workloads**, with **less than 5% throughput regression across 3 sharing scopes and 2 workload families**.
- **Education Through Music — Curriculum search.** Led development through Columbia Software Solutions of a Next.js and PostgreSQL platform that helps music teachers find resources buried in Google Drive. Reduced resource navigation from **5 minutes to under 5 seconds**.
- **ScoreSight — Accessible music technology.** Developed Python/FastAPI audio-to-score alignment and REST/WebSocket integration for low-vision musicians. Reduced cursor drift after 300 ms from **102 to 20 of 110 controlled pause replays**; contributed to a demo paper accepted to **ACM UIST 2026**.
- **JevMarket — Data infrastructure.** Built an Alpaca → Kafka → Spark pipeline and budget-controlled AI news classification for personalized market intelligence. Deployed on Google Cloud with **≥81% line and branch coverage for both backend and frontend**.
- **HCED — Heterogeneous LLM decoding.** Implemented a C++/CUDA prototype with GPU projections and CPU-resident KV-cache attention. Compared three execution strategies, checked numerical correctness, and profiled memory/latency tradeoffs with Nsight.

## Tools I work with

**Languages:** Python, TypeScript/JavaScript, SQL, MATLAB, C++/CUDA  
**Systems and ML:** PyTorch, vLLM, FastAPI, Kafka, Spark, Docker, Google Cloud  
**Applications:** React, Next.js, PostgreSQL, Supabase, Vercel
