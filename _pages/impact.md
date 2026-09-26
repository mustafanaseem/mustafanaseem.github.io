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

.show-more-wrap {
  margin: 4px 0 6px 0;
}

button.show-more {
  background: none;
  border: 0;
  padding: 4px 2px;
  margin: 0;
  font: inherit;
  font-size: 15px;
  color: #2a7ae2;
  cursor: pointer;
  display: inline-flex;
  align-items: center;
  gap: 5px;
  border-radius: 4px;
  line-height: 1.3;
}

button.show-more:hover .show-more-text {
  text-decoration: underline;
}

button.show-more:focus {
  outline: none;
}

button.show-more:focus-visible {
  outline: 3px solid #4c8bf5;
  outline-offset: 3px;
}

.show-more-arrow {
  display: inline-block;
  transition: transform 220ms ease;
  font-size: 12px;
  line-height: 1;
  transform: rotate(0deg);
}

details.impact-project[open] > summary.project-summary .show-more-arrow {
  transform: rotate(180deg);
}

.stat-block {
  margin: 8px 0 26px 0;
}

.stat-label {
  font-size: 12px;
  font-weight: 600;
  letter-spacing: 0.06em;
  color: #6a7480;
  margin-bottom: 6px;
  text-transform: uppercase;
}

.stat-headline {
  font-size: 30px;
  font-weight: 700;
  color: #0051a5;
  line-height: 1.25;
  letter-spacing: -0.005em;
}

@media (max-width: 640px) {
  .stat-headline {
    font-size: 24px;
  }
}
</style>

<div class="impact-lede">Selected projects and what came of them.</div>

<details class="impact-project" id="har-zindagi">
<summary class="project-summary">
<div class="summary-head">
<h2 class="project-title">Har Zindagi: Immunization records that families, vaccinators, and supervisors can trust</h2>
<span class="summary-chevron" aria-hidden="true"></span>
</div>
<div class="project-meta">Punjab, Pakistan · 2015&ndash;2020 · Principal investigator · Funded by DFID through the Sub-National Governance Programme, and by the Gates Foundation</div>
<p class="project-intro">Har Zindagi ("Every Life Matters") began with a design contest. In 2013 the Gates Foundation invited redesigns of the home-based child health record, the card a family keeps through six vaccination visits and a vaccinator reads at each one. Our team at Information Technology University entered a bright yellow, laminated booklet that showed the next-visit date through a slit in its closed cover and used carbonless copies to carry each visit into a digital record. When the Sub-National Governance Programme (SNG, a DFID grantee) funded us to build the idea out, I led the Har Zindagi team in partnership with Punjab's Expanded Program on Immunization, pairing a card shaped by what families and vaccinators told us with an Android app that vaccinators used to create digital records in the field. Two Gates Foundation grants later forced me to ask a harder question: whether the data such a system produces can be trusted.</p>
<div class="show-more-wrap"><button type="button" class="show-more" aria-expanded="false" aria-controls="har-zindagi"><span class="show-more-text">Read more</span><span class="show-more-arrow" aria-hidden="true">&#9662;</span></button></div>
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
<p><strong>Publications.</strong> Two peer-reviewed papers from this phase (ICTD 2016; ACM DEV 2016) document the card and app redesigns and the ways in which caregiver and vaccinator feedback shaped the system.</p>
</div>

