---
layout: archive
title: ""
permalink: /talks/
author_profile: true
---

<style>
  body {
    font-family: 'Times New Roman', Times, serif !important;
  }
  h1, h2, h3, p, table, span, a {
    font-family: inherit !important;
  }
  code, pre {
    font-family: 'Courier New', monospace !important;
  }
</style>


**• International Talks** 

<div style="width: 100%; margin: 20px 0;">
  <img src="https://sportssuper.github.io/ZSL/assets/images/talk2.png" 
       alt="Map"
       style="width: 100%; height: auto; display: block; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
</div>

| Title | Conference |
|-------|------------|
| [Interaction effects of physical activity and sleep duration on motoric cognitive risk syndrome in Chinese older adults: A population-based cohort study](talks/ecss25gld.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">ECSS, Rimini, Italy, 2025.06.</span>**|
| [Hoop-MSSL: Multi-task self-supervised representation learning on basketball spatio-temporal data](talks/Hoop_MSSL.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">NIPS WS, Vancouver, Canada, 2024.10.</span>**|
| [Explainable artificial intelligence model for identifying market value in professional soccer players](talks/Davison等.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">ECSS, Glasgow, Scotland, 2024.07</span>**|
| [Using interpretable machine learning to predict injury risk among collegiate male basketball players](talks/predictinjuryriskamongcollegiatemalebasketballplayers.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">ASCM Boston, USA, 2024.05</span>**|
| [Effects of caffeine supplementation on athletic performance in basketball: A systematic review and meta analysis](talks/Effectsofcaffeinesupplementationonathleticperformanceinbasketball.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">ASCM Boston, USA, 2024.05</span>**|
| [Enhancing fall risk prediction in Chinese older adults using explainable machine learning](talks/machinelearning331.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">ACSM Boston, USA，2024.05</span>**|
| [Clustering football game situations via deep representation learning](talks/ClusteringFootballGameSituations.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">Statsbomb Wembley, UK, 2023.10</span>**|
| [Modelling and simulation in game performances of basketball players and teams in the national basketball association](talks/Modellingandsimulation.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">CIB En Cáceres, Spain, 2020.12</span>**|
| [Comparison of the movement characteristics based on position-specific between U18 and professional basketball players](talks/18baxi.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">CIB, Florianópolis/SC, Brazi, 2018.11</span>**|
| [The interactive effects of situational variables on team performance in NBA](talks/Book of abstracts.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">ECSS Dublin, Ireland, 2018.07</span>**|
| [Performance profiles of basketball players in NBA according to anthropometric attributes and playing experience](talks/Complexsystemsinsport.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">CSS Barcelona, Spain, 2017.10</span>**|
| [Evaluating the quality of opposition in basketball games based on TOPSIS method](talks/BACA-2016.pdf) | **<span style="background-color: #7E099D; color: white; padding: 1px 4px;">ECSS, Vienna, Austria, 2016.07</span>**|







{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
