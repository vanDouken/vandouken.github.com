---
layout: page
title:
tagline:
---
{% include JB/setup %}

vanDouken is an interactive Simulation showcasing [HPX](http://stellar.cct.lsu.edu) and
[LibGeoDecomp](http://www.libgeodecomp.org).

Instead of simulating protons in a fusion reactor, we simulate brush strokes adapting
to interactively changing force fields. The simulation can be run on any device, ranging from Supercomputers
to small handheld Android Devices. In addition we provide programs to interactively steer,
visualize and introspect performance metrics of the running Simulation.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
