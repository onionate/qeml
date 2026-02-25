---
layout: page
title: Practical Quantum Fisher Kernel
description: Bringing quantum advantage in machine learning
img: assets/img/qfk.png
importance: 2
category: work
---
<p>Quantum kernel methods have been proven to suffer from a phenomenon called exponential concentration, where increasing the number of features of a quantum machine learning model leads to a kernel that is ineffective as all samples are categorized as completely different from eachother, leading to reduced classification power.</p>
<p>To combat this effect we implemented a previously simulation-only quantum kernel method called Quantum Fisher Kernel (QFK) which allowed us to compete with state-of-the-art quantum kernel methods such as Fidelity Kernel and the Projected Quantum Kernel, which respectively have a scalability and information loss issue. Our method provides effective exploitation of the quantum paradigm at the cost of added computation time, but avoiding work-arounds that affect the generalization and classification power of our machine learning method. We further demonstrated the potential for great improvement in time complexity, which will follow naturally from our developments. We also showed how QFKs are a viable solution for obtaining quantum advantage.</p>


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/qfk.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">

    A graph showing the effective dimension of the QFK compared with standard approaches. A lower effective dimension is better as it signifies better generalization power.
</div>


{% endraw %}
