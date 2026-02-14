---
layout: single
title: ""
permalink: /projects/research_2/
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
    src="{{ '/projects/research_2/assets/Frame 48.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">Civic Intelligence</h1>

  <!-- 4-column info blocks -->
  <div class="kv-grid">
    <div class="kv-item">
      <div class="k">Team</div>
      <div class="v">Evanna Yang</div>
      <div class="v">Yitong Du</div>
    </div>

    <div class="kv-item">
      <div class="k">Tool</div>
      <div class="v">Figma</div>
      <div class="v">R Language</div>
      <div class="v">Qualtrics</div>
      <div class="v">Bolt.ai</div>
    </div>

    <div class="kv-item">
      <div class="k">Role</div>
      <div class="v">
        33.3% Prototype Design;<br/>
        33.3% Usability Testing;<br/>
        33.3% Experimental Design;<br/>
        50% Data Analysis;<br/>
        33.3% Report Writing.
      </div>
    </div>

    <div class="kv-item">
      <div class="k">Timeline</div>
      <div class="v">Sep 2025 – Dec 2025</div>
    </div>
  </div>

  <!-- Tags -->
  <div class="tag-row">
    <span class="tag">Human-AI Interaction</span>
    <span class="tag">Experimental Research</span>
    <span class="tag">Civic Tech</span>
    <span class="tag">Usability Evaluation</span>
  </div>

  <!-- Intro paragraph -->
  <p class="lede">
    <strong>Civic Intelligence</strong> originated from our participation in the
    <a href="https://innovation-hub.seattle.gov/2025/10/28/community-innovation-pactathon-permitting/" target="_blank" rel="noopener">
      Community Innovation Hackathon
    </a>
    hosted by the City of Seattle’s Innovation &amp; Performance team. The event challenged participants to design AI-driven solutions that improve transparency and efficiency in the city’s construction permitting system using newly released public datasets. Building on the hackathon prototype, we further developed the project in collaboration with the HCDE516 course at University of Washington. Through coursework and iterative evaluation, we explored how AI assistance can support usability, trust, and decision-making in civic service workflows.
  </p>

  <hr style="margin: 2rem 0;">
</div>


<h2>Background</h2>

In 2025, the City of Seattle launched its Responsible AI Plan (2025–2026) alongside a Community Innovation Hackathon series aimed at promoting transparent and accountable AI use in public services. Within this civic context, our project emerged as a response to real-world challenges in the city’s construction permitting system, exploring how human–AI collaboration can enhance usability, trust, and public sector decision-making.

![Figure placeholder]({{ '/projects/research_2/assets/Frame 49.png' | relative_url }})

<p class="figure-caption">
  Figure 1. Mayor Harrell & New Responsible AI Plan.
</p>


<h2>Research Question</h2>

While the hackathon prototype demonstrated the potential of AI-assisted permitting, it also raised important questions about the appropriate level of AI involvement in public-facing systems. This prompted a more structured investigation into how different degrees of AI integration influence user outcomes.

![Figure placeholder]({{ '/projects/research_2/assets/Frame 50.png' | relative_url }})

<h2>Hypothesis</h2>

Building on existing discussions around automation levels and human–AI collaboration, we examined how increasing system intelligence might reshape user experience in civic workflows. This perspective informed the directional hypothesis outlined below：

![Figure placeholder]({{ '/projects/research_2/assets/Frame 51.png' | relative_url }})

<h2>Methods</h2>

We designed a 3 (AI integration level) × 2 (user type: architects vs. residents) between-subject study. Participants were randomly assigned to one of three AI-assisted permit portal systems and completed three standardized permit application tasks. The final sample included 42 participants (12 architects, 30 residents). After completing the tasks, participants completed a 15-item survey (5 multi-select, 9 Likert-scale, 1 open-ended) measuring perceived usability, helpfulness, and task-related experience.

![Figure placeholder]({{ '/projects/research_2/assets/Frame 52.png' | relative_url }})

<p class="figure-caption">
  Figure 2. Experimental Methods.
</p>

The three system versions operationalized increasing levels of AI agency and personalization within identical task structures. While all participants completed the same three permit-related tasks, the type and depth of AI intervention varied systematically across conditions, enabling controlled comparison of AI involvement effects on user performance and perception.

![Figure placeholder]({{ '/projects/research_2/assets/Frame 53-1.png' | relative_url }})

<p class="figure-caption">
  Figure 3. Levels of AI Integration Across Permit Portal Tasks.
</p>

<h2>Experimental Platform Prototypes</h2>

Video 1. Control Version (No AI Assistance)
Participants completed the permit application workflow without AI support, manually performing time lookup, form entry, and pre-submission review.

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;margin-bottom:2rem;">
  <iframe 
    src="https://player.vimeo.com/video/1164916970?title=0&byline=0&portrait=0"
    style="position:absolute;top:0;left:0;width:100%;height:100%;"
    frameborder="0"
    allow="autoplay; fullscreen; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

Video 2. Partial AI Assistance
Participants received case-based time estimation, chatbot support during form filling, and automated review feedback.

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;margin-bottom:2rem;">
  <iframe 
    src="https://player.vimeo.com/video/1164917004?title=0&byline=0&portrait=0"
    style="position:absolute;top:0;left:0;width:100%;height:100%;"
    frameborder="0"
    allow="autoplay; fullscreen; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

Video 3. Full AI Assistance 
Participants interacted with a fully integrated AI system providing personalized time estimation, autofill based on user information, and annotated AI review with documented sources.

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;margin-bottom:2rem;">
  <iframe 
    src="https://player.vimeo.com/video/1164917115?title=0&byline=0&portrait=0"
    style="position:absolute;top:0;left:0;width:100%;height:100%;"
    frameborder="0"
    allow="autoplay; fullscreen; picture-in-picture"
    allowfullscreen>
  </iframe>
</div>

<h2>Survey Design</h2>

blablabla placeholder

![Figure placeholder]({{ '/projects/research_2/assets/Frame 55.png' | relative_url }})

<p class="figure-caption">
  Figure 4. blablabla placeholder.
</p>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 56-2.png' | relative_url }})

<p class="figure-caption">
  Figure 5. blablabla placeholder.
</p>

<h2>Results & Findings</h2>

<p class="section-subtitle">
  Clean & Transform Data
</p>
blablabla placeholder.

<p class="section-subtitle">
  Measures
</p>
blablabla placeholder.

<p class="section-subtitle">
  Sample Characteristics
</p>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 57.png' | relative_url }})

<p class="figure-caption">
  Figure 6. blablabla placeholder.
</p>

<p class="section-subtitle">
  Descriptive Stats for Indices by Version
</p>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 58.png' | relative_url }})

<p class="figure-caption">
  Figure 7. blablabla placeholder.
</p>

<p class="section-subtitle">
  Boxplots: Indices by Version
</p>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 60.png' | relative_url }})

<p class="figure-caption">
  Figure 8. blablabla placeholder.
</p>

<p class="section-subtitle">
  One-Way ANOVAS
</p>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 61.png' | relative_url }})

<p class="figure-caption">
  Figure 9. blablabla placeholder.
</p>

<p class="section-subtitle">
  Post-hoc Tukey Comparisons
</p>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 62.png' | relative_url }})

<p class="figure-caption">
  Figure 10. blablabla placeholder.
</p>

<h2>Qualitative Data</h2>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 63.png' | relative_url }})

<h2>Discussion</h2>

![Figure placeholder]({{ '/projects/research_2/assets/Frame 64.png' | relative_url }})

<h2>Summary</h2>










