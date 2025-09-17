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
* Ph.D in Electrical Engineering, University of Washington, 2021
* B.S. in Physics, National Taiwan University, 2015

## <i class="fa fa-fw fa-briefcase"></i> Work experience
* **Staff Research Scientist**, Meta, Seattle, WA <span class="element-align-right">*Sep 2021 -- Present*&nbsp;&nbsp;</span> <br>
  * Tech-led a team of MLEs on LLM post-training to enhance ad performance and ensure alignment with advertisers’ brand values
    * Designed and implemented a multi-objective PPO framework to jointly optimize performance/user engagement and brand alignment using
users’ and AI-driven signals
    * Investigating vision-aware multimodal LLM post-training to mitigate clickbait text and drive incremental conversion gains
    * Delivered 7.34% top-line improvement in ad quality metrics, translating to tens of millions of dollars in incremental revenue
    * News coverage:
      * https://www.facebook.com/business/news/introducing-ai-sandbox-and-expanding-meta-advantage-suite
      * https://techcrunch.com/2023/05/11/meta-announces-generative-ai-features-for-advertisers/
  * Investigated automatic text engagement and hallucination scoring models as thhe evaluators for the generated texts
    * Created a Multi-Text with Engagement label pipeline from the impression-level data to rank text performance within the same ads
    * Developed a hallucination detection model using human-annotated texts with label distillations

* **Machine Learning Intern**, Facebook, Seattle, WA <span class="element-align-right">*Jun 2020 -- Sep 2020*&nbsp;&nbsp;</span> <br>
  * Developed deep learning models to optimize the click-through rate (CTR) based recommendation system for search ads placement
  * Investigated various modeling techniques, including transfer learning and multi-task learning

* **Research Intern**, Microsoft Research, Redmond, WA <span class="element-align-right">*Jun 2018 -- Sep 2018*&nbsp;&nbsp;</span> <br>
  * Studied large-scale dynamic network model based on stochastic block model(SBM) and its extension to causal impact on temporal graphs
  * Our work has been accepted to [KDD'19 research track](/publication/2019-dsbm-causal-impact) (acceptance rate 14.2%) and [Animal Behaviour](/publication/2021-giraffe-social-network)

* **Teaching Assistant**, University of Washington, Seattle, WA <span class="element-align-right">*Jan 2017 -- Dec 2017*&nbsp;&nbsp;</span> <br>
  * Courses: Digital Signal Processing (graduate level), Devices And Circuits, Discrete Time Linear Systems, Fundamentals of Electrical Engineering

* **Front-end Software Engineer**, Psychological Warfare Group of M.N.D., Taipei, Taiwan <span class="element-align-right">*Aug 2015 -- Jul 2016*&nbsp;&nbsp;</span> <br>
  * Lead engineer on cloud-based file exchanging platform, which enables users to search, view, and share streaming media
  * Technology used: JavaScript (react.js), HMTL/CSS

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
