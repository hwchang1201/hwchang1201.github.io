---
title: "Publications"
permalink: /publications/
---

# Preprints

- Q. Zhou and **H. Chang**. "**Complexity analysis of Bayesian learning of high-dimensional DAG models and their equivalence classes**". Submitted.

  [arXiv](https://arxiv.org/abs/2101.04084){: .btn--research} 


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
