---
permalink: /
title: ""
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

# Welcome!

I am a Master’s student in the Computer Science Department at Western University. My research interest includes **Human Centered Computing**, **3D Computer Vision**, **Multi-modal Machine Learning**, **Computational Social Science** and **Health Informatics**. My work explores the intersection of computer science, data analytics, and AI applications, utlizing interdisciplinary approaches to enhance user experiences and healthcare outcomes. I am particularly interested in developing innovative solutions that bridge technology and human well-being. I am passionate about using emerging technologies to solve complex real-world challenges while ensuring solutions remain accessible and user-friendly.

In 2024, I worked as an AI4Education Research Assistant at the [Suzhou Research Institute of National University of Singapore](http://en.nusri.cn/). My research centered on leveraging AI to enhance educational outcomes, specifically in coding education and assessment. 

From 2023 to 2024, I served as an Undergraduate Research Assistant at Soochow University, contributing to multimodal fake news detection via fine-grained semantic consistency [Guobiao Zhang](https://scholar.google.com/citations?hl=en&user=9063vvMAAAAJ). I helped designed and implemented a detection model integrating BERT for text representation, Faster R-CNN with an attention mechanism for extracting fine-grained visual features, and CLIP for global image-text alignment.

In 2023, I was honored to be selected for the [Mitacs Globalink Research Internship](https://www.mitacs.ca/our-programs/globalink-research-internship-students/), where I collaborated with Assistant Professor [Matthew Hamilton](https://scholar.google.com/citations?user=PWi6hlkAAAAJ&hl=en) in Memorial University of Newfoundland. My work focused on the Light Field project and enhanced holographic imagery simulation using CUDA parallel computing, showcasing my technical expertise and innovative problem-solving skills.

From 2022 to 2023, I collaborated with Associate Professor [Xi Cheng](https://www.researchgate.net/profile/Xi_Cheng65) at Soochow University to explore the impact of Open Peer Review on Citations and Altmetrics. I utilized Python web scraping to collect extensive data from Nature Communications and PLoS One, employed an LM Linear Regression model in R to analyze the correlation between citation counts and time.

You can find my detailed CV here: [**William's Curriculum Viate**](https://william-hrwang.github.io/_pages/CV.pdf). If you are interested in my work, please feel free to drop me an email. 

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.04*: &nbsp;🎉🎉 Our new paper, "*Open peer review correlates with altmetrics but not with citations: Evidence from Nature Communications and PLoS One*" has been accepted for publication in Journal of Informetrics.
- *2024.02*: &nbsp;I am excited to announce that I was admitted as an AI4Education research intern at the Suzhou Research Institute of National University of Singapore.
- *2023.09*: &nbsp;🎉🎉 Our new paper, "*Improved Simulated Viewing of Holographic Imagery*" was accepted for presentation at the 32nd Annual Newfoundland Electrical and Computer Engineering Conference.
- *2022.07*: &nbsp;🎉🎉 Our paper, "*Research on the Impact of Scientific Publications under Open Science*" was accepted for the 2022 International Association for Media and Communication Research (Suzhou Pre-conference).
- *2022.07*: &nbsp;🎉🎉 Our paper, "*Rapid Response in an Uncertain Environment: Study of COVID-19 Scientific Research Under the Parallel Model*" has been accpeted for publication in Risk Management and Healthcare Policy.


# 📝 Publications 

<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">Journal of Infometrics</div>
<img src='images/opr.png' alt="open peer review" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[Open peer review correlates with altmetrics but not with citations: Evidence from Nature Communications and PLoS One](https://doi.org/10.1016/j.joi.2024.101540)

Xi Cheng, **Haoran Wang**, Li Tang, Weiyan Jiang, Maotian Zhou, Guoyan Wang

[**Project**](https://github.com/william-hrwang/NC-PO-OpenPeerReview) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span> | SCI Journal Paper </strong>

- Build a large extensive dataset about Open Peer Review, Altmetrics and Citations, leading to a future study in Bibliometrics field
- Utilize big data analysis to demonstrate that open peer review increases public and media visibility of scientific work, despite not significantly impacting citation-based academic recognition.

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">NECEC 2023</div>
<img src='images/light-field.png' alt="light field" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[Improved Simulated Viewing of Holographic Imagery](https://william-hrwang.github.io/_pages/NECEC.pdf)

Nicholas Wells, Devender Singh, **Haoran Wang**, Amilcar Soare, Matthew Hamilton, Oscar Meruvia-Pastor

<strong> IEEE Conference | Mitacs Globalink Research Internship</strong>

- Employ CUDA parallel computing to integrate a Gaussian Blur-based model into a light field display simulation, enhancing its ability to accurately replicate the light leakage phenomenon in physical 3D display.
- Develop and implement a standardized testing procedure to enhance the efficiency and repeatability of assessments for light field images and compression designs.
- Enhance the graphical user interface (GUI) by implementing Dear ImGui in C++

</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
<div>
<div class="badge">Risk Management and Healthcare Policy</div>
<img src='images/health.jpg' alt="light field" width="100%">
</div>
</div>

<div class='paper-box-text' markdown="1">

[Study of COVID-19 Scientific Research Under the Parallel Model](https://www.dovepress.com/rapid-response-in-an-uncertain-environment-study-of-covid-19-scientifi-peer-reviewed-fulltext-article-RMHP)

Xi Cheng, Qiyuan Chen, Li Tang, Yue Wu, **Haoran Wang**, Guoyan Wang

<strong> SSCI Journal</strong>

- Take an active role in the acquisition, curation, and meticulous pre-processing of research datasets from  Web of Science and PubMed, ensuring data accuracy and comprehensiveness
- Utilize advanced analytical tools like VosViewer to conduct in-depth knowledge graph analysis, demonstrating the existence of a parallel model of COVID-19 scientific research.


</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2023.05* &nbsp;International Mathematical Contest in Modeling: Finalist in Interdisciplinary Contest in Modeling (Top 1%)
- *2023.05* &nbsp;Mitacs Globalink Research Internship Award (Top 200 students in China)
- *2023.05* &nbsp;Visiting Undergraduate Student funded by China Scholarship Council (Top 200 students in China)
- *2023.05* &nbsp;"Huashu Cup" International University Student Mathematical Modeling Competition: Grand Prize (Top 5%)
- *2022.09* &nbsp;First-class Scholarship for Academic Excellence in Sophomore (Top 9%)
- *2021.09* &nbsp;First-class Scholarship for Academic Excellence in Freshman (Top 9%)



# 📖 Educations
- *2024.09 - 2025.8 (Expected)*, Western University
  - Master of Computer Science (Score: **92.5**/100)
- *2020.09 - 2024.07*, Soochow University
  - Bachelor of Art in Network and New Media (GPA: **3.9**/4.0, Ranking: 1/92) 
  - Minor Degree in Software Engineering
  - Micro-Major Project in Intelligent Computing and Frontier Applications

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.09 - 2024.02*, [Suzhou Research Institute of National University of Singapore](http://en.nusri.cn/), China.
- *2023.09 - 2024.02*, [BOSCH](https://www.bosch.com.cn/en/our-company/bosch-in-china/bosch-automotive-products-suzhou/), China.
- *2022.07 - 2022.08*, [Bank of Communications](https://www.bankcomm.com/BankCommSite/shtml/jyjr/en/2600212/list.shtml?channelId=2600212), China.
