---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
excerpt: "CV of Ching-Hsiang (Andrew) Huang: robot learning, computer vision and geospatial ML research at the University of Michigan, ITRI and Purdue."
redirect_from:
  - /resume
---
{% include base_path %}

<a href="{{ base_path }}/files/Ching-Hsiang_Huang_CV.pdf" class="btn btn--primary" style="text-decoration:none"><i class="fa fa-download" aria-hidden="true"></i> Download CV (PDF)</a>

## EDUCATION

**Master of Science in Electrical & Computer Engineering**<br>
*Signal and Image Processing and Machine Learning*<br>
University of Michigan, Ann Arbor, MI · Expected May 2027

**Bachelor of Science in Computer Engineering with Distinction**<br>
Purdue University, West Lafayette, IN · Dec 2024

---

## EXPERIENCE

### Robot Sensing AI System Intern

*Industrial Technology Research Institute (ITRI)* · May 2026 – Oct 2026 · [Project page](/portfolio/intern_itri/)

* Trained a vision-based quadruped locomotion policy with PPO in NVIDIA Isaac Gym across 4,096 parallel environments (6 terrain types, 20 difficulty levels); in simulation, the policy learned to jump 0.9 m gaps and cross beam terrain with 0.3 m spacing
* Designed a CNN + GRU + MLP policy network fusing 289-dimensional visual and proprioceptive observations for terrain-aware control
* Distilled privileged teacher policies into a deployable vision-based student via dual-teacher distillation
* Closed the sim-to-real gap with domain randomization and sensor-noise injection, validating from Isaac Gym and Gazebo to the physical Unitree Go2
* Consistently climbed 15–18 cm stairs and 25–40 cm platform obstacles in Gazebo and on the real robot
* Wrote Bash scripts to automate routine tasks and used AI coding tools (Claude Code) in day-to-day development

### Research Intern

*University of Michigan Transportation Research Institute (UMTRI)* · Mar 2026 – Jun 2026

* Built an AI-assisted HD-map lane editor combining agentic AI predictions with human review, correction, and QA for road-attribute mapping
* Developed a computer vision and geospatial pipeline that infers lane count, directionality, turn lanes, and median presence from aerial imagery and GIS data, automating HD-map attribute labeling
* Integrated SAM, DeepLabV3, and vision-language reasoning to validate roadway predictions against aerial imagery and GIS data, flagging errors before human review

---

## RESEARCH EXPERIENCE

### Research Assistant

*PixAIL Lab, University of Michigan* · Oct 2026 – Present

* Investigated possible causes of underestimated left atrial emptying, prioritized the likely factors, and designed validation tests using existing data
* Reviewed cardiac strain and twist metrics; identified through literature why circumference-based strain does not capture rotational deformation, supporting separate 3D torsion evaluation
* Proposed literature-backed fiber-aware regularization, size-independent twist metrics, and tagged-MRI benchmarks

### Graduate Researcher

*LASER (Life-cycle Assessment Synthesized with Ecosystems and Risk), University of Michigan* · Aug 2025 – Sep 2026 · [Project page](/portfolio/agbd/)

* Improved forest-biomass prediction R² from 0.66 (random-forest baseline) to 0.78 (RMSE ≈ 36.6 Mg/ha) by designing and training a multimodal FCN on Sentinel-2 imagery, AlphaEarth embeddings, and tabular data with PyTorch and Rasterio
* Fused tabular features into CNN encoders for multichannel image patches using residual MLPs and FiLM conditioning
* Built an end-to-end inference pipeline on the Great Lakes HPC GPU cluster (Slurm) to generate large-scale biomass maps for Michigan deciduous forest
* Performed GIS-based validation and error analysis to diagnose spatial artifacts and model failure modes

### Undergraduate Researcher

*ECELabs, Purdue University* · Jun 2023 – Dec 2024

* Built and maintained an online FPGA experimentation platform used by 200+ students across 20+ FPGA boards, enabling remote hardware access and monitoring
* Designed a full-stack dashboard to track device performance, usage metrics, and system health
* Cut Diagram-to-SystemVerilog translation time 50× by replacing a Yosys-based conversion with a custom Python compiler that rebuilds netlists from schematic geometry, keeping user signal names and readable RTL
* Built a design-rule checker enforcing 13 rules on student schematics before synthesis (multidrive, combinational loops, bus-width mismatches, unconnected nets, PCF pin constraints), reporting all violations in one pass and cutting the fix-and-rerun cycle
* Developed VGA and audio hardware extensions for ICE40 FPGA using Pmod interfaces

### Undergraduate Researcher

*Autonomous Motorsport Purdue, Purdue University* · Aug 2023 – Dec 2024 · [Publications](/publications/)

