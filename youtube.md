---
layout: page
title: People that shape my way of thinking about...
permalink: /youtube/
softwareId: 
  - Tng6Fox8EfI
  - watS54iWH9U
  - whi0T1a4cWU
  - 15X0qFtBqiQ
  - e4MT_OguDKg
teamId: 
  - lvs7VEsQzKY
  - hZFShSjAhlQ
  - USc-yLHXNUg
skillUpId:
  - wXQLil_SGCI
intelliJId:
  - bFcaO1pXzws
  - MZge92bbU7E
---

**Software**
<div class="scrollmenu">
{% for video in page.softwareId %}
{% include youtubePlayer.html id=video %}
{% endfor %}
</div>

**Teams**
<div class="scrollmenu">
{% for video in page.teamId %}
{% include youtubePlayer.html id=video %}
{% endfor %}
</div>

**Skills**
<div class="scrollmenu">
{% for video in page.skillUpId %}
{% include youtubePlayer.html id=video %}
{% endfor %}
</div>

**IntelliJ**
<div class="scrollmenu">
{% for video in page.intelliJId %}
{% include youtubePlayer.html id=video %}
{% endfor %}
</div>
