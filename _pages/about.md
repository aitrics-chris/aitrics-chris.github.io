---
layout: about
title: About
permalink: /
subtitle: <b>Contact:</b> joohyunglee [dot] research [at] gmail [dot] com

# profile:
#   align: right
#   image: prof_pic.jpg
#   # image_random: true
#   image_circular: true # crops the image to make it circular
#   more_info: >
#     <p>Machine Learning Researcher at</p>
#     <p><a href="https://aitrics.com/en">AITRICS</a></p>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true
  more_info: >
    <p class="profile-role">Machine Learning Researcher</p>
    <p class="profile-affil">at <a href="https://aitrics.com/en">AITRICS</a></p>

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

I study self-supervised representation learning for vision and time series. At [AITRICS](https://aitrics.com/en) in Seoul, I work with [Prof. Eunho Yang](https://mli.kaist.ac.kr/people/) on forecasting from irregular clinical records. For my PhD, I want to understand what a model can predict about an object's next physical outcome using only observations made before contact or loss of support.

A cup's motion relative to the fingers holding it can reveal slip even when its surface looks unchanged. My current video project, **ALTO**, asks when changes in features along a patch's track add predictive information beyond motion. I compare carrying the latest features forward along a predicted track with extrapolating their recent change. I use the same frozen depth predictor for both forecasts and compare its estimates with the observed depth in the next frame.

I want to extend this work to forecasts that depend on an earlier interaction. Suppose two balls approach the same surface at the same height and downward speed. Does showing a model each ball's earlier bounce help it predict the height of the next rebound? I would end both videos before impact and compare the forecasts with the measured heights. Longer term, I want robots with little opportunity to practice at a new site to anticipate the outcome of an action and verify it afterward.

With [Prof. Juho Lee](https://juho-lee.github.io/), I developed [Soft Equivariance Regularization](https://openreview.net/forum?id=TuQW7VPfXF) to preserve geometry in intermediate vision features while training the final embedding for recognition. I am following up on how the two objectives affect feature diversity. In my clinical work, I test what a predictor can infer from which measurements were taken and when, even with the numerical readings removed. Related work includes [patient deterioration forecasting](https://arxiv.org/pdf/2210.16598), [learning from incomplete records](https://arxiv.org/pdf/2305.02504), and [whole-slide pathology](https://arxiv.org/pdf/2402.10595).

Previously, I worked at the [Korea Electronics Technology Institute (KETI)](https://www.keti.re.kr/eng/main/main.php) and in the Robotics and Computer Vision Lab at [KAIST](https://www.kaist.ac.kr/en/) with [Prof. In So Kweon](http://rcv.kaist.ac.kr/). I also collaborated with researchers and clinicians at the [National Cancer Center](https://www.ncc.re.kr/indexEn.ncc) on [rectal cancer staging from MRI](https://arxiv.org/abs/2209.05771).
