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

* Having both intensive university research and software engineering work experience, which enables me to fast prototyping and commercially implementing novel ideas.

* Four years' full-time research experience in computer vision, artificial intelligence and medical informatics, and additional nine years' industry work experience as a senior/software engineer in development and architecture design of large-scale commercial software projects.

* Currently working on research projects that have potentials to revolutionize diagnosis and treatment of severe diseases with the support of machine learning.

* Academic and industry achievements (2008-2021):

  * 2016-2021:

  * Achieved high academic merit after reentering school, including high honor rolls, half-fee, summer research, dean’s list, Ph.D., and postgraduate supplementary scholarships from the University of Sydney as a Master's and PhD student. Published high quality scientific papers in areas of machine learning, pattern recognition and translational medicine in IEEE, Cancers, and Lancet family journals.

  * 2008-2016:

  * Responsible for architecture design and development of a cross-platform video streaming system in iQiYi.com.  Designed and implemented the universal video streaming model, the streaming architecture is stably running in hundreds of millions of mobile devices, PCs and smart TVs. It supported more than one billion video views per day successfully and stably and promoted more than 6% video view success rate in iQiYi platform since 2014.

  * Designed the technical solution which can stream iQiYi's video & AD content in third-party platforms. With the help of this technical solution, China’s top smartphone maker XiaoMi invested 300 million US dollars in iQiYi for video content cooperation at the end of 2014.

  * Implemented the human-machine interaction and video-on-demand solution for early-stage Internet TV (Smart TV) using Windows as the simulation platform. The pioneer design and solution has been the standard reference for many android streaming clients since 2012. The design and streaming solution was widely used by hundreds of millions of Smart TV/TVBox devices since 2013.


Education
======
* The University of Sydney, Australia
  * Ph.D (Artificial Intelligence and Image Processing, Thesis under submission), 2018-2021
  * Master of Information Technology, 2016-2018
* Shandong University, China
  * Undergraduate in Computer Science, 2003-2007

Academic Awards
======
* School of Computer Science, University of Sydney
  * **Dean's List of Excellence in Academic Performance** (09/2018)
  * **High Honour Roll in Digital Media Computing** (05/2018)
  * **High Honour Roll in Research Project** (05/2018)
  * **Summer Research Scholarship** (11/2017)
  * **Half-Fee scholarship** (05/2017)
* Ph.D. Scholarship, University of Sydney
  * **Engineering and Information Technologies Research Scholarship** (04/2018)
  * **Postgraduate Research Supplementary Scholarship** (08/2018) 
  * **University of Sydney International Scholarship (USydIS)** (08/2018)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Open-source Projects
