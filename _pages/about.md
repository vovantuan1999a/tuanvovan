---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="academic-home">
  <section id="about-me" class="home-section home-section--intro">
    {% include_relative includes/intro.md %}
  </section>

  <section id="news" class="home-section">
    {% include_relative includes/news.md %}
  </section>

  <section id="publications" class="home-section">
    {% include_relative includes/pub.md %}
  </section>

  <section id="education" class="home-section">
    {% include_relative includes/educations.md %}
  </section>

  <section id="experience" class="home-section">
    {% include_relative includes/experience.md %}
  </section>

  <section id="service" class="home-section">
    {% include_relative includes/academic_service.md %}
  </section>

  <section id="honors" class="home-section">
    {% include_relative includes/honers.md %}
  </section>

  <section id="visitors" class="home-section">
    {% include_relative includes/visitors.md %}
  </section>
</div>
