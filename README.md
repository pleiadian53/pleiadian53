# Barnett Chiu

**Independent research scientist — end-to-end AI/ML systems for scientific discovery.** New York.

I build the whole stack — models, data pipelines, GPU infrastructure, and the application
layer — taking ambiguous scientific problems from first principles to working implementation,
as researcher, engineer, and product owner. Current work is in **computational biology**, along
two independent lines: generative and self-supervised methods (VAE families, diffusion, flow
matching, JEPA) plus agentic AI, modality-agnostic and aimed at computational biology broadly;
and **RNA therapeutics** — splicing and decay — which began at Envisagenics.

I go by **Barnett Chiu** and publish as **Po-Hsiang Chiu** — both resolve to
[ORCID 0000-0001-8816-9799](https://orcid.org/0000-0001-8816-9799).

🌐 **[pleiadian53.github.io](https://pleiadian53.github.io/)** &nbsp;·&nbsp;
[Google Scholar](https://scholar.google.com/citations?user=EE3r5rgAAAAJ) &nbsp;·&nbsp;
[LinkedIn](https://www.linkedin.com/in/barnettchiu53) &nbsp;·&nbsp;
[ORCID](https://orcid.org/0000-0001-8816-9799)

---

More than six projects are active at any time, and GitHub pins only six. Here is the whole map.

### RNA Therapeutics &nbsp;·&nbsp; active

Two halves of one question: **where does splicing go, and what survives?**

| | |
|---|---|
| **[agentic-spliceai](https://github.com/pleiadian53/agentic-spliceai)** | Model-agnostic adaptive splice-site prediction and novel isoform discovery. Extends *any* per-nucleotide scorer with meta-learning adaptors, multimodal context (conservation, chromatin, RNA-seq junctions, RBP binding), and an agentic reasoning layer over variant databases, tissue/tumor RNA-seq, and the literature. — [docs](https://pleiadian53.github.io/agentic-spliceai/) · [DOI](https://doi.org/10.5281/zenodo.21696681) |
| **[meta-spliceai](https://github.com/pleiadian53/meta-spliceai)** | The foundation-adaptor meta-learning predecessor. |
| **nmdiff** *(private)* | Self-supervised quantification of nonsense-mediated decay efficiency per transcript. No labeled dataset exists at scale, so the *labeling rule itself* becomes an interpretable parameter vector, selected by whether its labels are predictable from a disjoint view — expression labels, structure predicts. |

### Generative & Self-Supervised Modeling &nbsp;·&nbsp; active

Novel methods, developed modality-agnostically and aimed at computational biology broadly — gene
expression, perturbation response, in-silico experimentation — not only at the RNA work above.

| | |
|---|---|
| **[ssl-lab](https://github.com/pleiadian53/ssl-lab)** *(active)* | JEPA past representation learning: a generative JEPA (flow-matching prior over a frozen latent + decoder) and an action-operator line that turns a passive predictor into a controllable world model. — [docs](https://pleiadian53.github.io/ssl-lab/) |
| **[genai-lab](https://github.com/pleiadian53/genai-lab)** | Generative AI for computational biology — VAEs, diffusion, DiT, flow matching, foundation-model adaptation. Flagship: Perturb-seq perturbation response with uncertainty quantification. — [docs](https://pleiadian53.github.io/genai-lab/) |
| **[GRL](https://github.com/pleiadian53/GRL)** | Generalized reinforcement learning — actions as *operators* on state space, not discrete symbols. The formalism ssl-lab's world-model line builds on. — [docs](https://pleiadian53.github.io/GRL/) · [arXiv:2208.04822](https://arxiv.org/abs/2208.04822) |
| **[causal-bio-lab](https://github.com/pleiadian53/causal-bio-lab)** | Causal inference, discovery, and representation learning for drug discovery and target ID. |

### Agentic Systems

| | |
|---|---|
| **[agentic-ai-lab](https://github.com/pleiadian53/agentic-ai-lab)** | Where **Nexus** was built — a multi-agent research system — before being refactored into agentic-spliceai. |
| **openclaw-py** *(private)* | A typed Python SDK for an agent OS, and the use cases that earned it: scheduled research digests, per-topic agent routing, pre-flight migration checks, and semantic memory *measured* rather than trusted. |
| **[llm-lab](https://github.com/pleiadian53/llm-lab)** | Pre-training and post-training building blocks — SFT, DPO, RLHF, alignment — for computational biology. |

### Clinical & Health Data

| | |
|---|---|
| **[ehr-sequencing](https://github.com/pleiadian53/ehr-sequencing)** | Health records as a language: codes as tokens, patient histories as sequences. BEHRT, transformers, recurrent baselines for disease progression and temporal phenotyping. — [docs](https://pleiadian53.github.io/ehr-sequencing/) |
| **[loinc-predictor](https://github.com/pleiadian53/loinc-predictor)** | Three-stage retrieval-and-ranking for LOINC code prediction and reliability assessment. |
| **[cf-ensemble](https://github.com/pleiadian53/cf-ensemble)** | Ensemble learning through latent-factor collaborative filtering, for disease risk modeling and phenotyping. — [docs](https://pleiadian53.github.io/cf-ensemble/) |

### Other Projects &nbsp;·&nbsp; incubating

| | |
|---|---|
| **[pgm-lab](https://github.com/pleiadian53/pgm-lab)** | Probabilistic graphical models — a reusable library of PGM building blocks plus research into novel methods, aimed at computational biology *and* physics. |
| **protein-ml-lab** *(not public yet)* | The protein-ML stack: protein language models (ESM), structure prediction in the AlphaFold lineage, generative design (RFdiffusion, ProteinMPNN, Chroma), and the frontier questions in biology foundation models. |

Earlier work: [probability-lab](https://github.com/pleiadian53/probability-lab),
[biographlab](https://github.com/pleiadian53/biographlab), [combio-lab](https://github.com/pleiadian53/combio-lab),
[pytorch-lab](https://github.com/pleiadian53/pytorch-lab), and more on the profile.

---

<sub>If you use Agentic-SpliceAI, please cite it —
<a href="https://doi.org/10.5281/zenodo.21696681">10.5281/zenodo.21696681</a>.
Full publication list on <a href="https://scholar.google.com/citations?user=EE3r5rgAAAAJ">Google Scholar</a>.</sub>
