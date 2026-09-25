---
layout: archive
title: "Impact"
permalink: /impact/
author_profile: true
---

{% include base_path %}

<style>
.impact-lede {
  font-size: 16px;
  line-height: 1.7;
  color: #555;
  margin-bottom: 36px;
}

details.impact-project {
  margin: 0;
  padding: 0;
  border: 0;
}

details.impact-project + details.impact-project {
  border-top: 1px solid #e5e7eb;
  margin-top: 28px;
  padding-top: 28px;
}

details.impact-project[open] {
  padding-bottom: 20px;
}

summary.project-summary {
  display: block;
  list-style: none;
  cursor: pointer;
  padding: 6px 0 2px 0;
  border-radius: 4px;
}

summary.project-summary::-webkit-details-marker {
  display: none;
}

summary.project-summary::marker {
  content: "";
}

summary.project-summary:focus {
  outline: none;
}

summary.project-summary:focus-visible {
  outline: 3px solid #4c8bf5;
  outline-offset: 4px;
}

.summary-head {
  display: flex;
  align-items: flex-start;
  gap: 14px;
}

summary.project-summary .project-title {
  flex: 1 1 auto;
  min-width: 0;
}

.summary-chevron {
  flex: 0 0 auto;
  align-self: flex-start;
  margin-top: 12px;
  color: #6a7480;
  transition: transform 220ms ease;
  transform: rotate(0deg);
  line-height: 0;
}

.summary-chevron::before {
  content: "";
  display: block;
  width: 10px;
  height: 10px;
  border-right: 2.5px solid currentColor;
  border-bottom: 2.5px solid currentColor;
  transform: rotate(45deg) translate(-1px, -1px);
}

details.impact-project[open] > summary.project-summary .summary-chevron {
  transform: rotate(180deg);
}

.project-title {
  font-size: 26px;
  font-weight: 700;
  color: #0051a5;
  margin: 0 0 6px 0;
  line-height: 1.25;
}

.project-meta {
  font-size: 14px;
  color: #6a7480;
  margin-bottom: 22px;
  line-height: 1.5;
}

summary.project-summary .project-intro {
  margin-bottom: 6px;
}

.project-intro {
  font-size: 16px;
  line-height: 1.85;
  color: #333;
  margin-bottom: 24px;
}

.project-collapse {
  padding-top: 14px;
}

.project-figure {
  margin: 0 0 30px 0;
}

.project-figure img {
  width: 100%;
  height: auto;
  display: block;
  border: 1px solid #e5e7eb;
  border-radius: 4px;
}

.project-figure figcaption {
  font-size: 13px;
  color: #666;
  margin-top: 8px;
  line-height: 1.55;
}

.project-figure .stacked > img {
  margin-bottom: 10px;
}

.video-embed {
  position: relative;
  width: 100%;
  padding-top: 56.25%; /* 16:9 */
  background: #f2f4f7;
  border: 1px solid #e5e7eb;
  border-radius: 4px;
  overflow: hidden;
}

.video-embed iframe,
.video-embed .video-placeholder {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0;
}

.video-embed .video-placeholder {
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  color: #6a7480;
  font-size: 14px;
  padding: 20px;
  line-height: 1.55;
}

.project-h3 {
  font-size: 17px;
  font-weight: 700;
  color: #1a1a1a;
  margin-top: 32px;
  margin-bottom: 10px;
  padding-bottom: 6px;
  border-bottom: 1px solid #e5e7eb;
}

.project-body p {
  font-size: 15px;
  line-height: 1.8;
  color: #333;
  margin-bottom: 14px;
}

.project-body .in-practice p {
  margin-bottom: 12px;
}

.project-body .in-practice p strong {
  color: #1a1a1a;
}

.project-refs {
  list-style: none;
  padding: 0;
  margin: 12px 0 0 0;
}

.project-refs li {
  font-size: 14.5px;
  line-height: 1.7;
  color: #333;
  padding: 8px 0;
  border-bottom: 1px solid #eef1f4;
}

.project-refs li:last-child {
  border-bottom: none;
}

.pdf-link {
  color: #2a7ae2;
  font-weight: 700;
  text-decoration: none;
  margin-left: 6px;
}

.pdf-link:hover {
  text-decoration: underline;
}
</style>

<div class="impact-lede">Selected projects and what came of them.</div>

