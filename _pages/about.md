---
permalink: /
title: "Ping Tang"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* 整体样式 */
.section-title {
  color: #667eea;
  border-bottom: 3px solid #667eea;
  padding-bottom: 10px;
  margin-top: 40px;
  margin-bottom: 20px;
}

/* 新闻框 */
.news-box {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 20px;
  border-radius: 10px;
  margin: 20px 0;
}
.news-box h2 {
  color: white;
  border-bottom: 2px solid rgba(255,255,255,0.3);
  padding-bottom: 10px;
  margin-top: 0;
}
.news-item {
  display: flex;
  align-items: center;
  margin: 10px 0;
}
.news-date {
  background: rgba(255,255,255,0.2);
  padding: 2px 10px;
  border-radius: 15px;
  margin-right: 10px;
  font-size: 0.85em;
  white-space: nowrap;
}

/* 高亮框 */
.highlight-box {
  background: #f8f9fa;
  border-left: 4px solid #667eea;
  padding: 15px 20px;
  margin: 20px 0;
  border-radius: 0 10px 10px 0;
}

/* 研究方向卡片 */
.research-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 15px;
  margin: 20px 0;
}
@media (max-width: 600px) {
  .research-grid {
    grid-template-columns: 1fr;
  }
}
.research-card {
  background: white;
  border: 1px solid #eee;
  border-radius: 10px;
  padding: 20px;
  transition: all 0.3s ease;
  box-shadow: 0 2px 5px rgba(0,0,0,0.05);
}
.research-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
}
.research-card h3 {
  color: #667eea;
  margin-top: 0;
  font-size: 1.1em;
}
.research-card p {
  color: #666;
  font-size: 0.9em;
  margin-bottom: 0;
}
.icon {
  font-size: 1.5em;
  margin-bottom: 10px;
}

/* 统计数字 */
.stats-container {
  display: flex;
  justify-content: space-around;
  text-align: center;
  margin: 30px 0;
  flex-wrap: wrap;
  background: #f8f9fa;
  padding: 20px;
  border-radius: 10px;
}
.stat-item {
  padding: 15px 25px;
}
.stat-number {
  font-size: 2.5em;
  font-weight: bold;
  color: #667eea;
}
.stat-label {
  color: #666;
  font-size: 0.9em;
}

