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
</style>

<div class="project-wrap">

  <!-- Cover image -->
  <img
    src="{{ '/projects/research_0/assets/Frame 1.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">Made in Flushing test3</h1>

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
        33.3% conceptual design<br/>
        100% street view data crawling<br/>
        100% visual & gustatory ML analysis<br/>
        100% data visualization
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
    Flushing is one of the world’s largest Chinatowns, with a rich and woven cultural history.
    This project studies Chinese elements in Flushing through a multisensory lens—using street view texts,
    audios from walking tour videos, and food as cultural symbols. It explores how diverse cultures merge,
    highlighting what makes Flushing a truly multicultural community. We apply machine learning to assess
    cultural proportions across visual, aural, and gustatory dimensions, then visualize their coexistence.
  </p>

  <hr style="margin: 2rem 0;">
</div>

<h2>Background</h2>
<p class="section-subtitle">
  Flushing as a thriving Chinatown & multicultural urban hub
</p>

![Figure placeholder]({{ '/projects/research_0/assets/Frame 2.png' | relative_url }})

*Figure 1. Historical timeline of Flushing.*

Flushing, located in Queens, New York, is a diverse neighborhood shaped by centuries of migration and urban transformation. Although widely recognized today as one of the world’s largest Chinatowns, this dominant perception often overshadows deeper layers of multicultural integration formed by Chinese, Korean, Indian, and earlier European influences. Our research addresses this gap by computationally examining how Chinese cultural elements coexist with other cultural features.

---

<h2>Purpose</h2>
<p class="section-subtitle">
  Studying multisensory Chinese elements via machine learning
</p>

![Figure placeholder]({{ '/projects/research_0/assets/Frame 10.png' | relative_url }})

*Figure 2. Cultural elements identified in street views.*

This project investigates how cultural identity can be quantified through visual, auditory, and gustatory signals in urban environments. By integrating image segmentation, OCR, sound classification, and NLP-based analysis, we model how cultural expressions manifest spatially and sensorially within Flushing.

<h2>Visual Chinese Elements in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 3.png' | relative_url }})
*Figure 3. Procession of visual elements in street views*
![Figure placeholder]({{ '/projects/research_0/assets/Frame 4.png' | relative_url }})
*Figure 4. Data visualization of visual cultural elements in Flushing*

<h2>Aural Chinese Elements in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 5.png' | relative_url }})
*Figure 5. Procession of aural elements in street videos*
![Figure placeholder]({{ '/projects/research_0/assets/Frame 6.png' | relative_url }})
*Figure 6. Data visualization of aural cultural elements in Flushing*

<h2>Gustatory Chinese Elements in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 7.png' | relative_url }})
*Figure 7. Procession of gustatory elements in Google map comments*
![Figure placeholder]({{ '/projects/research_0/assets/Frame 8.png' | relative_url }})
*Figure 8. Data visualization of gustatory cultural elements in Flushing*

<h2>Multi-sensory Chinese Elements & Multi-cultural Fusion in Flushing</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 9.png' | relative_url }})
*Figure 9. Final data visualization*

