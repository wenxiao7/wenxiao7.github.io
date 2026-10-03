---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>
# 💻 About Me
I am Wenxiao Zhao, a second-year Master's student in the Department of Statistics & Data Science, University of California Los Angeles, advised by [Prof. Ying Nian Wu](http://www.stat.ucla.edu/~ywu/). I received my B.Eng in Computer Science and Engineering at the Chinese University of Hong Kong in 2024, advised by [Prof. Baoxiang Wang](https://bxiangwang.github.io/).

My research focuses on **large language models and reinforcement learning**, especially preference optimization, strategic reasoning, and multi-agent systems. My recent work also explores scientific discovery and evidence-grounded evaluation. I am additionally interested in robotics.

<p>
  I'm eager to collaborate on exciting research or projects. Please feel free to contact me at 
  <a href="mailto:wenxiao0367@ucla.edu" style="text-decoration: underline;">wenxiao0367@ucla.edu</a> if you're interested.
</p>


<span class="anchor" id="publications"></span>
# 📝 Publications

My recent work on language-model reasoning, learning, and agent systems. See [Google Scholar](https://scholar.google.com/citations?user=J1U0aPkAAAAJ&hl=en) for the full publication list and current citations.

## Conference Papers

{% assign papers = site.data.publications | where: "category", "conference" %}
{% for paper in papers %}
{% include publication.html paper=paper %}
{% endfor %}

## Workshop Papers

{% assign papers = site.data.publications | where: "category", "workshop" %}
{% for paper in papers %}
{% include publication.html paper=paper %}
{% endfor %}

## Preprints

{% assign papers = site.data.publications | where: "category", "preprint" %}
{% for paper in papers %}
{% include publication.html paper=paper %}
{% endfor %}

<span class="anchor" id="honors-and-awards"></span>
# 🎖 Honors and Awards
- Bowen First Class Scholarship, The Chinese University of Hong Kong(SZ).
- Third Prize, The 13th Chinese Mathematics Competitions(CMC), AY2021.
- Undergraduate Research Awards, The Chinese University of Hong Kong(SZ), 19th Round & 23rd Round.
- Excellent Peer Advisor, School of Data Science, The Chinese University of Hong Kong(SZ), AY2023.

<span class="anchor" id="education"></span>
# 📖 Education
- Sep 2024-June 2026 (Expected), M.S in Statistics, Department of Statistics & Data Science, University of California Los Angeles.
- Sep 2020 – July 2024, B.Eng in Computer Science and Engineering, School of Data Science, The Chinese University of Hong Kong(SZ).

<p></p>
<br><br> <!-- two blank lines -->
<p></p>

