---
title: Taming Uncertainty in the Assurance Process of Self-Adaptive Systems&#058; a Goal-Oriented Approach
permalink: publications/2019-SEAMS.html
layout: page
---

## Reference
Gabriela Solano, Ricardo Caldas, Genaina Rodrigues, Thomas Vogel, and Patrizio Pelliccione. "Taming Uncertainty in the Assurance Process of Self-Adaptive Systems: a Goal-Oriented Approach". In: International Symposium on Software Engineering for Adaptive and Self-Managing Systems. SEAMS ’19. IEEE, 2019, pp. 89--99. DOI: 10.1109/SEAMS.2019.00020

## Links
* [Open access version](https://arxiv.org/abs/1905.02228){:target="_blank"}
* [Paper at ACM DL](https://dl.acm.org/doi/10.1109/SEAMS.2019.00020){:target="_blank"}
* [Paper at IEEE DL](https://doi.ieeecomputersociety.org/10.1109/SEAMS.2019.00020){:target="_blank"}
* [Paper at IEEE Xplore](https://doi.org/10.1109/SEAMS.2019.00020){:target="_blank"}
* [Artifact (deployed as a web application)](https://seams2019.herokuapp.com/){:target="_blank"}
* [Code](https://github.com/lesunb/pistarGODA-MDP){:target="_blank"}

## Abstract
Goals are first-class entities in a self-adaptive system (SAS) as they guide the self-adaptation. A SAS often operates in dynamic and partially unknown environments, which cause uncertainty that the SAS has to address to achieve its goals. Moreover, besides the environment, other classes of uncertainty have been identified. However, these various classes and their sources are not systematically addressed by current approaches throughout the life cycle of the SAS. In general, uncertainty typically makes the assurance provision of SAS goals exclusively at design time not viable. This calls for an assurance process that spans the whole life cycle of the SAS. In this work, we propose a goal-oriented assurance process that supports taming different sources (within different classes) of uncertainty from defining the goals at design time to performing self-adaptation at runtime. Based on a goal model augmented with uncertainty annotations, we automatically generate parametric symbolic formulae with parameterized uncertainties at design time using symbolic model checking. These formulae and the goal model guide the synthesis of adaptation policies by engineers. At runtime, the generated formulae are evaluated to resolve the uncertainty and to steer the self-adaptation using the policies. In this paper, we focus on reliability and cost properties, for which we evaluate our approach on the Body Sensor Network (BSN) implemented in OpenDaVINCI. The results of the validation are promising and show that our approach is able to systematically tame multiple classes of uncertainty, and that it is effective and efficient in providing assurances for the goals of self-adaptive systems.

## BibTeX

<div class="bibtex">
<pre>@inproceedings{2019-SEAMS,
    author = {Solano, Gabriela and Caldas, Ricardo and Rodrigues, Genaina and Vogel, Thomas and Pelliccione, Patrizio},
    title = {Taming Uncertainty in the Assurance Process of Self-Adaptive Systems: a Goal-Oriented Approach},
    year = {2019},
    booktitle = {International Symposium on Software Engineering for Adaptive and Self-Managing Systems},
    series = {SEAMS~'19},
    publisher = {IEEE},
    pages = {89--99},
    doi = {10.1109/SEAMS.2019.00020},
}</pre>
</div>
