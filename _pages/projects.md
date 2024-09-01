---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
Below are some past and current side projects I've worked on with brief descriptions, sample figures, and links to code/slide decks. These projects are generally not directly related to my thesis work.

### [Clinical Subtyping of Multiple Sclerosis with SuStaIn](https://github.com/LeavittLabCUMC/SuStaIn_Clustering)
**Description:** This project is in collaboration with Columbia University Medical Center. The objective of the project is to derive subtypes and subtype stages based solely on clinical data from a large longitudinal cohort of patients with Multiple Sclerosis (MS). We specifically focus on behavioral clinical data that can be recorded at clinical visits. To derive subtypes that differ both phenotypically and temporally, we combine two related methods, Subtype and Stage Inference with Temporal Event-Based Modeling. In this ongoing work, we have fit preliminary models to identify 3 subtypes that differ in their disease progression as well as demographic and neurophysiological features. The ultimate goal is to develop our model to assign an unseen patient into a subtype in order to accurately predict their biomarker progression. 
_In Progress_   
<img src='/images/clinical_subtypes.png' width ='450'>
<br/>
<img src='/images/KDE_clinical_features.png' width='280'>
<img src='/images/KDE_clinical_features.png' width='280'>
_
###### Figures: Left - derived subtypes from patient data showing order of clinical progression. Right - kernel density estimates of clinical features between patients and asymptomatic patients.

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
<img src='/images/center_feature_performance.png' width='400'>
###### Figures: Left - model correctness for 2020 All-NBA team. Right - feature weights for center position (based on a comparable accuracy random forest model trained on same dataset) 

---

<!--
{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
