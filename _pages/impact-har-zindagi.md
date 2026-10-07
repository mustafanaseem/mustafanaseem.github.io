---
layout: archive
title: "Har Zindagi: Immunization records that families, vaccinators, and supervisors can trust"
permalink: /impact/har-zindagi/
author_profile: true
---

{% include base_path %}

{% include impact-styles.html %}

<div class="impact-back-link"><a href="{{ base_path }}/impact/">&larr; Back to Impact</a></div>

<div class="project-meta">Punjab, Pakistan · 2015&ndash;2020 · Principal investigator · Funded by DFID through the Sub-National Governance Programme, and by the Gates Foundation</div>

<p class="project-intro">Har Zindagi ("Every Life Matters") began with a design contest. In 2013 the Gates Foundation invited redesigns of the home-based child health record, the card a family keeps through six vaccination visits and a vaccinator reads at each one. Our team at Information Technology University entered a bright yellow, laminated booklet that showed the next-visit date through a slit in its closed cover and used carbonless copies to carry each visit into a digital record. When the Sub-National Governance Programme (SNG, a DFID grantee) funded us to build the idea out, I led the Har Zindagi team in partnership with Punjab's Expanded Program on Immunization, pairing a card shaped by what families and vaccinators told us with an Android app that vaccinators used to create digital records in the field. Two Gates Foundation grants later led me to ask a harder question: whether the data such a system produces can be trusted.</p>

<figure class="project-figure">
  <img src="{{ base_path }}/images/harzindagi.png" alt="Photograph of the redesigned Har Zindagi immunization booklet, open to the six-week visit. The left page shows date-of-visit fields for OPV-1, Penta-1, PCV 10-1, and Rotavirus-1, each color coded and paired with an icon of the body system the vaccine protects. The right page marks the child's developmental stage in Urdu ('6-week-old child') and illustrates three milestones with pictorial captions." />
  <figcaption>The deployed immunization booklet, open to the six-week visit. Each vaccine row carries a distinct color and an icon of the body system it protects; the facing page marks the child's developmental stage. Photograph from the project team.</figcaption>
</figure>

<div class="stat-block">
  <div class="stat-label">Seven-month pilot in Sahiwal and Sheikhupura; the Government of Punjab later adopted the card design and printed millions each year</div>
  <div class="stat-headline">25,000 cards printed &middot; 20,000 children vaccinated &middot; 90,000 visits</div>
</div>

<div class="project-body">

<h3 class="project-h3">Motivation</h3>
<p>Interviews with 69 caregivers and five vaccinators showed that most caregivers already kept the card carefully and many read Urdu or Punjabi, so a next-visit date they could read at a glance and a schedule they could follow at home would let them plan each visit themselves. Vaccinators wanted a record they could complete wherever the visit happened, with or without a network. A card that served both, and smoothed the handoff between them, became the brief for the project.</p>

<h3 class="project-h3">The card</h3>
<p>We tested three prototypes with caregivers and vaccinators across six districts over roughly two months. The deployed booklet gives each visit its own color-coded page, marks the child's developmental stage on that page, pairs each vaccine with an icon of the body system it protects, adds a page for the mother's own vaccinations, and uses passport-style materials and a Government of Punjab monogram so that the document reads as one worth keeping. An embedded NFC chip linked the paper record to the child's digital record. Field testing showed that the pictorial guidance worked best when a vaccinator walked caregivers through it, so we designed the card as a conversation aid as well as a record.</p>

<h3 class="project-h3">The app</h3>
<p>The Android app went through three iterations with vaccinators before field testing. Vaccinators could create records offline and upload them when a signal returned, so they could finish a day's work in a village and sync on the way home. Tapping a card's chip opened the correct visit, and a search by booklet number or phone number served families who arrived without a card. Visit pages in the app used the same colors as the card, so paper and screen read as one document. Vaccinators told us their daily routes were already agreed with their supervisors, so we retired a route-planning feature and put that effort into the screens they used all day. In usability testing, most of 50 vaccinators in Sahiwal and Sheikhupura completed child registration on their own, and the few errors pointed us to specific data-entry fields to refine.</p>

<h3 class="project-h3">Seven-month field deployment</h3>
<div class="in-practice">
<p><strong>Pilot.</strong> Over seven months in Sahiwal and Sheikhupura, 50 government vaccinators used 25,000 printed booklets and the app to create digital records for more than 20,000 children vaccinated across more than 90,000 visits.</p>
<p><strong>Adoption.</strong> The Government of Punjab adopted a modified version of the card's visual design and printed approximately four million cards annually; the NFC link and the app remained our research prototype.</p>
<p><strong>Publications.</strong> Two peer-reviewed papers from this phase (ICTD 2016; ACM DEV 2016) document the card and app redesigns and the ways in which caregiver and vaccinator feedback shaped the system.</p>
</div>

