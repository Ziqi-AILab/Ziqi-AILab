<h1 align="center">Ziqi Wang</h1>

<p align="center">
  <strong>PhD Research in AI + Chemistry · Domain Foundation Models · LLM Post-Training</strong>
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
  I am a PhD researcher in AI + Chemistry, developing language-model-based scientific foundation models
  and studying how knowledge learned from small molecules can transfer to polymers.<br>
  My work spans pretraining, continued pretraining, and post-training; in parallel, I study broader
  LLM post-training, test-time training, memory, and Multi agents.
</p>

<p align="center">
  <code>Pretraining</code> →
  <code>Continued Pretraining</code> →
  <code>Post-Training</code> →
  <code>Runtime Adaptation</code> →
  <code>Agents &amp; Harnesses</code>
</p>

---

## Current Focus

<table>
<tr>
<td colspan="2" valign="top">

<h3>🧪 AI + Chemistry: Small-Molecule-to-Polymer Foundation Models</h3>

<p>My PhD project develops domain foundation models across the full lifecycle: corpus curation and tokenizer–structure audit, small-molecule pretraining, molecule-to-polymer continued pretraining, and polymer-domain post-training with distillation, PEFT, preference optimization, and structured memory. The motivation is to transfer reusable chemical knowledge from small-molecule corpora to polymer domains with different sequence and structural distributions.</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>🧠 LLM Post-Training &amp; Test-Time Adaptation</h3>

<p>Working across offline and runtime adaptation: knowledge distillation, supervised adaptation, LoRA/DoRA/soft prompts, DPO, synthetic supervision, and query-local TTT with removable parameter states, self-supervised objectives, selective updates, accept/rollback, and verifier-guided test-time scaling.</p>

</td>
<td width="50%" valign="top">

<h3>🖥️ Memory, RAG &amp; Multi Agents</h3>

<p>Studying external, session, and parametric memory; retrieval and runtime routing; and Multi agents that combine screenshot/UI-hierarchy perception, protocol-state planning, structured tool use, invariant checks, and failure recovery within a stateful harness.</p>

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
  Configuration-driven experiments · Matched baselines · Low-label/OOD evaluation ·
  Multi-seed ablations · Checkpoint/resume · Latency and GPU-cost accounting
</p>
