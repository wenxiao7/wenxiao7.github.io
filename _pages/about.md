---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

# 📝 Publications 
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">NAACL 2025</div>
      <img src='images/chess.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    
  [Explore the Reasoning Capability of LLMs in the Chess Testbed](https://arxiv.org/abs/2411.06655)  
  Shu Wang, Lei Ji, Renxi Wang, **Wenxiao Zhao**, Haokun Liu, Yifan Hou, Ying Nian Wu
  NAACL2025 Main Conference
  We collect a dataset named MATE, which consists of 1 million chess positions with candidate moves annotated by chess experts for strategy and tactics. We finetune the LLaMA-3-8B model and compare it against state-of-the-art commercial         language models in the task of selecting better chess moves. Our experiments show that our models perform better than GPT, Claude, and Gemini models. We find that language explanations can enhance the reasoning capability of large language    models. 
  </div>
</div>

# 🎖 Honors and Awards
- Bowen First Class Scholarship, The Chinese University of Hong Kong(SZ).
- Third price, The 13th Chinese Mathematics Competitions(CMC), AY2021.
- Undergraduate Research Awards, The Chinese University of Hong Kong(SZ), 19th Round & 23th Round.
- Excellent Peer Advisor, School of Data Science, The Chinese University of Hong Kong(SZ), AY2023.

# 📖 Educations
- * Sep 2024-June 2026 (Expected) *, M.S in Statistics, Department of Statistics & Data Science, University of California, Los Angeles.
- * Sep 2020 – July 2024*, B.Eng in Computer Science and Engineering, School of Data Science, The Chinese University of Hong Kong(SZ).

