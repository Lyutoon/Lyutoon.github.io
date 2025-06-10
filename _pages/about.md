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

My name is Liu Tong, a second-year PhD student in Institute of Information Engineering, Chinese Academy of Sciences, advised by Prof. [Kai Chen](https://kaichen.org) and Prof. [Guozhu Meng](https://people.ucas.ac.cn/~gzmeng). I am also a core player of the well-known CTF teams [Nu1L](https://www.nu1l.com) and [Straw Hat](https://strawhat.team).

My current research interests mainly focus on **AI security** and **software security**, with particular attention to their intersection and exploring security issues within the AI software ecosystem. My work has been published in top-tier academic and industry conferences and journals such as **CCS, USENIX Security, TOSEM, and BlackHat**.

Besides research, I am an independent bug hunter who has discovered hundreds of vulnerabilities in both open-source and closed-source software, earning acknowledgments from leading tech companies including **Apple, Google, Microsoft, Baidu, and Huawei**.


# 🔥 News
- *2025.06*: &nbsp;🎉🎉 I'll present my research as an *invited speaker* in **ISSTA LLMSC workshop**. 
- *2024.07*: &nbsp;🎉🎉 One paper accepted by **CCS 2024**. 
- *2024.05*: &nbsp;🎉🎉 One paper accepted by **USENIX Security 2024**. 
- *2024.01*: &nbsp;🎉🎉 Our talk got accepted by **BlackHat Asia 2024**. 

# 📝 Publications 

- **Demystifying RCE Vulnerabilities in LLM-Integrated Apps**  [[PDF](/papers/LLMSmith-CCS.pdf)] [[Code](https://github.com/LLMSmith/LLMSmith)]  
  <u>Tong Liu</u>, Zizhuang Deng, Guozhu Meng, Yuekang Li, Kai Chen.  
  *ACM Conference on Computer and Communications Security (**CCS**), 2024* (<span style="color:#B00C00">CCF-A</span>)   

- **Making Them Ask and Answer: Jailbreaking Large Language Models in Few Queries via Disguise and Reconstruction**  [[PDF](/papers/usenixsecurity24-liu-tong-3.pdf)] [[Code](https://github.com/LLM-DRA/DRA)] [[Video](https://www.youtube.com/watch?v=_hXBL_Wj_RM&t=3s)]  
  <u>Tong Liu</u>, Yingjie Zhang, Zhe Zhao, Yinpeng Dong, Guozhu Meng, Kai Chen.  
  *USENIX Security Symposium (**Security**), 2024* (<span style="color:#B00C00">CCF-A</span>)   

- **LLM4Shell: Discovering and Exploiting RCE Vulnerabilities in Real-World LLM-Integrated Frameworks and Apps**  [[Slides](/papers/bh-asia-2024-llm4shell-2.pdf)] [[Video](https://www.youtube.com/watch?v=LcLrG_4i19E)]  
  <u>Tong Liu</u>, Yuekang Li, Zizhuang Deng, Guozhu Meng, Kai Chen.  
  *BlackHat Asia, 2024*

- **Differential Testing of Cross Deep Learning Framework APIs: Revealing Inconsistencies and Vulnerabilities**  [[PDF](https://www.usenix.org/system/files/usenixsecurity23-deng-zizhuang.pdf)] [[Slides](https://www.usenix.org/system/files/sec23_slides_deng-zizhuang.pdf)] [[Video](https://www.youtube.com/watch?v=-Nh8eu9bVGw)]  
  Zizhuang Deng, Guozhu Meng, Kai Chen, <u>Tong Liu</u>, Lu Xiang, Chunyang Chen.  
  *USENIX Security Symposium (**Security**), 2023* (<span style="color:#B00C00">CCF-A</span>)

- **Attack as Detection: Using Adversarial Attack Methods to Detect Abnormal Examples**  [[PDF](/papers/TOSEM23)]  
  Zhe Zhao, Guangke Chen, <u>Tong Liu</u>, Taishan Li, Fu Song, Jingyi Wang, Jun Sun.  
  *ACM Transactions on Software Engineering and Methodology (**TOSEM**)* (<span style="color:#B00C00">CCF-A</span>)

# 🎖 Honors and Awards

## 🛡️ Bug Bounty & Security Research
- **Bug Bounty and Acknowledgements** from leading tech companies including Apple, Microsoft, Google, Huawei, and Baidu etc.
- Discovered and reported **40+ CVEs** in AI infrastructures (Deep learning libraries, LLM-integrated frameworks, etc.)

## 🏆 Selected CTF & AI Competitions

| Achievement | Team |
|:------------|-----:|
| **4th Place**, DEFCON CTF Qual 2024 |  Straw Hat |
| **5th Place**, DEFCON CTF Final 2024 |  Straw Hat |
| **1st Place**, ByteAI 2024 |  suibianwanwan |
| **5th Place**, DEFCON CTF Final 2023 |  Straw Hat |
| **6th Place**, DEFCON CTF Qual 2023 |  Straw Hat |
| **1st Place**, D3CTF 2022 |  Nu1L |
| **3rd Place**, 0CTF 2022 |  Straw Hat |
| **7th Place**, DEFCON CTF Final 2022 |  Straw Hat |
| **8th Place**, DEFCON CTF Qual 2022 |  Straw Hat |
| **1st Place**, CVPR 2022 Workshop-Track II Phase I |  ShanghaiTech-S3L |
| **5th Place**, CVPR 2022 Workshop-Track II Phase II |  ShanghaiTech-S3L |
| **7th Place**, 0CTF 2021 Final |  Nu1L |
| **7th Place**, DEFCON CTF 2021 Final |  Nu1L |

# 📖 Educations
- *2023.09 - now*, Ph.D, Institute of Information Engineering, Chinese Academy of Sciences; School of Cyber Security, University of Chinese Academy of Sciences.
- *2019.09 - 2023.06*, ShanghaiTech University, SIST. 

# 💬 Invited Talks
- *2025.06*, Invited speaker, ISSTA LLMSC workshop 2025.
- *2025.03*, LLM Security, Aliyun WhiteHat Conference 2025.
- *2024.08*, New Security Exploitations in the Era of LLMs, CTFCON 2024.
- *2024.04*, LLM4Shell, BlackHat Asia 2024. 
