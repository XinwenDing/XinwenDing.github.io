---
layout: archive
title: "Publications & Preprints"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
![snapshot](https://xinwending.github.io/files/woi/snapshot.png){: style="float: right; height: 120px; margin-left: 20px;" }
**Walk-on-Interfaces: A Monte Carlo Estimator for an Elliptic Interface Problem with Nonhomogeneous Flux Jump Conditions and a Neumann Boundary Condition**\
X. Ding & A. R. Stinchcombe. Journal of Computational Physics, 2026 \
*Description:* A Monte Carlo method for elliptic interface problem.\
[[Paper]](https://www.sciencedirect.com/science/article/pii/S0021999126004584?__cf_chl_tk=d5zJCnbDx74t6jaN6Nheya0JkgZtG4fYb2D6rrAQPyo-1780676013-1.0.1.1-kfKG1D8HYH_ARrvou55gkguARzXl7TuTgt1B3vxETmk)
[[Poster]](https://xinwending.github.io/files/woi/poster.pdf)
[[Codes]](https://github.com/XinwenDing/Walk-on-Interfaces)


![snapshot](https://xinwending.github.io/files/DifferentiableCurlNoise/snapshot.png){: style="float: right; height: 120px; margin-left: 20px;" }
**Differentiable Curl-Noise: Boundary-Respecting Procedural Incompressible Flows Without Discontinuities**\
X. Ding & C. Batty. Proceedings of the ACM on Computer Graphics and Interactive Techniques (Symposium on Interactive 3D Graphics and Games), 2023.\
*Description:* A modification of the "Curl-Noise" method for procedural fluid flow in two dimensions that eliminates discontinuities and kinks in the flow around obstacles.\
[[Paper(PDF)]](https://xinwending.github.io/files/DifferentiableCurlNoise/Curl_Noise_Paper.pdf)
[[Supplementary]](https://xinwending.github.io/files/DifferentiableCurlNoise/Curl_Noise_Supplementary_Proof.pdf)
[[Animation]](https://cs.uwaterloo.ca/~c2batty/papers/Ding2023/SupplementaryVideoLarge.mp4)
[[Talks]](https://youtu.be/m8rggUd7cAQ?si=VIVtlgNJkq8ZxbDY&t=3555)
[[Codes]](https://github.com/XinwenDing/DifferentiableCurlNoise)
