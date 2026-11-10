---
permalink: /
title: "About me"
homepage: true
description: "Riccardo Terrenzi researches dataset discovery, information retrieval, and trustworthy AI at the University of Southern Denmark."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<p class="research-lead">I'm Riccardo Terrenzi, a PhD researcher in Artificial Intelligence and Information Retrieval at the University of Southern Denmark, supervised by Serkan Ayvaz.</p>

I am part of the [AI & Machine Learning Lab](https://aiml-sdu.github.io/) at the SDU Center for Industrial Software, Maersk Mc-Kinney Moller Institute. I study how we can make data easier to discover and AI-generated results more faithful, transparent, and auditable.

## Research interests

My work connects dataset search, retrieval-augmented generation, and knowledge graphs. I focus on understanding where retrieved evidence comes from, how it shapes an answer, and how to keep AI systems transparent and auditable.

<ul class="research-topics">
  <li>Dataset discovery</li><li>Information retrieval</li><li>Retrieval-augmented generation</li>
  <li>Knowledge graphs</li><li>Trustworthy AI</li><li>Software architecture</li>
</ul>

## Beyond research

I teach artificial intelligence, supervise student projects, and mentor aspiring data scientists. Before my PhD, I earned an MSc in Computer Science and Engineering from Politecnico di Milano and a BSc in Computer and Automation Engineering from Marche Polytechnic University. I also worked as a Software and DevOps Engineer at Blue Reply and gained international experience in Germany and Denmark.

## Selected publications

{% assign selected_publications = site.publications | where: 'featured', true | sort: 'date' | reverse %}
{% for post in selected_publications %}
  {% include publication-card.html heading="h3" compact=true %}
{% endfor %}

[All publications &rarr;]({{ '/publications/' | relative_url }})
