---
permalink: /
title: "Guoqing's Profiles"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

About
======
Since 2022, Dr. Bao has been a Senior Staff Researcher specializing in optimizing ML systems on custom hardware. He received the Shanghai Leading Talent (Overseas) and Shanghai Pujiang Program Awards in 2022 and 2023, respectively, leading a 2-year research project in artificial intelligence and heterogeneous computing. He has six years of full-time research experience in computer vision, deep learning, and medical informatics, and nine years of industry experience as a senior software engineer in developing and designing large-scale commercial software projects.

From 2008 to 2016, he played a crucial role in designing and developing a cross-platform video streaming system at iQiYi.com. This system, supporting over one billion daily views, remains stable across hundreds of millions of devices and has improved the platform's video view success rate by over 6% since 2014. He also pioneered streaming solutions for third-party platforms, attracting a $300 million investment from Xiaomi in 2014. Additionally, he developed a human-machine interaction and video-on-demand solution for early-stage Smart TVs and TVBox devices, widely adopted since 2013.

From 2016 to 2021, he excelled as a Master's and PhD student at the School of Computer Science, University of Sydney, earning high honour rolls, half-fee scholarships, summer research opportunities, and placement on the dean's list. He also received PhD and postgraduate supplementary scholarships. During this time, he published high-quality papers in machine learning, pattern recognition, and translational medicine in prestigious journals such as Pattern Recognition, IEEE JBHI, and Lancet family journals.

Education
======
* The University of Sydney, Australia
  * PhD (Artificial Intelligence and Image Processing), 2018.07-2022.04
  * Master of Information Technology, 2016-2018
* Shandong University, China
  * Undergraduate in Computer Science, 2003-2007

Academic Awards
======
* Shanghai Municipality
  * Shanghai Leading Talent (Overseas) Award (09/2023)
* Science and Technology Commission of Shanghai Municipality
  * Shanghai Pujiang Program Award (10/2022)
* School of Computer Science, University of Sydney
  * Dean's List of Excellence in Academic Performance (09/2018)
  * High Honour Roll in Digital Media Computing (05/2018)
  * High Honour Roll in Research Project (05/2018)
  * Summer Research Scholarship (11/2017)
  * Half-Fee scholarship (05/2017)
* Ph.D. Scholarship, University of Sydney
  * Engineering and Information Technologies Research Scholarship (04/2018)
  * Postgraduate Research Supplementary Scholarship (08/2018) 
  * University of Sydney International Scholarship (USydIS) (08/2018)

Patents
======
* A Unified Machine Learning Computing Strategy (Device, Equipment, and Media) in Heterogeneous Scenarios (ZL202310348238.2), April 2023.
* A Method and Device for Determining Neural Network Task Scheduling Strategies in Heterogeneous Scenarios (ZL202310430896.6), April 2023.
* A Unified Machine Learning Compiler Based on Multi-Level Code Generation (ZL202310834277.3), July 2023.
* A Deep Learning Operator Fusion Method, Device, Electronic Equipment, and Storage Medium (ZL202311559655.8, China), November 2023.
* A Static Generation Method, Device, Equipment, and Medium for Reverse Computational Graphs of DNN Models (ZL202311576922.2, China), February 2024.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Work experience
======
- **Senior Staff Researcher** at Enflame Tech (04/2022 – Present)
  - Optimize machine learning systems and frameworks on custom hardware.

- **PhD Candidate & Research Assistant** at School of Computer Science, University of Sydney (04/2018 – 04/2022)  
  - Medical imaging and genomic big data analyses using machine learning and deep learning.
  - Design and implement machine learning models for disease diagnosis.
  - Publish scientific papers on computer vision, pattern recognition, machine learning, and translational medicine.
  - Enhance deep learning algorithms for medical image recognition and genomic data processing.
  - Improve computer vision algorithms for pathology and CT image data analysis.
- **Senior Software Engineer** at iQiYi.com (11/2011 – 07/2016)  
  - Development and architecture design for a cross-platform video streaming system.
  - Created a universal and reliable video streaming method.
  - Integrate video streaming clients for iQiYi and PPS.
  - Developed solutions for iQiYi-XiaoMi cooperation.
  - Research video streaming solutions for early-stage Internet TV.
  - Implemented human-machine interaction and video-on-demand solutions.
