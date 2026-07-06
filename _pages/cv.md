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

- **Nanjing University** — Software Engineering

Research interests
======

- Distributed systems testing and debugging
- Deterministic failure reproduction
- Deep learning framework and operator testing
- Static analysis and fault localization

Publications
======

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Selected projects
======

- [RediI](https://github.com/SSCT-Lab/RediI) — deterministic reproduction of distributed-system failures
- [Craft](https://github.com/SSCT-Lab/craft) — cross-framework repair-assisted fuzzing for equivalent deep learning operators
- [LogHound](https://github.com/SSCT-Lab/loghound) — method-level fault localization using static analysis, execution paths, coverage, and stack traces

Contact
======

- Email: [zheyuanlin@smail.nju.edu.cn](mailto:zheyuanlin@smail.nju.edu.cn)
- GitHub: [MartyLinZY](https://github.com/MartyLinZY)
- Blog: [martylinzy.github.io](https://martylinzy.github.io/)
