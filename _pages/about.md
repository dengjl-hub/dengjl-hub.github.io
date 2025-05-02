---
permalink: /
title: "Jingliang Deng"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
/* 论文卡片容器 */
.paper-container {
  counter-reset: paper-count;
}
.paper-card {
  counter-increment: paper-count;
  position: relative;
  padding: 1.5rem;
  background: #f8f9fa;
  border-radius: 8px;
}
.paper-card::before {
  content: "P" counter(paper-count);
  position: absolute;
  right: -1rem;
  top: -1rem;
  font-size: 1.2rem;
  color: #6c757d;
}

/* 响应式适配 */
@media (max-width: 768px) {
  .paper-card { flex-direction: column; }
  .paper-thumbnail { margin-bottom: 1rem; }
}
</style>
I am a master student with the School of Software Engineering at South China University of Technology. Previously, I focused on Computer Programming Contest and obtained ICPC regional Bronze medal.  Currently, My research interests include backend development, deep learning and compuer vision.

Honor and Award
======
研究生国家奖学金, 2024

国家奖学金, 2021

国家奖学金, 2019

企业奖学金（腾讯、温氏筠城）

Competition Award
======

华为杯研究生数学建模竞赛全国三等奖, 2023

全国大学生电子商务“创新、创意及创业”挑战赛二等奖，2023&2024

ACM-ICPC Regional Bronze medal, 2022

GuangDong Province Programming Contest Silver medal, 2022

HuBei Province Programming Contest Gold medal, 2021

# Journal Papers
<div style="display: flex; align-items: center;">
  <img src="/files/thumbnails/ufo.jpg" alt="论文缩略图" style="width: 100px; margin-right: 10px;">
  <div>
    <a href="/files/publications/ufo.pdf" style="color: #0066c0; text-decoration: underline;">Uncertainty-Calibrated Test-Time Model Adaptation without Forgetting</a>
    <p style="color: #555; margin: 0;">Mingkui Tan, Guohao Chen, Jiaxiang Wu, Yifan Zhang, Yaofo Chen, Peilin Zhao, and Shuaicheng Niu</p>
    <div style="margin-top: 5px;">
      <a href="/files/publications/ufo.pdf" style="color: #0066c0; text-decoration: underline;">Pdf</a>
      <a href="/files/publications/ufo.pdf" style="color: #0066c0; text-decoration: underline; margin-left: 5px;">ArXiv</a>
      <a href="/files/bibtex/ufo.txt" style="color: #0066c0; text-decoration: underline; margin-left: 5px;">BibTex</a>
    </div>
  </div>
</div>
## Journal Publications
::: paper-container
<div class="paper-card">
  <div class="paper-thumbnail">
    ![3D Reconstruction via Neural Radiance Fields](/files/thumbnails/ufo.jpg){: width="200" .left-image }
  </div>
  <div class="paper-info">
    **NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis**  
    *Jingliang Deng*, Ben Mildenhall, Pratul P. Srinivasan et al.  
    [$$PDF$$](/files/publications/ufo.pdf) | [$$Code$$](https://github.com/dengjl/nerf)
  </div>
</div>

<div class="paper-card">
  <div class="paper-thumbnail">
    ![Vision-Language Pre-training](/files/thumbnails/ufo.jpg){: .scale-75 }
  </div>
  <div class="paper-info">
    **Unified Vision-Language Pre-training with Cross-modal Contrastive Learning**  
    Jingliang Deng, Yang Liu, Wei Huang  
    [$$PDF$$](/files/publications/ufo.pdf) | [$$Project Page$$](/files/publications/ufo.pdf)
  </div>
</div>
:::
# Conference Papers
<div style="display: flex;">
  <div style="width: 100px;">
    <img src="/files/thumbnails/ufo.jpg" alt="thumbnail2">
  </div>
  <div style="margin-left: 10px;">
    <h3><a href="/files/publications/ufo.pdf">论文标题示例</a></h3>
    <p>作者署名示例</p>
    <a href="/files/publications/ufo.pdf">Pdf</a>
    <a href="/files/publications/ufo.pdf">ArXiv</a>
    <a href="/files/bibtex/ufo.txt">BibTex</a>
  </div>
</div>
