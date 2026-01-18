# JassidNet
The repository is for the papaer: **JassidNet: A Quantization-Aware Lightweight Phenotyping Framework for High-Throughput Cotton Jassid (*Amrasca biguttula*) Detection and Counting Toward Objective Resistance Screening**, including the code and a benchmark subset for reproducing.

This paper is under review on [***Industrial Crops and Products***](https://www.sciencedirect.com/journal/industrial-crops-and-products).

## Problem Statement
<p align="center">
  <img src="assets/statement.png" width="800">
  <br>
  <em><strong>Fig.1</strong> Illustration of background complexity in field-acquired cotton leaf images and the target-specific focus of the proposed approach.</em>
</p>

## Dataset and Dataset Construction
We propose a ***pseudo-label iteration–based dataset construction strategy*** and introduce the first vision dataset dedicated to cotton jassid recognition, termed the **Cotton Jassid Recognition (CJR) Dataset**.

The dataset will be publicly released on [Kaggle](coming soon).

<p align="center">
  <img src="assets/Pseudo-label iteration-based dataset construction pipeline chart.png" width="800">
  <br>
  <em><strong>Fig.2</strong> Workflow of semi-supervised dataset construction with iteration-based pseudo-labels. <strong>Note:</strong> Flows in the loop are highlighted by pink arrows; pink dashed line indicates that the operation is performed only once; the yellow star marks the start of the entire pipeline.</em>
</p>

<p align="center">
  <img src="assets/Representative examples of dataset samples.png" width="800">
  <br>
  <em><strong>Fig.3</strong> Representative images of CJR dataset samples. <strong>Note:</strong> Red circles represents adults (longer length, presence of wings and the characteristic two black spots), and yellow represents nymphs (smaller size when compared to adults and absence of wings).</em>
</p>




