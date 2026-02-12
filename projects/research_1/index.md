---
layout: single
title: ""
permalink: /projects/research_1/
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
    src="{{ '/projects/research_0/assets/Frame 17.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">The Living Data</h1>

  <!-- 4-column info blocks -->
  <div class="kv-grid">
    <div class="kv-item">
      <div class="k">Team</div>
      <div class="v">Junkai An</div>
    </div>

    <div class="kv-item">
      <div class="k">Tool</div>
      <div class="v">Unreal Engine</div>
      <div class="v">C++</div>
    </div>

    <div class="kv-item">
      <div class="k">Role</div>
      <div class="v">
        50% Action Dataset Optimization;<br/>
        50% System Packaging;<br/>
        33.3% Data Quality Validation;<br/>
        100% Camera Setting.
      </div>
    </div>

    <div class="kv-item">
      <div class="k">Timeline</div>
      <div class="v">Sep 2024 – Dec 2024</div>
    </div>
  </div>

  <!-- Tags -->
  <div class="tag-row">
    <span class="tag">Human Factors</span>
    <span class="tag">Behavioral Study</span>
    <span class="tag">Data Synthesis</span>
  </div>

  <!-- Intro paragraph -->
  <p class="lede">
    The behavioral datasets have broad applications across multiple fields; however, they still face limitations in data collection, scene constraints, scale, and cost. Data synthesis is gaining increasing attention due to its ability to provide more diverse, cost-effective, and targeted data. Our research aims to overcome the limitations of existing datasets by using Unreal Engine to synthesize an unconstrained behavioral dataset within a residential environment, aiming to provide a general template applicable across various scenarios in human living behavior studies.
  </p>

  <hr style="margin: 2rem 0;">
</div>


<h2>Background</h2>
<p class="section-subtitle">
  Constrained Human Behavior Dataset VS Unconstrained Human Behavior Dataset
</p>

![Figure placeholder]({{ '/projects/research_0/assets1/Frame 18.png' | relative_url }})

<p class="figure-caption">
  Figure 1. Comparison Between Constrained VS Unconstrained Human Behavior Datasets.
</p>


<h2>Field Scanning to Scene Building</h2>

In the early experiment, we performed point cloud scanning of public areas in each residence, such as the living room, dining room, and kitchen,
achieving millimeter-level precision. Based on the point cloud models, the data was refined and organized to construct virtual residential scenarios
that closely resemble real-life settings.

![Figure placeholder]({{ '/projects/research_0/assets/Frame 19.png' | relative_url }})

<p class="figure-caption">
Figure 2. The Process from Real Living Scenes to Unreal Engine Scenes.
</p>


<h2>Scene Mapping</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 20.png' | relative_url }})

<p class="figure-caption">
Figure 3. Mapping from Real Scenes to Unreal Engine Scenes.
</p>


<h2>Camera Settings</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 21.png' | relative_url }})

<p class="figure-caption">
Figure 5. Camera Settings in Unreal Engine
</p>


<h2>Motion Settings</h2>
![Figure placeholder]({{ '/projects/research_0/assets/Frame 22.png' | relative_url }})

<p class="figure-caption">
Figure 7. Motion Setting Process
</p>


<h2>Output</h2>

![Figure placeholder]({{ '/projects/research_0/assets/Frame 9.png' | relative_url }})

<p class="figure-caption">
Figure 9. Final Data Visualization
</p>











