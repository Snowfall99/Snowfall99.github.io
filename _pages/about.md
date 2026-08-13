---
title: "About"
permalink: /
classes: wide
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<section id="bio">
  <p>
    I am a second-year Master's student at <a href="https://www.ini.cmu.edu/">Carnegie Mellon University</a> (CMU).
    I work with <a href="https://www.cs.cmu.edu/~zhihaoj2/">Prof. Zhihao Jia</a> and
    <a href="https://www.cs.cmu.edu/~rvinayak/">Prof. Rashmi Vinayak</a> on large-scale distributed LLM serving.
    My research interests include large-scale systems for LLM serving, KV-cache scheduling and ML compilers.
  </p>

  <p>
    Before coming to CMU, I was a Senior Software Engineer at <a href="https://www.bytedance.com/">ByteDance</a>, where
    I worked on building large-scale scheduling systems for AI infrastructure. I received my Bachelor's degree from the
    School of Computer Science at <a href="https://en.sjtu.edu.cn/">Shanghai Jiao Tong University</a> (SJTU) in 2022,
    where I worked with Prof. Shengyun Liu on distributed consensus protocols.
  </p>
</section>

<section id="publications">
  <h2>Publications</h2>

  <ul class="publication-list">{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
</section>

<section id="experience">
  <h2>Experience</h2>

  <div class="experience-list">
    <article class="experience-item">
      <p class="experience__heading"><strong><a href="https://vlm.run/">VLM Run</a></strong> — Machine Learning Intern</p>
      <p class="experience__meta">May 2026 – Aug. 2026 · Santa Clara, CA</p>
    </article>

    <article class="experience-item">
      <p class="experience__heading"><strong><a href="https://catalyst.cs.cmu.edu/">Catalyst Group</a>, CMU</strong> — Research Assistant</p>
      <p class="experience__meta">Oct. 2025 – Present · Pittsburgh, PA</p>
    </article>

    <article class="experience-item">
      <p class="experience__heading"><strong><a href="https://www.bytedance.com/">ByteDance</a></strong> — Senior Software Engineer</p>
      <p class="experience__meta">Jul. 2022 – Apr. 2025 · Beijing, China</p>
    </article>
  </div>
</section>

<section id="education">
  <h2>Education</h2>

  <div class="experience-list">
    <article class="experience-item">
      <p class="experience__heading"><strong>Carnegie Mellon University</strong> — MSIN, Advanced Study</p>
      <p class="experience__meta">Aug. 2025 – May 2027 (expected) · Pittsburgh, PA</p>
    </article>

    <article class="experience-item">
      <p class="experience__heading"><strong>Shanghai Jiao Tong University</strong> — B.Eng., School of Computer Science</p>
      <p class="experience__meta">Sep. 2018 – Jun. 2022 · Shanghai, China</p>
    </article>
  </div>
</section>

<section id="teaching">
  <h2>Teaching</h2>

  <div class="experience-list">
    <article class="experience-item">
      <p class="experience__heading"><strong>Teaching Assistant</strong> — <a href="https://15445.courses.cs.cmu.edu/">15-445/645: Database Systems</a></p>
      <p class="experience__meta">Fall 2026 · Carnegie Mellon University</p>
    </article>
  </div>
</section>
