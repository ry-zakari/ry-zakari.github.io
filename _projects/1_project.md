---
layout: page
title: project 1
description: An Enhanced Wildfire Spread Prediction Using Multimodal Satellite Imagery and Deep Learning Models
img: assets/img/project1.jpg
importance: 1
category: work
related_publications: true
---

Wildfire spread prediction is critical for mitigating risks and improving management strategies. This study uses next-day weather forecasts and terrain features to enhance the Next Day Wildfire Spread (NDWS) dataset, initially designed for wildfire spread modeling. This enriched dataset spans from July 2015 to October 2024, incorporating forecast variables such as temperature, wind speed, wind direction, precipitation, slope, and aspect to complement existing elevation data. Leveraging this enriched dataset, we propose the Atrous Pyramid Attention U-Net (APAU-Net). This modified U-Net-based architecture combines Atrous Spatial Pyramid Convolution (ASPC) blocks and convolutional attention mechanisms to improve feature extraction and segmentation accuracy. The results demonstrate that APAU-Net, trained on the enhanced dataset, achieved an F1 Score of 0.720 and a mIoU of 0.635 on 64 × 64 resolution, and an F1 Score of 0.689 and mean Intersection over Union (mloU) of 0.605 on 32 × 32 resolution. These results demonstrate notable improvements compared to prior studies and existing methods. Comprehensive ablation studies were then conducted using APAU-Net to evaluate the contributions of different feature groups, revealing the importance of integrating weather, topography, and previous fire activity for accurate predictions. Additionally, Integrated Gradients were utilized to provide interpretability for the model's decisions, offering an understanding of the significance of each feature in the prediction process. The computational efficiency of APAU-Net was also evaluated, showing a significant reduction in training time compared to previous models, making it a viable solution for real-time applications. The APAU-Net model provides an effective approach for predicting the next day's wildfire spread, providing a valuable tool for improving wildfire risk management and response strategies in the face of increasingly complex wildfire behavior.

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/project1.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
