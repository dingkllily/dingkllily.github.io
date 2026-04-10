---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* **Ph.D. Candidate in Civil Engineering**, University of Illinois Urbana-Champaign, 2021 - Present  
  Focus: Machine Learning, Computer Vision | GPA: 4.0 / 4.0
* **Master of Science in Civil Engineering**, University of Illinois Urbana-Champaign, 2019 - 2021  
  GPA: 3.98 / 4.0
* **Bachelor of Engineering in Harbor, Waterway, and Coastal Engineering**, Zhejiang University, 2016 - 2020

Research and Engineering Experience
======

* **Graduate Research Assistant / Machine Learning Engineer**, University of Illinois Urbana-Champaign, 2020 - Present
  * Built and deployed production-facing ML systems for field inspection, multimodal sensing, and 3D analysis workflows.
  * Developed agent-based and deployment-oriented AI workflows integrating data processing, model inference, and result interpretation across modular components.
  * Designed and evaluated large-scale image, video, and 3D pipelines under real-world field conditions.

  * **Machine Learning-Based Field Ballast Condition Evaluation**, 2025 - Present
    * Built and deployed I-BALLAST Mobile, an iOS application for field ballast inspection with real-time image processing and on-device inference.
    * Built a performance-sensitive inference workflow supporting concurrent local inference and higher-quality remote DINO-SAM inference when needed.
    * Owned deployment workflow design, profiling, and latency optimization for large-image inference pipelines based on RTMDet and SAHI.

  * **Mud Spot Ballast Segmentation**, 2024 - 2025
    * Trained a DETR-based detector and fine-tuned SAM on augmented muddy-ballast imagery, improving segmentation performance by about 5% in both mAP and mAR.
    * Validated the DETR-SAM pipeline on real field data, achieving 4.18% MAE in Fouling Index and 3.45% MAE in Particle Size Distribution.

  * **Simulation-Driven Dataset Generation**, 2023 - 2024
    * Built desktop software using the Blender Python API to automate simulation-driven synthetic image and point-cloud generation.
    * Developed reusable data pipelines to improve model robustness under limited labeled real-world data.

  * **Automated Machine Vision-Based Ballast Scanning**, 2020 - 2023
    * Designed and implemented the Ballast Scanning Vehicle (BSV), integrating cameras, 3D scanning, and GPS positioning for large-scale field evaluation.
    * Developed segmentation pipelines using Swin Transformer and Cascade Mask R-CNN.
    * Deployed inspection software adopted by the Federal Railroad Administration for field evaluations.

  * **Riprap Aggregate Size and Shape Analysis**, 2020 - 2022
    * Developed I-RIPRAP 3D, an interactive software system for deep-learning-based 3D aggregate analysis and physical-scale estimation.
    * Delivered software adopted by the Illinois Department of Transportation.

Technical Skills
======

* **Languages:** Python, C/C++, Swift, Objective-C++, Java, JavaScript
* **ML / AI:** PyTorch, Core ML, ONNX, Vision Transformers, DETR, SAM, YOLO, Mask R-CNN, GCN
* **Vision / 3D:** OpenCV, Open3D, COLMAP, Blender Python API, structure from motion, point cloud processing, multi-sensor fusion
* **Systems / Data:** Spark, Hadoop, MySQL, MongoDB, SQLite, AWS (S3, Lambda, DynamoDB, SageMaker, Bedrock)
* **Applications:** SwiftUI, PyQt, React.js, Vue.js, REST APIs

Selected Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
