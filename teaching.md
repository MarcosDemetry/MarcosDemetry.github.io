---
layout: page
title: Teaching
---

<style>
/* ---- scoped to the teaching page widgets only ---- */
.teaching-viz { font-family: 'Open Sans','Helvetica Neue',Helvetica,Arial,sans-serif; margin: 0 0 2.5rem; }

/* per-level course groups */
.tv-group { margin: 0 0 1.4rem; }
.tv-group > h4 { font-size: 0.72rem; letter-spacing: .06em; text-transform: uppercase; color: #999; margin: 0 0 0.55rem; font-weight: 700; }
.tv-chips { display: flex; flex-wrap: wrap; gap: 0.45rem; }

.tv-chip { display: inline-flex; align-items: center; gap: 0.4rem; border: none; border-radius: 8px; padding: 0.4rem 0.75rem; font-size: 0.86rem; font-family: inherit; color: #fff; line-height: 1.25; cursor: pointer; text-align: left; transition: transform .12s, opacity .18s, box-shadow .12s; }
.tv-chip:hover { transform: translateY(-1px); box-shadow: 0 2px 6px rgba(0,0,0,.18); }
.tv-chip .count { font-size: 0.68rem; opacity: 0.9; background: rgba(255,255,255,.22); border-radius: 999px; padding: 0.05rem 0.45rem; }
.tv-chip .role  { font-size: 0.66rem; opacity: 0.85; border: 1px solid rgba(255,255,255,.5); border-radius: 4px; padding: 0 0.3rem; }
.tv-chip.lv-ug  { background: #2a9d8f; }
.tv-chip.lv-ma  { background: #4361a8; }
.tv-chip.lv-phd { background: #9b3d6b; }
.tv-chip[aria-expanded="true"] { box-shadow: 0 0 0 2px rgba(0,0,0,.2) inset; }

/* detail panel shown under a course group when a chip is pressed */
.tv-detail { margin: 0.6rem 0 0; padding: 0.75rem 1rem; border-left: 3px solid #ccc; background: #fafafa; border-radius: 0 8px 8px 0; font-size: 0.9rem; color: #444; line-height: 1.55; display: none; }
.tv-detail.show { display: block; }
.tv-detail.lv-ug  { border-left-color: #2a9d8f; }
.tv-detail.lv-ma  { border-left-color: #4361a8; }
.tv-detail.lv-phd { border-left-color: #9b3d6b; }
.tv-detail .tv-detail-title { font-weight: 700; color: #303030; }
.tv-detail .tv-terms { display: block; margin-top: 0.4rem; font-size: 0.8rem; color: #777; }

/* ---- bottom bar chart: courses per semester ---- */
.tv-chart { font-family: 'Open Sans','Helvetica Neue',Helvetica,Arial,sans-serif; margin: 1.5rem 0 1rem; }
.tv-bars { display: flex; align-items: flex-end; gap: 0.5rem; height: 170px; padding-top: 1.4rem; border-bottom: 2px solid #e6e6e6; }
.tv-bar { flex: 1 1 0; height: 100%; display: flex; flex-direction: column-reverse; justify-content: flex-start; min-width: 0; position: relative; }
.tv-bar .seg { width: 100%; }
.tv-bar .seg.lv-ug  { background: #2a9d8f; }
.tv-bar .seg.lv-ma  { background: #4361a8; }
.tv-bar .seg.lv-phd { background: #9b3d6b; }
.tv-bar .seg:first-child { border-radius: 3px 3px 0 0; }
.tv-bar .total { position: absolute; top: -1.15rem; left: 0; right: 0; text-align: center; font-size: 0.72rem; font-weight: 700; color: #777; }
.tv-xlabels { display: flex; gap: 0.5rem; margin-top: 0.35rem; }
.tv-xlabels span { flex: 1 1 0; text-align: center; font-size: 0.62rem; color: #999; min-width: 0; }

@media (max-width: 480px) {
  .tv-xlabels span { font-size: 0.5rem; }
  .tv-bars { gap: 0.25rem; }
}
</style>

I've given **39 lectures**, **39 exercise sessions**, **3 computer labs**, and **13 teaching seminars** in a variety of economics courses. All the courses below are at **Linnaeus University** and **Uppsala University**. Click any course for its details.

<div class="teaching-viz">

  <div class="tv-group">
    <h4>Undergraduate</h4>
    <div class="tv-chips">
      <button class="tv-chip lv-ug" data-level="ug"
        data-terms="Spring 2023, Spring 2024, Spring 2025, Spring 2026"
        data-detail="5 lectures for a first-year undergraduate course, focusing on production theory, competitive markets and monopolies. Taught on both the Kalmar and Växjö campuses.">Introductory Microeconomics <span class="count">×4</span></button>
      <button class="tv-chip lv-ug" data-level="ug"
        data-terms="Autumn 2022"
        data-detail="2 lectures and 1 exercise session for a second-year undergraduate course, focusing on externalities, public goods and asymmetric information.">Intermediate Microeconomics</button>
      <button class="tv-chip lv-ug" data-level="ug"
        data-terms="Spring 2024"
        data-detail="Grading for a distance undergraduate microeconomics course.">Mikroekonomi <span class="role">grading</span></button>
      <button class="tv-chip lv-ug" data-level="ug"
        data-terms="Spring 2024"
        data-detail="Teaching assistant for a second-year undergraduate course. I developed 3 computer labs on project-flow management and on gathering, cleaning, and visualizing data — evaluating real, previously unstudied Swedish reforms with students as inspiration for their term papers and theses.">Public Policy Evaluation with Big Data <span class="role">TA</span></button>
      <button class="tv-chip lv-ug" data-level="ug"
        data-terms="Autumn 2017, Spring 2018, Autumn 2018 — Uppsala University"
        data-detail="8 exercise sessions per semester for a second-year undergraduate course at Uppsala University. As teaching assistant I helped students navigate microeconomics and game theory through discussions, solving exercises on the board, and one-on-one help — once a week, three hours long. Student feedback rose from 4.0/5.0 in my first semester to 4.8/5.0 in my third and last.">Microeconomics with Applications <span class="role">TA</span></button>
      <button class="tv-chip lv-ug" data-level="ug"
        data-terms="2019 — Uppsala University"
        data-detail="3 seminars for a first-year undergraduate course at Uppsala University. As seminar leader I discussed and evaluated students' term papers and presentations on economic theory and its applications. Students produced a paper across the seminars and, in the final one, both presented and defended it.">Principles of Micro- and Macroeconomics <span class="role">TA</span></button>
    </div>
    <div class="tv-detail-slot"></div>
  </div>

  <div class="tv-group">
    <h4>Master's</h4>
    <div class="tv-chips">
      <button class="tv-chip lv-ma" data-level="ma"
        data-terms="Autumn 2022, Autumn 2024, Autumn 2025"
        data-detail="2 lectures and 2 exercise sessions for a master's course, focusing on welfare, market inefficiencies, and behavioral economics with applications to environmental sustainability. (In 2022 the course had a single exercise session.)">Advanced Microeconomics <span class="count">×3</span></button>
      <button class="tv-chip lv-ma" data-level="ma"
        data-terms="Autumn 2024, Autumn 2025"
        data-detail="2 lectures and 2 exercise sessions for a master's course in mathematical economics.">Advanced Mathematical Economics <span class="count">×2</span></button>
      <button class="tv-chip lv-ma" data-level="ma"
        data-terms="Spring 2025, Spring 2026"
        data-detail="3 lectures for a master's course on economic methodology.">Advanced Economic Methodology <span class="count">×2</span></button>
      <button class="tv-chip lv-ma" data-level="ma"
        data-terms="Spring 2026"
        data-detail="4 exercise sessions for a master's course in public economics.">Public Economics</button>
      <button class="tv-chip lv-ma" data-level="ma"
        data-terms="Spring 2024, Spring 2025, Spring 2026"
        data-detail="3 seminars for a master's course on behavioral economics for economic policy and decision-making.">Behavioral Economics for Economic Policy and Decision-Making <span class="count">×3</span></button>
      <button class="tv-chip lv-ma" data-level="ma"
        data-terms="Autumn 2024"
        data-detail="1 seminar for a master's course on data-driven decision-making.">Data-Driven Decisionmaking</button>
      <button class="tv-chip lv-ma" data-level="ma"
        data-terms="Spring 2024"
        data-detail="1 lecture for a master's course in environmental economics.">Environmental Economics</button>
    </div>
    <div class="tv-detail-slot"></div>
  </div>

  <div class="tv-group">
    <h4>PhD</h4>
    <div class="tv-chips">
      <button class="tv-chip lv-phd" data-level="phd"
        data-terms="Spring 2026"
        data-detail="1 exercise session for a PhD course in econometrics.">Econometrics</button>
    </div>
    <div class="tv-detail-slot"></div>
  </div>

</div>

<!--
Student feedback for my Uppsala mentorship sessions was overwhelmingly positive — from 4.0/5.0 in my first semester to **4.8/5.0** in my third and last. Here's what attendance looked like across the three semesters:

<img src="/assets/img/micro_attendance.png" alt="micro_attendance" width="100%"/>
-->

#### Number of courses taught each year by academic level

<div class="tv-chart">
  <div class="tv-bars">
    <div class="tv-bar"><span class="total">1</span><div class="seg lv-ug" style="height:11%"></div></div>
    <div class="tv-bar"><span class="total">2</span><div class="seg lv-ug" style="height:22%"></div></div>
    <div class="tv-bar"><span class="total">1</span><div class="seg lv-ug" style="height:11%"></div></div>
    <div class="tv-bar"></div>
    <div class="tv-bar"></div>
    <div class="tv-bar"><span class="total">2</span><div class="seg lv-ug" style="height:11%"></div><div class="seg lv-ma" style="height:11%"></div></div>
    <div class="tv-bar"><span class="total">1</span><div class="seg lv-ug" style="height:11%"></div></div>
    <div class="tv-bar"><span class="total">8</span><div class="seg lv-ug" style="height:33%"></div><div class="seg lv-ma" style="height:55%"></div></div>
    <div class="tv-bar"><span class="total">5</span><div class="seg lv-ug" style="height:11%"></div><div class="seg lv-ma" style="height:44%"></div></div>
    <div class="tv-bar"><span class="total">5</span><div class="seg lv-ug" style="height:11%"></div><div class="seg lv-ma" style="height:33%"></div><div class="seg lv-phd" style="height:11%"></div></div>
  </div>
  <div class="tv-xlabels">
    <span>2017</span><span>2018</span><span>2019</span><span>2020</span><span>2021</span><span>2022</span><span>2023</span><span>2024</span><span>2025</span><span>2026</span>
  </div>
</div>

<script>
(function () {
  var viz = document.querySelector('.teaching-viz');
  if (!viz) return;

  function levelClass(el) {
    return Array.prototype.find.call(el.classList, function (c) { return c.indexOf('lv-') === 0; });
  }

  // --- click a course to reveal its detail (one open per level group) ---
  viz.querySelectorAll('.tv-chip').forEach(function (chip) {
    chip.setAttribute('aria-expanded', 'false');
    chip.addEventListener('click', function () {
      var group = chip.closest('.tv-group');
      var slot = group.querySelector('.tv-detail-slot');
      var wasOpen = chip.getAttribute('aria-expanded') === 'true';
      // collapse whatever is open in this group
      group.querySelectorAll('.tv-chip[aria-expanded="true"]').forEach(function (c) { c.setAttribute('aria-expanded', 'false'); });
      slot.innerHTML = '';
      slot._owner = null;
      if (wasOpen) return;
      // build this chip's detail
      var lv = levelClass(chip);
      var title = chip.textContent.replace(/×\d+\s*$/, '').trim();
      var panel = document.createElement('div');
      panel.className = 'tv-detail show ' + lv;
      panel.innerHTML = '<span class="tv-detail-title">' + title + '</span>: ' + chip.dataset.detail +
        '<span class="tv-terms">Taught: ' + chip.dataset.terms + '</span>';
      slot.appendChild(panel);
      slot._owner = chip;
      chip.setAttribute('aria-expanded', 'true');
    });
  });
})();
</script>
