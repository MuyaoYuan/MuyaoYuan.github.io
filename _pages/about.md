---
permalink: /
title: "Muyao Yuan"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.pub-item {
  display: flex;
  gap: 24px;
  align-items: center;
  padding-bottom: 28px;
  margin-bottom: 28px;
}

/* 只在中间的 item 加分割线 */
.pub-item:not(:last-child) {
  border-bottom: 1px solid #eee;
}

.pub-image {
  flex-shrink: 0;
}

.pub-image img {
  width: 220px;
  display: block;
}

.pub-content {
  font-size: 16px;
  line-height: 1.6;
}

/* ===== 标题：使用主题默认链接颜色 ===== */
.pub-title {
  font-size: 18px;
  font-weight: 600;
  text-decoration: none;   /* 不强制蓝色 */
}

.pub-title:hover {
  text-decoration: underline;
}

/* ===== 作者 & venue：item 点（桌面 + 手机） ===== */
.pub-meta span {
  display: block;
  position: relative;
  padding-left: 14px;
}

.pub-meta span::before {
  content: "•";
  position: absolute;
  left: 0;
  color: #999;
}

/* ===== 按钮（仅桌面显示） ===== */
.pub-button {
  display: inline-block;
  padding: 6px 12px;
  background: #333;
  color: #fff;
  border-radius: 4px;
  text-decoration: none;
  margin-right: 10px;
  font-size: 14px;
}

/* ===== 手机端 ===== */
@media (max-width: 768px) {
  .pub-item {
    flex-direction: column-reverse;
    align-items: flex-start;
  }

  .pub-image img {
    width: 100%;
    max-width: 420px;
  }

  /* 手机端隐藏按钮 */
  .pub-button {
    display: none;
  }
}
</style>

I am **Muyao Yuan** (袁慕遥), a Ph.D. candidate in the MOEKLINNS Lab at Xi'an Jiaotong University, under the guidance of [Prof. Weizhan Zhang](https://gr.xjtu.edu.cn/en/web/zhangwzh123). My research interests include **model compression**, **model adaptation**, and **MLLM**.

---

🔥 News
======
- 📅 **[2025.11]** 🎉 Our paper titled _“InfoCLIP: Bridging Vision-Language Pretraining and Open-Vocabulary Semantic Segmentation via Information-Theoretic Alignment Transfer”_ has been accepted by **AAAI 2026**!
- 📅 **[2025.05]** 🎉 Our paper titled _“InfoSAM: Fine-Tuning the Segment Anything Model from an Information-Theoretic Perspective”_ has been accepted as a **Spotlight Poster** at **ICML 2025**!

---

📝 Publications
======
<div class="pub-item">
  <div class="pub-image">
    <img src="/images/infoclip.svg">
  </div>
  <div class="pub-content">
    <a class="pub-title" href="https://muyaoyuan.github.io/InfoCLIP-Page/">
      InfoCLIP: Bridging Vision-Language Pretraining and Open-Vocabulary Semantic Segmentation via Information-Theoretic Alignment Transfer
    </a>
    <div class="pub-meta">
      <span><b>M. Yuan</b>, Y. Zhang, W. Zhang, L. Ma, Y. Gao, J. Ying, Y. Xin</span>
      <span><i>AAAI Conference on Artificial Intelligence (AAAI), 2026</i></span>
    </div><br>
    <a class="pub-button" href="https://muyaoyuan.github.io/InfoCLIP-Page/">Project Page</a>
    <a class="pub-button" href="https://arxiv.org/pdf/2511.15967">PDF</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-image">
    <img src="/images/infosam.svg">
  </div>
  <div class="pub-content">
    <a class="pub-title" href="https://muyaoyuan.github.io/InfoSAM_Page/">
      InfoSAM: Fine-Tuning the Segment Anything Model from an Information-Theoretic Perspective
    </a>
    <div class="pub-meta">
      <span>Y. Zhang*, <b>M. Yuan*</b>, W. Zhang, T. Gong, W. Wen, J. Ying, W. Shi</span>
      <span><i>International Conference on Machine Learning (ICML Spotlight), 2025</i></span>
    </div><br>
    <a class="pub-button" href="https://muyaoyuan.github.io/InfoSAM_Page/">Project Page</a>
    <a class="pub-button" href="https://openreview.net/pdf?id=VpBBw1bL47">PDF</a>
    <a class="pub-button" href="https://github.com/MuyaoYuan/InfoSAM">Code</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-image">
    <img src="/images/ats-detr.svg">
  </div>
  <div class="pub-content">
    <a class="pub-title" href="https://doi.org/10.1016/j.knosys.2024.112036">
      Adaptive Token Selection for Efficient Detection Transformer with Dual Teacher Supervision
    </a>
    <div class="pub-meta">
      <span><b>M. Yuan</b>, W. Zhang, C. Yan, T. Gong, Y. Zhang, J. Ying</span>
      <span><i>Knowledge-Based Systems (KBS), 2024</i></span>
    </div><br>
    <a class="pub-button" href="https://doi.org/10.1016/j.knosys.2024.112036">PDF</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-image">
    <img src="/images/LCA.png">
  </div>
  <div class="pub-content">
    <a class="pub-title" href="https://ieeexplore.ieee.org/document/10829727">
      Lightweight Configuration Adaptation with Multi-teacher Reinforcement Learning for Live Video Analytics
    </a>
    <div class="pub-meta">
      <span>Y. Zhang, W. Zhang, <b>M. Yuan</b>, L. Xu, C. Yan, T. Gong, H. Du</span>
      <span><i>IEEE Transactions on Mobile Computing (TMC), 2025</i></span>
    </div><br>
    <a class="pub-button" href="https://ieeexplore.ieee.org/document/10829727">PDF</a>
  </div>
