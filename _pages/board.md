---
title: Board Members
permalink: /board/
sidebar:
  nav: "docs"

---

{% for member in site.board_members %}
  <h2>{{ member.name }} | {{ member.position }}</h2> 
  ![bio-pic]({{member.photo}}){:height="400px" width="700px" .align-center}

  <p>{{ member.bio | markdownify }}</p>
  <h3>{{ member.question }}</h3>
  <p>{{ member.answer | markdownify }}</p>
{% endfor %}
