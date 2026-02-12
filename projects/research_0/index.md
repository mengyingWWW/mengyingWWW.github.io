---
layout: single
title: ""
permalink: /projects/research_0/
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
  color:#66d9ef; /* blue label */
  margin-bottom:0.6rem;
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
  padding:8px 12px;
  border-radius:999px; /* pill */
  border:1px solid rgba(255,255,255,0.16);
  background:rgba(255,255,255,0.04);
  color:rgba(255,255,255,0.92);
  font-size:0.9rem;
  line-height:1;
  white-space:nowrap;
}
.lede{
  margin-top:1rem;
  font-size:1.05rem;
  line-height:1.75;
  opacity:0.9;
}
</style>

<div class="project-wrap">

  <!-- Cover image (same width as other figures) -->
  <img
    src="{{ '/projects/research_0/assets/Frame 1.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">Made in Flushing</h1>

  <!-- 4-column info blocks -->
  <div class="kv-grid">
    <div class="kv-item">
      <div class="k">Group Work</div>
      <div class="v">Hu Rong, Mo Di</div>
    </div>

    <div class="kv-item">
      <div class="k">Tool</div>
      <div class="v">Python</div>
    </div>

    <div class="kv-item">
      <div class="k">Role</div>
      <div class="v">
        33.3% conceptual design;<br/>
        100% street view data crawling;<br/>
        100% visual & gustatory element analysis (ML);<br/>
        100% data visualization
      </div>
    </div>

    <div class="kv-item">
      <div class="k">Timeline</div>
      <div class="v">2024/08–2024/10</div>
    </div>
  </div>

  <!-- Tags -->
  <div class="tag-row">
    <span class="tag">Machine Learning</span>
    <span class="tag">Data Visualization</span>
  </div>

  <!-- Intro paragraph -->
  <p class="lede">
    Flushing is one of the world’s largest Chinatowns, with a rich and woven cultural history.
    This project studies Chinese elements in Flushing through a multisensory lens—using street view texts,
    audios from walking tour videos, and food as cultural symbols. It also explores how diverse cultures merge,
    highlighting what makes Flushing a diverse community. We use machine learning to assess the proportions of Chinese
    and other cultures across visual, aural, and gustatory dimensions, then we use data visualization to show the
    coexistence of Chinese and other cultures across these three sensory dimensions.
  </p>

  <hr style="margin: 2rem 0;">
</div>

## Background
![Figure placeholder]({{ '/projects/research_0/assets/Frame 2.png' | relative_url }})

Flushing, located in Queens, New York, is a diverse neighborhood with a rich history that has shaped its cultural character. While Flushing’s rich history has cultivated deep multicultural fusion, it is predominantly recognized today as one of the world’s largest Chinatown. This dominant perception often
overshadows the diverse cultural integration shaped by not only Chinese, Korean, and Indian communities, but also earlier influences from European colonizers and other immigrant groups. Our research aims to fill this gap by applying machine learning to study the multisensory composition of Chinese
elements and their integration with other cultural features, offering new insights into Flushing’s complex identity.

## Purpose
![Figure placeholder]({{ '/projects/research_0/assets/Frame 3.png' | relative_url }})

*Figure 1. Placeholder caption.*
