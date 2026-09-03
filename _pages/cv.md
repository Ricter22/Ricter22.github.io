---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD researcher in Artificial Intelligence and Information Retrieval, University of Southern Denmark
* MSc in Computer Science and Engineering, Politecnico di Milano, 2025
* BSc in Computer and Automation Engineering, Marche Polytechnic University, 2022

Work experience
======
* PhD Researcher, SDU Center for Industrial Software, University of Southern Denmark
  * Research in artificial intelligence, information retrieval, dataset discovery, RAG, and knowledge graphs
  * Teaching in artificial intelligence and supervision of student projects
* Software and DevOps Engineer, Blue Reply

Skills
======
* Artificial intelligence, machine learning, and natural language processing
* Information retrieval, data management, and data mining
* Retrieval-augmented generation and knowledge graphs
* Software engineering, DevOps, and good coding practices
* Academic writing and data analytics

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Mentoring
======
* Mentor, Danish Data Science Academy mentoring programme, 2026/2027
