---
permalink: /
title: "Welcome"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
{% include base_path %}
{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}
<link rel="stylesheet" href="{{ "assets/css/pages/experience.css" | relative_url }}">
<p>Welcome to my personal website, where I share my expertise, achievements, and professional journey. Here, you’ll find insights into my work, projects, and innovations in cutting-edge technologies.</p>
 <img src="{{ author.membership | prepend: "/images/" | prepend: base_path }}" id="author__membership" alt="{{ author.membership }}">
<h2>About Me</h2>
 <div class="col-sm-8" id="mainLeft">
                <div id="dynamic-text" class="row col-sm-12">
                    <ul class="text-dynamic">
                        <li class="text-item"><strong>Software Engineer</strong></li>
                        <li class="text-item"><strong>Full Stack Developer</strong></li>
                        <li class="text-item"><strong>Data Scientist</strong></li>
                        <li class="text-item"><strong>Data Analyst</strong></li>
                    </ul>
                </div>
<p>I am a <strong>technology leader and innovator</strong> with a strong foundation in <strong>software engineering, data science, and cloud architecture</strong>. With a passion for solving complex problems, I have honed my skills across multiple disciplines to drive scalable, high-impact solutions in the ever-evolving tech landscape.</p>

<div align="center">
  <h2>Education & Certifications 🎓</h2>
  <ul style="list-style: none; padding: 0;">
    <li><strong>MSc Data Science</strong></li>
    <li><strong>MSc Software Architecture</strong></li>
    <li><strong>BSc Computer Engineering (Hons)</strong></li>
    <li><strong>BCS, The Chartered Institute for IT</strong></li>
    <li><strong>AWS Certified Solutions Architect – Associate</strong></li>
  </ul>
</div>

<p>I started my career as a <strong>Java developer</strong>, building robust, high-performance applications. Over time, my curiosity and dedication led me to explore emerging technologies, shaping my transition into a <strong>computer healthcare scientist</strong>, applying <strong>software, data, and AI-driven solutions</strong> to enhance computational healthcare.</p>

<p>Beyond my professional roles, I am a <strong>self-taught investor</strong> in knowledge and technology, continuously refining my expertise in <strong>AI, cloud computing,</strong> and <strong>scalable architectures</strong>. My mission is to leverage cutting-edge innovations to build transformative solutions that make a meaningful impact.</p>
