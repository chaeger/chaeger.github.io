---
layout: page
permalink: /publications/
title: publications
description: 
years: [2014, 2013, 2012]
nav: true
---

<div class="publications">

<h3>preprints</h3>

{% bibliography -f papers -q @*[keywords=preprint]* %}

<h3>journals</h3>

{% bibliography -f papers -q @article[]* %}

<h3>conference</h3>

{% bibliography -f papers -q @inproceedings[keywords!=preprint]* %}

<h3>Patents</h3>

<ol class="bibliography">
<li><div class="title">Systems and methods for decoding forward error correction codes based on component codes</div>
<div class="author">
Henry D. Pfister and <em>Christian Häger</em> (US 10,693,500 B2), filed: Sep. 17, 2018
</div>
<div class="title">
[<a href="https://patents.google.com/patent/US10693500B2/en" target="_blank">PDF</a>]
</div>
</li>
</ol>

<h3>Thesis</h3>

<ol class="bibliography">
<li><div class="title">Analysis and Design of Spatially-Coupled Codes with Application to Fiber-Optical Communications</div>
PhD thesis, Chalmers University of Technology, May 2016
<div class="title">
[<a href="/assets/pdf/haeger_phd_thesis.pdf" target="_blank">PDF</a>]
[<a href="/assets/pdf/haeger_phd_seminar.pdf" target="_blank">Slides</a>]
[<a href="https://research.chalmers.se/publication/234952" target="_blank">CPL</a>]
</div>
</li>
<li><div class="title">On Signal Constellations and Coding for Long-Haul Fiber-Optical Systems </div>
Licentiate thesis, Chalmers University of Technology, April 2014
<div class="title">
[<a href="/assets/pdf/haeger_licentiate_thesis.pdf" target="_blank">PDF</a>]
[<a href="/assets/pdf/haeger_licentiate_seminar.pdf" target="_blank">Slides</a>]
[<a href="https://research.chalmers.se/publication/196845" target="_blank">CPL</a>]
</div>
</li>
<li><div class="title">Bidirectional Wireless Communication via Relay Nodes using Lattices</div>
Diploma thesis, Ulm University, July 2011
<div class="title">
[<a href="/assets/pdf/haeger_diploma_thesis.pdf" target="_blank">PDF</a>]
</div>
</li>
<li><div class="title">Turbo Equalization Performance: The Effect of Precoding and Application of Turbo Codes</div>
Study thesis, Ulm University, 2009
<div class="title">
[<a href="/assets/pdf/haeger_study_thesis.pdf" target="_blank">PDF</a>]
</div>
</li>
</ol>

</div>

<br>

Disclaimer: This material is presented to ensure timely dissemination of scholarly and technical work. Copyright and all rights therein are retained by authors or by other copyright holders. All persons copying this information are expected to adhere to the terms and constraints invoked by each author's copyright. In most cases, these works may not be reposted without the explicit permission of the copyright holder.

