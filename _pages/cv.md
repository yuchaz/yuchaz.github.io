---
layout: archive
title: "Curriculum vitae"
permalink: /cv/
inline_obj: true
author_profile: true
redirect_from:
  - /resume
header:
  overlay_image: mt_rainier_tweak.jpeg
  caption: "Mt. Rainier, WA, USA"
---

{% include base_path %}

<h2 style='margin-top: 10pt'>
<i class="fa fa-fw fa-file-pdf"></i> PDF version is available
<a href="/files/resume.pdf" target="_blank">here</a>.
</h2>

## <i class="fa fa-fw fa-graduation-cap"></i> Education
* Ph.D in Electrical Engineering, University of Washington, 2021 (expected)
* B.S. in Physics, National Taiwan University, 2015

## <i class="fa fa-fw fa-briefcase"></i> Work experience
* **Research Intern**, Microsoft Research, Redmond, WA <span class="element-align-right">*Jun 2018 -- Sep 2018*&nbsp;&nbsp;</span> <br>
  * Studied large scale dynamic network model based on stochastic block model(SBM) and the extension to causal impact on temporal graphs.
  * [Paper](/publication/2019-dsbm-causal-impact) accepted to KDD2019 research track (acceptance rate 14.2%).

* **Teaching Assistant**, University of Washington, Seattle, WA <span class="element-align-right">*Jan 2017 -- Dec 2017*&nbsp;&nbsp;</span> <br>
  * Courses: Digital Signal Processing (graduate level), Devices And Circuits, Discrete Time Linear Systems, Fundamentals of Electrical Engineering.

* **Front-end Software Engineer**, Psychological Warfare Group of M.N.D., Taipei, Taiwan <span class="element-align-right">*Aug 2015 -- Jul 2016*&nbsp;&nbsp;</span> <br>
  * Lead engineer on cloud-based file exchanging platform, which enabled user to search, view and share streaming media.
  * Technology used: JavaScript (react.js), HMTL/CSS.

## <i class="fa fa-fw fa-code"></i> Skills
* Python
* MATLAB
* JavaScript
* C++

## <i class="fa fa-fw fa-book"></i> Publications
  <ol>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ol>


## <i class="fa fa-fw fa-language"></i> Languages
* English -- Advanced
* Mandarin -- Native
* Taiwanese -- Native
