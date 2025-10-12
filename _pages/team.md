---
permalink: /team/
title: "Team"
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



<img src="{{ '/images/logo.svg' | relative_url }}" alt="">

# <font color="#2B6ADD"> Welcome to Visual Intelligence and Multimedia (VIM) Group !</font>

<p style="text-align: justify;font-family: Roboto;">

VIM@IMAG, focus on Visual and Intelligence Multimedia, is a group of the <a href="https://imag-njust.net/">Intelligent Media Analysis Group (IMAG)</a> built by the chief leader of Prof. <a href="https://v2.imag-njust.net/people/user/tangjinhui/">Jinhui Tang</a>. The leader of VIM@IMAG is <a href="https://shuxb104.github.io/">Xiangbo Shu</a>, a Professor at the School of Computer Science and Engineering, Nanjing University of Science and Technology, China. Based on IMAG, the primary goal of VIM@IMAG is to break through bottlenecks and to make hardcore innovations in human-centric vision problems, including Visual Perception, Visual Understanding, Model Deployment. Our team members are as follows.

</p>

<span class='anchor' id='team'></span>

<style>
  table {
    border-collapse: collapse;
  }
  table, th, td {
    border-color: transparent;
  }

  .row > .col {
    margin-bottom: 1rem; /* 或 24px / 2rem 自行调 */
  }

  .card-body {
    padding:0.75rem 1rem;
    margin-bottom: 0rem;
    padding-bottom: 0rem;
  }

  .card-img {
    width: 130px;
    height:180px;
    border-radius: 8px;
    object-fit: cover;
    margin-bottom: -1.2rem;
  }

  .card-title {
      font-size: 1.2rem;
      font-weight: 600;
      margin-bottom: 0.25rem;
  }

  .card-body p {
      font-size: 0.8rem;
  }

  .card-footer {
      background: none;
      border-top: none;
      padding-bottom: 1rem;
      padding-left: 1rem;
      font-size: 1.4rem;  /* 默认大约是 1rem，调大即可 */
      margin-right: 0.5rem;
      padding-top: 0.2rem;
      color: #333;
      transition: transform 0.2s;
  }

  .card-footer i:hover {
      transform: scale(1.2);
      color: var(--lv-orange); 
  }

  .custom-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 0rem;
  }

  /* 左侧头像区域 padding 调整 */
  .custom-card .author-avater {
      margin-right: 20px;
  }

  /* 整体卡片上下 padding 调整 */
  .custom-card {
      padding: 24px 28px;
      flex-wrap: wrap;
      align-items: center; 
  }

  .custom-card .right span {
      font-size: 0.85rem;
      color: #888;
      display: block;
      margin-bottom: 2px;
  }

  .custom-card .right h5 {
      font-size: 1.15rem;
      font-weight: 600;
      color: #d80000; 
      margin-bottom: 6px;
  }

  .custom-card .right p {
      font-size: 0.9rem;
      color: #666;
      margin-bottom: 0;
      line-height: 1.5;
  }

  .custom-card .intro-text {
      font-size: 0.95rem;
      color: #444;
      line-height: 1.7;
      padding-left: 16px;
      border-left: 1px solid #eee;
  }

  /* .justify-text {
      text-align: justify;
      line-height: 1.8;
      font-size: 0.95rem;
      color: #444;
      padding-left: 1rem;
      border-left: 1px solid #eee;
      hyphens: auto;
      word-break: break-word;
      text-indent: 2em;
  }

  .right-wrapper{
      min-width:0;         
  }

  .social-icons {
      display: flex;
      gap: 12px;
      margin-top: 8px;
  }

  .social-icons a {
      color: #777;
      font-size: 18px;
      transition: color 0.2s ease;
  }

  .social-icons a:hover {
      color: #ee7023;  /* 橙色 hover 效果，可改为品牌色 */
  /* } */

  @media (max-width: 768px) {
      .custom-card {
          flex-direction: column !important;
          align-items: flex-start !important;
      }

      .custom-card > div {
          width: 100% !important;
          padding-right: 0 !important;
          margin-bottom: 1rem;
      }

      .custom-card img {
          width: 100% !important;
          height: auto !important;
          max-width: 240px;
          margin-bottom: 1rem;
      }

      .right-wrapper {
          padding-left: 0 !important;
          border-left: none !important;
      } */
  }
</style>


