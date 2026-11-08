---
permalink: /
title: "BIOGRAPHY"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* =========================================
     1. STATIC LIGHT THEME VARIABLES (Locked)
     ========================================= */
  :root {
    --port-primary: #2c3e50;    /* Dark Academic Blue */
    --port-text: #3b3b3b;       /* Dark Gray for readability */
    --port-muted: #64748b;      /* Muted gray for subtitles */
    --port-bg: #fdfdfd;         /* Almost white for cards */
    --port-border: #eaeaea;     /* Light gray borders */
    --accent-color: #f0f7ff;    /* Soft blue for milestones */
  }

  /* =========================================
     2. GLOBAL HEADER FIXES (Matches Portfolio)
     ========================================= */
  .masthead, 
  .masthead__inner-wrap, 
  .masthead__menu, 
  .masthead__menu ul, 
  .greedy-nav {
    background-color: #ffffff !important;
    background: #ffffff !important;
  }
  
  .masthead {
    border-bottom: 1px solid var(--port-border) !important;
  }

  .masthead a, 
  .masthead__menu-item,
  .masthead__menu-item a,
  .greedy-nav a, 
  .greedy-nav .visible-links,
  .greedy-nav .visible-links li,
  .greedy-nav .visible-links a {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-text) !important;
  }

  .masthead a:hover,
  .greedy-nav a:hover,
  .greedy-nav .visible-links a:hover,
  .greedy-nav .visible-links li.masthead__menu-item--current a,
  .greedy-nav .visible-links li.masthead__menu-item--current a:hover {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-primary) !important;
  }

  h1.page__title, .page__title {
    color: var(--port-primary) !important;
    font-weight: 700 !important;
  }

  /* =========================================
     3. BIOGRAPHY LAYOUT STYLES
     ========================================= */
  /* Standardized Section Titles */
  .section-title {
    margin-top: 45px; 
    border-bottom: 1px solid var(--port-border); 
    padding-bottom: 8px; 
    text-transform: uppercase; 
    color: var(--port-primary) !important;
    font-size: 1.15em !important; 
    letter-spacing: 0.1em;
    font-weight: 700;
  }

  /* Standardized Text Style for Bio */
  .content-text {
    text-align: justify !important; 
    text-justify: inter-word !important;
    font-size: 0.95em; 
    line-height: 1.7; 
    margin-bottom: 20px; 
    color: var(--port-text);
  }

  /* Collaboration Alert */
  .collab-box {
    background-color: var(--accent-color);
    border-left: 4px solid var(--port-primary);
    padding: 14px 18px;
    font-size: 0.95em;
    color: var(--port-primary);
    font-weight: 500;
    margin: 30px 0;
    border-radius: 0 4px 4px 0;
    box-shadow: 0 1px 3px rgba(0,0,0,0.03);
    line-height: 1.6;
  }

  /* News Timeline Styling */
  .news-scroll-container {
    max-height: 500px; 
    overflow-y: auto; 
    margin-top: 20px;
    padding-right: 15px;
  }
  
  .news-scroll-container::-webkit-scrollbar { width: 5px; }
  .news-scroll-container::-webkit-scrollbar-track { background: var(--port-bg); }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #d1d5db; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #9ca3af; }

  .timeline-item {
    display: flex; 
    margin-bottom: 14px; 
    font-size: 0.9em; 
    line-height: 1.5;
    padding: 4px 0;
    align-items: baseline; 
  }
  
  .timeline-date {
    min-width: 95px; 
    font-weight: 700; 
    color: var(--port-muted); 
  }
  
  .timeline-content {
    flex: 1; 
    color: var(--port-text);
    word-wrap: break-word; /* Prevents text cutoff */
  }

  /* Highlighted Milestones */
  .timeline-item.milestone {
    background-color: var(--accent-color); 
    border-radius: 4px;
    padding: 8px 12px; /* Added horizontal padding to prevent cutoff */
    margin-left: -12px; /* Offsets the padding to align visually */
    margin-top: 2px;
    margin-bottom: 12px;
  }

  /* Mobile & Tablet Responsiveness */
  @media (max-width: 768px) {
    .timeline-item { 
      flex-direction: column; 
      margin-bottom: 18px;
    }
    .timeline-date { 
      margin-bottom: 4px; 
      font-size: 0.85em; 
      color: var(--port-primary);
    }
    .timeline-item.milestone { 
      margin-left: 0; 
      padding: 10px 12px;
    }
  }

  /* Education & Awards */
  .cv-row {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    gap: 16px;
    font-size: 0.95em;
    color: var(--port-text);
    margin: 14px 0 4px;
  }
  .cv-row .cv-date {
    color: var(--port-muted);
    font-weight: 600;
    white-space: nowrap;
    font-size: 0.9em;
  }
  .cv-sub {
    font-size: 0.9em;
    color: var(--port-muted);
    margin: 0 0 6px;
  }
  .awards-list { list-style: none; padding-left: 0; margin-top: 10px; }
  .awards-list li { display: flex; justify-content: space-between; gap: 16px; font-size: 0.92em; margin-bottom: 8px; color: var(--port-text); }
  .awards-list .cv-date { color: var(--port-muted); font-weight: 600; white-space: nowrap; }
  @media (max-width: 768px) {
    .cv-row, .awards-list li { flex-direction: column; gap: 2px; }
  }
