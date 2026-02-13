---
layout: single
title: ""
permalink: /projects/design_0/
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
    src="{{ '/projects/design_0/asset/Frame 24.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">Permission to the Forbidden</h1>

  <!-- 4-column info blocks -->
  <div class="kv-grid">
    <div class="kv-item">
      <div class="k">Individual Work</div>
    </div>

    <div class="kv-item">
      <div class="k">Tool</div>
      <div class="v">Unity (AR Core)</div>
      <div class="v">C#</div>
      <div class="v">Figma</div>
    </div>

    <div class="kv-item">
      <div class="k">Role</div>
      <div class="v">
        100% AR Game Planning and Developing;<br/>
        100% Front-end User Interface.<br/>
      </div>
    </div>

    <div class="kv-item">
      <div class="k">Timeline</div>
      <div class="v">Jun 2024 – Oct 2024</div>
    </div>
  </div>

  <!-- Tags -->
  <div class="tag-row">
    <span class="tag">AR Game Developing</span>
    <span class="tag">UI UX Design</span>
  </div>

  <!-- Intro paragraph -->
  <p class="lede">
    A gamified augmented reality (AR) game offers an immersive historical tour of the Forbidden City in Beijing. Players choose different dynastic periods, follow plotdriven AR paths, and complete tasks to learn about historical stories. Players play as historical roles, exploring stories, artifacts, and ancient architecture from a firstperson view. By the journey’s end, players will have a deeper understanding of the Forbidden City. With multi-timeline, multi-view, and multi-route options, the game makes exploring history of the Forbidden City both engaging and educational.
  </p>

  <hr style="margin: 2rem 0;">
</div>


<h2>Problems</h2>

<p class="section-subtitle">
  Limitations of Third-Person View in Traditional Tours
</p>

Traditional guided tours of cultural heritage sites, such as the Forbidden City, primarily rely on third-person narration and passive observation. While visitors can take photographs and access historical facts, the experience often lacks interaction, contextual understanding, and emotional engagement. This model limits the educational potential of heritage spaces, especially for diverse audiences with different cognitive and learning needs. The gap between visual spectacle and meaningful comprehension highlights the need for more interactive and embodied approaches to cultural learning.

![Figure placeholder]({{ '/projects/design_0/asset/Frame 25.png' | relative_url }})

<p class="figure-caption">
  Figure 1. Tension Between Tourism, Education, and Engagement in Heritage Spaces
</p>


<h2>Strategy</h2>

This framework illustrates how an AR gamified tour mediates between historical elements and visitor engagement. By transforming on-site exploration into first-person interactive experiences, the strategy bridges heritage content with immersive, emotionally resonant user experience.

![Figure placeholder]({{ '/projects/design_0/asset/Frame 26.png' | relative_url }})

<p class="figure-caption">
Figure 2. AR Gamified Tour as a Mediating Mechanism Between Heritage Elements and Visitor Experience.
</p>


<h2>Goal</h2>

<p class="section-subtitle">
  First-Person View Engagement with AR
</p>

This design framework illustrates how first-person engagement is achieved through AR-based mapping, multi-timeline narratives, multimodal interaction (vision, audition, and physical interaction), and chapter-based historical storytelling.

![Figure placeholder]({{ '/projects/design_0/asset/Frame 27.png' | relative_url }})

<p class="figure-caption">
Figure 3. Goal-Oriented AR Experience Design from Site Mapping to Narrative Chapter Design.
</p>


<h2>Game Assets</h2>

The numerous artifacts and intricate historical character relationships create a perfect foundation for vibrant game assets. In this AR-guided tour of the Forbidden City, players discover the stories behind these artifacts and connect historical events to real-world settings, bringing both the
artifacts and characters vivid to life as they explore.

![Figure placeholder]({{ '/projects/design_0/asset/Frame 28.png' | relative_url }})

<p class="figure-caption">
Figure 4. Game Assets.
</p>

<h2>Game Planning of Chapter 1</h2>

Taking Chapter 1’s game plan as an example, the player enters the game as a palace maid, experiencing one day during Renyin Palace Coup
from a first-person perspective while collecting artifact cards along the way. At the chapter’s start, player is provided with a timeline-based route
map using the ancient Chinese Zodiac timekeeping method, providing an overview of the tour and guiding them through tasks.

![Figure placeholder]({{ '/projects/design_0/asset/Frame 29.png' | relative_url }})

<p class="figure-caption">
Figure 5. Chapter 1 Route Map.
</p>


<h2>Techflow</h2>

<p class="section-subtitle">
  Plot-Driven AR Navigation
</p>

![Figure placeholder]({{ '/projects/design_0/asset/Frame 30.png' | relative_url }})

![Figure placeholder]({{ '/projects/design_0/asset/Frame 31.png' | relative_url }})

![Figure placeholder]({{ '/projects/design_0/asset/Frame 32.png' | relative_url }})

<p class="figure-caption">
Figure 6,7,8. Technical Pipeline.
</p>

<h2>Front-end Interfaces</h2>

<p class="section-subtitle">
  Game user journey
</p>

![Figure placeholder]({{ '/projects/design_0/asset/Frame 33.png' | relative_url }})

<p class="figure-caption">
Figure 9. User Interface Design.
</p>























