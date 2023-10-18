---
layout: page
title: Nano-Precision Control
description: Research on Piezoelectric Nano-Precision Control
img: assets/img/PEA/Fig2.png
importance: 1
category: Projects
---
    ---
    Title of the Paper: Model-Free Adaptive Nonlinearity and Hysteresis Compensation Control Strategy with Application to Nano-Precision Piezoelectric Stage
    Conference name: IEEE ICCMA
    Date of publication: 1st Nov. 2023
    Description: A novel and adaptive hysteresis compensation control strategy
    ---

<p style="text-align:justify"> In the realm of nano-precision piezoelectric systems extensively applied in industrial measuring and manufacturing, addressing the inherent nonlinearities, particularly hysteresis is crucial. In this paper, a nonlinearity compensation strategy that achieves excellent tracking performance has been proposed without the need for a hysteresis model. <b>The approach commences with the establishment of the closed-loop feedback system. Subsequently, a well-designed feedforward Zero Phase Error Tracking Control is introduced, which effectively compensates for tracking errors induced by the reference. Finally, an adaptive compensator is employed to eliminate residual errors, including hysteresis and modeling error.</b> The proposed model-free compensation strategy demonstrates comparable performance to <strong>iterative learning control (ILC) </strong> without requiring time-consuming offline iterations while enhancing robustness against trajectory variations. The experimental results consistently validate the effectiveness and superiority of the proposed strategy for various trajectory-tracking tasks, including the adaptability to mutation trajectories. This model-free strategy can be readily applied without complex modeling or time-consuming iterations, demonstrating its potential for practical industrial applications in nanoprecision motion control. </p>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/PEA/Fig2.png" title="a" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   The block diagram of the control system.
</div>

With Error Reconstruction, the proposed method offers several merits summarized as follows:

• The proposed method achieves high tracking performance similar to ILC achieved through adaptive compensation for nonlinearities. More importantly, the method has successfully addressed the sensitivity to trajectory variations.

• As the compensation term for hysteresis is determined during the real-time motion, the proposed method does not depend on accurate hysteresis modeling.

• The model-free method is efficient and convenient since it eliminates the need for off-line pre-implementations, making it more applicable for practical applications.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/PEA/Fig1.png" title="b" class="img-fluid rounded z-depth-1" %}  
    </div>
</div>
<div class="caption">
    The overall experimental setup of the PEA system.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/PEA/Fig4_ai.png" title="b" class="img-fluid rounded z-depth-1" %}  
    </div>
</div>
<div class="caption">
<p style="text-align:justify"> Trajectory tracking results under different control strategies: (a) Case I - 20 Hz sinusoidal trajectory, (b) Case II – multi-sinusoidal trajectory, (c)
Case III – 20 Hz triangular trajectory.</p>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/PEA/Fig6_ai.png" title="b" class="img-fluid rounded z-depth-1" %}  
    </div>
</div>
<div class="caption">
<p style="text-align:justify"> Trajectory tracking performance indexes comparison of different control strategies.</p>
</div>

