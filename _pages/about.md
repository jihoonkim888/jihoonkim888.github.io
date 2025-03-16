---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Department of Mechanical Engineering, KAIST</a>

profile:
  align: left
  image: profile_pic_informal.jpg
  image_circular: true # crops the image to make it circular
  more_info: <p>F431, Faculty Building, </p> <p>193, Munji-ro, Yuseong-gu, </p> <p>Daejeon, Republic of Korea</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---

As an AI Researcher at [Narnia Labs](https://www.narnia.ai/) and a Ph.D. student in Mechanical Engineering at KAIST, my driving passion is to transform Generative Design from a mere conceptual tool into a practical, efficient, and innovative solution for the manufacturing challenges of the future. 

Guided by the expertise of Prof. Namwoo Kang at [Smart Design Lab](http://www.smartdesignlab.org/index.html), I am pioneering the application of deep learning techniques to revolutionize the optimization of mechanical components, focusing on manufacturability, mass production, and crucially, mechanical performance.

At [SLB (previously Schlumberger)](https://www.slb.com/), my work involved developing machine learning models that enhanced the efficiency and accuracy of oil and gas production, tackling [well construction challenges](https://www.slb.com/products-and-services/innovating-in-oil-and-gas/drilling/bottomhole-assemblies) such as [predictive steering](https://www.slb.com/products-and-services/innovating-in-oil-and-gas/drilling/bottomhole-assemblies/directional-drilling/autonomous-solutions), [drill bit optimization](https://www.slb.com/products-and-services/innovating-in-oil-and-gas/drilling/bottomhole-assemblies/drill-bits), and predictive maintenance.

Before joining KAIST, I received my [MSc degree in Data Science](https://www.bath.ac.uk/courses/postgraduate-2024/taught-postgraduate-courses/msc-data-science-with-professional-placement/) from University of Bath, UK, advised by [Dr. Wenbin Li](https://peringlab.org/), and [BEng degree in Mechanical Engineering](https://www.bristol.ac.uk/study/undergraduate/2024/mechanical-engineering/beng-mechanical-engineering/) from University of Bristol, UK.

## Featured Projects

{% if site.data.repositories.github_repos %}
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.html repository=repo %}
  {% endfor %}
</div>
{% endif %}
