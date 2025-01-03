---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

About
======
Since 2022, Dr. Bao has been a Senior Staff Researcher specializing in optimizing ML systems. In October 2022, he received the Shanghai Leading Talent (Overseas) award and the Shanghai Pujiang Program Award, leading a 2-year research project in artificial intelligence and heterogeneous computing. With extensive experience in university research and industry software engineering, he excels in rapidly prototyping and commercially implementing innovative ideas. He has six years of full-time research experience in computer vision, deep learning, and medical informatics, and nine years of industry experience as a senior software engineer in developing and designing large-scale commercial software projects.

From 2008 to 2016, he played a crucial role in the architecture design and development of a cross-platform video streaming system at iQiYi.com. His work included creating and implementing a universal video streaming system that remains in stable operation across hundreds of millions of devices, supporting over one billion daily video views and improving the platform's video view success rate by over 6% since 2014. He also pioneered the technical solution for streaming iQiYi's video and advertising content on third-party platforms, leading to a $300 million investment by Xiaomi in late 2014. Additionally, he developed a human-machine interaction and video-on-demand solution for early-stage Internet TV (Smart TV), which has been widely adopted by Smart TV and TVBox devices since 2013.

From 2016 to 2021, he achieved academic success as a Master's and PhD student at the University of Sydney, earning high honours, half-fee scholarships, summer research opportunities, and placement on the dean's list. He also received PhD and postgraduate supplementary scholarships. During this time, he published high-quality scientific papers in the fields of machine learning, pattern recognition, and translational medicine in prestigious journals such as Pattern Recognition, IEEE JBHI and Lancet family journals.

Education
======
* The University of Sydney, Australia
  * Ph.D (Artificial Intelligence and Image Processing), 2018.07-2022.04
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
  * **Postgraduate Research Supplementary Scholarship (08/2018) 
  * University of Sydney International Scholarship (USydIS) (08/2018)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Academic Research Experience
======
* **PhD Candidate & Research Assistant** in School of Computer Science, The University of Sydney (04/2018 – 2022.04)
  * Analyses medical imaging data and genomic big data based on machine learning/deep learning. 
  * Design and implement machine learning models that can harness medical big data for disease diagnosis. 
  * Write and publish high-quality scientific papers on computer vision, pattern recognition, machine learning, and translational medicine related areas. 
  * Improve the performance of deep learning algorithms in medical image recognition and genomic data processing.
  * Research and improve computer vision algorithms (such as image detection, segmentation, registration, etc.) for pathology and CT image data analysis.

Regular Reviewer for
======
  * Pattern Recognition
  * IEEE Journal of Biomedical and Health Informatics
  * Briefings in Bioinformatics
 
Industry Work experience
======
* **Senior Staff Research Scientist** in Enflame Tech (04/2022 – Present)
  * Research in AI framework optimization and computer vision
* **Senior Software Engineer** in iQiYi.com (11/2011 – 07/2016)
  * Responsible for architecture design and development of the cross-platform video streaming architecture; design and implement the universal video streaming model; in charge of technical design, cooperation and communication with third parties, like XiaoMi, Lenovo, Huawei, etc.
  * Designed and implemented a universal and cross-platform video streaming architecture.
  * Designed the technical solutions that can stream iQiYi’s video and AD content on third party platforms.
* **Software Engineer** in SuperD (02/2011 - 09/2011)
  * Responsible for design and development of the glasses-free 3D video client, include 3D video synthesis, 3D video renderer module, video transforming module.
  * Software design and implementation of the first commercial naked-eye 3D video player (client).
  * GPU synthesis and rendering of 3D video (left-right and up-down format of 3D videos).
* **Software Developer** in Vale Internet (Beijing) Co., Ltd. (09/2008 - 02/2011)
  * Mainly responsible for the development of the video distribution system, include product management application, video transforming client, video uploading client. Supported the whole life-cycle of the project, ranging from video transforming, distributing to the exhibition.
* **Software Developer** in Beijing ZhiFang Tech Co., Ltd. (02/2008 - 09/2008)
  * Responsible for the development and integration of a communication module which is used in medical research and examination application, this communication module can retrieve testing data from medical instruments and translate these raw data to readable report, and then print it.
  
Open-source Projects
======
* **UFront**
  * Unified MLIR compilation frontend (compile Pytorch, Tensorflow and ONNX models into MLIR TOSA and executable on different hardware)
  * Code: [https://github.com/guoqingbao/Candle-GCU](https://github.com/guoqingbao/ufront)
  * Paper: [https://dl.acm.org/doi/10.1145/3691620.3695002](https://dl.acm.org/doi/10.1145/3691620.3695002)
* **Candle-vLLM**
  * A large language model inference framework entirely based on Rust (support GPU, Apple Silicon/Metal and Enflame GCU)
  * (equivalent to vLLM in Python ecosystem) 
  * Code: [https://github.com/EricLBuehler/candle-vllm](https://github.com/EricLBuehler/candle-vllm)
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

 
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Mentoring junior developers in IT industry (iQiYi.com)
* Lead seven research projects and managed over 50 sudents with different culture background (Syndey Uni)

  
Skills
======
* Software Architecture Design
* Machine Learning/Deep learning
  * Pytorch
  * Keras
  * Tensorflow,
  * Sklearn
* Data Analysis and Visualization
  * Pandas
  * Numpy
  * R
  * Matplotlib
  * Plotly
  * SSPS
  * Seaborn
* Image and Video Processing
  * OpenCV
  * FFmpeg
* Windows GUI
  * MFC
  * WPF
  * GDI/GDI+
* Video Streaming
  * DirectShow
  * Media Foundation
  * HLS
  * RTMP
* Software Development Language
  * Python
  * C++
  * C#
  * R
  * Rust
* Database
  * SQL Server
  * Firebird
  * SQLite
  * MySQL
* Web and Network
  * Django
  * ASP/ASP.Net
  * HTML
  * Socket/Boost Asio
  * COM/ActiveX
* Development tools
  * VS Code
  * Jupyter Notebook
  * Visual Studio (VC++, VC#)
  * Eclipse
  * Delphi
  * PyCharm
  * Android ADT Bundle
  * IBM Rhapsody
* Version Control
  * Tortoise SVN
  * Git