<h3 class="project-h3">Next Steps: two Gates Foundation grants to make immunization data actionable</h3>
<p>With immunization coverage rates of up to 99 percent showing up on the dashboard, the pilot left me wondering how much of the vaccination data reaching Punjab's dashboards was true. With <a href="https://armanrezaee.github.io/" target="_blank" rel="noopener">Arman Rezaee</a> (UC Davis) and <a href="https://www.umarsaif.org/" target="_blank" rel="noopener">Umar Saif</a> (ITU) as co-principal investigators, I led two Grand Challenges Explorations grants from the Gates Foundation to pursue it. The first, <a href="https://gcgh.grandchallenges.org/grant/using-data-driven-algorithms-detect-false-data-entries" target="_blank" rel="noopener">Using Data-Driven Algorithms to Detect False Data Entries</a> (2018), set out to train an algorithm on audited vaccination records. The second, <a href="https://gcgh.grandchallenges.org/grant/beyond-data-collection-actionable-insights-vaccinator-supervisors" target="_blank" rel="noopener">Beyond Data Collection: Actionable Insights to Vaccinator Supervisors</a> (2019), built an Android app that put front-line data in front of the mid-level supervisors who oversee vaccinators. Interviews with 30 supervisors across five districts of Punjab showed that data falsification by vaccinators was common and that supervisors had developed their own ways of catching it: triangulating across records, collecting supplementary data, spotting anomalies, and questioning vaccinators directly. Those findings shaped the supervisor app, which <a href="https://sites.google.com/nd.edu/amnabatool/datamonitoring?authuser=0" target="_blank" rel="noopener">Amna Batool</a> designed and tested with supervisors, and became a CHI 2021 paper with Amna as first author. The algorithm strand depended on access to the province's eVaccs records, which did not come through during the grant, so the supervisors' detection strategies documented in the paper stand as that grant's lasting contribution.</p>

<h3 class="project-h3">Team</h3>
<p>I was principal investigator across all three grants. In the SNG-funded phase I led the card redesign and secured the Government of Punjab's approval to pilot the card and app with state-appointed vaccinators; in the Gates-funded phase I set the research direction on data quality and led the collaboration with our co-principal investigators, Arman Rezaee (UC Davis) and Umar Saif (ITU). Samia Razaq (now <a href="https://samiaibtasam.com/" target="_blank" rel="noopener">Samia Ibtasam</a>) was the project's technical lead and led the design of the mobile app and dashboard; she is first author on the system paper. <a href="https://sites.google.com/nd.edu/amnabatool/immunization?authuser=0" target="_blank" rel="noopener">Amna Batool</a> led the caregiver fieldwork and is first author on the card paper; she later led the supervisor interviews and the data-monitoring app, and is first author on the CHI paper, which she wrote with Kentaro Toyama, Tiffany Veinot, and Beenish Fatima. Umair Ali and Muhammad Salman Khalid contributed to fieldwork and system development. Umar Saif of Information Technology University, Lahore, was a senior advisor on the first phase before becoming co-principal investigator. Ali Murtaza, design consultant, created the visual identity of the booklet and program; his images appear on his portfolio, linked below. Ali Imran, Ahmed Mehmood, Bilal Saleem, Shaheryar Khan, and Ali Abbas Jaffri developed the Android app.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li><a href="{{ base_path }}/files/chi2021_intentioanldatafalsification-2.pdf" target="_blank" rel="noopener">Detecting Data Falsification by Front-line Development Workers: A Case Study of Vaccination in Pakistan</a>. Batool, A., Toyama, K., Veinot, T., Fatima, B., &amp; <strong>Naseem, M.</strong> (2021). <em>CHI 2021</em>. DOI: <a href="https://doi.org/10.1145/3411764.3445630">10.1145/3411764.3445630</a>.</li>
  <li><a href="{{ base_path }}/files/2016_immunization information system.pdf" target="_blank" rel="noopener">Iterative Design of an Immunization Information System in Pakistan</a>. Razaq, S., Batool, A., Ali, U., Khalid, M. S., Saif, U., &amp; <strong>Naseem, M.</strong> (2016). <em>ACM DEV 2016</em>. DOI: <a href="https://doi.org/10.1145/3001913.3001925">10.1145/3001913.3001925</a>.</li>
  <li><a href="{{ base_path }}/files/2016_Immunization card redesign.pdf" target="_blank" rel="noopener">Child Immunization Health Card Redesign: an Iterative, User-Centered Approach</a>. Batool, A., Ali, U., Razaq, S., &amp; <strong>Naseem, M.</strong> (2016). <em>ICTD 2016</em>.</li>
  <li>Amna Batool. Project pages on the <a href="https://sites.google.com/nd.edu/amnabatool/immunization?authuser=0" target="_blank" rel="noopener">card redesign</a>, the <a href="https://sites.google.com/nd.edu/amnabatool/vaccination?authuser=0" target="_blank" rel="noopener">Har Zindagi app</a>, and the <a href="https://sites.google.com/nd.edu/amnabatool/datamonitoring?authuser=0" target="_blank" rel="noopener">supervisor data-monitoring app</a>.</li>
  <li>Ali Murtaza. Har Zindagi (Every Life) Immunization Program Design. <em>Behance</em>. <a href="https://www.behance.net/gallery/48482987/Har-Zindagi-(Every-Life)-Immunization-Program-Design" target="_blank" rel="noopener" class="pdf-link">[link]</a></li>
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
<div class="show-more-wrap"><button type="button" class="show-more" aria-expanded="false" aria-controls="water-atms"><span class="show-more-text">Read more</span><span class="show-more-arrow" aria-hidden="true">&#9662;</span></button></div>
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
<p>I was the U.S. principal investigator and co-led the project with Dr. Tauseef Tauqeer, the Pakistani principal investigator, whose Industrial Monitoring and Automation Lab at ITU designed, built, and maintained the units in the field. Zill Ullah Khan and M. Umair Anwar led the hardware and firmware work and are first authors on the MobiCom paper. Sabah Pirani led the qualitative study and wrote her <a href="https://deepblue.lib.umich.edu/items/625ace55-e69a-40db-a9eb-587129dbc82f" rel="noopener">master's thesis</a> on it, co-advised by Kentaro Toyama. Faisal Lalani and Babatunde Adegoke are co-authors on the paper. Arman Rezaee at Michigan collaborated on the project. Haya Fatima Iqbal made the film.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li>Khan, Z. U., Anwar, M. U., Pirani, S., Lalani, F., Adegoke, B., Tauqeer, T., &amp; <strong>Naseem, M.</strong> (2020). Poster: Design of an IoT-based water flow monitoring system. <em>MobiCom 2020</em>. DOI: <a href="https://doi.org/10.1145/3372224.3418170">10.1145/3372224.3418170</a>.</li>
  <li>Pirani, S. (2020). Differential Access: Water Infrastructure and Water Quality Awareness among Lahore's Urban Poor. <em>Master's thesis, University of Michigan School of Information</em>. DOI: <a href="https://doi.org/10.7302/1714">10.7302/1714</a>.</li>
  <li>Haya Fatima Iqbal (dir.). (2020). <em>Water ATMs: Design and Testing of Water Dispensing and Quality Measurement Units in Lahore</em>. Five-minute documentary. Link: <a href="https://youtu.be/TSojzm678kM">https://youtu.be/TSojzm678kM</a></li>
