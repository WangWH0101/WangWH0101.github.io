---
title: Weihan Wang
---

<style>
  /* ===== Neutralize the default GitHub Pages (primer) theme ===== */
  .page-header, .site-footer { display: none !important; }
  .main-content {
    max-width: none !important;
    margin: 0 !important;
    padding: 0 !important;
    background: transparent !important;
  }
  body {
    background: #F3EFE6 !important;
    color: #29261F;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
  }

  /* ===== Claude-inspired design tokens =====
     warm cream ground · coral crimson accent · serif display · generous whitespace */
  .ww-page {
    --bg: #F3EFE6;
    --surface: #FCFAF4;
    --surface-2: #EFE9DC;
    --ink: #29261F;
    --muted: #6F6A5C;
    --faint: #9A9484;
    --line: #E2DCCC;
    --accent: #C15F3C;
    --accent-deep: #A34E30;
    --accent-soft: #F4E4D6;
    --serif: Georgia, "Iowan Old Style", "Palatino Linotype", "Times New Roman", "Songti SC", serif;
    --sans: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", "PingFang SC", "Microsoft YaHei", Arial, sans-serif;
    max-width: 920px;
    margin: 0 auto;
    padding: 0 22px 96px;
    font-family: var(--sans);
    color: var(--ink);
    line-height: 1.75;
    font-size: 15.5px;
  }
  .ww-page *, .ww-page *::before, .ww-page *::after { box-sizing: border-box; }
  .ww-page a { color: var(--accent-deep); text-decoration: none; }
  .ww-page a:hover { color: var(--accent); text-decoration: underline; text-underline-offset: 3px; }
  .ww-page img { max-width: 100%; }

  /* ===== Sticky nav ===== */
  .ww-nav {
    position: sticky; top: 0; z-index: 50;
    display: flex; align-items: center; justify-content: space-between;
    padding: 14px 4px; margin: 0 -4px 8px;
    background: rgba(243, 239, 230, 0.88);
    backdrop-filter: blur(10px); -webkit-backdrop-filter: blur(10px);
    border-bottom: 1px solid var(--line);
  }
  .ww-nav .ww-nav-name {
    font-family: var(--serif); font-size: 17px; font-weight: 700; letter-spacing: .02em;
    color: var(--ink);
  }
  .ww-nav .ww-nav-name span { color: var(--accent); }
  .ww-nav-links { display: flex; flex-wrap: wrap; gap: 4px 18px; }
  .ww-nav-links a {
    font-size: 13.5px; color: var(--muted); letter-spacing: .01em;
  }
  .ww-nav-links a:hover { color: var(--accent-deep); text-decoration: none; }

  /* ===== Hero ===== */
  .ww-hero {
    display: flex; gap: 28px; align-items: flex-start;
    padding: 44px 8px 36px;
  }
  .ww-avatar {
    width: 104px; height: 104px; flex: 0 0 auto;
    border-radius: 26px;
    border: 1px solid var(--line);
    background: var(--surface);
    box-shadow: 0 1px 2px rgba(41, 38, 31, .06);
  }
  .ww-hero h1 {
    font-family: var(--serif);
    font-size: 42px; line-height: 1.15;
    margin: 2px 0 8px; font-weight: 700; letter-spacing: -0.01em;
    color: var(--ink);
  }
  .ww-hero .ww-sub {
    color: var(--muted); font-size: 15px; margin: 0 0 18px; max-width: 560px;
  }
  .ww-btn-row { display: flex; flex-wrap: wrap; gap: 10px; margin-bottom: 20px; }
  .ww-btn {
    display: inline-flex; align-items: center; gap: 7px;
    font-size: 14px; font-weight: 500;
    padding: 8px 16px; border-radius: 999px;
    border: 1px solid var(--line);
    background: var(--surface); color: var(--ink);
    transition: all .15s ease;
  }
  .ww-btn:hover { border-color: var(--accent); color: var(--accent-deep); text-decoration: none; }
  .ww-btn.ww-btn-primary {
    background: var(--accent); border-color: var(--accent); color: #FDFBF6;
  }
  .ww-btn.ww-btn-primary:hover { background: var(--accent-deep); border-color: var(--accent-deep); color: #FDFBF6; }

  /* ===== Tags ===== */
  .ww-tags { display: flex; flex-wrap: wrap; gap: 8px; }
  .ww-tag {
    font-size: 13px; color: #7A4A32;
    background: var(--accent-soft);
    border: 1px solid #E8CDB8;
    padding: 3px 12px; border-radius: 999px; line-height: 1.6;
  }
  .ww-tag.ww-tag-plain {
    color: var(--muted); background: var(--surface-2); border-color: var(--line);
  }

  /* ===== Sections ===== */
  .ww-section { margin-top: 56px; scroll-margin-top: 76px; }
  .ww-section-head { display: flex; align-items: baseline; gap: 12px; margin-bottom: 22px; }
  .ww-section-head::before {
    content: ""; width: 10px; height: 10px; border-radius: 3px;
    background: var(--accent); align-self: center; flex: 0 0 auto;
  }
  .ww-section-head h2 {
    font-family: var(--serif); font-size: 27px; font-weight: 700;
    margin: 0; letter-spacing: -0.01em; color: var(--ink);
  }
  .ww-section-head .ww-section-note { font-size: 13px; color: var(--faint); }

  /* ===== Cards ===== */
  .ww-card {
    background: var(--surface);
    border: 1px solid var(--line);
    border-radius: 14px;
    padding: 24px 26px;
    box-shadow: 0 1px 2px rgba(41, 38, 31, .04);
  }
  .ww-card + .ww-card { margin-top: 16px; }

  /* ===== Timeline (education) ===== */
  .ww-timeline { position: relative; padding-left: 24px; }
  .ww-timeline::before {
    content: ""; position: absolute; left: 5px; top: 8px; bottom: 8px;
    width: 1px; background: var(--line);
  }
  .ww-tl-item { position: relative; padding: 0 0 22px 12px; }
  .ww-tl-item:last-child { padding-bottom: 2px; }
  .ww-tl-item::before {
    content: ""; position: absolute; left: -24px; top: 9px;
    width: 9px; height: 9px; border-radius: 50%;
    background: var(--bg); border: 2px solid var(--accent);
  }
  .ww-tl-date { font-size: 13px; color: var(--accent-deep); font-weight: 600; letter-spacing: .02em; }
  .ww-tl-title { font-family: var(--serif); font-size: 17.5px; font-weight: 700; margin: 2px 0 1px; }
  .ww-tl-desc { color: var(--muted); font-size: 14.5px; }

  /* ===== Work ===== */
  .ww-work-head { display: flex; justify-content: space-between; align-items: flex-start; gap: 18px; }
  .ww-work-head h3 { font-family: var(--serif); font-size: 19px; margin: 0 0 4px; }
  .ww-work-logo { width: 64px; height: 64px; object-fit: contain; border-radius: 12px; border: 1px solid var(--line); background: #fff; padding: 6px; flex: 0 0 auto; }
  .ww-meta { color: var(--muted); font-size: 14px; }
  .ww-duty { margin: 14px 0 0; padding: 0; list-style: none; }
  .ww-duty li {
    position: relative; padding: 7px 0 7px 22px; font-size: 14.5px;
    border-top: 1px dashed var(--line);
  }
  .ww-duty li:first-child { border-top: none; }
  .ww-duty li::before {
    content: ""; position: absolute; left: 2px; top: 15px;
    width: 7px; height: 7px; border-radius: 2px; background: var(--accent-soft);
    border: 1.5px solid var(--accent);
  }

  /* ===== Publications ===== */
  .ww-pub { display: flex; gap: 16px; padding: 14px 0; border-top: 1px solid var(--line); }
  .ww-pub:first-of-type { border-top: none; }
  .ww-pub-num {
    font-family: var(--serif); font-size: 15px; color: var(--faint);
    flex: 0 0 auto; width: 26px; padding-top: 2px;
  }
  .ww-pub-body { font-size: 14.5px; }
  .ww-pub-body b { color: var(--ink); }
  .ww-badge {
    display: inline-block; font-size: 12px; font-weight: 600;
    color: #7A4A32; background: var(--accent-soft); border: 1px solid #E8CDB8;
    border-radius: 6px; padding: 0 7px; margin-left: 6px; vertical-align: 1px;
  }
  .ww-subhead {
    font-family: var(--serif); font-size: 16px; font-weight: 700;
    color: var(--muted); margin: 18px 0 4px; letter-spacing: .02em;
  }

  /* ===== Research project cards ===== */
  .ww-proj h3 {
    font-family: var(--serif); font-size: 19.5px; font-weight: 700;
    margin: 0 0 10px; line-height: 1.4;
  }
  .ww-proj .ww-tags { margin-bottom: 14px; }
  .ww-proj p { margin: 0 0 12px; font-size: 14.5px; color: #3B382F; }
  .ww-proj .ww-status { font-size: 13.5px; color: var(--faint); font-style: italic; }
  .ww-stage {
    font-size: 12px; font-weight: 600; letter-spacing: .06em; text-transform: uppercase;
    color: var(--accent-deep);
  }
  .ww-gallery { display: flex; flex-wrap: wrap; gap: 10px; margin-top: 14px; }
  .ww-gallery a { display: inline-block; line-height: 0; }
  .ww-gallery img {
    height: 148px; width: auto; max-width: 100%;
    border-radius: 10px; border: 1px solid var(--line);
    background: #fff; padding: 4px;
    transition: transform .15s ease, box-shadow .15s ease;
  }
  .ww-gallery img:hover { transform: translateY(-2px); box-shadow: 0 6px 18px rgba(41,38,31,.10); }
  .ww-gallery-label {
    font-size: 12.5px; font-weight: 600; letter-spacing: .04em; color: var(--faint);
    margin: 16px 0 2px; text-transform: uppercase;
  }
  .ww-refs { font-size: 13px; color: var(--muted); border-top: 1px dashed var(--line); margin-top: 18px; padding-top: 12px; }
  .ww-refs p { margin: 4px 0; font-size: 13px; color: var(--muted); }

  /* ===== Grid cards (grades / language / programming) ===== */
  .ww-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 16px; }
  .ww-mini h3 {
    font-family: var(--serif); font-size: 17px; margin: 0 0 10px;
    display: flex; align-items: center; gap: 8px;
  }
  .ww-mini h3::before {
    content: ""; width: 8px; height: 8px; border-radius: 2px; background: var(--accent); flex: 0 0 auto;
  }
  .ww-mini p, .ww-mini li { font-size: 14px; color: #3B382F; }
  .ww-mini ul { margin: 0; padding-left: 18px; }
  .ww-mini .ww-kv { margin: 6px 0; font-size: 14px; }
  .ww-mini .ww-kv b { color: var(--ink); }
  .ww-mini img { border-radius: 10px; border: 1px solid var(--line); margin-top: 8px; }

  /* ===== Footer ===== */
  .ww-foot {
    margin-top: 72px; padding-top: 22px; border-top: 1px solid var(--line);
    display: flex; justify-content: space-between; flex-wrap: wrap; gap: 10px;
    font-size: 13px; color: var(--faint);
  }
  .ww-foot a { color: var(--muted); }

  /* ===== Responsive ===== */
  @media (max-width: 720px) {
    .ww-hero { flex-direction: column; gap: 18px; padding-top: 32px; }
    .ww-hero h1 { font-size: 33px; }
    .ww-grid { grid-template-columns: 1fr; }
    .ww-nav-links { display: none; }
    .ww-gallery img { height: 120px; }
    .ww-page { font-size: 15px; }
  }
</style>

<div class="ww-page">

<nav class="ww-nav">
  <div class="ww-nav-name">Weihan Wang <span>·</span> 王维翰</div>
  <div class="ww-nav-links">
    <a href="#education">Education</a>
    <a href="#work">Work</a>
    <a href="#publications">Publications</a>
    <a href="#research">Research</a>
    <a href="#awards">Awards</a>
    <a href="#more">More</a>
  </div>
</nav>

<header class="ww-hero">
  <img class="ww-avatar" src="https://github.com/WangWH0101.png" alt="Weihan Wang's avatar">
  <div>
    <h1>Weihan Wang</h1>
    <p class="ww-sub">
      Engineer at Chongqing Changan Industry (Group), working on autonomous driving.
      M.Cs in Computer Science at Southwest University; trained in theoretical physics at Sichuan University.
    </p>
    <div class="ww-btn-row">
      <a class="ww-btn ww-btn-primary" href="mailto:wangwh0101@gmail.com">wangwh0101@gmail.com</a>
      <a class="ww-btn" href="https://github.com/WangWH0101">GitHub · WangWH0101</a>
    </div>
    <div class="ww-tags">
      <span class="ww-tag">Machine Learning</span>
      <span class="ww-tag">Data Modeling</span>
      <span class="ww-tag">Computer Vision</span>
      <span class="ww-tag">Big Data</span>
      <span class="ww-tag">Natural Language Processing</span>
      <span class="ww-tag">Self-Driving</span>
    </div>
  </div>
</header>

<section class="ww-section" id="education">
  <div class="ww-section-head">
    <h2>Education</h2>
    <span class="ww-section-note">2015 — 2022</span>
  </div>
  <div class="ww-card">
    <div class="ww-timeline">
      <div class="ww-tl-item">
        <div class="ww-tl-date">2019.09 — 2022.06</div>
        <div class="ww-tl-title">M.Cs in Computer Science (exam-exempted)</div>
        <div class="ww-tl-desc">Network Science and Big Data · College of Computer and Information Science, Southwest University (211 Project, China)</div>
      </div>
      <div class="ww-tl-item">
        <div class="ww-tl-date">2017.09 — 2019.06</div>
        <div class="ww-tl-title">Undergraduate · Theoretical Physics</div>
        <div class="ww-tl-desc">College of Physics, Sichuan University (985 Project, China)</div>
      </div>
      <div class="ww-tl-item">
        <div class="ww-tl-date">2017.08 — 2017.09</div>
        <div class="ww-tl-title">Summer Session · Physics 7D</div>
        <div class="ww-tl-desc">School of Physical Sciences, University of California, Irvine (USA)</div>
      </div>
      <div class="ww-tl-item">
        <div class="ww-tl-date">2015.09 — 2017.08</div>
        <div class="ww-tl-title">Undergraduate · Theoretical Physics</div>
        <div class="ww-tl-desc">College of Physics, Sichuan University (985 Project, China)</div>
      </div>
    </div>
  </div>
</section>

<section class="ww-section" id="work">
  <div class="ww-section-head">
    <h2>Work Experience</h2>
    <span class="ww-section-note">2023 — present</span>
  </div>
  <div class="ww-card">
    <div class="ww-work-head">
      <div>
        <h3>Chongqing Changan Industry (Group) Co., Ltd</h3>
        <div class="ww-meta">Engineer · 2023/04 — Present</div>
      </div>
      <img class="ww-work-logo" src="/Pics/MyWork/15.png" alt="Company Logo">
    </div>
    <ul class="ww-duty">
      <li>Software and hardware architecture design for autonomous vehicles</li>
      <li>Equipment system and application scenario design</li>
      <li>Design and development of unmanned task models and algorithms</li>
    </ul>
  </div>
</section>

<section class="ww-section" id="publications">
  <div class="ww-section-head">
    <h2>Publications</h2>
    <span class="ww-section-note">Patent &amp; Journals</span>
  </div>
  <div class="ww-card">
    <div class="ww-subhead">Patent</div>
    <div class="ww-pub">
      <div class="ww-pub-num">1</div>
      <div class="ww-pub-body"><b>W. Wang</b>, Y. Wu &amp; P. He. A hand-held weeder for tobacco fields in hilly and mountainous areas. 20210915, 202122237182.2</div>
    </div>
    <div class="ww-subhead">Journal</div>
    <div class="ww-pub">
      <div class="ww-pub-num">1</div>
      <div class="ww-pub-body">Tan X, Gao L, <b>Wang W</b>, et al. Modelling alteration of leaf coloration peak date in <i>Cotinus coggygria</i> in a high-elevation karst region. <i>Agricultural and Forest Meteorology</i>, 2022, 323: 109044. <span class="ww-badge">JIF 6.424</span><br>
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S0168192322002337">sciencedirect.com/science/article/abs/pii/S0168192322002337</a></div>
    </div>
    <div class="ww-pub">
      <div class="ww-pub-num">2</div>
      <div class="ww-pub-body">Tan X, <b>Wang W</b>, Gao L, et al. The difference in leaf color quality of <i>Cotinus coggygria</i> during the coloration peak period affected by soil and topographic heterogeneity. <i>Catena</i>, 2023, 228: 107140. <span class="ww-badge">JIF 6.3</span></div>
    </div>
    <div class="ww-pub">
      <div class="ww-pub-num">3</div>
      <div class="ww-pub-body">Gao L, <b>Wang W</b>, Liao X, et al. Soil nutrients, enzyme activities, and bacterial communities in varied plant communities in karst rocky desertification regions in Wushan County, Southwest China. <i>Frontiers in Microbiology</i>, 2023, 14: 1180562. <span class="ww-badge">JIF 5.2</span></div>
    </div>
    <div class="ww-pub">
      <div class="ww-pub-num">4</div>
      <div class="ww-pub-body">王维翰. 基于实证数据的机构与国家论文引用量分析与建模研究 [D]. 西南大学, 2022. <a href="https://doi.org/10.27684/d.cnki.gxndx.2022.000501">DOI: 10.27684/d.cnki.gxndx.2022.000501</a></div>
    </div>
  </div>
</section>

<section class="ww-section" id="awards">
  <div class="ww-section-head">
    <h2>Honors &amp; Awards</h2>
  </div>
  <div class="ww-card">
    <div class="ww-pub">
      <div class="ww-pub-num" style="color:#C15F3C;">★</div>
      <div class="ww-pub-body">Third Prize in <b>“Huawei Cup” The 17th China Post-Graduate Mathematical Contest in Modeling</b> · <a href="/Pics/Others/MathModelAward.pdf">Award certificate</a></div>
    </div>
  </div>
</section>

<section class="ww-section" id="research">
  <div class="ww-section-head">
    <h2>Research Experience</h2>
    <span class="ww-section-note">Selected projects</span>
  </div>

  <div class="ww-card ww-proj">
    <span class="ww-stage">Undergraduate</span>
    <h3>Electrospinning</h3>
    <div class="ww-tags">
      <span class="ww-tag ww-tag-plain">Polyvinyl pyrrolidone (PVP)</span>
      <span class="ww-tag ww-tag-plain">Fabric</span>
      <span class="ww-tag ww-tag-plain">Electrospinning</span>
      <span class="ww-tag ww-tag-plain">Filterability</span>
      <span class="ww-tag ww-tag-plain">Air permeability</span>
    </div>
    <p>As the team leader, I designed the experiment and research targets. With the help of all members, we carried out research about the influence of PVP-based electrospinning fabric on the filtration performance of masks. The liquid polymer material forms filaments under high voltage electricity and attaches to the experimental object (i.e., mask). The filterability and air permeability of the mask with filaments attached are tested. In addition, this new method of attaching extra fabric on filters (e.g., mask) may improve their filterability and durability. This study can be very valuable under the effects of Covid-19.</p>
    <p class="ww-status">Still under research by other students in Sichuan University.</p>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Electrospinning"><img src="/Pics/Electrospinning/FlowChart.png" alt="Flow chart"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Electrospinning"><img src="/Pics/Electrospinning/SpinEquip.png" alt="Spinning equipment"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Electrospinning"><img src="/Pics/Electrospinning/FiltTST.png" alt="Filtration test"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Electrospinning"><img src="/Pics/Electrospinning/PermTST.png" alt="Permeability test"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Electrospinning"><img src="/Pics/Electrospinning/Equip1.jpeg" alt="Equipment 1"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Electrospinning"><img src="/Pics/Electrospinning/Equip2.jpeg" alt="Equipment 2"></a>
    </div>
  </div>

  <div class="ww-card ww-proj">
    <span class="ww-stage">Undergraduate</span>
    <h3>Network State Propagation</h3>
    <div class="ww-tags">
      <span class="ww-tag ww-tag-plain">Complex networks</span>
      <span class="ww-tag ww-tag-plain">Stochastic binary-state networks</span>
      <span class="ww-tag ww-tag-plain">Network construction</span>
      <span class="ww-tag ww-tag-plain">Propagation dynamics</span>
    </div>
    <p>The existence of various kinds of networks brings a large number of topological structures composed of different nodes and corresponding states. The research on network science has been showing increasing importance in many domains, such as epidemic prediction, rumor spreading and recommendation systems. I've studied the SI and SIS propagation of node states under randomly generated undirected networks of Poisson and regular distribution. The fractions of infected nodes under continuous and discrete propagations are compared. Besides, the theoretical calculation methods including AME, PA and mean field (MF)<sup>[1]</sup> are introduced and tested. This study is basically done through Matlab.</p>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Network%20state%20propagation"><img src="/Pics/Network state propagation/NodeStateChange.png" alt="Node state change"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Network%20state%20propagation"><img src="/Pics/Network state propagation/NodeStateUpdate.png" alt="Node state update"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Network%20state%20propagation"><img src="/Pics/Network state propagation/ContinuousDiscrete.png" alt="Continuous vs discrete"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Network%20state%20propagation"><img src="/Pics/Network state propagation/ContiDisc_SIS.png" alt="Continuous discrete SIS"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Network%20state%20propagation"><img src="/Pics/Network state propagation/ContiDisc_SampIntv.png" alt="Sampling interval"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Network%20state%20propagation"><img src="/Pics/Network state propagation/AME_PA_MF.png" alt="AME PA MF"></a>
    </div>
    <div class="ww-refs">
      <p>[1] V. Marceau, A. Allard, Adaptive Networks: Coevolution of Disease and Topology, Phys. Rev. E 82, 036116 (2010).</p>
    </div>
  </div>

  <div class="ww-card ww-proj">
    <span class="ww-stage">Master</span>
    <h3>International Citation Ratio (ICR) and Citation Preference</h3>
    <div class="ww-tags">
      <span class="ww-tag ww-tag-plain">Big data</span>
      <span class="ww-tag ww-tag-plain">Data processing</span>
      <span class="ww-tag ww-tag-plain">Evolution model</span>
      <span class="ww-tag ww-tag-plain">Citation network</span>
    </div>
    <p>Based on the data of Web of Science (WoS), Python was used to process the original XML data. I used the null model of random citation to further explore the key reason for the abnormal phenomenon that the proportion of foreign citations in total citations received by China has been dramatically decreasing compared to other main countries with large scientific output. By analogy with concentration problems, I found that the critical factor is the number of papers a country cites compared to others in a year, and successfully verified it with real data. In short, it can simply be attributed to this: the more you publish, the more likely you would suffer the pressure of ICR decline from others. Besides, the Z score (standard score) of citation has been calculated at country level to show the international citation preference of main countries. Meanwhile, the country-to-country Z score has shown an obvious clustering phenomenon, demonstrating the collaboration strength in the corresponding citation network. In this research, I cleaned and arranged the enormous original WoS data from 1970 to 2018, and generated a large number of structured data files for analysis and future work. This work is based on Google server with Python as the main programming language.</p>
    <p class="ww-status">Undergoing groupwork · first contributor · planned submission to Nature Communications.</p>
    <div class="ww-gallery-label">Phenomenon</div>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/Phenomenon"><img src="/Pics/CitationRatioPref/Phenomenon/BigNum_CN.png" alt="Big number CN"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/Phenomenon"><img src="/Pics/CitationRatioPref/Phenomenon/ICR_2010_2017.png" alt="ICR 2010-2017"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/Phenomenon"><img src="/Pics/CitationRatioPref/Phenomenon/ICR_2017.png" alt="ICR 2017"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/Phenomenon"><img src="/Pics/CitationRatioPref/Phenomenon/SelfCitationStrength.png" alt="Self citation strength"></a>
    </div>
    <div class="ww-gallery-label">Z-Score and Cluster</div>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/Z_Score"><img src="/Pics/CitationRatioPref/Z_Score/CitZscoreCluster.png" alt="Citation Z-score cluster"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/Z_Score"><img src="/Pics/CitationRatioPref/Z_Score/Zscore_NZscore_OtherToCN.png" alt="Z-score other to CN"></a>
    </div>
    <div class="ww-gallery-label">Experiment and Verification</div>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/ReferenceGrowthRate.png" alt="Reference growth rate"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/ICR_NullModel.png" alt="ICR null model"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/ImpactOnICR_CtryToCtry.png" alt="Country to country impact"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/ICR_CN_HalfRFGrowthRt_NullModel.png" alt="Half reference growth null model"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/ICR_CN_0.01RFGrowthRt_NullModel.png" alt="1% reference growth null model"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/ICR_CN_RFGrowthAsUS_OriData.png" alt="Reference growth as US"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/ICR_CN_PubGrowthAsUS_OriData.png" alt="Publication growth as US"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CitationRatioPref/ReferenceGrowthRate"><img src="/Pics/CitationRatioPref/ReferenceGrowthRate/IN_ICR_NOCN2.png" alt="India ICR with/without CN"></a>
    </div>
  </div>

  <div class="ww-card ww-proj">
    <span class="ww-stage">Master</span>
    <h3>Influence of Counting Methods on Institution Level Ranking</h3>
    <div class="ww-tags">
      <span class="ww-tag ww-tag-plain">Big data</span>
      <span class="ww-tag ww-tag-plain">Natural language processing</span>
      <span class="ww-tag ww-tag-plain">Named entity identification</span>
      <span class="ww-tag ww-tag-plain">Counting methods</span>
    </div>
    <p>The ranking of academic bodies (e.g. country, institution and person) will unavoidably measure their research output and impact. Publication and citation are the most widely used indexes. Generally, publication number reflects the academic volume, while citation received shows the scientific impact to some extent. However, different counting methods have various ranking results. Since Marianne Gauffriau gave a normative and rigorous definition of counting methods<sup>[2]</sup>, while many so-called institution-level rankings only discussed universities, it's necessary to take this opportunity to carry out a complete and accurate research on this topic. However, as many institutions have more than one formal name in the database, disambiguation (named entity identification) is an essential step before any further operation. After processing the original WoS data, I've raised a rule-based method which combines different approaches<sup>[3]</sup> to disambiguate the institutions in the database (<a href="https://github.com/WangWH0101/Named-Entity-Identification">Specific Method</a>). Then, a total of six counting methods are utilized for publication and citation counting at institution level in WoS data between 2000 and 2016. So far, the main discovery is that the six defined methods can be further divided into three types, which can provide guidance for future counting-method choosing.</p>
    <p class="ww-status">Group work led by me · first contributor · still unfinished.</p>
    <div class="ww-gallery-label">Institution Name Disambiguation (sample)</div>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CountMethod"><img src="/Pics/CountMethod/InsDisamSample.jpg" alt="Institution disambiguation sample"></a>
    </div>
    <div class="ww-gallery-label">Counting Methods</div>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CountMethod"><img src="/Pics/CountMethod/CountMethodClassf.jpg" alt="Counting method classification"></a>
    </div>
    <div class="ww-gallery-label">Ranking in CS (sample) · Methods Classification (sample)</div>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CountMethod"><img src="/Pics/CountMethod/RankSample.jpg" alt="Ranking sample"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/CountMethod"><img src="/Pics/CountMethod/SpearmanCo.png" alt="Spearman correlation"></a>
    </div>
    <div class="ww-refs">
      <p>[2] Marianne Gauffriau. Counting methods introduced into the bibliometric research literature 1970–2018: A review. <i>Quantitative Science Studies</i> (2021). <a href="https://doi.org/10.1162/qss_a_00141">doi.org/10.1162/qss_a_00141</a></p>
      <p>[3] Huang S., Ronald R. &amp; Yang B. Institution name disambiguation for research assessment. <i>Scientometrics</i>, 2014.</p>
    </div>
  </div>

  <div class="ww-card ww-proj">
    <span class="ww-stage">Collaborative · Interdisciplinary</span>
    <h3>Modulation of Leaf Color Change Date and Period</h3>
    <div class="ww-tags">
      <span class="ww-tag ww-tag-plain">Big data</span>
      <span class="ww-tag ww-tag-plain">Prediction</span>
      <span class="ww-tag ww-tag-plain">Leaf coloration peak date</span>
      <span class="ww-tag ww-tag-plain">Climatic variables</span>
      <span class="ww-tag ww-tag-plain">Generalized additive regression</span>
    </div>
    <p>The ecotourism based on plants with leaves of changing color has become a new economic growth point for some regions, while it's also a kind of sustainable development. In order to maximize the economic benefits, it's necessary to predict both the best sightseeing date and lasting time window. In this study, we used the generalized additive model (GAM) for prediction based on the long-term data we collected. The importance of deciduous plants' autumn phenological phase is reflected not only in the material cycle but also in the fall foliage ecotourism industry. However, the lack of observation data has made it difficult to model the phase of deciduous plants in the high-elevation karst region. Based on the data between 2001 and 2020, methods including multiple linear regression, multivariate binomial regression, robust regression, ridge regression, elastic net, and generalized additive regression were utilized to find out the correlation of the temperature and the precipitation with <i>Cotinus coggygria</i>'s leaf coloration peak date variation in the related regions of China. The mean absolute error, root mean squared error, coefficient of determination, and ratio of performance to interquartile distance were applied to evaluate the prediction accuracy. The generalized additive model's better performance suggested its capacity as a useful tool in prediction. The results showed that the increase of prophase temperature and the decrease of prophase precipitation could delay the leaf coloration peak date, while the date could be earlier on the contrary. Besides, the number of days with the daily maximum temperature continuously above 20°C before November 10th exerted the highest contribution in the prediction of the date. Moreover, we showed that a higher average diurnal temperature range in mid-May could defer the date as an objective contributor in prediction. This indirectly reveals the importance of the spring phenological phase in predicting the autumn phenological phase. Finally, the model forecasted a trend of the leaf coloration peak date delay from 2021 to 2100 under different emissions scenarios, showing the effects of warming on the plant's growth season and even the development of ecotourism.</p>
    <p class="ww-status">Group work · participated as data processor and paper reviewer.</p>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/ColorLfPredic"><img src="/Pics/ColorLfPredic/Location.jpg" alt="Study location"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/ColorLfPredic"><img src="/Pics/ColorLfPredic/Parameters.jpg" alt="Parameters"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/ColorLfPredic"><img src="/Pics/ColorLfPredic/RegressionMethods.jpg" alt="Regression methods"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/ColorLfPredic"><img src="/Pics/ColorLfPredic/MethodComp2.png" alt="Method comparison"></a>
    </div>
  </div>

  <div class="ww-card ww-proj">
    <span class="ww-stage">Collaborative · Interdisciplinary</span>
    <h3>Weeding Equipment Platform</h3>
    <div class="ww-tags">
      <span class="ww-tag ww-tag-plain">Visual navigation</span>
      <span class="ww-tag ww-tag-plain">Computer vision</span>
      <span class="ww-tag ww-tag-plain">Weeding</span>
      <span class="ww-tag ww-tag-plain">Soft shaft</span>
      <span class="ww-tag ww-tag-plain">Seedling avoidance</span>
      <span class="ww-tag ww-tag-plain">Tobacco field</span>
    </div>
    <p>Tobacco is an important cash crop, while the vigorous weeds in the tobacco field have been seriously affecting the growth and development of tobacco plants, resulting in the reduction of related products' yield and quality. Therefore, the weeds in tobacco fields should be removed in time after uncovering the film. However, manual weeding with high labor intensity and low efficiency in hilly and mountainous areas has been a common phenomenon in China. As a result, I've cooperated with students from the College of Engineering and Technology to develop a self-driving weeding platform suitable for relevant areas. Due to the complexity and variability in the work environment, reinforcement learning was chosen as the approach for self-driving in the fields. We've already built the hardware of the platform and got a patent. Specifically, the equipment mainly consists of a weeding mechanism with soft shaft and a seedling avoidance mechanism. We are now working on the self-driving part with the help of Donkeycar<sup>[4]</sup>, which is based on reinforcement learning. A virtual environment of a typical field has been built in Unity to pre-train the model and adjust the parameters.</p>
    <p class="ww-status">Weeding robot development research, invited by my friend in the College of Engineering and Technology.</p>
    <div class="ww-gallery">
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Mower"><img src="/Pics/Mower/MowerDesign.png" alt="Mower design"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Mower"><img src="/Pics/Mower/UnityEnv1.png" alt="Unity environment 1"></a>
      <a href="https://github.com/WangWH0101/WangWH0101.github.io/tree/main/Pics/Mower"><img src="/Pics/Mower/UnityEnv22.png" alt="Unity environment 2"></a>
    </div>
    <div class="ww-refs">
      <p>[4] Donkeycar documentation: <a href="https://docs.donkeycar.com/">docs.donkeycar.com</a></p>
    </div>
  </div>
</section>

<section class="ww-section" id="more">
  <div class="ww-section-head">
    <h2>More About Me</h2>
  </div>
  <div class="ww-grid">
    <div class="ww-card ww-mini">
      <h3>Grades</h3>
      <div class="ww-kv"><b>Undergraduate</b> · Theoretical Physics</div>
      <div class="ww-kv">GPA: <b>3.53</b> (compulsory) / <b>3.54</b> (all)</div>
      <div class="ww-kv">Scores: <b>86.32</b>/100 (compulsory) · <b>86.46</b>/100 (all)</div>
      <div class="ww-kv"><a href="/Grades/UndergraduateScore.pdf">Undergraduate transcript →</a></div>
      <div class="ww-kv" style="margin-top:12px;"><b>Master</b> · Network Science and Big Data</div>
      <div class="ww-kv">GPA: <b>3.74</b> (all courses)</div>
      <div class="ww-kv">Scores: <b>87.64</b>/100 (all courses)</div>
      <div class="ww-kv"><a href="/Grades/PostGraduateScore.jpg">Master transcript →</a></div>
    </div>
    <div class="ww-card ww-mini">
      <h3>Languages</h3>
      <div class="ww-kv"><b>Chinese</b> · Native</div>
      <div class="ww-kv"><b>English</b> · TOEFL <b>106</b> (2021/05/26)</div>
      <div class="ww-kv"><b>Japanese</b> · A little bit</div>
      <img src="/Pics/Others/TOEFL.png" alt="TOEFL score report">
      <div class="ww-kv"><a href="/Pics/Others/TOEFL_Score20210526.pdf">Official TOEFL score report →</a></div>
    </div>
    <div class="ww-card ww-mini">
      <h3>Programming</h3>
      <div class="ww-tags" style="margin-bottom:14px;">
        <span class="ww-tag ww-tag-plain">Python</span>
        <span class="ww-tag ww-tag-plain">Java</span>
        <span class="ww-tag ww-tag-plain">C++/C</span>
        <span class="ww-tag ww-tag-plain">Matlab</span>
      </div>
      <p>Daily drivers for data processing, modeling, and autonomous-driving R&amp;D.</p>
    </div>
  </div>
</section>

<footer class="ww-foot">
  <div>© 2026 Weihan Wang · Built with Markdown on GitHub Pages</div>
  <div><a href="mailto:wangwh0101@gmail.com">Email</a> &nbsp;·&nbsp; <a href="https://github.com/WangWH0101">GitHub</a></div>
</footer>

</div>
