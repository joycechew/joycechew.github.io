---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Click [here](https://joycechew.github.io/files/CV.pdf) to download full CV (last updated: January 2024).

Education
======
* Ph.D. in Mathematics, University of California, Los Angeles, 2025 (expected)
  * Advisor: Deanna Needell
* C.Phil. in Mathematics, University of California, Los Angeles, 2023
* M.A. in Mathematics, University of California, Los Angeles, 2022
* B.S. in Mathematics (Honors), Calvin University, 2020
* B.A. in Chemistry, Calvin University, 2020

<!-- Research experience
======
* June 2021 - present: Graduate Student Researcher
  * University of California, Los Angeles Department of Mathematics
  * Supervisor: Prof. Deanna Needell
  * Research interests:
    * Numerical linear algebra
    * Stochastic iterative methods
    * Graph and manifold learning

* June 2019 - August 2019: NSF REU
  * Cornell University Department of Mathematics
  * Supervisor: Dr. Andy Borum
  * Studied the equilibrium configurations of flexible helical springs using optimal control. Developed numerical methods to find unstable configurations and demonstrated the presence of saddle-node bifurcations in the equilibrium configurations of twisted springs.

* May 2018 - September 2020: Undergraduate Researcher
  * Calvin University Department of Chemistry and Biochemistry
  * Supervisor: Prof. Douglas A. Vander Griend
  * Projects:
    * _Development of a parallelized, high-throughput website for equilibrium binding analysis:_ Applied several classes of optimization algorithms to the simultaneous determination of reaction stoichiometry and binding constants of equilibrium systems of host-guest binding. Evaluated speed, convergence, and accuracy to devise a new hybrid algorithm. Currently implementing this new methodology in a supercomputer software package to facilitate fast, high-throughput analysis via a website interface.
    * _Mathematical and computational analysis of 1:1 equilibrium binding:_ Wrote Monte Carlo simulations to determine the robustness of global analysis for determination of binding constants of 1:1 host-guest equilibrium binding. Numerically demonstrated the benefits of using mathematically-derived optimal parameters for the titration experiment.

* May 2017 - August 2017: Undergraduate Researcher
  * Calvin University Department of Mathematics and Statistics
  * Supervisor: Prof. James Turner
  * Worked towards a new proof of the 3-variable Moreno-Socias conjecture to prove the generalized conjecture. Used computer algebra systems to compute Grobner bases of generic ideals. Formulated a conjecture characterizing generic Grobner bases and proved the 2-variable case.
 -->
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

Preprints
======
{% assign sorted_posts = site.pubP | sort: "date" | reverse %}
  <ol reversed>{% for post in sorted_posts %}
    {% include archive-single-pub-cv.html %}
  {% endfor %}</ol>

Conference/Workshop Papers
======
{% assign sorted_posts = site.pubC | sort: "date" | reverse %}
  <ol reversed>{% for post in sorted_posts %}
    {% include archive-single-pub-cv.html %}
  {% endfor %}</ol>

Journal Papers
======
{% assign sorted_posts = site.pubJ | sort: "date" | reverse %}
  <ol reversed>{% for post in sorted_posts %}
    {% include archive-single-pub-cv.html %}
  {% endfor %}</ol>

Talks and Presentations
======
{% assign sorted_posts = site.talks | sort: "date" | reverse %}
  <ol reversed>{% for post in sorted_posts %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ol>

<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

Awards
======
* UCLA Raymond Redheffer Prize (recognizes graduate student going above and beyond who taught freshman calculus course), 2022
* NSF Graduate Research Fellowship, 2020
* NCWIT Collegiate Award Finalist, 2019
* Goldwater Scholarship Honorable Mention, 2018
* Calvin Student Research Fellowship, 2016

Mentoring
======
Click [here](https://joycechew.github.io/mentoring/) for more information about each of these programs.
* UCLA/Los Angeles Pierce College Collaborative Undergraduate Research Experience (2023-present)
* UCLA CAM REU (2021, 2022)
* UCLA Women in Mathematics (2021-2023)
* UCLA Directed Reading Program (2021-2022)
