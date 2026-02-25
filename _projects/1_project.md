---
layout: page
title: Experimental Analysis of Two-Local Quantum Machine Learning Models
description: Evaluating state-of-the-art quantum machine learning circuits.
img: assets/img/expval.png
importance: 1
category: work
---

With this project, our objective wass to assess how the components of a quantum circuit influence
a Two-Local Variational Quantum Classifier (VQC), which is the most often used quantum machine learning model. We studied how its depth influences the classification performance and whether it
is possible to formulate experimental heuristics to navigate this wide range of possible
combinations. The results are obtained after an analysis over three different datasets all possible combinations for the choices of our hyper-parameters, consisting in rotation gates, entanglement type and topology. Through this study, we are able to formulate practical guidelines for designing Two-Local VQCs across multiple dimensions, problem complexity and number of layers.
    ---


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/expval.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A graph showing how many implementation with a specific entanglement topology outperformed were the best performing model according to different metrics.
</div>