<details class="impact-project" id="har-zindagi">
<summary class="project-summary">
<div class="summary-head">
<h2 class="project-title">Har Zindagi: Making childhood immunization records useful to families and vaccinators</h2>
<span class="summary-chevron" aria-hidden="true"></span>
</div>
<div class="project-meta">Punjab, Pakistan · 2015&ndash;2017 · Principal investigator · Funded by DFID through the Sub-National Governance Programme</div>
<p class="project-intro">A child's immunization record has to work for several people at once: a caregiver keeping track of the next visit, a vaccinator recording what happened, and a health system trying to reach every child. As principal investigator of Har Zindagi ("Every Life Matters"), I led a team working with Punjab's Expanded Program on Immunization to redesign that record end to end, pairing a more legible physical card with an Android app that vaccinators used to create digital records in the field.</p>
</summary>

<div class="project-collapse">

<figure class="project-figure">
  <img src="{{ base_path }}/images/harzindagi.png" alt="Photograph of the redesigned Har Zindagi immunization booklet, open to the six-week visit. The left page shows date-of-visit fields for OPV-1, Penta-1, PCV 10-1, and Rotavirus-1, each color coded and paired with an icon of the body system the vaccine protects. The right page marks the child's developmental stage in Urdu ('6-week-old child') and illustrates three milestones with pictorial captions." />
  <figcaption>The deployed immunization booklet, open to the six-week visit. Each vaccine row carries a distinct color and an icon of the body system it protects; the facing page marks the child's developmental stage. Photograph from the project team.</figcaption>
</figure>

<div class="project-body">

<h3 class="project-h3">Motivation</h3>
<p>Interviews with 69 caregivers and five vaccinators showed that most caregivers already kept the card carefully and many read Urdu or Punjabi, so a next-visit date they could read at a glance and a schedule they could follow at home would let them plan each visit themselves. Vaccinators wanted a record they could complete wherever the visit happened, with or without a network. A card that served both, and smoothed the handoff between them, became the brief for the project.</p>

<h3 class="project-h3">The card</h3>
<p>We tested three prototypes with caregivers and vaccinators across six districts over roughly two months. The deployed booklet gives each visit its own color-coded page, marks the child's developmental stage on that page, pairs each vaccine with an icon of the body system it protects, adds a page for the mother's own vaccinations, and uses passport-style materials and a Government of Punjab monogram so that the document reads as one worth keeping. An embedded NFC chip linked the paper record to the child's digital record. Field testing showed that the pictorial guidance worked best when a vaccinator walked caregivers through it, so we designed the card as a conversation aid as well as a record.</p>

<h3 class="project-h3">The app</h3>
<p>The Android app went through three iterations with vaccinators before field testing. Vaccinators could create records offline and upload them when a signal returned, so they could finish a day's work in a village and sync on the way home. Tapping a card's chip opened the correct visit, and a search by booklet number or phone number served families who arrived without a card. Visit pages in the app used the same colors as the card, so paper and screen read as one document. Vaccinators told us their daily routes were already agreed with their supervisors, so we retired a route-planning feature and put that effort into the screens they used all day. In usability testing, most of 50 vaccinators in Sahiwal and Sheikhupura completed child registration on their own, and the few errors pointed us to specific data-entry fields to refine.</p>

<h3 class="project-h3">Seven-month field deployment</h3>
<div class="in-practice">
<p><strong>Pilot.</strong> Over seven months in Sahiwal and Sheikhupura, 50 government vaccinators used the app to create digital records for more than 20,000 children across more than 90,000 visits.</p>
<p><strong>Adoption.</strong> The Government of Punjab adopted a modified version of the card's visual design and printed approximately four million cards annually; the NFC link and the app remained our research prototype.</p>
<p><strong>Publications.</strong> Two peer-reviewed papers (ICTD 2016; ACM DEV 2016) document the card and app redesigns and the ways in which caregiver and vaccinator feedback shaped the system.</p>
</div>

<h3 class="project-h3">Team</h3>
<p>As principal investigator, I led the project and the card redesign, and coordinated with the Government of Punjab to secure approval to pilot the card and app with state-appointed vaccinators. Samia Razaq was the project's technical lead and led the design of the mobile app and dashboard; she is first author on the system paper. Amna Batool is first author on the card paper and led the caregiver fieldwork. Umair Ali and Muhammad Salman Khalid contributed to fieldwork and system development. Umar Saif of Information Technology University, Lahore, was a senior collaborator. Ali Murtaza, design consultant, created the visual identity of the booklet and program; his images appear on his portfolio, linked below. Ali Imran, Ahmed Mehmood, Bilal Saleem, Shaheryar Khan, and Ali Abbas Jaffri developed the Android app.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li>Batool, A., Ali, U., Razaq, S., &amp; <strong>Naseem, M.</strong> (2016). Child Immunization Health Card Redesign: an Iterative, User-Centered Approach. <em>ICTD 2016</em>. <a href="{{ base_path }}/files/2016_Immunization card redesign.pdf" class="pdf-link">[PDF]</a></li>
  <li>Razaq, S., Batool, A., Ali, U., Khalid, M. S., Saif, U., &amp; <strong>Naseem, M.</strong> (2016). Iterative Design of an Immunization Information System in Pakistan. <em>ACM DEV 2016</em>. DOI: <a href="https://doi.org/10.1145/3001913.3001925">10.1145/3001913.3001925</a>. <a href="{{ base_path }}/files/2016_immunization information system.pdf" class="pdf-link">[PDF]</a></li>
  <li>Ali Murtaza. Har Zindagi (Every Life) Immunization Program Design. <em>Behance</em>. <a href="https://www.behance.net/gallery/48482987/Har-Zindagi-(Every-Life)-Immunization-Program-Design" class="pdf-link">[link]</a></li>