# <font color="#2B6ADD"> Current Member </font>

<div class="row custom-grid">
    <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/hp.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Peng Huang</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">(co-supervise)</p>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidates</p>
              <p class="mb-neg-2">2020 ~ Present</p>
          </div>
      </div> 
    </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/xbq.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0"><a href="https://1xbq1.github.io/">Binqian Xu</a></h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2022 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/dgz.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Guangzhao Dai</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2022 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/lpp.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Pengpeng Li</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2023 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/cmq.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Meiqi Cao</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2023 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/zxy.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Xingyu Zhu</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">(co-supervise)</p>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2023 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/qhy.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0"><a href="https://quhongyu.github.io/">Hongyu Qu</a></h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/gjj.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Jinjin Gong</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/lzx.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Zhixuan Li</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/lcj.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0"><a href="https://chengjian-li.github.io/">Chengjian Li</a></h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">(co-supervise)</p>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/dq.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Qun Dai</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/wz.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Zheng Wang</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/ff.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Fei Feng</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/wyq.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Yuanqing Wang</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
    <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/drx.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Rongxing Ding</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">(co-supervise)</p>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/sym.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Yumeng Su</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2023 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/ply.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Luying Peng</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2023 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/gwx.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Wenxuan Ge</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/hch.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Chenghao Hu</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/wjy.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Jingyuan Wang</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/yz.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Zheng Yin</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/yyr.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Yiran Yang</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">(co-supervise)</p>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2024 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/why.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Haiyue Wei</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/yh.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Hui Yang</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/lb.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Bo Li</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">(co-supervise)</p>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/lxy.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Xinyu Liu</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
  <div class="col">
      <div class="card d-flex flex-column h-100 text-center">
          <div class="px-3 mt-3">
            <img src="{{ '/images/team/current/jyx.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
          </div>
          <div class="card-body">
              <!-- text-uppercase -->
              <h6 class="card-title mb-0">Yixiang Jiang</h6>
              <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. Candidate</p>
              <p class="mb-neg-2">2025 ~ Present</p>
          </div>
      </div> 
  </div>
</div>

# <font color="#2B6ADD"> Alumni Member </font>


<div class="row custom-grid">
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/wmy.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Mengyin Wang</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. (2013 ~ 2020)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">DLNU</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/yr.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Rui Yan</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ph.D. (2017 ~ 2022)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Professor in NJUST</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/scl.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Chenglong Shi</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2018 ~ 2021)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">SAP, China</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/zrp.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Ruipeng Zhang</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2018 ~ 2021)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Ningbo Municipal Government</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/dj.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Jing Ding</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2019 ~ 2022)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Aibaba</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/jq.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Qian Jiang</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2019 ~ 2022)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">H3C, Hangzhou</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/lbn.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Boning Li</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2019 ~ 2022)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Shenyang Fire and Rescue Brigade</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/zxy.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Xiangyu Zhao</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2019 ~ 2022)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">ZTE Corporation</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/yjw.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Jiawen Yang</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2021 ~ 2023)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">IDATA, Hefei</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/cyf.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Yafei Cui</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2021 ~ 2023)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Tonghuashun, Zhejiang</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/ckk.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Keke Chen</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2021 ~ 2024)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Hikvision, Hangzhou</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/tzw.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Zhewei Tu</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2021 ~ 2024)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Huawei, Nanjing</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/gxj.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Xiaojing Ge</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2021 ~ 2024)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Agricultural Bank of China, Ningbo</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/glj.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Longjie Guo</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2021 ~ 2024)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Shanghai Institute of Satellite Engineering</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/ghl.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Hailiang Gao</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2022 ~ 2025)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">Huawei, Shanghai</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/myg.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Yunguo Ma</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2022 ~ 2025)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">HONOR, Nanjing</p>
        </div>
    </div> 
  </div>
  <div class="col">
    <div class="card d-flex flex-column h-100 text-center">
        <div class="px-3 mt-3">
          <img src="{{ '/images/team/alumni/lw.webp' | relative_url }}" class="card-img mb-neg-2" alt="">
        </div>
        <div class="card-body">
            <!-- text-uppercase -->
            <h6 class="card-title mb-0">Wei Liu</h6>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">M.S. (2022 ~ 2025)</p>
            <p class="card-text mb-neg-1 fs--1 text-primary fw-bold">SEU</p>
        </div>
    </div> 
  </div>
</div>