---
title: Projects and Events
permalink: /events/
layout: collection
collection: events
entries_layout: grid
classes: wide
sidebar:
  nav: "docs"

---

Check out our upcoming events [here]({{ site.baseurl }}{% link _pages/upcoming.md %}).
<!-- 
layout: collection
collection: events
entries_layout: grid
classes: wide
sidebar:
  nav: "docs"
{{ site.members | where_exp:"item",
"item.graduation_year < 2014" }} -->


<!-- 

{% capture written_label %}'None'{% endcapture %}

{% for collection in site.collections %}
  {% unless collection.output == false or collection.label == "posts" %}
    {% capture label %}{{ collection.label }}{% endcapture %}
    {% if label != written_label %}
      <h2 id="{{ label | slugify }}" class="archive__subtitle">{{ label }}</h2>
      {% capture written_label %}{{ label }}{% endcapture %}
    {% endif %}
  {% endunless %}
  {% for post in collection.docs %}
    {% unless collection.output == false or collection.label == "posts" %}
      {% include archive-single.html %}
    {% endunless %}
  {% endfor %}
{% endfor %}

 -->




