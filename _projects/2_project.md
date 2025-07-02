---
layout: page
title: project 2
description: Mapping wildfire susceptibility in the tropical region of Brunei, a machine learning and explainable AI approach using google earth engine with remote sensing data
img: assets/img/5.jpg
importance: 2
category: work
giscus_comments: true
---

As wildfires escalate globally, the need for accurate and interpretable predictions of their occurrence has never been more pressing. While Brunei experiences wildfires less frequently, their potential to disrupt ecosystems, harm biodiversity, and impact socio-economic activities highlights the need for proactive management strategies. In this study, we utilized Google Earth Engine (GEE) and its freely available remote sensing image collection data spanning from 2019 – 2024 to map wildfire susceptibility in Brunei. We assessed the performance of four machine learning (ML) models including Random Forest (RF), Extreme Gradient Boosting (XGBoost), Adaptive Boosting (AdaBoost), and Support Vector Machines (SVMs) for mapping wildfire susceptibility. These models were evaluated using thirteen independent factors related to wildfires, grouped into four main categories: climate, environment, topography, and human impact conditions. A multicollinearity analysis was performed to examine the interrelationships among these factors. According to the Performance evaluation outcomes, the predictive capabilities of the ML algorithms were compared using different performance metrics. The results demonstrated that the RF model performed best, achieving an F1 score of 0.900, a precision of 0.845, an accuracy of 0.854, and an ROC of 0.959. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dataP1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/project1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/resultsP1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>
