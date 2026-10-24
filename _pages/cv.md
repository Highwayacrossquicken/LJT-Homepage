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
=======

- **2024–present:** Ph.D. in Computer Science, Hong Kong University of Science and Technology.
- **2020–2024:** B.Eng., Shanghai Jiao Tong University (graduated June 2024).

Research experience
=================

- **February 2025–present:** Research Intern, MINIMAX.
- **June 2024–September 2024:** Research Intern, Tencent WXG.
- **June 2023–December 2023:** Research Intern, Shanghai AI Lab.

Publications
===========

{% assign sorted_publications = site.publications | sort: "year" | reverse %}
<ul>{% for post in sorted_publications %}{% include archive-single-cv.html %}{% endfor %}</ul>
