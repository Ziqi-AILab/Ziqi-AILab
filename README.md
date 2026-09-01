<h1 align="center">Ziqi Wang</h1>

<p align="center">
  <strong>PhD Student in AI + Chemistry · Domain Foundation Models · LLM Post-Training</strong>
</p>

<p align="center">
  <a href="mailto:Ziqi.Wang@liverpool.ac.uk">
    <img src="https://img.shields.io/badge/Liverpool-Ziqi.Wang%40liverpool.ac.uk-1f6feb?style=flat-square" alt="University of Liverpool Email">
  </a>
  <a href="mailto:Ziqi.Wang21@student.xjtlu.edu.cn">
    <img src="https://img.shields.io/badge/XJTLU-Ziqi.Wang21%40student.xjtlu.edu.cn-7a3e9d?style=flat-square" alt="XJTLU Email">
  </a>
  <a href="https://github.com/Ziqi-AILab?tab=repositories">
    <img src="https://img.shields.io/badge/Research-Code-181717?style=flat-square&logo=github&logoColor=white" alt="Research Code">
  </a>
</p>

<p align="center">
  I am a PhD student working at the intersection of AI and chemistry.<br>
  My doctoral research uses the shift from small molecules to polymers to study how scientific foundation models
  acquire and transfer chemical knowledge through pretraining, continued pretraining, and post-training.<br>
  Beyond this domain setting, I work on general LLM post-training, test-time training, memory and retrieval,
  and multi-agent systems.
</p>

<p align="center">
  <code>Pretraining</code> ·
  <code>Continued Pretraining</code> ·
  <code>Post-Training</code> ·
  <code>Test-Time Training</code> ·
  <code>Memory &amp; RAG</code> ·
  <code>Multi-Agent Systems</code>
</p>

---

## Current Focus

<table>
<tr>
<td colspan="2" valign="top">

<h3>🧪 PhD Project: Small-Molecule-to-Polymer Foundation Models</h3>

<p>Using small-molecule-to-polymer transfer as the scientific setting, I work across domain corpus curation, tokenizer–structure alignment, small-molecule pretraining, molecule-to-polymer continued pretraining, and polymer-domain post-training. The goal is to identify what chemical knowledge transfers, where it stops transferring, and how polymer-specific knowledge should be added through distillation, PEFT, preference optimization, and structured memory.</p>

</td>
</tr>
<tr>
<td colspan="2" valign="top">

<h3>🧠 LLM Post-Training &amp; Test-Time Training</h3>

<p>Working on post-training for both general-purpose and scientific LLMs, including distillation, SFT, LoRA/DoRA/soft prompts, DPO, and synthetic supervision. My TTT work treats query-local updates as removable parametric memory, using self-supervised objectives, state isolation, selective updates, accept/rollback, and verifier-guided test-time scaling.</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>💾 Memory &amp; Retrieval</h3>

<p>Studying where knowledge should live and how long it should persist across external, session, episodic, and parametric memory, together with RAG, knowledge-gap retrieval, and runtime routing over <em>read / retrieve / reason / write / act</em>.</p>

</td>
<td width="50%" valign="top">

<h3>🤖 Multi-Agent Systems &amp; Harnesses</h3>

<p>Studying multi-agent systems and agent harnesses for planner–executor coordination, tool use, stateful workflows, verification, and failure recovery. GUI agents are one application, combining screenshot/UI-hierarchy perception with protocol-state planning and structured execution.</p>

</td>
</tr>
</table>

## Selected Research Code

| Project | Focus |
|---|---|
| **[AuraESG](https://github.com/Ziqi-AILab/AuraESG)** · [Paper](https://www.sciencedirect.com/science/article/pii/S0020025526005785) | Multi-stage LLM post-training with knowledge infusion, contrastive learning, DoRA, DPO, and uncertainty-aware routing. |
| **[SymForce](https://github.com/Ziqi-AILab/SymForce)** | LLM-guided iterative physical reasoning for molecular conformation generation. |
| **[Descriptor-Guided Molecular Pretraining](https://github.com/Ziqi-AILab/paper101)** | Molecular representation learning with descriptor-guided conditional computation and reproducible evaluation. |

## Research Engineering

<p align="center">
  <code>PyTorch</code> ·
  <code>Transformers</code> ·
  <code>Accelerate</code> ·
  <code>PEFT</code> ·
  <code>PyTorch Geometric</code> ·
  <code>CUDA</code> ·
  <code>Slurm</code>
</p>

<p align="center">
  Reproducible experiments · Matched baselines · Low-label/OOD evaluation ·
  Multi-seed ablations · Checkpoint/resume · Latency and GPU-cost accounting
</p>
