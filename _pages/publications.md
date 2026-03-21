---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Many of the papers below formalize frameworks and perspectives developed over multiple years of professional practice and research. They are written in an applied style for institutional investors, policymakers, boards, and research collaborators, with a focus on how governance structures shape capital allocation across traditional and emerging asset systems.


## Capital Allocation & Risk Design
This section examines how institutions allocate capital across asset classes, with attention to risk budgets, liquidity, implementation design, manager selection, and the governance assumptions embedded in portfolio construction.

{% assign pubs = site.publications | where: "category", "capital_risk" | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single.html titles_only=true %}
{% endfor %}

## Fiduciary Architecture & Institutional Governance
This section serves as the intellectual spine of my research. It examines fiduciary duty, board oversight, institutional accountability, decision-making under uncertainty, and the governance structures that shape long-term capital allocation outcomes.

{% assign pubs = site.publications | where: "category", "fiduciary_governance" | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single.html titles_only=true %}
{% endfor %}

## Digital Infrastructure & Tokenized Markets
This section examines tokenization, digital market infrastructure, and real-world asset systems through an institutional lens, focusing on governance, legal structure, market design, and implementation constraints rather than technology alone.

{% assign pubs = site.publications | where: "category", "digital_tokenized" | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single.html titles_only=true %}
{% endfor %}

{% assign pubs = site.publications | where: "category", "applied_notes" | sort: "date" | reverse %}
{% for post in pubs %}
  {% include archive-single.html titles_only=true %}
{% endfor %}