======
* **COVID-MTL**
  * A multitask learning framework for diagnosis and severity assessment of COVID-19
  * Code: [https://github.com/guoqingbao/COVID-MTL](https://github.com/guoqingbao/COVID-MTL)
  * Paper: [https://www.sciencedirect.com/science/article/pii/S0031320321006750](https://www.sciencedirect.com/science/article/pii/S0031320321006750)
* **Pancancer Survival Analysis Framework**
  * We proposed a machine learning powered pipeline for survival analysis of different types of cancers based on gene expression
  * Code: [https://github.com/guoqingbao/PanCancerLncRNA](https://github.com/guoqingbao/PanCancerLncRNA)
  * Paper: [https://ieeexplore.ieee.org/document/9209037](https://ieeexplore.ieee.org/document/9209037)
* **Multiception**
  * A novel convolutional method that designed to improve the performance of depthwise separable convolution
  * Code: [https://github.com/guoqingbao/Multiception](https://github.com/guoqingbao/Multiception)
  * Presentation: [https://cloudstor.aarnet.edu.au/plus/s/vcmh8wLXVDtsZKQ](https://cloudstor.aarnet.edu.au/plus/s/vcmh8wLXVDtsZKQ)
  * Paper: [https://ieeexplore.ieee.org/document/9305369](https://ieeexplore.ieee.org/document/9305369)
* **PathoFusion**
  * An AI framework for automated detection of cancerous features in whole-slide histopathology images and mapping with immunohistochemical data in adjacent tissue sections
  * Code: [https://github.com/guoqingbao/Pathofusion](https://github.com/guoqingbao/Pathofusion)
  * Video demo: [https://www.youtube.com/watch?v=NXN6MpribTU](https://www.youtube.com/watch?v=NXN6MpribTU)
  * Presentation of core method: [https://cloudstor.aarnet.edu.au/plus/s/trQ3fL6acH345Ec](https://cloudstor.aarnet.edu.au/plus/s/trQ3fL6acH345Ec)
  * Paper for core method: [https://ieeexplore.ieee.org/document/9305369](https://ieeexplore.ieee.org/document/9305369)
  * Paper for application: [https://www.mdpi.com/2072-6694/13/4/617](https://www.mdpi.com/2072-6694/13/4/617)
* **PathoLabelling**
  * As a part of PathoFusion system, patholabelling enables the researchers and clinical experts marking the histopathology images for training AI model in recognition of malignant structures. The website provide functions to speed up traditional microscopic diagnostic workflow by overlaying the detected heatmaps on top of whole-slide tissue sections.
  * Code: [https://github.com/guoqingbao/Patholabelling](https://github.com/guoqingbao/Patholabelling)
  * Video demo: [https://cloudstor.aarnet.edu.au/plus/s/JSASsezqvrB9sgA](https://cloudstor.aarnet.edu.au/plus/s/JSASsezqvrB9sgA)
* **DeepAdipose**
  * We proposed a deep learning based framework for evaluation of metabolic disorders and surgery-induced weight loss effects using CT texture features extracted from human visceral.
  * Code: [https://github.com/guoqingbao/DeepAdipose](https://github.com/guoqingbao/DeepAdipose)
  * Paper: [https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(21)00264-4/fulltext](https://www.thelancet.com/journals/ebiom/article/PIIS2352-3964(21)00264-4/fulltext) 

Regular Reviewer for
======
  * Pattern Recognition
  * IEEE Journal of Biomedical and Health Informatics
  * Briefings in Bioinformatics
  * PLOS One
  * International Conference on Control, Automation, Robotics and Vision

Research Experience
======
* **PhD Candidate & Research Assistant** in School of Computer Science, The University of Sydney (04/2018 – Present)
  * Analyses medical imaging data and genomic big data based on machine learning/deep learning. 
  * Design and implement machine learning models that can harness medical big data for disease diagnosis. 
  * Write and publish high-quality scientific papers on computer vision, pattern recognition, machine learning, and translational medicine related areas. 
  * Improve the performance of deep learning algorithms in medical image recognition and genomic data processing.
  * Research and improve computer vision algorithms (such as image detection, segmentation, registration, etc.) for pathology and CT image data analysis.

Industry Work experience
======
* **Senior Software Engineer** in iQiYi.com (11/2011 – 07/2016)
  * Architecture design and development of a cross-platform video streaming kernel
  * Design and implementation of a universal video streaming model which has high extensibility and reliability
  * Responsible for video client integration of iQiYi & PPS in video streaming
  * Research, architecture design and development of technical solutions for iQiYi-XiaoMi cooperation
  * Research and exploration of the video streaming solutions for early-stage internet TV
  * Implementation of the human-machine interaction and video-on-demand solution for early-stage internet TV.
* **Software Engineer** in SuperD (02/2011 - 09/2011)
  * Responsible for design and development of the glasses-free 3D video client, include 3D video synthesis, 3D video renderer module, video transforming module.
  * Software design and implementation of the first commercial naked-eye 3D video player (client).
  * GPU synthesis and rendering of 3D video (left-right and up-down format of 3D videos).
* **Software Developer** in Vale Internet (Beijing) Co., Ltd. (09/2008 - 02/2011)
  * Mainly responsible for the development of the video distribution system, include product management application, video transforming client, video uploading client. Supported the whole life-cycle of the project, ranging from video transforming, distributing to the exhibition.
* **Software Developer** in Beijing ZhiFang Tech Co., Ltd. (02/2008 - 09/2008)
  * Responsible for the development and integration of a communication module which is used in medical research and examination application, this communication module can retrieve testing data from medical instruments and translate these raw data to readable report, and then print it.
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
