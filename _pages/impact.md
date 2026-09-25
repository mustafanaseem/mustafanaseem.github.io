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

.impact-project {
  margin: 0 0 56px 0;
}

.impact-project + .impact-project {
  border-top: 1px solid #e5e7eb;
  padding-top: 44px;
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

.project-intro {
  font-size: 16px;
  line-height: 1.85;
  color: #333;
  margin-bottom: 24px;
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

<article class="impact-project">

<h2 class="project-title">Har Zindagi: Making childhood immunization records useful to families and vaccinators</h2>
<div class="project-meta">Punjab, Pakistan · 2015&ndash;2017 · Principal investigator · Funded by DFID through the Sub-National Governance Programme</div>

<p class="project-intro">A child's immunization record has to work for several people at once: a caregiver keeping track of the next visit, a vaccinator recording what happened, and a health system trying to identify children who have been missed. As principal investigator of Har Zindagi ("Every Life Matters"), I led a team working with Punjab's Expanded Program on Immunization to redesign that record end to end, pairing a more legible physical card with an Android app that vaccinators used to create digital records in the field.</p>

<figure class="project-figure">
  <img src="{{ base_path }}/images/harzindagi.png" alt="Photograph of the redesigned Har Zindagi immunization booklet, open to the six-week visit. The left page shows date-of-visit fields for OPV-1, Penta-1, PCV 10-1, and Rotavirus-1, each color coded and paired with an icon of the body system the vaccine protects. The right page marks the child's developmental stage in Urdu ('6-week-old child') and illustrates three milestones with pictorial captions." />
  <figcaption>The deployed immunization booklet, open to the six-week visit. Each vaccine row carries a distinct color and an icon of the body system it protects; the facing page marks the child's developmental stage. Photograph from the project team.</figcaption>
</figure>

<div class="project-body">

<h3 class="project-h3">Why the record needed redesign</h3>
<p>Punjab's existing card was a single, small-format page. Interviews with 69 caregivers and five vaccinators found that roughly a third of caregivers could not read the next-visit date a vaccinator had written in, and about as many could not follow the schedule printed on the back. Most caregivers kept the card carefully and many read Urdu or Punjabi, but the instructions were in small print and offered no pictorial guidance. Vaccinators, meanwhile, worked across paper registers and a provincial app that required connectivity before a record could be saved. Digitizing the vaccinator's work alone had left families with the same illegible record. The design had to serve both sides of a visit, and the handoff between them.</p>

<h3 class="project-h3">The card</h3>
<p>Three prototypes were tested with caregivers and vaccinators across six districts over roughly two months. The deployed booklet gives each visit its own color-coded page, marks the child's developmental stage on that page, pairs each vaccine with an icon of the body system it protects, adds a page for the mother's own vaccinations, and uses passport-style materials and a Government of Punjab monogram so that the document reads as one worth keeping. An embedded NFC chip linked the paper record to the child's digital record. Field testing showed that the pictorial guidance worked best when a vaccinator walked caregivers through it; on its own, it reached few caregivers with limited literacy.</p>

<h3 class="project-h3">The app</h3>
<p>The Android app went through three iterations with vaccinators before field testing. Records could be created offline and uploaded when a signal returned, a direct response to vaccinators' reports that the previous system would not let them finish a day's work without connectivity. Tapping a card's chip opened the correct visit; a search by booklet number or phone number handled families who arrived without a card. Visit pages in the app used the same colors as the card. A route-planning feature built into the first version was removed after vaccinators explained that their daily plans were already fixed with supervisors. Usability testing with 50 vaccinators in Sahiwal and Sheikhupura found that most completed child registration without assistance, with errors concentrated in data-entry fields.</p>

<h3 class="project-h3">In practice</h3>
<div class="in-practice">
<p><strong>Pilot.</strong> Over a seven-month pilot in Sahiwal and Sheikhupura, 50 government vaccinators used the app to create digital records for more than 20,000 children across more than 90,000 visits.</p>
<p><strong>Adoption.</strong> The Government of Punjab adopted a modified version of the card design and printed approximately four million cards annually. The NFC-linked booklet and app remained a research prototype; the adopted card carries the visual design without the chip.</p>
<p><strong>Publications.</strong> Two peer-reviewed papers (ICTD 2016; ACM DEV 2016) document the card and app redesigns and the ways in which caregiver and vaccinator feedback changed the system.</p>
</div>

<h3 class="project-h3">Team</h3>
<p>As principal investigator, I led the project and the card redesign, and coordinated with the Government of Punjab to secure approval to pilot the card and app with state-appointed vaccinators. Samia Razaq was the project's technical lead and led the design of the mobile app and dashboard; she is first author on the system paper. Amna Batool is first author on the card paper and led the caregiver fieldwork. Umair Ali and Muhammad Salman Khalid contributed to fieldwork and system development. Umar Saif of Information Technology University, Lahore, was a senior collaborator. Ali Murtaza, design consultant, created the visual identity of the booklet and program; his images appear on his portfolio, linked below. Android development was carried out by Ali Imran, Ahmed Mehmood, Bilal Saleem, Shaheryar Khan, and Ali Abbas Jaffri.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li>Batool, A., Ali, U., Razaq, S., &amp; <strong>Naseem, M.</strong> (2016). Child Immunization Health Card Redesign: an Iterative, User-Centered Approach. <em>ICTD 2016</em>. <a href="{{ base_path }}/files/2016_Immunization card redesign.pdf" class="pdf-link">[PDF]</a></li>
  <li>Razaq, S., Batool, A., Ali, U., Khalid, M. S., Saif, U., &amp; <strong>Naseem, M.</strong> (2016). Iterative Design of an Immunization Information System in Pakistan. <em>ACM DEV 2016</em>. DOI: 10.1145/3001913.3001925. <a href="{{ base_path }}/files/2016_immunization information system.pdf" class="pdf-link">[PDF]</a></li>
  <li>Ali Murtaza. Har Zindagi (Every Life) Immunization Program Design. <em>Behance</em>. <a href="https://www.behance.net/gallery/48482987/Har-Zindagi-(Every-Life)-Immunization-Program-Design" class="pdf-link">[link]</a></li>
</ul>

</div>

</article>
