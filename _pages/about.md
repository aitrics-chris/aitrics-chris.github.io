---
layout: about
title: About
permalink: /
subtitle: <b>Contact:</b> joohyunglee [dot] research [at] gmail [dot] com

profile:
  align: right
  image: prof_pic.jpg
  image_random: true
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>Machine Learning Researcher</p>
    at <a href="https://aitrics.com/en">AITRICS</a>
    

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a machine learning researcher at [AITRICS](https://aitrics.com/en), a healthcare AI startup in South Korea, advised by [Prof. Eunho Yang](https://mli.kaist.ac.kr/people/) and collaborating closely with [Prof. Juho Lee](https://juho-lee.github.io/).

My research focuses on inductive bias and symmetry-aware learning: how to design learning systems that generalize reliably by encoding principled regularities (e.g., geometry, acquisition processes, and temporal structure). I have worked on geometric priors [[1](https://openreview.net/forum?id=TuQW7VPfXF)], acquisition-informed priors[[2](https://arxiv.org/pdf/2402.10595),[3](https://arxiv.org/abs/2209.05771)], and temporal inductive biases[[4](https://arxiv.org/pdf/2305.02504), [5](https://arxiv.org/pdf/2210.16598)].

Previously, I worked as a researcher at the [Korea Electronics Technology Institute (KETI)](https://www.keti.re.kr/eng/main/main.php) and in the RCV Lab at [KAIST](https://www.kaist.ac.kr/en/) with [Prof. In So Kweon](http://rcv.kaist.ac.kr/). I also collaborated with clinicians and researchers at the [National Cancer Center](https://www.ncc.re.kr/indexEn.ncc).

I am currently investigating invariance–equivariance interference, empirical (infinitesimal) equivariance, and plausibility priors, with the goal of building trustworthy learning systems that robustly satisfy principled regularity constraints—especially in settings where distribution shift and underspecification are common.


<!-- 
layout: page
title: About
permalink: /
nav: true
nav_order: 1
---

<div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; gap: 0.5rem;">
  <h1 style="margin: 0;">Joohyung Lee</h1>
  <h2 style="margin: 0;">Research Statement</h2>
</div>

ML Researcher, AITRICS (Seoul) \| PhD applicant (Fall 2026) \| M.S. EE, Texas A&amp;M University

Email: [joohyunglee.research@gmail.com](mailto:joohyunglee.research@gmail.com) \| Scholar: [Google Scholar](https://scholar.google.com/) \| GitHub: [github.com/aitrics-chris](https://github.com/aitrics-chris)

## Research Focus

Despite rapid progress in foundation models and learned world models, even state-of-the-art systems can violate basic physical and logical regularities, e.g., producing anatomically implausible medical images, undermining trustworthiness in high-stakes domains like healthcare and in high-impact generative AI applications. My research asks what regularities learning systems should respect and how to enforce them at scale without sacrificing downstream utility. Across projects, I formalize domain regularities (symmetries, acquisition mechanisms, temporal dynamics) and translate them into scalable learning mechanisms, from SSL objectives and soft regularizers to architecture-level inductive biases.

## Selected contributions

- **Soft Equivariance Regularization (SER) for invariant SSL (ICLR 2026, accepted; first author).** SER decouples invariance and equivariance across layers: train the final embedding with an invariant SSL objective, while softly regularizing _intermediate, spatially structured_ representations toward equivariance via analytically specified group actions (no labels; no auxiliary networks). On ImageNet-1k MoCo-v3 (ViT-S), SER improves linear-eval Top-1 by +0.84, ImageNet-C/P by +1.11/+1.22, and frozen-backbone COCO detection by +1.7 mAP, with 1.008× training overhead. OpenReview.
- **Acquisition-physics priors in clinical imaging (first author).** In pathology, I used disease-negative slides as anchors to suppress acquisition-induced nuisance variation in multiple-instance learning (ICASSP 2024). In MRI, I introduced a late-fusion 3D design that respects anisotropic acquisition geometry (MICCAI 2022).
- **Temporal regularities for multimodal EHR forecasting (co-first/corresponding author).** I proposed a predictive-coding SSL framework for multimodal clinical trajectories under irregular sampling and missingness (ICLR 2023 TML4H workshop; Best Paper Honorable Mention) and introduced a shared time-embedding with modality-aware attention for cross-modal alignment (MLHC 2023 Spotlight).

## PhD research directions

My doctoral goal is to scale _structure-respecting learning_ beyond hand-specified groups and geometry, toward learned symmetries and semantic/physical plausibility constraints.

- **Discovering approximate symmetries from spatiotemporal signals.** Learn approximately equivariant transformation families from video and temporal coherence (e.g., motion-induced deformations), and enforce them with SER-style intermediate-layer constraints, leveraging small inter-frame transitions as a local equivariance signal without requiring analytic group actions.
- **Diagnosing and mitigating invariance-equivariance interference via subspace decoupling.** I will study when and why invariant SSL and equivariant objectives compete, tracking effective-rank dynamics, layerwise gradient alignment, and latent-orbit organization under group actions, and develop subspace-structured objectives (e.g., null-space-projected equivariance) that preserve invariant embeddings while encoding transformation-sensitive variation.
- **Semantic/physical constraints for trustworthy generative models.** Extract candidate constraints (anatomy, part consistency, numeracy, logical relations) from pretrained LLMs/VLMs, ground them with lightweight scoring modules, and enforce them with scalable alignment objectives. -->