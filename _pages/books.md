---
layout: archive
permalink: /books/
title: "Books"
author_profile: true
redirect_from:
  - /wordpress/blog-posts/
---
<div style="display: flex; gap: 40px; margin: 30px 0; align-items: center;">
  <!-- A4容器210:297 -->
  <div style="width: 15%; min-width: 200px; aspect-ratio: 210/297; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <img src="https://songuperman.github.io/ZSL/assets/images/book1.jpg" 
         alt="封面"
         style="width: 100%; height: 100%; object-fit: cover;">
  </div>

  <!-- 文字介绍区 -->
  <div style="width: 85%;">
    <h3 style="margin-top: 0; margin-bottom: 15px;">
      <strong>Theory of Participation In Sports Competitions</strong>
    </h3>
    <p style="line-height: 1.6; font-size: 15px; color: #333;">
      This book systematically establishes the theoretical framework of competitive participation for the first time, filling a long-standing gap in competitive sports research where "training was emphasized over competition," marking a milestone achievement. The project brought together three dedicated teams: a core authorship team comprising experts and scholars from seven institutions (Beijing Sport University, Shanghai University of Sport, Wuhan Sports University, Shanxi University, South China Normal University, Guangzhou University, and Tsinghua University), a translation team led by Professor Xu Aimei of South China Normal University, and an editorial team from People's Sports Publishing House. Over eight years of collaborative effort, these teams completed the revision, translation, and publication of the English edition of Theory of Participation In Sports Competitions, including the addition of two new chapters.<br>
The publication of the English version of this book introduces China's original academic achievements to the international competitive sports community, securing a theoretical stronghold in the field of competitive sports research. This work holds significant importance in strengthening theoretical confidence in China's competitive sports endeavors, constructing an autonomous knowledge system, and advancing the fulfillment of the grand vision of building a leading sports nation.

    </p>
    <div style="margin-top: 12px; font-size: 14px; color: #666;">
      <strong>Publisher:</strong> People's Sports Publishing House | <strong>Year:</strong> 2025 
    </div>
  </div>
</div>








<div style="display: flex; gap: 40px; margin: 30px 0; align-items: center;">
  <!-- A4容器210:297 -->
  <div style="width: 15%; min-width: 200px; aspect-ratio: 210/297; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    <img src="https://songuperman.github.io/ZSL/assets/images/book2.jpg" 
         alt="封面2"
         style="width: 100%; height: 100%; object-fit: cover;">
  </div>

  <!-- 文字介绍区 -->
  <div style="width: 85%;">
    <h3 style="margin-top: 0; margin-bottom: 15px;">
      <strong>Modelling and Simulation in Sport and Exercise</strong>
    </h3>
    <p style="line-height: 1.6; font-size: 15px; color: #333;">
      Modelling and simulation techniques are of central importance to conducting 
research in sport and exercise science, informing data collection and helping 
to analyze patterns of movement and physical performance. Modelling and 
Simulation in Sport and Exercise is the first book to offer an instructive reference for modelling and simulation methods for researchers and sport and exercise 
scientists.<br>
Based around a series of research cases, describing core theories in applied, 
practical settings, the book draws on examples of modelling and simulation in ball 
games, biomechanical analysis, physiological testing and monitoring, predictive 
analysis and sports engineering and product design. Each research case presents a 
central problem, discusses different modelling approaches that could be used to 
deal with the issue, analysis of results and a reflection on the methodology and an 
exercise for students to put the techniques discussed into practice.<br>
This is an important reference for any active researcher or upper-level student 
in sport and exercise science with an interest in mathematical modelling, computer science or simulation techniques.
    </p>
    <div style="margin-top: 12px; font-size: 14px; color: #666;">
      <strong>Publisher:</strong> Routledge | <strong>Year:</strong> 2023 
    </div>
  </div>
</div>





{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
