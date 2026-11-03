---
layout: page
permalink: /projects/
title: Projects
description: Machine learning projects by Ramesh Nair, including vessel and airplane detection, road and building segmentation, change detection, and super resolution for satellite imagery.
---

## Machine Learning for Satellite Imagery

<div class="card" markdown="1">

### Vessel & Airplane Detection

I built deep learning systems that find ships and aircraft in medium-resolution satellite images.

- Adapted open-source object detection models for satellite data
- Worked with domain experts to design how we label training images, so the labels are high quality
- Delivered systems that detect and track objects at large scale in near real time

</div>

<div class="card" markdown="1">

### Semantic Segmentation for Roads & Buildings

I led a team that built segmentation models for roads and buildings. Segmentation means labeling every pixel in an image. The models work across the whole world.

- Built automated ETL pipelines (steps that collect and prepare data) and model training pipelines, using Kubeflow (a tool for running ML workflows)
- Deployed the models on Kubernetes (a system that runs software across many computers), with monitoring of their performance
- Supported analytics work for several teams

</div>

<div class="card" markdown="1">

### Change Detection

I built a complete pipeline that finds changes in infrastructure and land use over time.

- Analyzed satellite images of the same place from many dates, to see how it changed
- Released an open-source change detection dataset to support community research
- Connected the results to large language models (LLMs) that write a short summary of each event

</div>

## Research & Development

<div class="card" markdown="1">

### Weakly Supervised Anomaly Detection

I designed and deployed a new method that finds unusual things in images (anomalies) using very few labels.

- Reached an F1 score of 0.85 (a score from 0 to 1 that balances finding real cases and avoiding false alarms), with low false-positive rates
- Led to a granted U.S. patent
- Published at the [ICML 2019 Workshop on Climate Change and AI](https://www.climatechange.ai/papers/icml2019/24.pdf)

</div>

<div class="card" markdown="1">

### Super Resolution for Satellite Imagery

I made satellite images sharper using deep generative networks. These are models that create new image detail.

- Modified ESRGAN (a well-known super resolution model) for remote sensing, which means studying Earth from satellites
- Designed custom loss functions (the rules a model learns from) that fit the textures and details of the ground
- Scaled the method to process imagery from the whole world

</div>
