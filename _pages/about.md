---
permalink: /
title: "Making data findable. Making AI trustworthy."
description: "Riccardo Terrenzi researches dataset discovery, information retrieval, and trustworthy AI at the University of Southern Denmark."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="eyebrow">Artificial intelligence & information retrieval</p>

<p class="research-lead">I'm Riccardo Terrenzi, a PhD researcher at the University of Southern Denmark. I study how we can make data easier to discover and AI-generated results more faithful, transparent, and auditable.</p>

<div class="profile-actions">
  <a href="{{ '/publications/' | relative_url }}">Explore my research</a>
  <a href="{{ '/cv/' | relative_url }}">View CV</a>
  <a href="mailto:{{ site.author.email }}">Get in touch</a>
</div>

I am part of the SDU Center for Industrial Software at the Maersk Mc-Kinney Moller Institute. My work connects dataset search, retrieval-augmented generation, and knowledge graphs, with a focus on understanding where retrieved evidence comes from and how it shapes an answer.

## Selected research

{% assign selected_publications = site.publications | where: 'featured', true | sort: 'date' | reverse %}
{% for post in selected_publications %}
  {% include publication-card.html heading="h3" %}
{% endfor %}

[All publications &rarr;]({{ '/publications/' | relative_url }})

## Research interests

<ul class="research-topics">
  <li>Dataset discovery</li><li>Information retrieval</li><li>Retrieval-augmented generation</li>
  <li>Knowledge graphs</li><li>Trustworthy AI</li><li>Software architecture</li>
</ul>

## Beyond research

I teach artificial intelligence, supervise student projects, and mentor aspiring data scientists. Before my PhD, I earned an MSc in Computer Science and Engineering from Politecnico di Milano and a BSc in Computer and Automation Engineering from Marche Polytechnic University. I also worked as a Software and DevOps Engineer at Blue Reply and gained international experience in Germany and Denmark.
