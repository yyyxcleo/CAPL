# Looking Back and Forth: Cross-Image Attention Calibration and Attentive Preference Learning for Multi-Image Hallucination Mitigation

## Authors
Xiaochen Yang · Hao Fang · Jiawei Kong · Yaoxin Mao · Bin Chen · Shu-Tao Xia

<div style='display:flex; gap: 0.25rem; '>
<a href='https://arxiv.org/abs/2603.07048'><img src='https://img.shields.io/badge/Paper-PDF-red'></a>
</div>

## Accepted By ECCV 2026!


 Although large vision-language models (LVLMs) have demonstrated remarkable capabilities, they are prone to hallucinations in multi-image tasks. We attribute this issue to limitations in existing attention mechanisms and insufficient cross-image modeling. 
 
 Inspired by this, we propose a structured hallucination mitigation framework involving **C**ross-Image **A**ttention calibration and **P**reference **L**earning **(CAPL)**. CAPL explicitly enhances inter-image interactions at the architectural level while reinforcing reliance on genuine cross-image evidence during training, thereby improving the model’s perception and modeling of cross-image associations. Specifically, we (i) introduce a selectable image token interaction attention mechanism to establish fine-grained cross-image entity alignment and information flow; (ii) design a cross-image modeling–based preference optimization strategy that contrasts reasoning outcomes under full inter-image interaction and those obtained when images are mutually invisible, encouraging the model to ground its predictions in authentic visual evidence and mitigating erroneous inferences driven by textual priors. Experimental results demonstrate that CAPL consistently improves performance across multiple model architectures, achieving stable gains on both multi-image hallucination and general benchmarks. Notably, performance on single-image visual tasks remains stable or slightly improves, indicating strong generalization capability.


## 💡 Highlights
- We analyze the structural causes of hallucination in multi-image reasoning, identifying imbalanced visual information flow and insufficient cross-image semantic association as key factors that limit multi-image reasoning performance.

- We propose a novel framework CAPL, which integrates selective cross-image attention with preference alignment training, enhancing semantic interaction among critical cross-image tokens and reinforcing the model to better perceive and utilize inter-image interactions.

- Extensive experiments demonstrate that our method generalizes well across multiple recent vision-language models, significantly reducing hallucination and improving reasoning performance on multi-image tasks.


## 💎 CAPL Framework

### Attention as an Indicator for Detecting Hallucinations

### Post-Selection for Data Cleaning



## 🎆 Training Data Examples

---

## 🛠️ Usage

### DPO Data Generation

### Support Models

### Evaluation

---

## ✒️ Citation