</ul>

</div>

</div>
</details>

<details class="impact-project" id="super-abbu">
<summary class="project-summary">
<div class="summary-head">
<h2 class="project-title">Super Abbu: Bringing fathers into maternal and child health over a simple phone call</h2>
<span class="summary-chevron" aria-hidden="true"></span>
</div>
<div class="project-meta">Pakistan · 2016&ndash;2024 · Organizer, designer, co-principal investigator, and principal investigator across four phases · Funded by the UNICEF Innovation Fund, the NIH Fogarty International Center, and the Gates Foundation</div>
<p class="project-intro">In Pakistan a pregnant woman's care runs through her husband: in our survey of 199 expectant couples in rural Punjab, 85 percent of husbands took part in decisions about their wife's healthcare, yet only 56 percent had ever sought out information on maternal health. Super Abbu ("Super Dad") is a hotline that lets a man with any phone, and no need for literacy or internet, record a question for a doctor, hear the answer in private, and listen to other fathers' questions and stories. It began as a student team's idea at a design summit I organized in 2016 and grew, over four grants, into a service that has reached more than 27,000 men in Urdu and Pashto. I have been part of it at every stage.</p>
<div class="show-more-wrap"><button type="button" class="show-more" aria-expanded="false" aria-controls="super-abbu"><span class="show-more-text">Read more</span><span class="show-more-arrow" aria-hidden="true">&#9662;</span></button></div>
</summary>

<div class="project-collapse">

<figure class="project-figure">
  <div class="video-embed" data-video-src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2Fwatch%2F%3Fv%3D2319115705080021&amp;show_text=false&amp;t=0" data-video-title="BBC Urdu report on Super Abbu">
    <div class="video-placeholder">Film embed reserved (responsive 16:9). Iframe src will be added when the URL is supplied.</div>
  </div>
  <figcaption>BBC Urdu's report on Super Abbu, in Urdu.</figcaption>
</figure>

<div class="project-body">

