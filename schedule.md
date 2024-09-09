---
layout: page
title: TA Hours
description: The weekly event schedule.
---

# Weekly Schedule

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}