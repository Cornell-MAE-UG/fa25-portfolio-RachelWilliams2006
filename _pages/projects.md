---
layout: default
title: Rachel Williams - Portfolio
permalink: /projects/
---

![Shaded rendering of earlier version]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

[2025-10-07 21-02.pdf](https://github.com/user-attachments/files/22757071/2025-10-07.21-02.pdf)

![Heat exchanger diagram](https://github.com/user-attachments/assets/3ace40c7-dda2-4675-810f-ff6779c61b18)


<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