</style>

<div class="content-text">
  I am a final-year MEng student in <strong>Robotics and Artificial Intelligence</strong> at <strong>University College London</strong> (First Class average). My work is in robot learning: <strong>humanoid and legged locomotion</strong>, <strong>reinforcement learning</strong>, and <strong>surgical scene understanding</strong>.
</div>

<div class="content-text">
  Most recently I was a Robotics Engineer at <strong>BYTE ABEE</strong> in Athens, where I fine-tuned the SONIC humanoid motion controller to transfer it from Unitree G1 to AgiBot X2 and deployed it on the physical robot. At the <strong>UCL Hawkes Institute</strong> I co-first-authored CasCVS-Net, a staged multi-task cascade for Critical View of Safety assessment in laparoscopic surgery (MICCAI SafeSurg 2026, Oral). Before that I worked on bipedal locomotion for quadruped robots at the <strong>UCL Robot Perception &amp; Learning Lab</strong>, a person-following mobile robot at <strong>ANTOBOT</strong>, and bio-inspired airflow sensing at <strong>The Future Laboratory, Tsinghua University</strong>.
</div>

<h2 class="section-title">Recent News</h2>
<div class="news-scroll-container">

  <div class="timeline-item milestone">
    <div class="timeline-date">Sep 2026</div>
    <div class="timeline-content"><a href="https://arxiv.org/abs/2609.27681">CasCVS-Net</a> (<strong>MICCAI SafeSurg 2026, Oral</strong>) is out on arXiv.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jul 2026</div>
    <div class="timeline-content"><a href="https://arxiv.org/abs/2607.06186">Calf-Integrated Arms for Bimanual Quadruped Loco-Manipulation</a> (<strong>CLAWAR 2026, Oral</strong>) is out on arXiv.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Jun 2026</div>
    <div class="timeline-content">Joined <strong>BYTE ABEE</strong> (Athens) as a Robotics Engineer, working on humanoid locomotion and motion control.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2026</div>
    <div class="timeline-content">18th place (<strong>Silver Medal</strong>) in the Kaggle Deep Past Challenge: Akkadian–English Translation.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Oct 2025</div>
    <div class="timeline-content"><a href="https://arxiv.org/abs/2503.02387">RGBSQGrasp</a> received the <strong>Best Workshop Paper Award</strong> at the IROS 2025 RGMC Workshop.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Mar 2025</div>
    <div class="timeline-content">Started a research internship at <strong>ANTOBOT</strong> on human-following mobile robots.</div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">Jun 2024</div>
    <div class="timeline-content">Started a research internship at <strong>The Future Laboratory, Tsinghua University</strong> on olfaction and bio-robotics.</div>
  </div>

  <div class="timeline-item milestone">
    <div class="timeline-date">Sep 2023</div>
    <div class="timeline-content">Started the MEng in Robotics and Artificial Intelligence at <strong>UCL</strong>.</div>
  </div>

</div>

<h2 class="section-title">Education</h2>
<div class="cv-row"><strong>University College London</strong><span class="cv-date">Sep 2023 – Jun 2027</span></div>
<p class="cv-sub">MEng Robotics and Artificial Intelligence, Department of Computer Science · London, UK<br>Average: 74.1% (First Class)</p>

<h2 class="section-title">Awards &amp; Honors</h2>
<ul class="awards-list">
  <li><span>Best Workshop Paper Award, IROS 2025 RGMC Workshop (RGBSQGrasp)</span><span class="cv-date">2025</span></li>
  <li><span>Kaggle 18th Place (Silver Medal), Deep Past Challenge: Akkadian–English Translation</span><span class="cv-date">2026</span></li>
  <li><span>Gold Medal, UKMT Mathematical Challenge</span><span class="cv-date">2023</span></li>
  <li><span>Gold Medal, British Physics Olympiad</span><span class="cv-date">2021</span></li>
</ul>
