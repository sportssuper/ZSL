---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: true
---

**• International Talks** 

|-------------------------|
| [Hoop-MSSL: Multi-Task Self-supervised Representation Learning on Basketball Spatio-Temporal Data](talks/Hoop_MSSL.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">NIPS WS, Vancouver, Canada, 2024.10.</span>**|
| [Explainable artificial intelligence model for identifying market value in professional soccer players](talks/Davison等.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ECSS, Glasgow, Scotland, 2024.07</span>**|
| [Using Interpretable Machine Learning to Predict Injury Risk Among Collegiate Male Basketball Players](talks/predictinjuryriskamongcollegiatemalebasketballplayers.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ASCM Boston, USA, 2024.05</span>**|
| [Effects Of Caffeine Supplementation On Athletic Performance In Basketball: A Systematic Review And Meta Analysis](talks/Effectsofcaffeinesupplementationonathleticperformanceinbasketball.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ASCM Boston, USA, 2024.05</span>**|
| [Enhancing fall risk prediction in Chinese older adults using explainable machine learning](talks/machinelearning331.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ACSM Boston, USA</span>**|
| [Clustering Football Game Situations via Deep Representation Learning](talks/ClusteringFootballGameSituations.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">Statsbomb Wembley, UK, 2023.10</span>**|
| [Modelling and simulation in game performances of basketball players and teams in the national basketball association](talks/Modellingandsimulation.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">CIB  En Cáceres, Spain, 2020.12</span>**|
| [The interactive effects of situational variables on team performance in NBA](talks/Book of abstracts.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ECSS Dublin, Ireland, 2018.07</span>**|
| [Performance Profiles of Basketball Players in NBA According to Anthropometric Attributes and Playing Experience](talks/Complexsystemsinsport.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">CSS Barcelona, Spain, 2017.10</span>**|
| [Evaluating the quality of opposition in basketball games based on TOPSIS method](talks/BACA-2016.pdf) | **<span style="background-color: #960DBD; color: white; padding: 1px 4px;">ECSS, Vienna, Austria, 2016.07</span>**|






{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
