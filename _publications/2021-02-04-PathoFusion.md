---
title: "PathoFusion: An open-source AI framework for recognition of pathomorphological features and mapping of immunohistochemical data "
collection: publications
permalink: /publication/2021-02-04-PathoFusion
excerpt: 'We proposed an AI framework for cross-modality analysis of whole-slide pathology images. Code: https://github.com/guoqingbao/Pathofusion.'
date: 2021-02-04
venue: 'Cancers'
paperurl: 'https://doi.org/10.3390/cancers13040617'
citation: '<b>Guoqing Bao</b>, Xiuying Wang, Ran Xu, Christina Loh, Oreoluwa Daniel Adeyinka, Dula Asheka Pieris, Svetlana Cherepanoff, Gary Gracie, Maggie Lee, Kerrie L. McDonald, Anna K. Nowak, Richard Banati, Michael E. Buckland, and Manuel B. Graeber, (2021). &quot;PathoFusion: An open-source AI framework for recognition of pathomorphological features and mapping of immunohistochemical data&quot; <i>Cancers</i>. 13(4):617.'
---
We have developed a platform, termed PathoFusion, which is an integrated system for marking, training, and recognition of pathological features in whole-slide tissue sections. The platform uses a bifocal convolutional neural network (BCNN) which is designed to simultaneously capture both index and contextual feature information from shorter and longer image tiles, respectively. This is analogous to how a microscopist in pathology works, identifying a cancerous morphological feature in the tissue context using first a narrow and then a wider focus, hence bifocal. Adjacent tissue sections obtained from glioblastoma cases were processed for hematoxylin and eosin (H&E) and immunohistochemical (CD276) staining. Image tiles cropped from the digitized images based on markings made by a consultant neuropathologist were used to train the BCNN. PathoFusion demonstrated its ability to recognize malignant neuropathological features autonomously and map immunohistochemical data simultaneously. Our experiments show that PathoFusion achieved areas under the curve (AUCs) of 0.985 ± 0.011 and 0.988 ± 0.001 in patch-level recognition of six typical pathomorphological features and detection of associated immunoreactivity, respectively. On this basis, the system further correlated CD276 immunoreactivity to abnormal tumor vasculature. Corresponding feature distributions and overlaps were visualized by heatmaps, permitting high-resolution qualitative as well as quantitative morphological analyses for entire histological slides. Recognition of more user-defined pathomorphological features can be added to the system and included in future tissue analyses. Integration of PathoFusion with the day-to-day service workflow of a (neuro)pathology department is a goal. The software code for PathoFusion is made publicly available.

[Access full paper here](https://doi.org/10.3390/cancers13040617)

Open-source Code in GitHub: [link](https://github.com/guoqingbao/Pathofusion).
