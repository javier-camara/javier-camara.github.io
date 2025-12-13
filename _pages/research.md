---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Complex software-intensive systems are increasingly relied upon in our society to support tasks in multiple areas (e.g., manufacturing, entertainment, communications, healthcare, transportation). At the same time, these systems are also progressively affected by higher degrees of variability and __uncertainties__ that can be introduced by run-time changes related to the lack of control over third-party system components (e.g., residing in the cloud), humans in the loop, as well as complex interactions between software and physical elements in cyber-physical systems, to name a few examples.

My research lies in the intersection of formal methods, software engineering, and artificial intelligence.  I am actively engaged in the research communities of __software engineering for self-adaptive systems__ and __software architecture__, contributing to their continued advancement through collaborations, publications, and community service. In recent years, I have devised techniques that combine [lightweight formal methods](https://people.csail.mit.edu/dnj/publications/ieee96-roundtable.html) and [quantitative verification](https://www.cs.bham.ac.uk/~parkerdx/papers/lms-qv.pdf) (probabilistic model checking) to analyze complex software-intensive systems subject to different forms of uncertainty, with applications to areas that include complex IT systems, security, and robotics.

One of the main areas in which I explore the application of these techniques is the provision of [assurances for self-adaptive systems](http://www.dagstuhl.de/de/programm/kalender/semhp/?semnr=13511).

I also have research interests in related areas that include control theory, cyber-physical and real-time systems, as well as [self-aware computing systems](https://www.dagstuhl.de/en/program/calendar/semhp/?semnr=15041).


## Research Projects

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
