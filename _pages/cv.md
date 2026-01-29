---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

## EDUCATION

**Master of Science in Electrical & Computer Engineering**
(Signal and Image Processing and Machine Learning)
University of Michigan, Ann Arbor, MI (Expected Aug 2027)

**Bachelor of Science in Computer Engineering with Distinction**
Purdue University, West Lafayette, IN (Dec 2024)

---

## RESEARCH EXPERIENCE

### Researcher

*LASER (Life-cycle Assessment Synthesized with Ecosystems and Risk), University of Michigan*

Aug 2025 - Present

* Designed and trained a fully convolutional neural network (FCN) for biomass prediction from multi-source satellite imagery using PyTorch and Rasterio
* Developed CNN encoders for multichannel image patches and residual MLPs for tabular feature fusion
* Built an end-to-end inference pipeline to generate large-scale biomass prediction maps over geographic regions
* Performed GIS-based validation and error analysis to diagnose spatial artifacts and model failure modes

### Undergraduate Research Assistant

*Autonomous Motorsport Purdue, Purdue University*

Aug 2023 - Dec 2024

* Created an automated annotation pipeline using YOLOv8 to scale training data generation and minimize manual labeling
* Developed a CNN-based real-time track and lane detection system for autonomous racing under extreme conditions
* Achieved 47× faster inference than YOLOv8 with 65% fewer parameters, enabling real-time
* deployment
* Co-developed RoRaTrack, the first multi-camera road-racing dataset with pixel-level track annotations
* Designed RaceGAN, a GAN-based model that outperformed 8 state-of-the-art baselines on racing scenarios

### Undergraduate Research Assistant

*ECELabs, Purdue University*

Jun 2023 - Dec 2024

* Built and maintained an online FPGA experimentation platform used by 200+ students, enabling remote hardware access and monitoring
* Designed a full-stack dashboard to track device performance, usage metrics, and system health
* Improved Diagram ↔ SystemVerilog translation pipelines by 50×, significantly accelerating iteration and debugging workflows
* Implemented design-rule checks and static analysis tools to improve code correctness and development efficiency
* Developed VGA and audio hardware extensions for ICE40 FPGA using Pmod interfaces

---

## TEACHING EXPERIENCE

**Teaching Assistant**
*Department of Computer Science, Purdue University*

Jan 2023 - Dec 2024

* Led in-person lab sessions on C programming for over 50 students.
* Held weekly office hours and organized exam review sessions.

---

## SELECTED PROJECTS

### Senior Design Electrical Lead

*Purdue University*

Aug 2024 - Dec 2024

* Led the electrical design for an autonomous vehicle, integrating custom PCBs for autonomous control and lane detection.
* Designed multi-layer PCBs to manage power distribution and communication.
* Developed microcontroller firmware in C and a lane detection algorithm in Python to interface with the Jetson Nano and other modules.

### Processor Prototyping

*Purdue University*

Aug 2024 - Dec 2024

* Designed and prototyped a pipelined processor with cache and multicore architectures using SystemVerilog.
* Implemented multicore and cache logic, including a bus controller state machine.
* Demonstrated improved performance for a dual-threaded program on the multicore design.

### Paris 2024 Central Planning Tool

*The Data Mine, Purdue University*

Aug 2022 - May 2023

* Partnered with the Ray Ewry Sports Engineering Center to develop a central planning tool for the International Olympic Committee.
* Implemented an ETL pipeline to process over 10,000 data entries using Python and SQL.
* Developed a full-stack web application for partners and organizers to view and consolidate data for Paris 2024.

---

## PUBLICATIONS

* Ghosh, S., Chen, Y. H., Huang, C. H., Jameel, A. S. M. M., El Gamal, A., & Labi, S. (2024). Weighted branch aggregation based deep learning model for track detection in autonomous racing. In The Second Tiny Papers Track at ICLR 2024.
* Ghosh, S., Chen, Y. H., Huang, C. H., Jameel, A. S. M. M., Ho, C. C., Gamal, A. E., & Labi, S. (2025). A Racing Dataset and Baseline Model for Track Detection in Autonomous Racing. arXiv preprint arXiv:2502.14068. (Under Review)

---

## CONFERENCE PRESENTATIONS

* Ghosh, S., Chen, Y.H., Huang, C.H., Jameel, A.S.M.M., El Gamal, A., Labi, S. (2024). Weighted branch aggregation based deep learning model for track detection in autonomous racing. Presented at the 12th International Conference on Learning Representations (ICLR 2024), May 7-11, 2024, Vienna, Austria.
* Ghosh, S., Chen, Y. H., Huang, C. H., Ho, C. C., & Labi, S. (2024). Purdue Vertically Integrated Program (VIP) for the Autonomous Motorsports Purdue Club. Presented at Next-Generation Transport Systems Conference (NGTS-4), Sep 2, 2024, West Lafayette, IN. (Poster)

---

## AWARDS AND HONORS

* Electrical and Computer Engineering General Scholarship, Purdue University (2023)
* Dean's List, Purdue University (2021-2024)
* Share with the World Award for Vertically Integrated Projects, Purdue University (2024)

---

## TECHNICAL SKILLS

* ML & Data: PyTorch, NumPy, Pandas, Rasterio, GIS (QGIS)
* Programming: Python, C, Julia, SystemVerilog, JavaScript, MATLAB
* Computer Vision, Deep Learning (CNNs, GANs), Segmentation
* Systems & Hardware: Embedded ML, Jetson Nano, FPGA, RTL Design, ASIC Development
* Languages: English, Mandarin

<!--<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>/-->