</ul>

</div>

</div>
</details>

<details class="impact-project" id="water-atms">
<summary class="project-summary">
<div class="summary-head">
<h2 class="project-title">Water ATMs: Helping Lahore's water utility see its filtration plants at work</h2>
<span class="summary-chevron" aria-hidden="true"></span>
</div>
<div class="project-meta">Lahore, Pakistan · 2017&ndash;2020 · U.S. principal investigator · Funded by the Pakistan-U.S. Science and Technology Cooperation Program</div>
<p class="project-intro">Many families in Lahore collect their drinking water from public filtration plants: neighborhood taps run by the city's water utility, WASA Lahore, where the water is free and carried home in jerry cans. A utility that can see each plant at work can keep the water flowing, fix a leaking tap the day it starts, and plan where the next plant should go. Together with Dr. Tauseef Tauqeer at Information Technology University, Lahore, I co-led a three-year project to build a low-cost sensing unit that gives the utility that view, and to pair the engineering with fieldwork on how low-income residents of Lahore get their water.</p>
</summary>

<div class="project-collapse">

<figure class="project-figure">
  <div class="video-embed" data-video-src="https://www.youtube.com/embed/TSojzm678kM" data-video-title="Water ATMs, a five-minute documentary by Haya Fatima Iqbal">
    <div class="video-placeholder">Film embed reserved (responsive 16:9). Iframe src will be added when the URL is supplied.</div>
  </div>
  <figcaption>A five-minute film about the project by documentary filmmaker Haya Fatima Iqbal. It follows residents collecting water at Lahore's filtration plants and includes conversations with Dr. Tauseef Tauqeer, WASA Lahore managing director Zahid Aziz, and me.</figcaption>
</figure>

<div class="project-body">

<h3 class="project-h3">Motivation</h3>
<p>Lahore draws its drinking water from an aquifer through some 600 tube wells, and WASA's filtration plants purify that water and hand it out free of charge. A flow sensor on every tap shows the utility when a tap has been left running, whether a plant opened on schedule for the families arriving with jerry cans, and how much each plant dispensed at which hours of the day. That view lets WASA keep every plant running well and shows where demand is growing. I wanted the system to be affordable enough for a public utility in Pakistan to put on every plant in the city, at a fraction of the cost of commercial monitoring built for industrial facilities.</p>

<h3 class="project-h3">The unit</h3>
<p>Water ATMs in India dispense water against a prepaid card; because WASA wanted Lahore's water to stay free and open to everyone, our unit simply measures what each tap dispenses. We fitted each of a plant's seven taps with an inline flow meter wired to a microcontroller that cost about five dollars. A battery carried the unit through Lahore's daily power cuts, and the chip stored readings and uploaded them whenever the plant's WiFi dongle had a signal. A second sensor package measured five water quality parameters every hour, pH, temperature, total dissolved solids, electrical conductivity, and dissolved oxygen, and raised an alarm when a reading fell outside its range. Low-cost sensors in a demanding environment produce noisy readings, so we built the cleaning into the pipeline; plant staff told us that nobody draws less than a glass of water, so transactions under 150 milliliters became our signature for a leaking tap. The dashboard displayed plant uptime, busy hours, liters dispensed, liters lost to leaks, and taps due for attention.</p>

<h3 class="project-h3">Qualitative inquiry</h3>
<p>Sabah Pirani, my master's student at Michigan, led the qualitative study of how Lahore's urban poor obtain and use water, combining observation at filtration plants and in people's homes with 39 semi-structured interviews with residents, the water utility, NGOs, and water researchers. She found a strikingly positive reception of the filtration plants: most respondents used them for drinking water or aspired to, and trusted the water they provided. Households drawing water from WASA worried most about contamination, while households with their own borewells felt the falling water table directly. Her thesis, co-advised by Kentaro Toyama, recommends a public inventory of filtration plants and an aquifer users' association to share the cost of Lahore's groundwater more equitably.</p>