* Cut manual labeling effort 90% with an automated YOLOv8 annotation pipeline that labeled 1,300 images
* Co-developed a CNN-based real-time track and lane detection system for autonomous racing under extreme conditions, 47× faster than YOLOv8 with 65% fewer parameters (ICLR 2024, Tiny Papers)
* Co-developed RoRaTrack, the first multi-camera road-racing dataset with pixel-level track annotations
* Co-designed RaceGAN (trained the generator and discriminator, proposed the post-processing step), a GAN-based model that outperformed 8 state-of-the-art baselines on racing scenarios (arXiv 2502.14068)
* Integrated perception models with the Purdue AI Racing vehicle and validated performance in the Indy Autonomous Challenge

---

## TEACHING EXPERIENCE

### Teaching Assistant

*Department of Computer Science, Purdue University* · Jan 2023 – Dec 2024

* Led weekly in-person C programming labs for 50+ students, held office hours, graded assignments, and organized exam review sessions

---

## SELECTED PROJECTS

### Senior Design Electrical Lead

*Purdue University* · Aug 2024 – Dec 2024 · [Project page](/portfolio/Senior%20Design/)

* Led the electrical design for an autonomous vehicle, integrating custom PCBs for autonomous control and lane detection
* Designed multi-layer PCBs to manage power distribution and communication between the ESP32 microcontroller, H-bridge, and other components
* Developed ESP32 microcontroller firmware in C (including BLE for wireless laptop control) and a Python lane-detection algorithm, interfacing the Jetson Nano over UART with motor drivers for real-time control and detection

### Processor Prototyping

*Purdue University* · Aug 2024 – Dec 2024 · [Project page](/portfolio/cpu_design/)

* Designed and prototyped a 5-stage pipelined processor with forwarding, hazard detection, instruction/data caches, and a dual-core architecture in SystemVerilog on FPGA
* Implemented multicore and cache logic, including a bus-controller state machine enforcing snooping-based cache coherence
* Achieved up to 1.43× speedup on dual-threaded workloads with the dual-core design and characterized CPI under 0–10 cycle memory latency with a mergesort benchmark

### Paris 2024 Central Planning Tool

*The Data Mine, Purdue University* · Aug 2022 – May 2023

* Partnered with Ray Ewry Sports Engineering Center to develop a central planning tool for the International Olympic Committee to coordinate logistics and scheduling
* Designed and implemented an ETL pipeline to process over 10,000 data entries using Python and SQL
* Developed a full-stack web application to allow partners and organizers to view and consolidate data for Paris 2024

---

## PUBLICATIONS

* Ghosh, S., Chen, Y. H., **Huang, C. H.**, Jameel, A. S. M. M., El Gamal, A., & Labi, S. (2024). [Weighted branch aggregation based deep learning model for track detection in autonomous racing](/publication/2024-05-11-wba). In *The Second Tiny Papers Track at ICLR 2024*.
* Ghosh, S., Chen, Y. H., **Huang, C. H.**, Jameel, A. S. M. M., Ho, C. C., El Gamal, A., & Labi, S. (2025). [A Racing Dataset and Baseline Model for Track Detection in Autonomous Racing](/publication/2025-racegan). *arXiv preprint arXiv:2502.14068*.

---

## CONFERENCE PRESENTATIONS

* Ghosh, S., Chen, Y. H., **Huang, C. H.**, Jameel, A. S. M. M., El Gamal, A., & Labi, S. (2024). Weighted branch aggregation based deep learning model for track detection in autonomous racing. Presented at the 12th International Conference on Learning Representations (ICLR 2024), May 7–11, 2024, Vienna, Austria.
* Ghosh, S., Chen, Y. H., **Huang, C. H.**, Ho, C. C., & Labi, S. (2024). Purdue Vertically Integrated Program (VIP) for the Autonomous Motorsports Purdue Club. Presented at Next-Generation Transport Systems Conference (NGTS-4), Sep 2, 2024, West Lafayette, IN.

---

## AWARDS AND HONORS

* Share with the World Award for Vertically Integrated Projects, Purdue University (2024)
* Electrical and Computer Engineering General Scholarship, Purdue University (2023)
* Dean's List, Purdue University (2021–2024)

---

## TECHNICAL SKILLS

* **ML & Data:** PyTorch, NumPy, Pandas, Rasterio, GIS (QGIS)
* **Programming:** Python, C, SQL, Bash, Julia, SystemVerilog, JavaScript, MATLAB
* **Methods:** Computer Vision, Deep Learning (CNNs, GANs), Segmentation, Reinforcement Learning (PPO)
* **Systems & Hardware:** Embedded ML, Jetson Nano, ESP32, FPGA, RTL Design, ASIC Development, Linux, Slurm/HPC
* **Tools:** Git, NVIDIA Isaac Gym, Gazebo, AI coding tools (Claude Code)
* **Languages:** English, Mandarin
