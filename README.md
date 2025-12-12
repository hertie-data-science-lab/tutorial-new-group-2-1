<p align="center">
  <img
    width="400"
    height="54"
    alt="image"
    src="https://github.com/user-attachments/assets/14c8187c-a36f-43f3-a1ab-4cbfe56324c4"
  />
</p>
<br><br>

## Tutorial for Sentinel-1 Flood Analysis: Transfer Learning and Embedding Applications  
**GRAD-E1394 Deep Learning – Assignment 3**

This tutorial is submitted as an assignment for the course GRAD-E1394 Deep Learning, which integrates the Data Science for Public Policy Master program at the Hertie School of Governance in Berlin. It presents a practical workflow for **flood detection using Sentinel-1 SAR satellite imagery**, demonstrating how **transfer learning with pretrained convolutional neural networks (CNNs)** can be applied to radar data to generate flood maps and reusable feature representations.

The notebook combines conceptual explanations with practical implementation, including a U-Net segmentation model with a ResNet-34 encoder. The model is trained using a two-stage transfer learning strategy, adapting ImageNet-pretrained features to Sentinel-1 VV and VH polarizations. The trained encoder is then used to extract 512-dimensional embeddings for downstream tasks including flood classification, image similarity search, and unsupervised clustering, illustrating how learned representations capture meaningful, region-agnostic flood patterns that can support rapid flood monitoring and climate-related decision-making.

In addition to the tutorial notebook, we also provide a [slide presentation](https://github.com/hertie-data-science-lab/tutorial-new-group-2-1/blob/main/DL%20Presentation%202025%20-%20Group%202%20(final).pdf) that covers the relevance of the topic for public policy and government, as well as a quick background and overview of what is covered in the tutorial.

This [video guide](https://youtu.be/adiGGknwwvE) can be accessed on YouTube and walks through the tutorial and its components to assist with the overall understanding of how to run the notebook.

<br>

### Authors
Aditi Joshi  
Elena Murray  
Leticia Figueiredo Collado  
Sattiki Ganguly  
Xiaohan Wu
<br><br>
**Collaboration statement:**  
All students actively collaborated to ensure the successful making of this tutorial.
