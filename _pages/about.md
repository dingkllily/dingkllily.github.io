---
permalink: /
title: "About Me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Ph.D. Candidate in Civil Engineering at the University of Illinois Urbana-Champaign, advised by [Professor Erol Tutumluer](https://cee.illinois.edu/directory/profile/tutumlue), with an expected graduation in 2026. 

My work sits at the intersection of transportation engineering, computer vision, and applied machine learning, with a focus on turning research into practical tools for field inspection and condition evaluation.

My research focuses on utilizing computer vision and deep learning to automate railway ballast inspection. This includes multimodal sensing, signal processing, image and point cloud segmentation, data synthesis, edge deployment, vision foundation models, and software systems that support large-scale ballast condition evaluation in real-world railway environments.

## Selected Publications

<div class="about-selected-publications">

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.permalink == '/publication/2026-image-based-moisture-content-prediction'
    or post.permalink == '/publication/2025-condition-evaluation-of-mud-spots'
    or post.permalink == '/publication/2025-ballast-angularity-index'
    or post.permalink == '/publication/2024-i-ballast-geodata-ai'
    or post.permalink == '/publication/2024-augmented-dataset-algorithms' %}
    {% include archive-single.html type="publication" %}
  {% endif %}
{% endfor %}

</div>
For a fuller list, see the [Publications](/publications/) page or my [Google Scholar](https://scholar.google.com/citations?user=XFGDhhQAAAAJ).


## Education

<div class="about-education">
  <ul class="education-list">
    <li class="education-entry">
      <div class="education-school">University of Illinois Urbana-Champaign</div>
      <ul class="education-degrees">
        <li>
          <div class="education-degree">Ph.D. in Civil Engineering, 2021 - Present (expected 2026)</div>
          <div class="education-meta">Advisor: <a href="https://cee.illinois.edu/directory/profile/tutumlue">Professor Erol Tutumluer</a> | GPA: 4.0 / 4.0</div>
        </li>
        <li>
          <div class="education-degree">M.S. in Civil Engineering, 2019 - 2021</div>
          <div class="education-meta">Advisor: <a href="https://cee.illinois.edu/directory/profile/tutumlue">Professor Erol Tutumluer</a> | GPA: 3.98 / 4.0</div>
        </li>
      </ul>
    </li>
    <li class="education-entry">
      <div class="education-school">Zhejiang University</div>
      <ul class="education-degrees">
        <li>
          <div class="education-degree">B.E. in Harbor, Waterway, and Coastal Engineering, 2016 - 2020</div>
        </li>
      </ul>
    </li>
  </ul>
</div>
