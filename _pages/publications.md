---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
{% include base_path %}
 
 {% for post in site.publications reversed %}
   {% include archive-single.html %}
 {% endfor %}

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}


## Research Publications

### Publication Title 1

- **Authors:** Author Name(s)
- **Published in:** Journal Name
- **Date:** Month Year
- **Link:** [Link to Publication](#)

Brief description or abstract of the publication.

### Publication Title 2

- **Authors:** Author Name(s)
- **Published in:** Journal Name
- **Date:** Month Year
- **Link:** [Link to Publication](#)

Brief description or abstract of the publication.
