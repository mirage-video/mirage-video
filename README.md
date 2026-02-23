<p align="center">
  <img src="https://raw.githubusercontent.com/mirage-video/Mirage/main/assets/banner.jpg" width="100%">
</p>

<h1 align="center">Mirage Team</h1>

<p align="center">
  <em>Building the future of open-source video generation</em>
</p>

<p align="center">
  <a href="https://gomirage.ai">Website</a> •
  <a href="https://x.com/gomirageai">Twitter</a> •
  <a href="https://github.com/mirage-video/Mirage">Mirage Repository</a>
</p>

---

## Our Mission

We believe in a future where AI-driven creativity is not confined to corporate silos. A future where high-fidelity, lifelike videos can be generated in seconds and made available to artists, educators, researchers, and individuals alike.

The field of AI video generation faces a profound divide. On one side stand closed-source models from industry leaders—remarkable in quality, yet inaccessible to the broader community. On the other, open-source alternatives that lag in temporal consistency, physical realism, and human rendering.

**We built Mirage to close this gap.**

---

## What We've Built

<table>
<tr>
<td align="center"><b>91.2</b><br>VBench Score</td>
<td align="center"><b>14B</b><br>Parameters</td>
<td align="center"><b>4</b><br>Inference Steps</td>
<td align="center"><b>~8s</b><br>Generation Time</td>
</tr>
</table>

**Mirage** is a 14-billion parameter open-source video generation model that achieves state-of-the-art quality through consistency distillation with score regularization (rCM).

We demonstrate that distillation can *exceed* teacher model quality—improving VBench from 84.0 (Wan2.2) to 91.2, surpassing closed-source systems including Veo3 (~90) and Sora2 (~88).

### Key Innovations

- **Mode-seeking distillation** concentrates probability mass on high-quality outputs
- **Hard example mining** addresses systematic failures in physics, hands, and faces
- **Consistency enforcement** eliminates "lucky path" dependence on specific noise samples
- **7× speedup** over 50-step teacher models without quality degradation

---

## The Team

We are researchers and engineers united by a common belief: **genuine innovation flourishes through collaboration and sharing**.

Our team operates under codenames. No faces, no names, no LinkedIn profiles. The work speaks for itself.

| Role | Focus |
|------|-------|
| **The Distiller** | Architecture & rCM implementation |
| **Miner** | Synthetic data & hard-example mining |
| **Enforcer** | Consistency training & stability |
| **Oracle** | Motion & physics realism |
| **Judge** | Benchmarking & human evaluation |

### Why Anonymous?

Our project should be judged purely on weights and results, not personalities. We believe this approach:

- Keeps focus on the science, not the scientists
- Enables contribution from diverse backgrounds without bias
- Protects our contributors in a complex regulatory landscape
- Follows the tradition of anonymous research collectives that have pushed boundaries before

---

## Our Philosophy

> *"The gap between open and closed video generation is not a gap in architecture or scale—it is a gap in methodology."*

We release everything openly: weights, code, pipelines, and scripts. This isn't compromise; it's a deliberate strategy to foster self-improving AI ecosystems where synthetic data becomes a tool for elevation, not degradation.

The mirage of inaccessible excellence is over. **The reality begins now.**

---

<p align="center">
  <a href="https://github.com/mirage-video/Mirage">
    <img src="https://img.shields.io/github/stars/mirage-video/Mirage?style=social" alt="GitHub stars">
  </a>
</p>

<p align="center">
  <sub>Open source. Open weights. Open future.</sub>
</p>
