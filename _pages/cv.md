---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, Peking University, Sept. 2017 -- July. 2021(Expected)
* Exchange Program, University of British Columbia, Sept. 2019 -- Dec. 2019

Honors and Awards
======
National Scholarship (<i>Sept. 2020, Top 1% overall in School</i>);
Li Wai Wing Scholarship (<i>Sep. 2018, Top 10% Overall in School</i>);
DTZ Scholarship (<i>Sept. 2019, Top 5% Overall in School</i>);
Outstanding Student Award (<i>Sept. 2020, Sept. 2019, Sept. 2019</i>);


Publications
======
* Peiqing Chen, Dong Chen, Lingxiao Zheng, Jizhou Li, Tong Yang. Out of ManyWe are One: Measuring Item Batch with Clock-Sketch. ACM SIGMOD 2021


Work experience
======
* Department of Computer Science, University of Chicago, Research Intern for Prof. Junchen Jiang, June 2020 -- Present
  * Better telemetry for network What-if analysis
    * Study a wide range of network emulators and find that their prediction accuracy can be improved by a more accurate L-4 network telemetry system
    * Deploy CM-sketch on programmable switches to measure network data stream
    * Propose a tighter error bound of CM-sketch using real-time traffic pattern and give a more accurate telemetry
* Network and Big Data Group, Peking University, Research Intern for Prof. Tong Yang, Feb. 2019 -- Now
  * Out of Many We are One: Measuring Item Batch with Clock-sketch Pose Guided Person Image Synthesis
    * Generalize a data stream pattern Item Batch, which means a batch of items with same ID in a data stream
    * Measuring data stream by item batches is useful in cache prefetching, burst detection and APT analysis
    * Design Clock-sketch algorithm to measure activeness, cardinality, time span and size of item batches
  * Sliding Hardware Estimator: A Generic Framework for Measurements over Sliding Windows
    * Introduce a framework which can evolve several static window measurement algorithms into sliding window scenarios in network measurement. The algorithms include Bitmap, HyperLogLog, Bloom Filter, etc.
    * Implement our sliding window algorithm on programmable switches to conduct real network measurement


Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* [Forum for American-Chinese Exchange at Stanford University](https://faces.stanford.edu/), Organizer, Mar 2019 -- Dec 2019
