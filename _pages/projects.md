---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
Below are some past and current projects I've worked on with brief descriptions, sample figures, and links to code.

### [Clinical Subtyping of Multiple Sclerosis with SuStaIn](https://github.com/LeavittLabCUMC/SuStaIn_Clustering)
**Description:** I led a project at Columbia University Medical Center to generate informative clinical subtypes in a large dataset of patients with MS. In evaluating the clinical features available, I chose to apply a self-optimized version of SuStaIn (sub typing and staging inference) and identified 3 subtypes that differed in their disease progression as well as demographic and neurophysiological features.
_2022_   
<img src='/images/clinical_subtypes.png' width ='350'>
<img src='/images/KDE_clinical_features.png' width='250'>
###### Figures: Left - derived subtypes from patient data. Right - kernel density estimates of clinical features between patients and asymptomatic patients.

---


### [NeuroAnalysis Project](https://github.com/alexander-ratzan/2020-NeuroAnalysis-Project)
**Description:** Applied various machine learning techniques (Support Vector Machines, Clustering, Multi-Dimensional  Scaling, Principal Component Analysis) and statistical analysis tools (Representational Similarity Analysis, correlational maps and matrices) to classify, predict, and examine neural data.
_2020_   
<img src='/images/PPA.png' width='260'>
<br/>
<img src='/images/2D_PPA.png' width='330'>
<img src='/images/3D_PPA.png' width='330'>
###### Figures: Left - Parahippocampal place area mask from which fMRI data was extracted while subjects viewed various items. Middle - 2D representation of fMRI data from PCA. Right - 3D representation of fMRI data from PCA.

---


### [All-NBA Machine Learning](https://github.com/alexander-ratzan/NBA-Machine-Learning)
**Description:** Predicted the 2020 All-NBA team with 87% accuracy using a multi-layer perceptron neural net optimized and trained on 20 seasons of NBA statistics.
_2019_   
<br/>
<img src='/images/NN_NBA_performance.png' width='270'>
<img src='/images/center_feature_performance.png' width='380'>
###### Figures: Left - model correctness for 2020 All-NBA team. Right - feature weights for center position (based on a comparable accuracy random forest model trained on same dataset) 

---

<!--
{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
