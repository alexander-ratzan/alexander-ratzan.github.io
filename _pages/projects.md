---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
Below are some past and current side projects (not directly related to my thesis work) that I've worked on with brief descriptions, sample figures, and links to code/slide decks.


### [Disease Gene Classification](https://github.com/alexander-ratzan/disease_gene_classification)
**Description:** 	In collaboration with Johns Hopkins University School of Medicine (Dr. Sandeep Wontakal), an expansive gene network was created, capturing diverse interactions of orthologous genes across 7 species. Gene properties and interactions were organized into a graph. Computational methods are being developed to leverage graph properties to probabilistically assign unclassified genes as disease related or non-disease related genes. 
_In Progress_
<br/>
<img src='/images/genenet_umap.png' width ='400'>
###### Figures: node2vec was applied to each gene in the graph to generate embeddings. The embeddings were then visualized using UMAP. This visualization represents 4000 nodes and 40,000 edges. 
---



### [Generalizable Deep Learning for a Handwriting BCI Decoder](https://www.kaggle.com/code/alexanderratzan/handwriting-bci-neuromatch-project)
**Description:** The act of imagining handwriting generates neural activity patterns in the hand motor cortex area that can be decoded with BCIs to generate letters and words. Improving deep learning models to decode neural activity provides a promising avenue for restoring real-time communication for individuals suffering from paralysis and motor-related disorders. In this project, we trained CNN and RNN models to decode handwriting at high accuracy without daily recalibriation, building on [research](https://www.nature.com/articles/s41586-021-03506-2) by Willet et al., 2021. This project was completed throughout the neuromatch academy deep learning course.
_2024_
<br/>
<img src='/images/willet_schematic.png' width ='300'>
<br/>
<img src='/images/CNN_RNN_handwriting.png' width ='700'>
###### Figures: Top - experiment schematic showing microelectrode array capturing signals from motor cortex. Bottom - CNN and RNN architectures and days after training performance curves.
---


### [Intracortical Gene Expression across Primate Species](https://docs.google.com/presentation/d/1FeLs4BjY18BV7PQdSf4ppqKBKcVN6mqtPCV0NioJcsM/edit?usp=sharing)
**Description:** 	In comparison to close evolutionary relatives, the human brain has distinct properties from a biological and behavioral standpoint. The present study aims to highlight differences in orthologous gene expression patterns between humans and chimpanzees. Focusing on two regions with central roles in cognition, the anterior cingulate cortex and cerebellar white matter, differential expression analysis identified sets of human-specific overexpressed genes in each region respectively. These gene expression patterns shed light on the evolutionary functional changes acquired in the human lineage beyond gene duplication events. 
_2024_ 
<img src='/images/primate_fig.png' width ='800'>
###### Figures: Top - phylogenetic tree schematic. Sagitall cross-section of brain highlighting the anterior cingulate cortex (11) and cerebellar white matter (28). Bottom - Enriched GO terms for differentlially expressed genes in the cerebellar white matter. Functional module plot created with [humanbase](https://hb.flatironinstitute.org/).
---

### [Clinical Subtyping of Multiple Sclerosis with SuStaIn](https://github.com/LeavittLabCUMC/SuStaIn_Clustering)
**Description:** This project is in collaboration with Columbia University Medical Center (Dr. Victoria Leavitt). The objective of the project is to derive subtypes and subtype stages based solely on clinical data from a large longitudinal cohort of patients with Multiple Sclerosis (MS). We specifically focus on behavioral clinical data that can be recorded at clinical visits. To derive subtypes that differ both phenotypically and temporally, we combine two related methods - Subtype and Stage Inference with Temporal Event-Based Modeling. In this ongoing work, we have fit preliminary models to identify 3 subtypes that differ in their disease progression as well as demographic and neurophysiological features. The final model should be able to assign an unseen patient to a given subtype and accurately predict biomarker progression.
_In Progress_   
<img src='/images/clinical_subtypes.png' width ='500'>
<br/>
<img src='/images/KDE_clinical_features.png' width='300'>
<img src='/images/SuStaIn_ternary_plot.png' width='300'>
###### Figures: Top - derived subtypes from patient data showing order of clinical progression. Left - kernel density estimates of clinical features between patients and asymptomatic patients. Right - Each point corresponds to a single subject and the location in the triangle reflects confidence of assignment to each subtype.
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
