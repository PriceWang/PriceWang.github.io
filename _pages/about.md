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

Guoxin Wang is a Research Fellow at Trinity College Dublin. His research interests span edge computing, dynamic inference, computer vision, multimodal alignment, and model interpretability. He focuses on developing efficient, adaptive, and trustworthy intelligent systems for resource-constrained environments, with particular interest in model efficiency, cross-modal representation learning, and explainable AI. His work aims to enable robust perception and decision-making on wearable, mobile, and edge platforms. He completed his PhD at University College Dublin, supervised by Avishek Nag and Deepu John. He has published high quality papers at the top international journals with google scholar citations <a href='https://scholar.google.com/citations?user=yo7t7CIAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

---

# 🔥 News

<title>Events</title>
<div class="bottom_box">
  <ul class="events">
    <li data-date="03/2026"> - New paper accepted: <i><a href=''>MoCrop: Training Free Motion Guided Cropping for Efficient Video Action Recognition</a></i>. </li>
    <li data-date="01/2026"> - New paper accepted: <i><a href=''>TinyDrop: Tiny Model Guided Token Dropping for Vision Transformers</a></i>. </li>
    <li data-date="12/2025"> - New paper accepted: <i><a href='https://ieeexplore.ieee.org/abstract/document/11426826/'>Dynamic Model Mixtures for Efficient AI Inference in Real-Time Biomedical Applications</a></i>. </li>
    <li data-date="11/2025"> - Start a new position: Research Fellow at Trinity College Dublin. </li>
    <li data-date="10/2025"> - Obtain a new certification: <i><a href='https://catalog-education.oracle.com/pls/certview/sharebadge?id=F7E62ECE7EDCB12733A43D57A256FC0BC39828F2737B9FCC7B20DF491682D955'>Oracle AI Vector Search Certified Professional</a></i>. </li>
    <li data-date="10/2025"> - Obtain a new certification: <i><a href='https://catalog-education.oracle.com/pls/certview/sharebadge?id=D1AC30496B8C354B2B97469AFBE23D1D21CA07DE13A0571490C4D4414F1B25C8'>Oracle Cloud Infrastructure 2025 Certified Generative AI Professional</a></i>. </li>
    <li data-date="10/2025"> - Obtain a new certification: <i><a href='https://www.coursera.org/account/accomplishments/professional-cert/certificate/24N394MQFZ09'>Google Advanced Data Analytics</a></i>. </li>
    <li data-date="10/2025"> - Obtain a new certification: <i><a href='https://www.coursera.org/account/accomplishments/professional-cert/certificate/2CKUJW2AAZFK'>Google IT Automation with Python</a></i>. </li>
    <li data-date="09/2025"> - Obtain a new certification: <i><a href='https://huggingface.co/datasets/agents-course/final-certificates/resolve/main/certificates/PriceWang/2025-09-25.png'>Hugging Face Agents Course</a></i>. </li>
    <li data-date="09/2024"> - New paper accepted: <i><a href='https://ieeexplore.ieee.org/abstract/document/10669223/'>ECG biometric authentication using self-supervised learning for IoT edge sensors</a></i>. </li>
    <li data-date="06/2024"> - Start a new position: Postdoc at University College Dublin. </li>
    <li data-date="05/2024"> - New paper accepted: <i><a href='https://ieeexplore.ieee.org/abstract/document/10541906/'>A task-generic high-performance unsupervised pre-training framework for ECG</a></i>. </li>
    <li data-date="10/2023"> - New paper accepted: <i><a href='https://ieeexplore.ieee.org/abstract/document/10388636/'>Unsupervised pre-training using masked autoencoders for ecg analysis</a></i>. </li>
    <li data-date="03/2021"> - New paper accepted: <i><a href='https://ieeexplore.ieee.org/abstract/document/9401741/'>Continuous user authentication using iot wearable sensors</a></i>. </li>
    <li data-date="09/2020"> - New paper accepted: <i><a href='https://ieeexplore.ieee.org/abstract/document/9332012/'>Low complexity ecg biometric authentication for iot edge devices</a></i>. </li>
    <li data-date="12/2019"> - Obtained a new certification: <i><a href='https://www.coursera.org/account/accomplishments/specialization/certificate/XK69QTLWMM6K'>Deep Learning Specialization</a></i>. </li>
  </ul>
</div>

# 📝 Publications

{% include_relative pubs.md %}

# 🔍 Service

- Reviewer for IEEE Transactions on Instrumentation and Measurement.
- Reviewer for IEEE Sensors Journal.
- Reviewer for IEEE Transactions on Biomedical Circuits and Systems.

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
