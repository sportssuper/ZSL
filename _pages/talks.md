---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

**• International Talks** 

|-------------------------|
| [Hoop-MSSL: Multi-Task Self-supervised Representation Learning on Basketball Spatio-Temporal Data](talks/Hoop_MSSL.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">NIPS WS</span>**, *2024.10*, Vancouver, Canada. |
| [Explainable artificial intelligence model for identifying market value in professional soccer players](talks/Davison等.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ECSS</span>**, *2024.07*, Glasgow, Scotland. |
| [Using Interpretable Machine Learning to Predict Injury Risk Among Collegiate Male Basketball Players](talks/predictinjuryriskamongcollegiatemalebasketballplayers.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ASCM</span>**, *2024.05*, Boston, USA. |
| [Effects Of Caffeine Supplementation On Athletic Performance In Basketball: A Systematic Review And Meta Analysis](talks/Effectsofcaffeinesupplementationonathleticperformanceinbasketball.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ASCM</span>**, *2024.05*, Boston, USA. |
| [Enhancing fall risk prediction in Chinese older adults using explainable machine learning](talks/machinelearning331.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ACSM</span>**, *2024.05*, Boston, USA. |
| [Clustering Football Game Situations via Deep Representation Learning](talks/ClusteringFootballGameSituations.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">Statsbomb</span>**, *2023.10*, Wembley, UK. |
| [Modelling and simulation in game performances of basketball players and teams in the national basketball association](talks/Modellingandsimulation.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">CIB</span>**, *2020.12*, En Cáceres, Spain. |
| [The interactive effects of situational variables on team performance in NBA](talks/Book of abstracts.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ECSS</span>**, *2018.07*, Dublin, Ireland. |
| [Performance Profiles of Basketball Players in NBA According to Anthropometric Attributes and Playing Experience](talks/Complexsystemsinsport.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">CSS</span>**, *2017.10*,Barcelona, Spain. |
| [Evaluating the quality of opposition in basketball games based on TOPSIS method](talks/BACA-2016.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ECSS</span>**, *2016.07*, Vienna, Austria. 






{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
