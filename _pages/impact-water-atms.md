---
layout: archive
title: "Water ATMs: Helping Lahore's water utility see its filtration plants at work"
permalink: /impact/water-atms/
author_profile: true
---

{% include base_path %}

{% include impact-styles.html %}

<div class="impact-back-link"><a href="{{ base_path }}/impact/">&larr; Back to Impact</a></div>

<div class="project-meta">Lahore, Pakistan · 2017&ndash;2020 · U.S. principal investigator · Funded by the Pakistan-U.S. Science and Technology Cooperation Program</div>

<p class="project-intro">Many families in Lahore collect their drinking water from public filtration plants: neighborhood taps run by the city's water utility, WASA Lahore, where the water is free and carried home in jerry cans. A utility that can see each plant at work can keep the water flowing, fix a leaking tap the day it starts, and plan where the next plant should go. Together with Dr. Tauseef Tauqeer at Information Technology University, Lahore, I co-led a three-year project to build a low-cost sensing unit that gives the utility that view, and to pair the engineering with fieldwork on how low-income residents of Lahore get their water.</p>

<figure class="project-figure">
  <div class="video-embed">
    <iframe src="https://www.youtube.com/embed/TSojzm678kM" title="Water ATMs, a five-minute documentary by Haya Fatima Iqbal" loading="lazy" allowfullscreen referrerpolicy="strict-origin-when-cross-origin" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
  <figcaption>A five-minute film about the project by documentary filmmaker Haya Fatima Iqbal. It follows residents collecting water at Lahore's filtration plants and includes conversations with Dr. Tauseef Tauqeer, WASA Lahore managing director Zahid Aziz, and me.</figcaption>
</figure>

<div class="stat-block">
  <div class="stat-label">Six WASA Lahore filtration plants, October 2019 to March 2020</div>
  <div class="stat-headline">42,000 transactions &middot; 1.28 million liters &middot; 6 plants</div>
</div>

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
<p><strong>Publications.</strong> A MobiCom 2020 poster describes the unit and the data pipeline, and Sabah Pirani's master's thesis presents the qualitative study.</p>
</div>

<h3 class="project-h3">Next steps: from six plants to the whole utility</h3>
<p>WASA's managing director set the goal on camera: every WASA installation monitored online, and a utility that runs on data rather than paper. Tauseef's lab at ITU went on to win funding from WASA to monitor Lahore's tube wells, and he founded a company to take the monitoring units to market. ITU's D-Lab course used the project as a case study in designing for underserved communities, so the next cohort of engineers in Lahore learned the method on this problem.</p>

<h3 class="project-h3">Team</h3>
<p>I was the U.S. principal investigator and co-led the project with Dr. Tauseef Tauqeer, the Pakistani principal investigator, whose Industrial Monitoring and Automation Lab at ITU designed, built, and maintained the units in the field. Zill Ullah Khan and M. Umair Anwar led the hardware and firmware work and are first authors on the MobiCom paper. Sabah Pirani led the qualitative study and wrote her <a href="https://deepblue.lib.umich.edu/items/625ace55-e69a-40db-a9eb-587129dbc82f" rel="noopener">master's thesis</a> on it, co-advised by Kentaro Toyama. Faisal Lalani and Babatunde Adegoke are co-authors on the paper. Arman Rezaee of UC Davis collaborated on the project. Haya Fatima Iqbal made the film.</p>

<h3 class="project-h3">Read the work</h3>
<ul class="project-refs">
  <li>Khan, Z. U., Anwar, M. U., Pirani, S., Lalani, F., Adegoke, B., Tauqeer, T., &amp; <strong>Naseem, M.</strong> (2020). <a href="https://doi.org/10.1145/3372224.3418170" target="_blank" rel="noopener">Poster: Design of an IoT-based water flow monitoring system</a>. <em>MobiCom 2020</em>. DOI: <a href="https://doi.org/10.1145/3372224.3418170">10.1145/3372224.3418170</a>.</li>
  <li>Pirani, S. (2020). <a href="https://doi.org/10.7302/1714" target="_blank" rel="noopener">Differential Access: Water Infrastructure and Water Quality Awareness among Lahore's Urban Poor</a>. <em>Master's thesis, University of Michigan School of Information</em>. DOI: <a href="https://doi.org/10.7302/1714">10.7302/1714</a>.</li>
  <li>Haya Fatima Iqbal (dir.). (2020). <em><a href="https://youtu.be/TSojzm678kM" target="_blank" rel="noopener">Water ATMs: Design and Testing of Water Dispensing and Quality Measurement Units in Lahore</a></em>. Five-minute documentary.</li>
</ul>

</div>

<div class="impact-back-link"><a href="{{ base_path }}/impact/">&larr; Back to Impact</a></div>
