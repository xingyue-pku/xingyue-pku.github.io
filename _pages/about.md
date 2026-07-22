---
permalink: /
title: ""
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
.hero-card {
  background: #fffaf0;
  border: 1px solid #d8cdb4;
  border-radius: 12px;
  padding: 28px 36px;
  margin: 6px 0 32px 0;
  box-shadow: 0 2px 10px rgba(107, 79, 44, 0.07);
}
/* stretch hero card to match the masthead nav width:
   .page sits inside #main with Susy prefix(0.5/12) span(10/12) suffix(2/12).
   Larger negative margins push card edges all the way to the nav edges. */
@media (min-width: 64em) {
  .hero-card {
    margin-left: -15%;
    margin-right: -25%;
  }
}
.hero {
  display: flex;
  gap: 36px;
  align-items: flex-start;
  margin: 0;
}
.hero-photo {
  flex: 0 0 36%;
  max-width: 380px;
}
.hero-photo img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  object-fit: cover;
  border: 1px solid #d8cdb4;
  box-shadow: 0 2px 6px rgba(107, 79, 44, 0.08);
}
.hero-info {
  flex: 1;
  min-width: 0;
}
.hero-info h2 {
  margin-top: 0;
  margin-bottom: 18px;
  font-size: 1.6em;
  color: #6b4f2c;
  letter-spacing: 1px;
}
.profile-fields {
  display: grid;
  grid-template-columns: max-content 1fr;
  column-gap: 28px;
  row-gap: 14px;
  margin: 0;
  font-size: 1.02em;
  line-height: 1.55;
}
.profile-fields dt {
  font-size: 1em;
  font-weight: 600;
  color: #6b4f2c;
  white-space: nowrap;
  margin: 0;
  padding: 0;
  align-self: baseline;
}
.profile-fields dd {
  font-size: 1em;
  font-weight: 400;
  color: #2c2c2c;
  margin: 0;
  padding: 0;
  align-self: baseline;
}
@media (max-width: 768px) {
  .hero { flex-direction: column; }
  .hero-photo { max-width: 260px; }
}

.news-list {
  list-style: none;
  padding: 0;
  margin: 6px 0 28px 0;
}
.news-list li {
  padding: 8px 0;
  border-bottom: 1px dashed #d8cdb4;
  line-height: 1.55;
}
.news-list li:last-child { border-bottom: 0; }
.news-list .news-date {
  display: inline-block;
  min-width: 92px;
  color: #6b4f2c;
  font-weight: 600;
  font-variant-numeric: tabular-nums;
}

.contact-list {
  list-style: none;
  padding: 0;
  margin: 6px 0;
}
.contact-list li {
  padding: 4px 0;
}
.contact-list .contact-label {
  display: inline-block;
  min-width: 72px;
  font-weight: 600;
  color: #6b4f2c;
}

h2 {
  color: #6b4f2c;
  border-bottom: 1px solid #e5dcc4;
  padding-bottom: 6px;
  margin-top: 32px;
}
</style>

<div class="hero-card">
  <div class="hero">
    <div class="hero-photo">
      <img src="{{ site.baseurl }}/images/profile.png" alt="邢玥">
    </div>
    <div class="hero-info">
      <dl class="profile-fields">
        <dt>姓名</dt><dd>邢玥 · Yue Xing</dd>
        <dt>学校</dt><dd>北京大学 · 信息管理系</dd>
        <dt>专业方向</dt><dd>大数据管理与应用</dd>
        <dt>学历状态</dt><dd>博士研究生在读</dd>
        <dt>导师</dt><dd>黄文彬 长聘副教授</dd>
        <dt>主要研究方向</dt><dd>AI 智能体与对齐约束 · 同行评议判断机制 · 生成式 AI 在学术工作中的使用与治理</dd>
        <dt>此前经历</dt><dd>多年互联网教育产业从业</dd>
      </dl>
    </div>
  </div>
</div>

## News

<ul class="news-list">
  <li><span class="news-date">2026-07</span>论文《外审分歧的文本形成机制研究》获中国情报学年会 2026 博士生学术论坛 <strong>期刊优选论文名单</strong></li>
  <li><span class="news-date">2026-07</span>海报 <em>After the Artifact: Reconstructing Academic Legitimacy</em> 被 ASIS&T Annual Meeting 2026 正式录用</li>
  <li><span class="news-date">2026-05-27</span>合作论文《生成式人工智能介入科研的风险感知与治理研究》被中国情报学年会 2026 博士生学术论坛收录（报告交流）</li>
  <li><span class="news-date">2026-05</span>论文《GenAI 介入高校科研实践的风险感知结构及治理启示》投出至《图书情报工作》(CSSCI)，进入外审</li>
  <li><span class="news-date">2025-12</span>第一发明人专利《活动水平的测评方法、系统、装置及电子设备》获国家知识产权局授权</li>
  <li><span class="news-date">2026</span>参与国家自然科学基金面上项目《学术能力评价语言模型研究》（62577003）</li>
  <li><span class="news-date">2025</span>论文 <em>Reconfiguring global LIS education</em> 发表于 <em>The Electronic Library</em></li>
  <li><span class="news-date">2025</span>课题组完成《高等教育人工智能应用边界指南 2.0》（汉英对照），北京出版社出版</li>
</ul>

## Contact

<ul class="contact-list">
  <li><span class="contact-label">邮箱</span><a href="mailto:xingyue_elaine@stu.pku.edu.cn">xingyue_elaine@stu.pku.edu.cn</a></li>
  <li><span class="contact-label">GitHub</span><a href="https://github.com/xingyue-pku">xingyue-pku</a></li>
  <li><span class="contact-label">ORCID</span><a href="https://orcid.org/0009-0002-4718-1964">0009-0002-4718-1964</a></li>
</ul>
