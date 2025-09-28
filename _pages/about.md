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

<span class='anchor' id='about'></span>

Guoxin Wang is a Postdoctoral Researcher in the School of Electrical & Electronic Engineering at University College Dublin. His research focuses on self- and unsupervised representation learning for physiological time-series, especially electrocardiogram (ECG), and on deploying robust analytics for wearable and edge devices. He co-authored an MAE-based pretraining framework for ECG analysis (IEEE Sensor Journal) and developed an ECG biometric authentication approach using self-supervised learning for IoT edge sensors (2024). Earlier, he worked on continuous user authentication using a genuine wearable chest-strap ECG device (ISCAS 2021). He completed his PhD at UCD, supervised by Avishek Nag and Deepu John.

His research interest includes self-/unsupervised learning for physiological time-series (ECG); wearable sensing and edge AI; efficient deployment (quantization, pruning) and dynamic neural network. He has published high quality papers at the top international journals with google scholar citations <a href='https://scholar.google.com/citations?user=yo7t7CIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

---

# 🔥 News

<title>Events</title>
<div class="bottom_box">
  <ul class="events">
    <li data-date="09/2025"> - Obtained a new <a href='https://huggingface.co/datasets/agents-course/final-certificates/resolve/main/certificates/PriceWang/2025-09-25.png'>certification</a>: <i>Hugging Face Agents Course</i>. </li>
    <li data-date="12/2024"> - Complete PhD program. </li>
    <li data-date="09/2024"> - One <a href='https://ieeexplore.ieee.org/abstract/document/10669223/'>paper</a> accepted by <i>IEEE Journal of Biomedical and Health Informatics</i>. </li>
    <li data-date="06/2024"> - Start a new position as Postdoc at University College Dublin. </li>
    <li data-date="05/2024"> - One <a href='https://ieeexplore.ieee.org/abstract/document/10541906/'>paper</a> accepted by <i>IEEE Sensors Journal</i>. </li>
    <li data-date="10/2023"> - One <a href='https://ieeexplore.ieee.org/abstract/document/10388636/'>paper</a> accepted by <i>2023 IEEE Biomedical Circuits and Systems Conference</i>. </li>
    <li data-date="03/2021"> - One <a href='https://ieeexplore.ieee.org/abstract/document/9401741/'>paper</a> accepted by <i>2021 IEEE International Symposium on Circuits and Systems</i>. </li>
    <li data-date="09/2020"> - One <a href='https://ieeexplore.ieee.org/abstract/document/9332012/'>paper</a> accepted by <i>2020 IEEE International Conference on Integrated Circuits, Technologies and Applications</i>. </li>
    <li data-date="12/2019"> - Obtained a new <a href='https://www.coursera.org/account/accomplishments/specialization/XK69QTLWMM6K'>certification</a>: <i>Deep Learning Specialization</i>. </li>
  </ul>
</div>

# 📝 Publications

{% include_relative pubs.md %}

# 🔍 Service

- Reviewer for IEEE transactions on biomedical circuits and systems.

<!-- # 🎖 Honors and Awards

<ul class="honors-list honors-has-logo">
  <li>
    <span class="honor-year">2025</span>
    <span class="honor-logos logos-center">
      <span class="logo-chip">
        <img class="honor-logo" src="images/logos/crunch.png" alt="Crunch">
      </span>
      <img class="honor-logo" src="images/logos/schmidt.png" alt="The Eric and Wendy Schmidt Center">
    </span>
    <span class="honor-title">Autoimmune Disease Machine Learning Challenge #1</span>
    <span class="honor-rank rank-top3">3rd place</span>
  </li>
  <li>
    <span class="honor-year">2023</span>
    <span class="honor-logos logos-center">
      <img class="honor-logo" src="images/logos/drivendata.svg" alt="DrivenData">
    </span>
    <span class="honor-title">DrivenData VisioMel Melanoma relapse prediction Challenge</span>
    <span class="honor-rank rank-top5">5th place</span>
  </li>
</ul> -->

# 📖 Educations

<ul class="edu-list">
  <li>
    <img src="images/ucd.png" class="edu-logo" alt="">
    <span class="edu-date">2019 - 2024 </span>
    <span class="edu-text">Ph.D in Electrical & Electronic Engineering, University College Dublin</span>
  </li>
  <li>
    <img src="images/ucd.png" class="edu-logo" alt="">
    <span class="edu-date">2015 - 2019</span>
    <span class="edu-text">B.Eng. in Internet of Things, University College Dublin</span>
  </li>
</ul>

<p>
&nbsp;
&nbsp;
<br/>
<br/>
<a href="https://www.easycounter.com/">
<img src="https://www.easycounter.com/counter.php?pricewang"
border="0" alt="HTML Counter"></a>
<i font size="3">hits since Apr. 2024</i>
</p>