<h3 class="project-h3">Motivation</h3>
<p>Husbands in our survey were involved in the decisions that matter most: 81 percent had a say in whether their wife received the antenatal tetanus vaccine. Their knowledge lagged behind their role. Barely half had ever sought information on maternal health, a third did not know their wife's vaccination status, and six in ten had never discussed the pregnancy with a health provider. Both partners wanted more: among couples where the husband had not spoken with a provider, 86 percent of the men and 94 percent of their wives said that was not enough. Fathers are rarely admitted to maternity facilities, so that demand needs another channel. A phone call is the one channel nearly every man already has, and it offers something a clinic visit cannot: privacy. A father can ask about his wife's bleeding, or his own fertility, without anyone in the room.</p>

<h3 class="project-h3">From Rehemaa to Super Abbu</h3>
<p>The idea surfaced in 2016 at the <a href="https://www.idin.org/blog-news-events/events/idds-lahore" target="_blank" rel="noopener">International Development Design Summit in Lahore</a>, which I led as lead organizer. A team of five participants, Sacha Ahmad, Kim Chatterjee, Ehsam Ullah Baig, Umair Anwar, and Faran Sikandar, working with design facilitator Claudine Chen, prototyped a service they called Rehemaa. Their first version was an SMS system, and fathers told them plainly that they wanted to hear a voice instead. With Sacha and Agha Ali Raza, then both at ITU, I was part of the team that redesigned it as a speech service and helped bring in the UNICEF Innovation Fund; Ali served as principal investigator on that grant while I moved to a consulting role after joining the University of Colorado. Testing with fathers in a low-income neighborhood of Lahore shaped the redesign: a missed call that the system returns, so the call costs the user nothing; a choice between a private question and a public one; a female physician persona, Dr. Saba, whose voice a speech artist recorded over the doctors' answers; and moderators who route each question to a gynecologist, a family physician, or a pediatrician.</p>

<h3 class="project-h3">Eleven weeks, 21,770 fathers</h3>
<p>Super Abbu went live in Punjab on the last day of 2017. Over eleven weeks, 21,770 men made 32,625 calls and spent 367,000 minutes on the line, recording 1,878 questions and 1,407 stories. Three doctors, working two hours a day, answered every question within 48 hours. The men asked about miscarriage, contraception, sexual health, and their wives' symptoms, and most of the listening time went to other fathers' questions and the doctors' answers to them. We recruited users through seven channels at once, from rickshaw banners and cable TV to robocalls and a voice-based entertainment service, and compared them; the entertainment service delivered the most engaged users at the lowest cost, a finding I reported as first author at CHI 2020, where the paper received a Best Paper Honorable Mention. The deployment also drew a BBC Urdu feature, embedded above.</p>

<h3 class="project-h3">Field deployments</h3>
<div class="in-practice">
<p><strong>Impact evaluation.</strong> With Arman Rezaee as principal investigator and Sarojini Hirshleifer, Agha Ali Raza, and me as co-principal investigators, an <a href="https://www.fic.nih.gov/Grants/Search/Pages/mhealth-r21hd095696.aspx" target="_blank" rel="noopener">NIH Fogarty mHealth grant</a> (2018&ndash;2023) set out to evaluate Super Abbu in Punjab. Its 2021 survey of 199 expectant couples, led by Sacha Ahmad and presented at APHA 2022, is the source of the figures above and the first evidence that both husbands and wives in rural Punjab want men more involved. When Covid arrived, the team redirected the grant toward delivering Covid-19 health information over Baang, a voice-based social network, and studying how misinformation travelled there.</p>
<p><strong>Khpal Tabeeb.</strong> As lead principal investigator on a Gates Foundation grant (2021&ndash;2024), I led the launch of a Pashto-language service for Khyber Pakhtunkhwa, with Agha Ali Raza running implementation at LUMS and Arman Rezaee leading evaluation. Community mobilizers told us that "Super Dad" meant little to Pashto speakers, so we renamed the service Khpal Tabeeb, "our doctor", and advertised it on Pashto radio in Peshawar, Bannu, and North and South Waziristan. Doctors from Khyber Medical University answered questions, and priority content on immunization and postnatal care was written with the provincial EPI cell and the Federal Directorate of Immunization. From March 2023 the service took 34,507 calls from 6,008 users, who asked 1,906 questions and played the immunization content 9,566 times. Focus groups with families who had refused vaccination were presented to health experts at the Federal Directorate of Immunization.</p>
<p><strong>Key findings.</strong> A voice-based social network that had spread Super Abbu in Punjab drew a loyal Pashto audience but sent few users on to the health service; radio and community mobilizers did the recruiting, and the 346 users who did arrive through the social network stayed eight times longer. Pashto users also treated the service differently from users in Punjab: they posted no stories of their own, even after we seeded the stories menu with earlier Super Abbu stories re-recorded in Pashto, and almost every question they asked was marked private. Maternal and child health is private information in Khyber Pakhtunkhwa in a way it was not in Punjab, an expression of purdah that any service for this region has to design around. Fathers also wanted more than information: many asked for a diagnosis, which an asynchronous service cannot responsibly give, and that gap points to the next design.</p>
</div>

