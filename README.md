# Kyusun Cho

**AI Engineer @ PlantyNet** — on-device deepfake detection, agentic LLM systems, and the MLOps that keeps them running in production.
M.S. in Computer Science (AI), Korea University · Advised by Prof. Seungryong Kim.

I work across two halves of the same problem: the research that makes a model good, and the systems
that make it useful. Lately that means training and shipping on-device vision AI models, orchestrating
multi-agent RAG agents over a 1,400-magazine archive, and building MLOps pipelines underneath both.

As an engineer I keep returning to the same three questions: why a system behaves the way it does,
how an idea becomes something useful, and what to improve next. I write through those on my
[blog](https://kyusuncho.github.io).

---

## Education

**M.S. in Computer Science (Artificial Intelligence)** · Korea University `2022.03 – 2025.02`
Advisor: [Seungryong Kim](https://cvlab.korea.ac.kr)

**B.S. in Statistics** · Korea University `2018.03 – 2022.02`

---

## Experience

**AI Engineer** · [PlantyNet](https://kyusuncho.github.io/blog/work/plantynet/) — Seongnam, South Korea
`2025.02 – present`

- **On-device deepfake detection** shipped to Android via TFLite — trained on a large-scale corpus
  of real and synthetic faces, with a Korean-face subset added to close a domain gap.
- **Research platform rebuild** on Ray, DVC, Lightning, Hydra, and W&B, replacing a script-driven
  workflow and cutting both experiment turnaround and GPU usage.
- **Multi-agent magazine RAG chatbot** — a LangGraph routing orchestrator delegating to article-QA
  and recommendation agents over hybrid Milvus retrieval (bge-m3 dense + Korean BM25), with layered
  RAGAS evaluation separating routing, retrieval, context, and generation quality.
- **Agentic content pipeline** for OCR correction, summarization, translation, and web-view
  generation. An ExpeL-style experience memory raised processing success rates, and knowledge
  distillation into a lightweight classifier cut LLM inference cost.
- **Knowledge-graph recommender** (in progress) — LLM facet tagging into a Neo4j content graph,
  with Personalized PageRank candidate generation and contextual-bandit exploration.

**Visiting Researcher** · [Queen Mary University of London](https://kyusuncho.github.io/blog/work/qmul/) — London, United Kingdom
`2024.08 – 2024.11`

Object-centric 3D reconstruction from monocular video — recovering per-object geometry and semantics
with 3D Gaussian Splatting, then evaluating robot navigation and manipulation in the reconstructed scene.

**Graduate Researcher** · Korea University Computer Vision Lab — Seoul, South Korea
`2022.03 – 2025.02`

- Real-time audio-driven 3D talking heads
- 3D pose-conditioned diffusion for person re-identification
- pose-estimation/sensor-fusion indicators for dementia screening. 
- TA for Samsung Electronics - internal courses on diffusion models and 3D reconstruction.

---

## Tech Stack

**ML & Research**

[![My Skills](https://skillicons.dev/icons?i=py,pytorch,tensorflow,sklearn,opencv&theme=dark)](https://skillicons.dev)

`Lightning` · `Hydra` · `Weights & Biases` · `ONNX` · `TFLite / LiteRT`

**LLM & Agents**

`LangGraph` · `LangChain` · `vLLM` · `RAGAS` · `Langfuse` · `Arize Phoenix`

**Backend & Data**

[![My Skills](https://skillicons.dev/icons?i=fastapi,django,spring,postgres,supabase,redis,rabbitmq&theme=dark)](https://skillicons.dev)

`DuckDB` · `Milvus` · `Neo4j`

**MLOps**

[![My Skills](https://skillicons.dev/icons?i=docker&theme=dark)](https://skillicons.dev)

`Docker Compose` · `Airflow` · `MLflow` · `Dagster` · `Ray Data` · `DVC` · `Triton`

**Infra & Observability**

[![My Skills](https://skillicons.dev/icons?i=aws,linux,grafana,prometheus,git,github&theme=dark)](https://skillicons.dev)

**Mobile**

[![My Skills](https://skillicons.dev/icons?i=kotlin,androidstudio&theme=dark)](https://skillicons.dev)

---

## Publications

### GaussianTalker: Real-Time High-Fidelity Talking Head Synthesis with Audio-Driven 3D Gaussian Splatting *(ACM Multimedia 2024)*
_**Kyusun Cho**, Joungbin Lee, Heeji Yoon, Yeobin Hong, Jaehoon Ko, Sangjun Ahn, Seungryong Kim_

[![Project](https://img.shields.io/badge/Project-Page-0a7bbb)](https://cvlab-kaist.github.io/GaussianTalker/)
[![arXiv](https://img.shields.io/badge/arXiv-2404.16012-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2404.16012)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white)](https://github.com/cvlab-kaist/GaussianTalker)

### Talk3D: High-Fidelity Talking Portrait Synthesis via Personalized 3D Generative Prior *(ICCV 2025 Workshop)*
_Jaehoon Ko, **Kyusun Cho**, Joungbin Lee, Heeji Yoon, Sangmin Lee, Sangjun Ahn, Seungryong Kim_

[![Project](https://img.shields.io/badge/Project-Page-0a7bbb)](https://cvlab-kaist.github.io/Talk3D/)
[![arXiv](https://img.shields.io/badge/arXiv-2403.20153-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2403.20153)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white)](https://github.com/cvlab-kaist/Talk3D)

### 3D GAN Inversion with Pose Optimization *(WACV 2023)*
_Jaehoon Ko, **Kyusun Cho**, Daewon Choi, Kwangrok Ryoo, Seungryong Kim_  

[![Project](https://img.shields.io/badge/Project-Page-0a7bbb)](https://3dgan-inversion.github.io/)
[![arXiv](https://img.shields.io/badge/arXiv-2210.07301-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2210.07301)
[![Code](https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white)](https://github.com/cvlab-kaist/3DGAN-Inversion)

### AE-NeRF: Auto-Encoding Neural Radiance Fields for 3D-Aware Object Manipulation *(arxiv 2022)*
_Mira Kim, Jaehoon Ko, **Kyusun Cho**, Junmyeong Choi, Daewon Choi, Seungryong Kim_

[![arXiv](https://img.shields.io/badge/arXiv-2204.13426-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2204.13426)
