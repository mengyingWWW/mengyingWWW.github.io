---
layout: single
title: ""
permalink: /projects/archive_1/
author_profile: false
toc: true
toc_label: "Contents"
toc_sticky: true
---

<style>
/* ===== Project page local styles (only affects this page) ===== */
.project-wrap{
  max-width:980px;
  margin:2rem auto 0 auto;
}

.project-title{
  margin-top:2rem;
  font-size:2.6rem;
  font-weight:800;
  line-height:1.1;
}

.kv-grid{
  display:grid;
  grid-template-columns:repeat(4,minmax(0,1fr));
  gap:22px;
  margin-top:1.75rem;
  margin-bottom:1.25rem;
}

@media (max-width:1024px){
  .kv-grid{ grid-template-columns:repeat(2,minmax(0,1fr)); }
}

@media (max-width:640px){
  .kv-grid{ grid-template-columns:1fr; }
}

.kv-item .k{
  font-weight:800;
  color:#66d9ef;
  margin-bottom:0.6rem;
  text-transform:uppercase;
  font-size:0.85rem;
  letter-spacing:1px;
}

.kv-item .v{
  opacity:0.92;
  line-height:1.6;
}

.tag-row{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
  margin-top:0.75rem;
  margin-bottom:1.25rem;
}

.tag{
  display:inline-flex;
  align-items:center;
  padding:8px 14px;
  border-radius:999px;
  border:1px solid rgba(255,255,255,0.16);
  background:rgba(255,255,255,0.04);
  color:rgba(255,255,255,0.92);
  font-size:0.85rem;
  line-height:1;
  white-space:nowrap;
}

.lede{
  margin-top:1rem;
  font-size:1.05rem;
  line-height:1.75;
  opacity:0.9;
}

/* Section subtitle style (PDF-like grey explanation) */
.section-subtitle{
  margin-top:-0.4rem;
  margin-bottom:1.2rem;
  color:#9aa0a6;
  font-size:0.95rem;
  letter-spacing:0.5px;
  line-height:1.5;
}
.figure-caption{
  margin-top:0.6rem;
  margin-bottom:2rem;
  font-size:0.85rem;
  color:#9aa0a6;
  font-style:italic; 
  line-height:1.5;
}
</style>

<div class="project-wrap">

  <!-- Cover image -->
  <img
    src="{{ '/projects/archive_1/assets/Frame 65.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">The Echo</h1>

  <!-- 4-column info blocks -->
  <div class="kv-grid">
    <div class="kv-item">
      <div class="k">Team</div>
      <div class="v">Kooi Pei Teoh, Tuerke, Yang Jinhua, Hu Xiaohan, Wang Xuan, Jin Chen, Cheng Zeyi, Deng Xinya, Fan Yuwei, Hu Yinyan, Chen Yiran, Huang Yu, Shi Jianan, Chen Zhuoshi, Li Hanyang, Ke Jingjing, Lin Zihan, Mi Yu, Liu Xu, Liu Yixuan, Luo Kai, Liu Xia, Pu Yanren, Zhang Xingzhao, Zhang Xiyu, Li Houyi, Wang Hongyi, Wang Mengying, Wang Zhiqi, Xiong Haisong, Xu Ye, Xu Yining, Yu Laiyan, Lin Yaoyu, Shen Jinkun, Zhu Junqiao, Zhao Chunxi, Zhao Xiaoxiao, Zheng Hanyu, Zhou Junyu, Zhou Yuchen, Zhang Xiaojing, Zhu Shilong, Li Chengyuan, Hu Yuelin</div>
    </div>

    <div class="kv-item">
      <div class="k">Tool</div>
      <div class="v">Stable Diffusion</div>
      <div class="v">Runway</div>
      <div class="v">Midjourney</div>
      <div class="v">Unreal Engine</div>
      <div class="v">Rhinoceros</div>
      <div class="v">C4D</div>
      <div class="v">Mubert</div>
      <div class="v">Adobe Premiere</div>
      <div class="v">Davinci</div>
    </div>

    <div class="kv-item">
      <div class="k">Role</div>
      <div class="v">
        10% Film Script Composition;<br/>
        10% Stable Diffusion Video Generation;<br/>
        10% Video Editing.
      </div>
    </div>

    <div class="kv-item">
      <div class="k">Timeline</div>
      <div class="v">Jul 2023</div>
    </div>
  </div>

  <!-- Tags -->
  <div class="tag-row">
    <span class="tag">Gen AI</span>
    <span class="tag">Film Making</span>
  </div>

  <!-- Intro paragraph -->
  <p class="lede">
    This experimental short film uses artificial intelligence as a generative artistic tool to explore the symbiotic relationship and inherent tensions between human, technology, and nature. Through the spatial narrative lens, it reflects on the connection and coexistence of these forces on earth, symbolized by a man, Al, and a wolf. The film seeks to dissolve the opposition between humanity, technology and nature, breaking down the divisions that separate them. At the end of the movie, a new symbiotic entity emerges, envisioning a post-human future of harmony.
  </p>

  <hr style="margin: 2rem 0;">
</div>


<h2>Film Production Tech Flow</h2>

Beginning with scene modeling and live-action footage as source material, we employed tools such as Stable Diffusion and Runway to generate and refine key frames through text-to-video, video-to-video, and image-to-video pipelines. ControlNet and prompt-based conditioning enabled stylistic consistency and narrative control. The final outputs were enhanced through music, sound design, and editing in professional software, forming a hybrid pipeline that bridges generative AI, and cinematic storytelling.

![Figure placeholder]({{ '/projects/archive_1/assets/Frame 66.png' | relative_url }})

<h2>Multi-Source Inputs to Generative Video Synthesis</h2>

![Figure placeholder]({{ '/projects/archive_1/assets/Frame 67.png' | relative_url }})

Multi-Source Visual Transformation via Stable Diffusion Pipelines
