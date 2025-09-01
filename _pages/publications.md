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

**Walk-on-Interfaces: A Monte Carlo Estimator for an Elliptic Interface Problem with Nonhomogeneous Flux Jump Conditions and a Neumann Boundary Condition**\
X. Ding & A. R. Stinchcombe \


![snapshot](https://xinwending.github.io/files/DifferentiableCurlNoise/snapshot.png){: style="float: right; height: 150px; margin-left: 20px;" }
**Differentiable Curl-Noise: Boundary-Respecting Procedural Incompressible Flows Without Discontinuities**\
X. Ding & C. Batty. Proceedings of the ACM on Computer Graphics and Interactive Techniques (Symposium on Interactive 3D Graphics and Games), 2023.\
*Description:* A modification of the "Curl-Noise" method for procedural fluid flow in two dimensions that eliminates discontinuities and kinks in the flow around obstacles.\
[[Paper(PDF)]](https://xinwending.github.io/files/DifferentiableCurlNoise/Curl_Noise_Paper.pdf)
[[Supplementary]](https://xinwending.github.io/files/DifferentiableCurlNoise/Curl_Noise_Supplementary_Proof.pdf)
[[Animation]](https://cs.uwaterloo.ca/~c2batty/papers/Ding2023/SupplementaryVideoLarge.mp4)
[[Talks]](https://youtu.be/m8rggUd7cAQ?si=VIVtlgNJkq8ZxbDY&t=3555)
[[Codes]](https://github.com/XinwenDing/DifferentiableCurlNoise)