<h3 class="project-h3">Field deployment</h3>
<div class="in-practice">
<p><strong>Deployment.</strong> After a six-month pilot at one plant, we signed a memorandum of understanding with WASA Lahore and installed units at six of its filtration plants. The units logged more than 42,000 transactions and 1.28 million liters of drinking water, streamed live to a web dashboard that WASA staff and policymakers could open from anywhere.</p>
<p><strong>Film.</strong> Documentary filmmaker Haya Fatima Iqbal made a five-minute film about the project, in which WASA's managing director describes the system identifying faults automatically and the utility's goal of bringing every WASA installation online.</p>
<p><strong>What lasted.</strong> Tauseef's lab at ITU went on to win funding from WASA to monitor Lahore's tube wells, and he founded a company to take the monitoring units to market. ITU's D-Lab course used the project as a case study in designing for underserved communities.</p>
<p><strong>Publications.</strong> A MobiCom 2020 poster describes the unit and the data pipeline, and Sabah Pirani's master's thesis presents the qualitative study.</p>
</div>

<h3 class="project-h3">Team</h3>
<p>I was the U.S. principal investigator and co-led the project with Dr. Tauseef Tauqeer, the Pakistani principal investigator, whose Industrial Monitoring and Automation Lab at ITU designed, built, and maintained the units in the field. Zill Ullah Khan and M. Umair Anwar led the hardware and firmware work and are first authors on the MobiCom paper. Sabah Pirani led the qualitative study and wrote her master's thesis on it, co-advised by Kentaro Toyama. Faisal Lalani and Babatunde Adegoke are co-authors on the paper. Arman Rezaee at Michigan collaborated on the project. Haya Fatima Iqbal made the film.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li>Khan, Z. U., Anwar, M. U., Pirani, S., Lalani, F., Adegoke, B., Tauqeer, T., &amp; <strong>Naseem, M.</strong> (2020). Poster: Design of an IoT-based water flow monitoring system. <em>MobiCom 2020</em>. DOI: <a href="https://doi.org/10.1145/3372224.3418170">10.1145/3372224.3418170</a>.</li>
  <li>Pirani, S. (2020). Differential Access: Water Infrastructure and Water Quality Awareness among Lahore's Urban Poor. <em>Master's thesis, University of Michigan School of Information</em>. DOI: <a href="https://doi.org/10.7302/1714">10.7302/1714</a>.</li>
  <li>Haya Fatima Iqbal. [Film title]. Five-minute documentary. <a href="https://youtu.be/TSojzm678kM" class="pdf-link">[link]</a></li>
</ul>

</div>

</div>
</details>

<script>
(function () {
  var projects = document.querySelectorAll('details.impact-project');
  if (!projects.length) return;

  function loadVideosIn(details) {
    var embeds = details.querySelectorAll('.video-embed[data-video-src]');
    for (var i = 0; i < embeds.length; i++) {
      var embed = embeds[i];
      var src = embed.getAttribute('data-video-src');
      if (!src) continue;
      if (embed.querySelector('iframe')) continue;
      var iframe = document.createElement('iframe');
      iframe.setAttribute('src', src);
      iframe.setAttribute('title', embed.getAttribute('data-video-title') || 'Project film');
      iframe.setAttribute('loading', 'lazy');
      iframe.setAttribute('allowfullscreen', '');
      iframe.setAttribute('referrerpolicy', 'strict-origin-when-cross-origin');
      iframe.setAttribute('allow', 'accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share');
      var placeholder = embed.querySelector('.video-placeholder');
      if (placeholder && placeholder.parentNode) placeholder.parentNode.removeChild(placeholder);
      embed.appendChild(iframe);
    }
  }

  function openFromHash() {
    var id = (window.location.hash || '').replace(/^#/, '');
    if (!id) return;
    var target = document.getElementById(id);
    if (!target || target.tagName !== 'DETAILS' || !target.classList.contains('impact-project')) return;
    if (!target.open) target.open = true;
    else loadVideosIn(target);
    setTimeout(function () {
      try { target.scrollIntoView({ behavior: 'smooth', block: 'start' }); }
      catch (e) { target.scrollIntoView(); }
    }, 60);
  }

  for (var i = 0; i < projects.length; i++) {
    (function (d) {
      d.addEventListener('toggle', function () {
        if (!d.open) return;
        if (window.history && typeof window.history.replaceState === 'function') {
          try { window.history.replaceState(null, '', '#' + d.id); } catch (e) {}
        }
        loadVideosIn(d);
      });
    })(projects[i]);
  }

  openFromHash();
  window.addEventListener('hashchange', openFromHash);
})();
</script>