<h3 class="project-h3">Next steps: two Gates Foundation grants to make immunization data actionable</h3>
<p>With immunization coverage rates of up to 99 percent showing up on the dashboard, the pilot left me wondering how much of the vaccination data reaching Punjab's dashboards was true. With <a href="https://armanrezaee.github.io/" target="_blank" rel="noopener">Arman Rezaee</a> (UC Davis) and <a href="https://www.umarsaif.org/" target="_blank" rel="noopener">Umar Saif</a> (ITU) as co-principal investigators, I led two Grand Challenges Explorations grants from the Gates Foundation to pursue it. The first, <a href="https://gcgh.grandchallenges.org/grant/using-data-driven-algorithms-detect-false-data-entries" target="_blank" rel="noopener">Using Data-Driven Algorithms to Detect False Data Entries</a> (2018), set out to train an algorithm on audited vaccination records. The second, <a href="https://gcgh.grandchallenges.org/grant/beyond-data-collection-actionable-insights-vaccinator-supervisors" target="_blank" rel="noopener">Beyond Data Collection: Actionable Insights to Vaccinator Supervisors</a> (2019), built an Android app that put front-line data in front of the mid-level supervisors who oversee vaccinators. Interviews with 30 supervisors across five districts of Punjab showed that data falsification by vaccinators was common and that supervisors had developed their own ways of catching it: triangulating across records, collecting supplementary data, spotting anomalies, and questioning vaccinators directly. Those findings shaped the supervisor app, which <a href="https://sites.google.com/nd.edu/amnabatool/datamonitoring?authuser=0" target="_blank" rel="noopener">Amna Batool</a> designed and tested with supervisors, and became a CHI 2021 paper with Amna as first author. The algorithm strand depended on access to the province's eVaccs records, which did not come through during the grant, so the supervisors' detection strategies documented in the paper stand as that grant's lasting contribution.</p>

<h3 class="project-h3">Team</h3>
<p>I was principal investigator across all three grants. In the SNG-funded phase I led the card redesign and secured the Government of Punjab's approval to pilot the card and app with state-appointed vaccinators; in the Gates-funded phase I set the research direction on data quality and led the collaboration with our co-principal investigators, Arman Rezaee (UC Davis) and Umar Saif (ITU). Samia Razaq (now <a href="https://samiaibtasam.com/" target="_blank" rel="noopener">Samia Ibtasam</a>) was the project's technical lead and led the design of the mobile app and dashboard; she is first author on the system paper. <a href="https://sites.google.com/nd.edu/amnabatool/immunization?authuser=0" target="_blank" rel="noopener">Amna Batool</a> led the caregiver fieldwork and is first author on the card paper; she later led the supervisor interviews and the data-monitoring app, and is first author on the CHI paper, which she wrote with Kentaro Toyama, Tiffany Veinot, and Beenish Fatima. Umair Ali and Muhammad Salman Khalid contributed to fieldwork and system development. Umar Saif of Information Technology University, Lahore, was a senior advisor on the first phase before becoming co-principal investigator. Ali Murtaza, design consultant, created the visual identity of the booklet and program; his images appear on his portfolio, linked below. Ali Imran, Ahmed Mehmood, Bilal Saleem, Shaheryar Khan, and Ali Abbas Jaffri developed the Android app.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li>Batool, A., Toyama, K., Veinot, T., Fatima, B., &amp; <strong>Naseem, M.</strong> (2021). <a href="{{ base_path }}/files/chi2021_intentioanldatafalsification-2.pdf" target="_blank" rel="noopener">Detecting Data Falsification by Front-line Development Workers: A Case Study of Vaccination in Pakistan</a>. <em>CHI 2021</em>. DOI: <a href="https://doi.org/10.1145/3411764.3445630">10.1145/3411764.3445630</a>.</li>
  <li>Razaq, S., Batool, A., Ali, U., Khalid, M. S., Saif, U., &amp; <strong>Naseem, M.</strong> (2016). <a href="{{ base_path }}/files/2016_immunization information system.pdf" target="_blank" rel="noopener">Iterative Design of an Immunization Information System in Pakistan</a>. <em>ACM DEV 2016</em>. DOI: <a href="https://doi.org/10.1145/3001913.3001925">10.1145/3001913.3001925</a>.</li>
  <li>Batool, A., Ali, U., Razaq, S., &amp; <strong>Naseem, M.</strong> (2016). <a href="{{ base_path }}/files/2016_Immunization card redesign.pdf" target="_blank" rel="noopener">Child Immunization Health Card Redesign: an Iterative, User-Centered Approach</a>. <em>ICTD 2016</em>.</li>
  <li>Amna Batool. Project pages on the <a href="https://sites.google.com/nd.edu/amnabatool/immunization?authuser=0" target="_blank" rel="noopener">card redesign</a>, the <a href="https://sites.google.com/nd.edu/amnabatool/vaccination?authuser=0" target="_blank" rel="noopener">Har Zindagi app</a>, and the <a href="https://sites.google.com/nd.edu/amnabatool/datamonitoring?authuser=0" target="_blank" rel="noopener">supervisor data-monitoring app</a>.</li>
  <li>Ali Murtaza. <a href="https://www.behance.net/gallery/48482987/Har-Zindagi-(Every-Life)-Immunization-Program-Design" target="_blank" rel="noopener">Har Zindagi (Every Life) Immunization Program Design</a>. <em>Behance</em>.</li>
</ul>

</div>

<div class="impact-back-link"><a href="{{ base_path }}/impact/">&larr; Back to Impact</a></div>