/* 时间轴 */
.timeline {
  position: relative;
  padding-left: 30px;
  margin: 20px 0;
}
.timeline::before {
  content: '';
  position: absolute;
  left: 8px;
  top: 0;
  bottom: 0;
  width: 3px;
  background: linear-gradient(to bottom, #667eea, #764ba2);
  border-radius: 3px;
}
.timeline-item {
  position: relative;
  margin-bottom: 25px;
}
.timeline-item::before {
  content: '';
  position: absolute;
  left: -26px;
  top: 5px;
  width: 12px;
  height: 12px;
  background: #667eea;
  border-radius: 50%;
  border: 3px solid white;
  box-shadow: 0 0 0 3px #667eea;
}
.timeline-year {
  color: #667eea;
  font-weight: bold;
  font-size: 0.9em;
}
.timeline-title {
  font-weight: bold;
  margin: 5px 0;
}
.timeline-desc {
  color: #666;
  font-size: 0.9em;
}

/* 徽章 */
.badge {
  display: inline-block;
  background: linear-gradient(135deg, #667eea, #764ba2);
  color: white;
  padding: 5px 15px;
  border-radius: 20px;
  font-size: 0.85em;
  margin: 5px 5px 5px 0;
}
.badge-gold {
  background: linear-gradient(135deg, #f5af19, #f12711);
}

/* 论文列表 */
.pub-item {
  background: #f8f9fa;
  padding: 15px;
  margin: 10px 0;
  border-radius: 8px;
  border-left: 4px solid #667eea;
}
.pub-title {
  font-weight: bold;
  color: #333;
}
.pub-venue {
  color: #667eea;
  font-style: italic;
}
.pub-year {
  background: #667eea;
  color: white;
  padding: 2px 8px;
  border-radius: 10px;
  font-size: 0.8em;
  margin-right: 10px;
}

/* 下载按钮 */
.download-btn {
  display: inline-block;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white !important;
  padding: 12px 24px;
  border-radius: 25px;
  text-decoration: none;
  font-weight: bold;
  margin: 20px 0;
  transition: all 0.3s ease;
}
.download-btn:hover {
  opacity: 0.9;
  transform: translateY(-2px);
  box-shadow: 0 5px 20px rgba(102, 126, 234, 0.4);
  color: white !important;
  text-decoration: none;
}

/* 表格美化 */
table {
  width: 100%;
  border-collapse: collapse;
  margin: 15px 0;
}
th {
  background: #667eea;
  color: white;
  padding: 12px;
  text-align: left;
}
td {
  padding: 12px;
  border-bottom: 1px solid #eee;
}
tr:hover {
  background: #f8f9fa;
}
</style>

## 👋 Welcome!

I am an **Associate Professor** at the [School of Foreign Studies](http://sfs.njust.edu.cn/), [Nanjing University of Science and Technology](https://www.njust.edu.cn/). I received my Ph.D. in Linguistics from [Macquarie University](https://www.mq.edu.au/) with **Vice-chancellor's Commendation for Academic Excellence**.

<div class="highlight-box">
💡 My research explores how children acquire the sounds and melodies of language — particularly <strong>Mandarin tones and prosody</strong> — and how this process differs in children with <strong>cochlear implants</strong>.
</div>

<div class="stats-container">
  <div class="stat-item">
    <div class="stat-number">15+</div>
    <div class="stat-label">Journal Articles</div>
  </div>
  <div class="stat-item">
    <div class="stat-number">29</div>
    <div class="stat-label">Students Supervised</div>
  </div>
  <div class="stat-item">
    <div class="stat-number">6</div>
    <div class="stat-label">Research Grants</div>
  </div>
  <div class="stat-item">
    <div class="stat-number">8</div>
    <div class="stat-label">Keynote Speeches</div>
  </div>
</div>

---

<h2 class="section-title">📰 Latest News</h2>

<div class="news-box">
  <div class="news-item">
    <span class="news-date">Aug 2025</span>
    <span>Keynote at Symposium on Language Development, Hong Kong Metropolitan University</span>
  </div>
  <div class="news-item">
    <span class="news-date">Jun 2025</span>
    <span>Invited talks at Huazhong University of Science and Technology & Hanjiang University</span>
  </div>
  <div class="news-item">
    <span class="news-date">Oct 2024</span>
    <span>Keynote at the First "Belt and Road" International Conference on Hearing and Speech Sciences</span>
  </div>
  <div class="news-item">
    <span class="news-date">2024</span>
    <span>New papers published in <em>Journal of Child Language</em> and <em>Ear and Hearing</em></span>
  </div>
</div>

---

<h2 class="section-title">🔬 Research Interests</h2>

<div class="research-grid">
  <div class="research-card">
    <div class="icon">🗣️</div>
    <h3>Language Development</h3>
    <p>Acquisition of Mandarin tones, prosody, and phonological processes by typically developing children</p>
  </div>
  <div class="research-card">
    <div class="icon">🦻</div>
    <h3>Hearing Rehabilitation</h3>
    <p>Speech perception and production by children with cochlear implants</p>
  </div>
  <div class="research-card">
    <div class="icon">🧠</div>
    <h3>Psycholinguistics</h3>
    <p>Real-time processing of prosodic information during sentence comprehension</p>
  </div>
  <div class="research-card">
    <div class="icon">📊</div>
    <h3>Phonetics</h3>
    <p>Acoustic analysis, infant-directed speech, and Lombard speech</p>
  </div>
</div>

---

<h2 class="section-title">🎓 Education</h2>

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-year">2019 - 2024</div>
    <div class="timeline-title">Ph.D. in Linguistics — Macquarie University, Australia</div>
    <div class="timeline-desc">
      Thesis: <em>The acquisition of Mandarin tones in context by children who are typically developing and those with hearing loss</em><br>
      Supervisors: Katherine Demuth, Nan Xu Rattanasone, Ivan Yuen<br>
      🏆 Vice-chancellor's Commendation for Academic Excellence
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2012 - 2015</div>
    <div class="timeline-title">M.A. in Linguistics — Nanjing Normal University, China</div>
    <div class="timeline-desc">Advisor: Wentao Gu</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2008 - 2012</div>
    <div class="timeline-title">B.A. in Chinese Linguistics & Literature — Fuyang Normal University, China</div>
  </div>
</div>

---

<h2 class="section-title">💼 Professional Experience</h2>

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-year">2023 - 2024</div>
    <div class="timeline-title">Visiting Scholar — University of Nottingham, UK</div>
    <div class="timeline-desc">School of English</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2019 - Present</div>
    <div class="timeline-title">Associate Professor — Nanjing University of Science and Technology</div>
    <div class="timeline-desc">School of Foreign Studies</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-year">2018 - 2019</div>
    <div class="timeline-title">Senior Research Officer — Macquarie University</div>
    <div class="timeline-desc">Child Language Lab</div>
  </div>
</div>

---

<h2 class="section-title">📚 Selected Publications</h2>

<div class="pub-item">
  <span class="pub-year">2025</span>
  <span class="pub-title">Due to increased variability, the expanded vowel and tone space in Mandarin IDS does not lead to enhanced contrasts.</span><br>
  Tang, P., Xu Rattanasone, N., Yuen, I., Demuth, K., Benders, T.<br>
  <span class="pub-venue">Journal of Child Language</span>
</div>

<div class="pub-item">
  <span class="pub-year">2024</span>
  <span class="pub-title">Mandarin-speaking Children with Cochlear Implants Face Challenges in Using F0 Expansion to Express Contrastive Focus.</span><br>
  Tang, P., Xu Rattanasone, N., Demuth, K., Wang, L., & Yuen, I.<br>
  <span class="pub-venue">Ear and Hearing</span>
</div>

<div class="pub-item">
  <span class="pub-year">2024</span>
  <span class="pub-title">Visual-articulatory cues facilitate children with CIs to better perceive Mandarin tones in sentences.</span><br>
  Tang, P., Li, S., Shen, Y., Yu, Q., & Feng, Y.<br>
  <span class="pub-venue">Speech Communication</span>
</div>

<div class="pub-item">
  <span class="pub-year">2023</span>
  <span class="pub-title">The Acquisition of Contrastive Focus During Online Sentence-comprehension by Children Learning Mandarin Chinese.</span><br>
  Tang, P., Yuen, I., Demuth, K., & Xu Rattanasone, N.<br>
  <span class="pub-venue">Developmental Psychology</span>
</div>

<div class="pub-item">
  <span class="pub-year">2021</span>
  <span class="pub-title">Longer Cochlear Implant Experience Leads to Better Production of Mandarin Tones for Early Implanted Children.</span><br>
  Tang, P., Yuen, I., Rattanasone, N. X., Gao, L., & Demuth, K.<br>
  <span class="pub-venue">Ear and Hearing</span>
</div>

<div class="pub-item">
  <span class="pub-year">2019</span>
  <span class="pub-title">The Acquisition of Mandarin Tonal Processes by Children with Cochlear Implants.</span><br>
  Tang, P., Yuen, I., Xu Rattanasone, N., & Demuth, K.<br>
  <span class="pub-venue">Journal of Speech, Language, and Hearing Research</span>
</div>

<div class="pub-item">
  <span class="pub-year">2017</span>
  <span class="pub-title">Phonetic Enhancement of Mandarin Vowels and Tones: Infant-directed Speech and Lombard Speech.</span><br>
  Tang, P., Xu Rattanasone, N., Yuen, I., & Demuth, K.<br>
  <span class="pub-venue">Journal of the Acoustical Society of America</span>
</div>

---

<h2 class="section-title">💰 Research Grants</h2>

| Year | Project | Amount |
|:-----|:--------|-------:|
| 2024 | Industry-Academia Joint Project with Cochlear Ltd. | ¥144,000 |
| 2020 | National Social Science Fund of China | ¥200,000 |
| 2020 | Research Fund for Returned Students, Nanjing Government | ¥30,000 |
| 2019 | Initiate Funding for Early Researchers, NJUST | ¥150,000 |
| 2019 | Fundamental Research Funds for Central Universities | ¥100,000 |
| 2018 | Dr. Li Sze Lim Mobility Award | A$34,000 |

---

<h2 class="section-title">🏆 Honors & Awards</h2>

<div style="margin: 20px 0;">
  <span class="badge badge-gold">🥇 ICPhS Best Student Paper 2019</span>
  <span class="badge badge-gold">🥇 BUCLD Best Student Paper 2018</span>
  <span class="badge">⭐ 333 High-Level Talents 2022</span>
  <span class="badge">🏅 Vice-chancellor's Commendation 2019</span>
  <span class="badge">🎯 NIH Diversity Enhancement Award 2018</span>
  <span class="badge">🏆 National Scholarship 2014</span>
  <span class="badge">🎖️ HDR Excellence Award 2018</span>
</div>

---

<h2 class="section-title">🎤 Selected Keynotes & Invited Talks</h2>

| Year | Event | Location |
|:-----|:------|:---------|
| 2025 | Symposium on Language Development in Chinese-speaking Populations | Hong Kong |
| 2025 | Invited Talk at Huazhong University of Science and Technology | Wuhan |
| 2024 | First "Belt and Road" International Conference on Hearing and Speech Sciences | Beijing |
| 2023 | Invited Talk at University of Nottingham | UK |
| 2023 | Invited Talk at Shanghai Jiaotong University | Shanghai |
| 2020 | Annual Conference of Jiangsu Foreign Languages & Linguistics Society | Nanjing |
| 2019 | International Workshop on Neurolinguistics Studies of Tone | Hong Kong |

---

<h2 class="section-title">👨‍🏫 Teaching & Supervision</h2>

**Courses**: R Programming, Statistical Analysis, Phonetics, Introductory Linguistics, Language Development

**Student Supervision**: Since 2019, I have supervised **1 PhD student**, **18 Master students**, and **10 Undergraduate students**. My students have published in top venues including *Journal of Child Language*, *Journal of Speech, Language, and Hearing Research*, *Interspeech*, and *Speech Prosody*.

---

<h2 class="section-title">📄 CV Download</h2>

<a href="/files/cv.pdf" class="download-btn">📥 Download Full CV (PDF)</a>

---

<h2 class="section-title">📬 Contact</h2>

📧 **Email**: [ping.tang@njust.edu.cn](mailto:ping.tang@njust.edu.cn)

🏢 **Office**: School of Foreign Studies, Nanjing University of Science and Technology

📍 **Address**: 200 Xiaolingwei St., Xuanwu District, Nanjing, Jiangsu 210094, China
