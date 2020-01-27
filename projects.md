---
layout: page
title: Projects
---

<!-- {% for project in site.projects reversed%}
<article class="project-listing">
    <div class="thumbnail-wrapper">
    <a href="{{ project.url | prepend: site.baseurl }}">
        <div class="thumbnail-description-wrapper">
        <img src="{{ project.thumbnail | prepend: site.image_serve_path }}" alt="{{ project.title }}" width="600" height="450">
        <p class="thumbnail-description">
            <span>{{ project.description }}</span>
        </p>
        </div>
        <h3>{{ project.title }}</h3>
    </a>
    </div>
</article>
{% endfor %} -->


<!-- NOTE: do not use future dates in project.date -->
{% for project in site.projects reversed %} 
{% if project.published %}
  [![{{ project.title }}]({{ site.baseurl }}/assets/img/{{ project.thumbnail }} "{{ project.title }}")
  {{ project.title }}]({{ project.url }})
{% endif %}
{% endfor %}