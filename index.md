---
layout: single
author_profile: false
permalink: /
title: ""
classes: landing
---

<div id="top"></div>

<div class="landing-hero">
  <div class="landing-avatar">
    <img src="/images/profilePic.png" alt="Mengying Wang portrait">
  </div>

  <div class="landing-bio">
    MS.HCDE @UW | B.Eng @Tsinghua
  </div>

  <div class="landing-links">
    {% if site.author.email %}
      <a href="mailto:{{ site.author.email }}"><i class="fas fa-envelope"></i> Email</a>
    {% endif %}

    {% for l in site.author.links %}
      {% if l.label == "GitHub" or l.label == "github" %}
        <a href="{{ l.url }}"><i class="{{ l.icon }}"></i> GitHub</a>
      {% endif %}
      {% if l.label == "LinkedIn" or l.label == "linkedin" %}
        <a href="{{ l.url }}"><i class="{{ l.icon }}"></i> LinkedIn</a>
      {% endif %}
    {% endfor %}
  </div>
</div>

<section id="about">
## About
TEST-DEPLOY-063 Hi! I’m **Mengying Wang**, an HCI researcher interested in human–AI interaction, learning sciences, and human factors.

I am currently a Research Assistant at the University of Washington and City University of Hong Kong. My work focuses on designing and evaluating AI-assisted systems for learning and creative tasks.
</section>

<section id="news">
## News
- Test 064
- 2025.10 — Teaching Assistant for HCDE 321 at UW.
- 2025.08 — Research Assistant at City University of Hong Kong.
</section>

<section id="publications">
## Publications
- Manuscripts in preparation.
</section>

<section id="portfolio">
## Portfolio
### Research
- (Coming soon)

### Design
- (Coming soon)
</section>

<section id="teaching">
## Teaching
- Teaching Assistant, HCDE 321 (University of Washington).
</section>
