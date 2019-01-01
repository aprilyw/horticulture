---
title: Board Members
permalink: /board/
sidebar:
  nav: "docs"

---

{% for member in site.board_members %}
  <h2> {{ member.name }} | {{ member.position }} </h2>
  {: id="{{ member.name | slugify}}"}


  ![bio-pic]({{ site.url }}{{ site.baseurl }}{{member.photo}}){:height="400px" width="700px" .align-center}


  > {{ member.bio | markdownify }}
  <h3> {{ member.question }} </h3>
  > {{ member.answer | markdownify }}

{% endfor %}

{: id="idhere"}

[link](#idhere)
[sicely](#sicely-li)
[april](#april-wang)
