<h1 align="center">RSNA Lumbar Spine Degenerative Detection & Classification</h1>

<p align="center">
    <strong>A deep learning-based diagnostic tool for automatic classification of lumbar spine degenerative conditions using MR images.</strong>
</p>

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/MRI_3D_medical_animation_still_showing_sagittal_section_of_human_lumbar_spine.jpg" alt="Lumbar Spine" width="400">
</p>

## Overview

This repository contains the final capstone project for the <strong>B.Tech in Artificial Intelligence and Data Science</strong>. The project focuses on using deep learning techniques, particularly with the <strong>EfficientNet</strong> architecture, to automatically classify degenerative conditions of the lumbar spine from MR images. The dataset used is provided by the RSNA 2024 Lumbar Spine Degenerative Classification competition on <a href="https://www.kaggle.com/competitions/rsna-2024-lumbar-spine-degenerative-classification">Kaggle</a>.

## Dataset

The dataset includes multi-view MR images (sagittal and axial views) of the lumbar spine, with corresponding labels for various degenerative conditions. The labels include:

- Left Neural Foraminal Narrowing
- Left Subarticular Stenosis
- Right Neural Foraminal Narrowing
- Right Subarticular Stenosis
- Spinal Canal Stenosis

Due to the size of the dataset (>7GB), the data itself is not included in this repository. Please follow the instructions below to download the dataset.

### How to Download the Dataset

1. Go to the <a href="https://www.kaggle.com/competitions/rsna-2024-lumbar-spine-degenerative-classification">RSNA 2024 Lumbar Spine Degenerative Classification</a> competition page on Kaggle.
2. Download all the files and folder on the website.

<h2>Installation</h2>

<ol>
  <li>
    <strong>Clone the Repository</strong>
    <pre><code>bash
git clone https://github.com/yourusername/rsna-lumbar-spine-degenerative-detection-classification.git
cd rsna-lumbar-spine-degenerative-detection-classification
</code></pre>
  </li>

  <li>
    <strong>Set Up Python Environment</strong>
    <p>Ensure you have Python 3.8+ installed. You can set up the environment using the following steps:</p>

    <h4>Using <code>virtualenv</code></h4>
    <pre><code>bash
python3 -m venv lumbar_env
source lumbar_env/bin/activate   # For macOS/Linux
lumbar_env\Scripts\activate      # For Windows
</code></pre>

    <h4>Using <code>conda</code></h4>
    <pre><code>bash
conda create --name lumbar_env python=3.8
conda activate lumbar_env
</code></pre>
  </li>

  <li>
    <strong>Install Dependencies</strong>
    <pre><code>bash
pip install -r requirements.txt
</code></pre>
    <p>This will install necessary packages, including TensorFlow, EfficientNet, and other dependencies.</p>
  </li>
</ol>