<h3 class="project-h3">Team</h3>
<p>I organized the 2016 summit where Rehemaa was born, was part of the leadership team that redesigned it as Super Abbu, served as co-principal investigator on the NIH grant, and was lead principal investigator on the Gates-funded Khpal Tabeeb. The original Rehemaa team was <a href="https://www.linkedin.com/in/sachastongeahmad/" target="_blank" rel="noopener">Sacha Ahmad</a>, Kim Chatterjee, Ehsam Ullah Baig, Umair Anwar, and Faran Sikandar, facilitated by Claudine Chen. <a href="https://aghaaliraza.com/" target="_blank" rel="noopener">Agha Ali Raza</a>, then at ITU and now at LUMS, was principal investigator on the UNICEF grant and led implementation throughout; his Center for Speech and Language Technology built and ran the platform. <a href="https://armanrezaee.github.io/" target="_blank" rel="noopener">Arman Rezaee</a> of UC Davis was principal investigator on the NIH grant and led evaluation on Khpal Tabeeb, with <a href="https://profiles.ucr.edu/app/home/profile/shirsh" target="_blank" rel="noopener">Sarojini Hirshleifer</a> of UC Riverside as co-principal investigator. Sacha Ahmad led the couples survey and is first author on the APHA paper. Bilal Saleem and Jay Chen co-authored the CHI 2020 paper. Doctors from a Lahore hospital and from Khyber Medical University answered the questions.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li><a href="{{ base_path }}/files/chi2020_superabbuads-7.pdf" target="_blank" rel="noopener">An Empirical Comparison of Technologically Mediated Advertising in Under-connected Populations</a>. <strong>Naseem, M.</strong>, Saleem, B., Ahmad, S. S., Chen, J., &amp; Raza, A. A. (2020). <em>CHI 2020</em>, Best Paper Honorable Mention. DOI: <a href="https://doi.org/10.1145/3313831.3376683">10.1145/3313831.3376683</a>.</li>
  <li><a href="https://apha.confex.com/apha/2022/meetingapi.cgi/Paper/516094?filename=2022_Abstract516094.html&amp;template=Word" target="_blank" rel="noopener">Ahmad, S. S., Hirshleifer, S., <strong>Naseem, M.</strong>, Rezaee, A., &amp; Raza, A. A. (2022). Perceptions of Paternal Involvement in Maternal Healthcare in Rural Pakistan. <em>APHA 2022 Annual Meeting and Expo</em>.</a></li>
  <li>Taboo Topics and Misconceptions: Design and Deployment of a Health Hotline for Expectant Fathers. Unpublished manuscript, 2022.</li>
  <li>BBC Urdu. Report on Super Abbu. <a href="https://www.facebook.com/watch/?v=2319115705080021" target="_blank" rel="noopener">https://www.facebook.com/watch/?v=2319115705080021</a></li>
</ul>

</div>

</div>
</details>