</div>

---

🛠 Projects
======
<div class="pub-item">
  <div class="pub-image">
    <img src="/images/project_MLLM.svg">
  </div>
  <div class="pub-content">
    <a class="pub-title" href="/portfolio/portfolio-1">
      Efficient Training and Inference of Multimodal Foundation Models
    </a>
    <div class="pub-meta">
      <span>Multimodal foundation models, efficient training and inference</span>
    </div><br>
    <a class="pub-button" href="/portfolio/portfolio-1">Project Page</a>
  </div>
</div>

<div class="pub-item">
  <div class="pub-image">
    <img src="/images/project_compression.png">
  </div>
  <div class="pub-content">
    <a class="pub-title" href="/portfolio/portfolio-2">
      Lightweight and Efficient Model Design for Diverse Tasks
    </a>
    <div class="pub-meta">
      <span>Model compression and efficient architecture design</span>
    </div><br>
    <a class="pub-button" href="/portfolio/portfolio-2">Project Page</a>
  </div>
</div>

---

💡 Selected Patents
======
  - Resource-Efficient Training for MLLMs via Adaptive Data Filtering
  - Efficient Collaborative Inference for Autoregressive MLLMs
  - Device and Edge Collaborative Personalized Inference for MLLMs with Heterogeneous Resources
  - Efficient MLLM Training via Expanded Pipeline Stages
  - Self-Driven Feedback and Symbolic Collaboration for MLLM Inference
  - LoRA and MoE-Based Fine-Tuning for MLLMs
  - Elastic Architecture Design and Pruning for MLLMs with Heterogeneous Experts
  - Efficient MLLM Initialization via Weight Inheritance

---

🏆 Selected Awards
======
  - Special Class Academic Scholarship, Xi’an Jiaotong University, 2025.
  - Excellent Postgraduate, Xi’an Jiaotong University, 2025.
  - Outstanding Graduate, Xi’an Jiaotong University, 2022. [[Certificate]](/images/Outstanding_Graduate.jpg)  
  - First Prize Scholarship, Xi’an Jiaotong University, 2020. [[Certificate]](/images/First_Prize_Scholarship.jpg)  
  - National Second Prize, WeChat Mini Program Development Competition, 2020. [[Certificate]](/images/wechat.jpg)  
  - Samsung Scholarship, 2019. [[Certificate]](/images/Samsung_Scholarship.jpg)  
  - National Second Prize, Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM), 2019. [[Certificate]](/images/cumcm.jpg)  
  - First Prize, Chinese Physics Olympiad (CPhO), 2017. [[Certificate]](/images/CPhO.jpg)  

---

📖 Educations
======
- **2022.09 – now**, Xi'an Jiaotong University —  PhD Candidate in Computer Science  
  • Supervisor: Prof. Weizhan Zhang  

- **2018.09 – 2022.06**, Xi'an Jiaotong University — B.S. in Automation  
  • GPA: 4.0/4.3 (Ranked 1th out of 180)  [[Transcript]](/images/transcript.jpg)

---

🏢 Internships
======
- **2023.10 – 2024.11**, China Telecom Artificial Intelligence Technology, Beijing.
- **2025.10 – 2025.11**, E-surfing Vision Technology, Shanghai.

---

🎓 Academic Service
======
- Reviewer for CVPR, AAAI, TMC, Neural Computation, Neural Networks.