- **Software Engineer** at SuperD (02/2011 - 09/2011)  
  - Designed and developed a glasses-free 3D video client.
  - Developed the first commercial naked-eye 3D video player.
  - Synthesize and render 3D videos using GPU.
- **Software Developer** at Vale Internet (Beijing) Co., Ltd. (09/2008 - 02/2011)  
  - Developed a video distribution system.
  - Supported the full project lifecycle from video transformation to exhibition.
- **Software Developer** at Beijing ZhiFang Tech Co., Ltd. (02/2008 - 09/2008)  
  - Developed a communication module for medical research and health examinations.
  - Enable data retrieval from medical instruments and translate raw data into readable reports.

Regular Reviewer for
======
  * Pattern Recognition
  * IEEE Journal of Biomedical and Health Informatics
  * Briefings in Bioinformatics
  
Open-source Projects
======
* **UFront**
  * Unified MLIR compilation frontend (compile Pytorch, Tensorflow and ONNX models into MLIR TOSA and executable on different hardware)
  * Code: [https://github.com/guoqingbao/ufront/](https://github.com/guoqingbao/ufront)
  * Paper: [https://dl.acm.org/doi/10.1145/3691620.3695002](https://dl.acm.org/doi/10.1145/3691620.3695002)
* **Candle-vLLM**
  * A large language model inference framework entirely based on Rust (support GPU, Apple Silicon/Metal and Enflame GCU)
  * (equivalent to vLLM in Python ecosystem) 
  * Code: [https://github.com/EricLBuehler/candle-vllm](https://github.com/EricLBuehler/candle-vllm)
* **Candle-GCU**
  * Porting Huggingface Candle ML framework to the Enflame platform.
  * Code (Partial code release): [https://github.com/guoqingbao/Candle-GCU](https://github.com/guoqingbao/Candle-GCU)
* **COVID-MTL**
  * A multitask learning framework for diagnosis and severity assessment of COVID-19
  * Code: [https://github.com/guoqingbao/COVID-MTL](https://github.com/guoqingbao/COVID-MTL)
  * Paper: [https://www.sciencedirect.com/science/article/pii/S0031320321006750](https://www.sciencedirect.com/science/article/pii/S0031320321006750)
* **Pancancer Survival Analysis Framework**
  * We proposed a machine learning-powered pipeline for survival analysis of different types of cancers based on gene expression
  * Code: [https://github.com/guoqingbao/PanCancerLncRNA](https://github.com/guoqingbao/PanCancerLncRNA)
  * Paper: [https://ieeexplore.ieee.org/document/9209037](https://ieeexplore.ieee.org/document/9209037)
* **PathoFusion**
  * An AI framework for automated detection of cancerous features in whole-slide histopathology images and mapping with immunohistochemical data in adjacent tissue sections
  * Code: [https://github.com/guoqingbao/Pathofusion](https://github.com/guoqingbao/Pathofusion)
  * Video demo: [https://www.youtube.com/watch?v=NXN6MpribTU](https://www.youtube.com/watch?v=NXN6MpribTU)
  * Presentation of core method: [https://cloudstor.aarnet.edu.au/plus/s/trQ3fL6acH345Ec](https://cloudstor.aarnet.edu.au/plus/s/trQ3fL6acH345Ec)
  * Paper for core method: [https://ieeexplore.ieee.org/document/9305369](https://ieeexplore.ieee.org/document/9305369)
  * Paper for application: [https://www.mdpi.com/2072-6694/13/4/617](https://www.mdpi.com/2072-6694/13/4/617)
* **DeepAdipose**
  * We proposed a deep learning-based framework for the evaluation of metabolic disorders and surgery-induced weight loss effects using CT texture features extracted from human visceral.
  * Code: [https://github.com/guoqingbao/DeepAdipose](https://github.com/guoqingbao/DeepAdipose)
  * Paper: [https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(21)00264-4/fulltext](https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(21)00264-4/fulltext) 

