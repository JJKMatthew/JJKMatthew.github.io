---
title: "LepidIO — Phase-Aware Inertial Odometry for Flapping-Wing Robots"
collection: portfolio
permalink: /portfolio/lepidio/
excerpt: "A research project supported by Tsinghua University's SLAM Training Camp (July–August 2026). LepidIO combines IMU, flapping phase, and wing-angle measurements in a lightweight TCN–GRU framework for 3D inertial odometry. **First author · ICRA 2027 submission under review.**"
code_url: ""
video_url: ""
---

**Tsinghua University SLAM Training Camp · July–August 2026 · First author**

LepidIO addresses strong flapping disturbances and inertial drift on payload-constrained flapping-wing robots. It combines IMU, flapping phase, and wing-angle measurements in a multi-branch causal TCN–GRU architecture to predict body-frame 3D relative displacement over a one-second window.

## Highlights

- Curated a real-flight dataset of 26 sequences, with multi-modal synchronization and UWB trajectory registration.
- Reduced mean horizontal ATE by 75.0% (2.873 m to 0.718 m), vertical ATE by 56.5%, and one-second RTE by 25.7% relative to AirIO on two unseen test trajectories.
- Conference paper under review at ICRA 2027.

## Code and demo

{% if page.code_url != empty %}
[Source code]({{ page.code_url }})
{% else %}
Source-code link coming soon.
{% endif %}

{% if page.video_url != empty %}
[Watch the demo]({{ page.video_url }})
{% else %}
Video demo coming soon.
{% endif %}

[Paper details](/publications/lepidio/)
