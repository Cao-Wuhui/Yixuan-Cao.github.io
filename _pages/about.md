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

I am a Ph.D. student at the [School of Computer Science](https://cs.nju.edu.cn/cs_en/main.htm), Nanjing University, advised by Prof. [Yanyan Jiang](https://jiangyy.github.io/). My research interests lie broadly in software systems. As intelligent agents become active participants in software development and maintenance, I am interested in how they can understand, reason about, and evolve complex software systems, enabling more reliable and efficient software engineering.

Previously, I received my B.S. and M.S. degrees from the [College of Computer Science and Software Engineering](https://csse.szu.edu.cn/), Shenzhen University, where I was advised by Prof. [Yuhong Feng](https://scholar.google.com/citations?user=29WXQ_sAAAAJ) and Prof. [Xu Wang](https://scholar.google.com/citations?user=XNDHhIEAAAAJ). I worked extensively on system software and security. I have contributed to the [Linux kernel](https://git.kernel.org/pub/scm/linux/kernel/git/next/linux-next.git/log/?qt=author&q=caoyixuan2019) and [LLVM](https://github.com/llvm/llvm-project/pulls?q=is%3Apr+author%3ACao-Wuhui) communities, including enhancements to [page_owner](https://docs.kernel.org/mm/page_owner.html), a Linux kernel memory debugging infrastructure, and [AddressSanitizer](https://clang.llvm.org/docs/AddressSanitizer.html), a memory safety tool. I have also conducted research on software reliability and contributed to vulnerability discovery and disclosure in open-source software systems. Additionally, I was selected as a [Huawei Developer Advocate](https://developer.huawei.com/home/program/advocates/member/7f07f1011f7d48b0bc989f8712919d79) in 2024 and a [Huawei Cloud Student Developers (HCSD) Campus Ambassador](https://developer.huaweicloud.com/program/hcsd/personal?applicationId=046f0ef1ac31471f84b97acadc709be5) in 2025.

Collaborations and discussions are warmly welcomed — feel free to reach out!

# 📝 Publications
- **Yixuan Cao**, Yuhong Feng<sup>†</sup>, Huafeng Li, Chongyi Huang, Fangcao Jian, Haoran Li, Xu Wang. Tech-ASan: Two-stage check for Address Sanitizer. Proceedings of the 16th International Conference on Internetware, 2025. [paper](https://doi.org/10.1145/3755881.3755918) [slides and video](https://conf.researchr.org/details/internetware-2025/internetware-2025-research-track/38/Tech-ASan-Two-stage-check-for-Address-Sanitizer) [dataset](https://github.com/Hufffman/Adjusted-Juliet-Test-Suite)
- Yufeng Wang, Yuhong Feng<sup>†</sup>, **Yixuan Cao**, Haoran Li, Haiyue Feng, Yifeng Wang. ORCAS: Obfuscation-Resilient Binary Code Similarity Analysis using Dominance Enhanced Semantic Graph. Proceedings of the 34th ACM International Conference on Information and Knowledge Management, 2025. [paper](https://dl.acm.org/doi/10.1145/3746252.3761266) [slides](/files/CIKM2025.pdf) [dataset](https://github.com/Cao-Wuhui/ORCAS)
- Qiuming Luo, Yanming Lei<sup>†</sup>, Kunzhong Wu, **Yixuan Cao**, Chengjian Liu. AutoFSM: A Multi-Agent Framework for FSM Code Generation with IR and SystemC-Based Testing. Proceedings of the 32nd International Conference on Neural Information Processing, 2025. [paper](https://link.springer.com/chapter/10.1007/978-981-95-4088-4_29)
- Yuhong Feng<sup>†</sup>, Fangcao Jian, **Yixuan Cao**, Xiaobin Jian, Jia Wang, Haiyue Feng, Chunyan Miao. Efficient Candidate-Free R-S Set Similarity Joins with Filter-and-Verification Trees on MapReduce. Preprint, 2025. [paper](https://doi.org/10.48550/ARXIV.2506.03893)
- Yuhong Feng, Haoran Li<sup>†</sup>, **Yixuan Cao**, Yufeng Wang, Haiyue Feng. CRABS-former: CRoss-Architecture Binary Code Similarity Detection based on Transformer. Proceedings of the 15th Asia-Pacific Symposium on Internetware, 2024. [paper](https://doi.org/10.1145/3671016.3671390)

*\* Equal contribution. † Corresponding author.*

# 📖 Educations
- *2026.09 - Present*, Ph.D., Computer Science and Technology, Nanjing University.
- *2023.09 - 2026.07*, M.S., Computer Science and Technology, Shenzhen University.
- *2019.09 - 2023.07*, B.S., Computer Science and Technology (Honor), Shenzhen University.

# 💼 Experiences
- *2025.06 - 2025.09*, Internship, Huawei Technologies Co., Ltd. *(Outstanding Intern, Top 20%)*

# 👨‍🏫 Teaching
**Instructor**
- Java Programming, [College of Continuing Education](https://en.szu.edu.cn/info/1017/1014.htm), Shenzhen University (Spring 2026)

**Teaching Assistant**
- Systems Programming, College of Computer Science and Software Engineering, Shenzhen University (2026 Spring, 2024 Spring, 2023 Fall)
- Design and Analysis of Algorithms, College of Computer Science and Software Engineering, Shenzhen University (2023 Spring)
- Computer Systems (3), College of Computer Science and Software Engineering, Shenzhen University (2022 Fall)

# 🏅 Honors & Awards
**Personal Honors**
- [2024] Huawei Developer of the Year – Pioneer Project Award *(only 15 awardees worldwide)*
- [2023] Top 100 Outstanding Undergraduate Thesis (Design), Shenzhen University *(96 of 6,615 graduates)*
- [2023] Outstanding Undergraduate Graduate, Shenzhen University

**Scholarship**
- [2025/2024/2023] SZU Master's Academic Scholarship: Special Class (2023), First Class (2024, 2025)
- [2024/2023/2022] Ministry of Education – Huawei Intelligent Base "Future Star" Scholarship
- [2023] openEuler Open Source Contribution Elite Scholarship *(only 13 awardees worldwide)*
- [2023] Star of SZU Scholarship, Shenzhen University *(top 1%)*
- [2023] Innovation & Entrepreneurship Star, First Prize, Shenzhen University

**Competition Awards**
- [2024] China International College Students' Innovation Competition, Guangdong Provincial Silver Award
- [2024] Huawei Software Elite Challenge 2024, Guangdong–Hong Kong–Macao Regional Second Prize
- [2023] Lanqiao Cup Programming Contest (Java Software Development), National Finals Second Prize
- [2022] The 4th National Collegiate Algorithm Design and Programming Challenge (Autumn), Excellence Award
- [2022] China Undergraduate Mathematical Contest in Modeling (CUMCM), Guangdong Provincial Second Prize
- [2021] Mathematical Contest in Modeling (MCM/ICM), Honorable Mention
- [2020] National Undergraduate Mathematics Competition (Non-Mathematics Major), First Prize

# 🐛 CVEs
- [CVE-2025-69720](https://www.cve.org/CVERecord?id=CVE-2025-69720): Stack-based buffer overflow in GNU ncurses. [advisory](https://github.com/Cao-Wuhui/CVE-2025-69720)

*More vulnerability disclosures are pending due to responsible disclosure timelines.
Stay tuned.*

# 📰 Reports
- [02/2024] [Student Feature | Yixuan Cao: Be Your Own Leader and Care for Others](https://mp.weixin.qq.com/s/bH_c5B2hyO-gAi1lKpiijw) <br>
  WeChat official account of the College of Computer Science and Software Engineering, Shenzhen University, with about 3,000 views.
- [11/2022] [My Story with the Intelligent Base](https://www.huawei.com/cn/huaweitech/industry-ecosystem/ascend-ai-developers) <br>
  Huawei official website.

<!-- # 🌍 Visiting Record -->

<div style="width: 600px; margin: 0 auto; display: none;">
<script type='text/javascript' id='mapmyvisitors' src='https://mapmyvisitors.com/map.js?cl=080808&w=a&t=n&d=l3UsKXXGpPWF-Pnbz4u6lLHStPnv8vHiVVCeCTWg-Wo&co=ffffff&ct=808080&cmo=3acc3a&cmn=ff5353'></script>
</div>

<br/>
