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
    src="{{ '/projects/research_0/assets/Frame 1.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">Made in Flushing test4</h1>

  <!-- 4-column info blocks -->
  <div class="kv-grid">
    <div class="kv-item">
      <div class="k">Team</div>
      <div class="v">Hu Rong, Mo Di</div>
    </div>

    <div class="kv-item">
      <div class="k">Tool</div>
      <div class="v">Python</div>
    </div>

    <div class="kv-item">
      <div class="k">Role</div>
      <div class="v">
        33.3% Conceptual Design;<br/>
        100% Street View Data Crawling;<br/>
        100% Visual & Gustatory ML Analysis;<br/>
        100% Data Visualization.
      </div>
    </div>

    <div class="kv-item">
      <div class="k">Timeline</div>
      <div class="v">Aug 2024 – Oct 2024</div>
    </div>
  </div>

  <!-- Tags -->
  <div class="tag-row">
    <span class="tag">Machine Learning</span>
    <span class="tag">Data Visualization</span>
    <span class="tag">Multisensory Analysis</span>
  </div>

  <!-- Intro paragraph -->
  <p class="lede">
    Flushing is one of the world’s largest Chinatowns, with a rich and woven cultural history. This project studies Chinese elements in Flushing through a multisensory lens—using street view texts, audios from walking tour videos, and food as cultural symbols. It also explores how diverse cultures merge, highlighting what makes Flushing a diverse community. We use machine learning to assess the proportions of Chinese and other cultures across visual, aural, and gustatory dimensions, then we use data visualization to show the coexistence of Chinese and other cultures across these three sensory dimensions.
  </p>

  <hr style="margin: 2rem 0;">
</div>

<h2>Background</h2>
<p class="section-subtitle">
  Flushing as a thriving Chinatown & multicultural urban hub
</p>

![Figure placeholder]({{ '/projects/research_0/assets/Frame 2.png' | relative_url }})

<p class="figure-caption">
  Figure 1. Historical Timeline of Flushing.
</p>

Flushing, located in Queens, New York, is a diverse neighborhood with a rich history that has shaped its cultural character. While Flushing’s rich history has cultivated deep multicultural fusion, it is predominantly recognized today as one of the world’s largest Chinatown. This dominant perception often overshadows the diverse cultural integration shaped by not only Chinese, Korean, and Indian communities, but also earlier influences from European colonizers and other immigrant groups. Our research aims to fill this gap by applying machine learning to study the multisensory composition of Chinese elements and their integration with other cultural features, offering new insights into Flushing’s complex identity.

<h2>Purpose</h2>
<p class="section-subtitle">
  Studying multisensory Chinese elements via machine learning
</p>

![Figure placeholder]({{ '/projects/research_0/assets/Frame 10.png' | relative_url }})

<p class="figure-caption">
Figure 2. Cultural Elements Identified in Street Views.
</p>


This project investigates how cultural identity can be quantified through visual, auditory, and gustatory signals in urban environments. By integrating image segmentation, OCR, sound classification, and NLP-based analysis, we model how cultural expressions manifest spatially and sensorially within Flushing.

<h2>Visual Chinese Elements in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 3.png' | relative_url }})

<p class="figure-caption">
Figure 3. Visual Element Analysis Pipeline from Street View Images
</p>


![Figure placeholder]({{ '/projects/research_0/assets/Frame 4.png' | relative_url }})

<p class="figure-caption">
Figure 4. Data Visualization of Visual Cultural Elements in Flushing
</p>


<h2>Aural Chinese Elements in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 5.png' | relative_url }})

<p class="figure-caption">
Figure 5. Aural Element Analysis Pipeline from Street Audio
</p>


![Figure placeholder]({{ '/projects/research_0/assets/Frame 6.png' | relative_url }})

<p class="figure-caption">
Figure 6. Data Visualization of Aural Cultural Elements in Flushing
</p>


<h2>Gustatory Chinese Elements in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 7.png' | relative_url }})

<p class="figure-caption">
Figure 7. Gustatory Element Analysis Pipeline from Google Maps Reviews
</p>


![Figure placeholder]({{ '/projects/research_0/assets/Frame 8.png' | relative_url }})

<p class="figure-caption">
Figure 8. Data Visualization of Gustatory Cultural Elements in Flushing
</p>


<h2>Multi-sensory Chinese Elements & Multi-cultural Fusion in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 9.png' | relative_url }})

<p class="figure-caption">
Figure 9. Final Data Visualization
</p>





