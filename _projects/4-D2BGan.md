---
layout: page

title: 🔆 D2BGAN  
description: "PyTorch Implementation of paper titled D2BGAN: A Dark to Bright Image Conversion Model for Quality Enhancement and Analysis Tasks Without Paired Supervision"
# img: assets/img/sp_cup_2024/sp_cup_denoising.png
importance: 1
category: ongoing
related_publications: false

date: 2022-10-05T14:08:51+05:30
draft: false
tags : ['Computational Photography',"PyTorch", "Image Processing", "CycleGAN"]
github: https://github.com/SasikaA073/D2BGAN-m
---
# D2BGAN Model Implementation from scratch

<div class="row">
    <div class="">
        {% include figure.liquid loading="eager" path="https://user-images.githubusercontent.com/73076876/138980624-cbcf98bc-ac43-41a5-a399-5ca186858be0.png" title="D2BGAN Experimental results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

# Paper 


### D2BGAN: A Dark to Bright Image Conversion Model for Quality Enhancement and Analysis Tasks Without Paired Supervision

[D2BGAN Paper](https://ieeexplore.ieee.org/document/9784432)

# Summary of D2BGAN paper

D2BGAN is a CycleGAN model that is designed to convert low light images to bright images. It is an unpaired GAN-based image enhancement operation that uses cycle consistency, geometric consistency, and illumination consistency. The model has been shown to provide competitive results on standard benchmark datasets, and it has been observed to perform well on DICM, LIME, and MEF datasets when D2BGAN was applied. However, it does not perform well on backlit images.


<div class="row">
    <div class="">
        {% include figure.liquid loading="eager" path="assets/img/d2bgan/D2BGAN_architecture.png" title="D2BGAN Model Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    D2BGAN Model Architecture
</div>

<div class="row">
    <div class="">
        {% include figure.liquid loading="eager" path="assets/img/d2bgan/D2BGAN_data_flow.png" title="D2BGAN Dataflow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    D2BGAN Dataflow
</div>

<div class="row">
    <div class="">
        {% include figure.liquid loading="eager" path="assets/img/d2bgan/D2BGAN_loss_contribution.png" title="D2BGAN Loss contribution" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    D2BGAN Loss contribution
</div>

<div class="row">
    <div class="">
        {% include figure.liquid loading="eager" path="assets/img/d2bgan/experimental_results.gif" title="D2BGAN Experimental results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    D2BGAN Experimental results
</div>

## References

[D2BGAN](https://arts.units.it/retrieve/e2913fdf-656a-f688-e053-3705fe0a67e0/D2BGAN_A_Dark_to_Bright_Image_Conversion_Model_for_Quality_Enhancement_and_Analysis_Tasks_Without_Paired_Supervision.pdf)