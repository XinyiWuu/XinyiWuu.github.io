---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

{% include_relative includes/welcome.md %}

{% include_relative includes/biography.md %}

{% include_relative includes/research_interest.md %}

{% include_relative includes/news.md %}

{% include_relative includes/publications.md %}

{% include_relative includes/research_experience.md %}

{% include_relative includes/projects.md %}

{% include_relative includes/honors_and_rewards.md %}

{% include_relative includes/educations.md %}

{% include_relative includes/work_experience.md %}

{% include_relative includes/skills.md %}

{% include_relative includes/updated.md %}