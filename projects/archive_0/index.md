---
layout: single
title: ""
permalink: /projects/archive_0/
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
    src="{{ '/projects/archive_0/assets/Frame 34.png' | relative_url }}"
    alt="Project cover"
    style="width: 100%; border: 1px solid rgba(255,255,255,0.18);"
  />

  <h1 class="project-title">A Healing Journey</h1>

  <!-- 4-column info blocks -->
  <div class="kv-grid">
    <div class="kv-item">
      <div class="k">Team</div>
      <div class="v">Xinyu Wang, Bella Sun, Rong Zhao</div>
    </div>

    <div class="kv-item">
      <div class="k">Tool</div>
      <div class="v">Arduino</div>
      <div class="v">Unreal Engine</div>
      <div class="v">Rhino</div>
      <div class="v">Grasshopper</div>
      <div class="v">N'Space Plug-in</div>
    </div>

    <div class="kv-item">
      <div class="k">Role</div>
      <div class="v">
        90% Installation Design;<br/>
        80% Installation Fabrication;<br/>
        50% Conceptual Design;<br/>
        50% Serial Communication.
      </div>
    </div>

    <div class="kv-item">
      <div class="k">Timeline</div>
      <div class="v">Nov 2023 – Jan 2024</div>
    </div>
  </div>

  <!-- Tags -->
  <div class="tag-row">
    <span class="tag">Behavioral Study</span>
    <span class="tag">Interactive Installation</span>
    <span class="tag">MR Development</span>
  </div>

  <!-- Intro paragraph -->
  <p class="lede">
    A Healing Journey is an interactive experience combining VR scenes and Arduino interactive installations, supported by the VR Lab at Tsinghua University’s School of Architecture. Designed to support campus stress relief through movement-based emotional engagement, the project uses Interactional Transference Theory to guide participants through choreographed movements in VR. With N'Space plug-in and Unreal Engine, participants’ actions prompt real-time responses in both the VR Lab's visual feedback and physical installations, creating a synchronized, soothing
experience.
  </p>
  <p>
  <em>Special thanks to Archifiction. Inc for their invaluable device support and collaboration on this project.</em>
  </p>

  <hr style="margin: 2rem 0;">
</div>


<h2>Research Framework</h2>

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 35.png' | relative_url }})

<p class="figure-caption">
  Figure 1. Quantitative Analysis of Campus Anxiety and Intervention Opportunity.
</p>

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 36.png' | relative_url }})

<p class="figure-caption">
  Figure 2. System Architecture for Embodied VR Anxiety Intervention.
</p>

<h2>Strategy</h2>

This strategy framework integrates embodied dance movements, emotion mapping, and VR-based environmental design to create an interactive anxiety-relief experience. By synchronizing motion detection, sentiment analysis, and physical installation feedback through serial communication, the system connects user movement, immersive storytelling, and multisensory output into a coherent therapeutic loop.

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 37.png' | relative_url }})

<p class="figure-caption">
  Figure 3. System Framework for an Embodied VR-Based Anxiety Intervention.
</p>


<h2>Technology</h2>

A multi-layered embodied interaction system connecting dance input, motion sensing, VR rendering, and physical installation feedback.

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 38.png' | relative_url }})

<p class="figure-caption">
  Figure 4. Hardware–Software Integration for Embodied VR Interaction.
</p>

<h2>Body Motion & Emotion Analysis</h2>

Based on emotion categorization theory, different emotions are categorized by two axes: valence and arousal. Each emotion is then related
to four basic movements, which will be further used in the dance moves. The strategy of behaviorism is taken into consideration in our dance
moves design, indicating that emotions are both reactive to behavior and can be influenced by subsequent behavior.

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 39.png' | relative_url }})

<p class="figure-caption">
  Figure 5. Body Motion & Emotion Mapping.
</p>

<h2>Dance Moves Design & Emotion Flow</h2>

The system organizes the experience into three embodied chapters (Relax, Energetic, Liberal), each associated with distinct motion patterns and emotional trajectories. Motion inputs from participants are mapped to affective states through keyframe analysis, triggering coordinated responses in both the VR environment and the physical installation. This closed-loop interaction translates bodily movement into spatial transformation and emotional modulation.

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 40.png' | relative_url }})

<p class="figure-caption">
  Figure 6. Motion–Emotion Correspondence in the VR Interaction System.
</p>


<h2>VR Scene Correlation</h2>

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 41.png' | relative_url }})

<p class="figure-caption">
  Figure 7. VR Scenes in Three Chapters.
</p>

<h2>VR Lab Setup</h2>

The VR Lab is configured as an immersive projection space integrating motion detection, real-time rendering, and physical installation control. Motion detection cameras capture participants’ movements, which are processed in the technical control room and translated into synchronized visual projections and installation responses, forming a unified interactive environment.

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 42.png' | relative_url }})

<p class="figure-caption">
  Figure 8. Tsinghua VR Lab.
</p>

<h2>Technical Interconnection</h2>

The system establishes a real-time body–environment interaction loop, where motion capture data is processed and transmitted to both VR rendering and Arduino-controlled installation mechanisms, enabling synchronized multimodal feedback.

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 43.png' | relative_url }})

<p class="figure-caption">
  Figure 9. Technical Interconnection of the Body–Installation–VR System.
</p>

<h2>Installation Design</h2>

The exploded view reveals the constructive logic of the installation, demonstrating how motorized units, vertical supports, and joint connections collaboratively generate synchronized surface transformations.

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 44.png' | relative_url }})

<p class="figure-caption">
  Figure 10. Assembly and Component Breakdown of the Kinetic Installation.
</p>

<h2>Material Testing</h2>

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 45.png' | relative_url }})

<p class="figure-caption">
  Figure 11. Material Testing Process.
</p>

<h2>User Journey Map</h2>

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 46.png' | relative_url }})

<p class="figure-caption">
  Figure 12.  Cross-Modal Interaction Timeline Across Three Experience Chapters.
</p>

<h2>Physical Prototyping & Deployment</h2>

![Figure placeholder]({{ '/projects/archive_0/assets/Frame 47.png' | relative_url }})

<p class="figure-caption">
  Figure 13. From Prototype to Full-Scale Installation.
</p>