<details class="impact-project" id="baang-covid">
<summary class="project-summary">
<div class="summary-head">
<h2 class="project-title">Baang during Covid-19: Trusted health information on a voice-based social network</h2>
<span class="summary-chevron" aria-hidden="true"></span>
</div>
<div class="project-meta">Pakistan · 2020&ndash;2026 · Co-principal investigator · Funded by the NIH Fogarty International Center</div>
<p class="project-intro">When Covid-19 reached Pakistan in March 2020, the people least likely to see a government advisory were those without internet, without literacy, and without much reason to trust official sources. <a href="https://dl.acm.org/doi/abs/10.1145/3173574.3174217" target="_blank" rel="noopener">Baang</a> is a voice-based social network, built by Agha Ali Raza's lab, that people use over an ordinary phone call to record and hear each other's posts. On April 2, 2020, Ali, Arman Rezaee, Sarojini Hirshleifer, and I, who were already collaborating on the Super Abbu evaluation, relaunched Baang as a channel for reliable Covid information. Over six months it took half a million calls from 12,000 people across Pakistan, who listened to official guidance, argued with it, shared it with friends, and told the government what they thought of its lockdowns.</p>
<div class="show-more-wrap"><button type="button" class="show-more" aria-expanded="false" aria-controls="baang-covid"><span class="show-more-text">Read more</span><span class="show-more-arrow" aria-hidden="true">&#9662;</span></button></div>
</summary>

<div class="project-collapse">

<div class="stat-block">
  <div class="stat-label">Baang during Covid-19, April to October 2020</div>
  <div class="stat-headline">500,000 calls &middot; 12,000 users &middot; 6 months</div>
</div>

<figure class="project-figure">
  <img src="{{ base_path }}/images/SuperAbbuPicture.jpg" alt="A father in a white shalwar kameez uses a mobile phone with a wired earpiece while seated on a charpai; his young son in a yellow and green striped shirt sits between his knees, and his wife in a blue and pink patterned dupatta sits to his right." />
  <figcaption>A phone call reaches the whole family. A father takes a call in Lahore while his wife and son look on. Photograph by Abdullah Kharal.</figcaption>
</figure>

<div class="project-body">

<h3 class="project-h3">Motivation</h3>
<p>A poll in 2020 found that 97 percent of Pakistanis held at least one misconception about the coronavirus (Ipsos poll). Text messages, apps, and websites reach the connected and the literate; a voice call reaches nearly everyone, and Baang had already shown that low-income, low-literate men would call in by the thousands to talk to each other. The question was whether a platform built for entertainment could carry health information that people would trust, listen to, and pass on, and what would happen to that flow of information when the platform started policing what was false.</p>

<h3 class="project-h3">Redesigning Baang for a pandemic</h3>
<p>Ali's lab at LUMS translated advisories from Pakistan's National Institutes of Health and the government into Urdu, had a bilingual public health expert check every translation, and recorded them as official posts that a new menu option played before anything else. Every user post and comment passed a moderator within four hours. I led the design of the incentives: Baang was made toll-free, each user received 30 free minutes a day, and users earned more minutes by sharing an official post with a friend who answered the call, by bringing a new user onto the platform, and more still if that new user stayed on the line or called back. Pinned posts asked users to think about where their information came from before they passed it on. Users who received all three, the official posts, the incentives, and the prompts, engaged with Covid content at significantly higher rates than the rest, a result reported at The Web Conference 2022.</p>

<h3 class="project-h3">Six months, 12,000 users</h3>
<p>Between April and October 2020, 12,000 people, 96 percent of them with fewer than ten years of schooling, placed nearly half a million calls to Baang. They recorded more than 35,000 posts, played them 2.4 million times, voted on them 322,000 times, and shared them with other users more than 130,000 times. The platform became a public square as much as a bulletin board: alongside questions about symptoms and prevention, users posted their views on school closures, mosque restrictions, and the cost of lockdown to people paid by the day.</p>

<h3 class="project-h3">The moderation experiment</h3>
<p>Arman and Sarojini designed a randomized experiment, run from June 27 to August 26, 2020 with 3,698 users, to ask a question most platforms cannot test: what happens when misinformation is removed before anyone sees it? Users were assigned to one of three conditions. In the control, moderators took misinformation down after it was posted, as most platforms do. In the second, misinformation was never posted. In the third, it was posted alongside a rebuttal carrying the official guidance. The results, published in the Journal of Development Economics in 2026, showed that fully controlling misinformation cut daily users by 19 percent and daily minutes by 26 percent, and reduced users' exposure to official information by 29 percent more than it reduced their exposure to misinformation. On this platform, official information was the more trusted content and the more widely shared, so the heavier moderation cost more good information than bad.</p>

<h3 class="project-h3">Key findings</h3>
<p>Reliable information can travel through the same social channels as rumor when the platform gives people a reason to share it; incentives tied to sharing official posts raised engagement across the board. Heavy-handed moderation carried a price in this setting: users disliked it, used the platform less, and ended up hearing less official guidance. In my own qualitative analysis of the 42 distinct myths that circulated, reported in my doctoral dissertation, most misinformation read as an attempt at community care: people relaying a remedy that had helped a neighbor, framing prevention in religious or traditional terms, or arguing for schools to reopen because families around them were going hungry. The voice medium gave those posts an intimacy that text cannot, which is why they persuaded, and why any response has to engage with the care behind them.</p>

<h3 class="project-h3">Team</h3>
<p>I was co-principal investigator and led the design of the engagement incentives; the qualitative analysis of misinformation on the platform forms a chapter of my doctoral dissertation. <a href="https://aghaaliraza.com/" target="_blank" rel="noopener">Agha Ali Raza</a> of LUMS created Baang and led its redeployment, content translation, and moderation; Namoos Hayat Qasmi, Fizzah Malik, and Behzad Taimur at LUMS ran the platform day to day. <a href="https://armanrezaee.github.io/" target="_blank" rel="noopener">Arman Rezaee</a> of UC Davis and <a href="https://profiles.ucr.edu/app/home/profile/shirsh" target="_blank" rel="noopener">Sarojini Hirshleifer</a> of UC Riverside designed and led the moderation experiment. Shan Randhawa at Michigan, <a href="https://www.linkedin.com/in/sachastongeahmad/" target="_blank" rel="noopener">Sacha Ahmad</a>, and Aditya Vashistha of Cornell co-authored the Web Conference paper.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li>Hirshleifer, S., <strong>Naseem, M.</strong>, Raza, A. A., &amp; Rezaee, A. (2026). The spread of (mis)information: A social media experiment in Pakistan. <em>Journal of Development Economics</em>, 183, 103784. DOI: <a href="https://doi.org/10.1016/j.jdeveco.2026.103784">10.1016/j.jdeveco.2026.103784</a>.</li>
  <li>Raza, A. A., <strong>Naseem, M.</strong>, Qasmi, N. H., Randhawa, S., Malik, F., Taimur, B., Ahmad, S. S., Hirshleifer, S., Rezaee, A., &amp; Vashistha, A. (2022). Fostering Engagement of Underserved Communities with Credible Health Information on Social Media. <em>The Web Conference 2022 (WWW '22)</em>. DOI: <a href="https://doi.org/10.1145/3485447.3512267">10.1145/3485447.3512267</a>.</li>
  <li><strong>Naseem, M.</strong> Doctoral dissertation, University of Michigan. The dissertation is embargoed while its findings are prepared for publication; the chapter on Covid-19 misinformation on Baang is available on request.</li>
  <li><a href="https://dl.acm.org/doi/abs/10.1145/3173574.3174217" target="_blank" rel="noopener">Raza, A. A., Saleem, B., Randhawa, S., Tariq, Z., Athar, A., Saif, U., &amp; Rosenfeld, R. (2018). Baang: A Viral Speech-based Social Platform for Under-Connected Populations. <em>CHI 2018</em>. DOI: 10.1145/3173574.3174217.</a></li>
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
        var btn = d.querySelector('button.show-more');
        if (btn) {
          btn.setAttribute('aria-expanded', d.open ? 'true' : 'false');
          var txt = btn.querySelector('.show-more-text');
          if (txt) txt.textContent = d.open ? 'Show less' : 'Read more';
        }
        if (!d.open) return;
        if (window.history && typeof window.history.replaceState === 'function') {
          try { window.history.replaceState(null, '', '#' + d.id); } catch (e) {}
        }
        loadVideosIn(d);
      });
      var showBtn = d.querySelector('button.show-more');
      if (showBtn) {
        showBtn.addEventListener('click', function (e) {
          e.preventDefault();
          e.stopPropagation();
          d.open = !d.open;
        });
      }
    })(projects[i]);
  }

  openFromHash();
  window.addEventListener('hashchange', openFromHash);
})();
</script>
