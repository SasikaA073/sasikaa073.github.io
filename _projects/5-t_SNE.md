---
layout: page

title: "🔮 t-SNE visualizer for image data"  
description: "Converts any image dataset into 2D t-SNE visualization"
img: assets/img/t_sne/withluke_color_1_t_sne_2000x_color.png
importance: 2
category: "Data + Machine Learning"
related_publications: false

date: 2024-04-15T14:08:51+05:30
draft: false
tags : ["Image Processing", "Data Visualization"]
github: https://github.com/SasikaA073/t-sne-visualiser/
---

t-SNE is a powerful technique for visualizing high-dimensional data in a low-dimensional space. It is particularly useful for exploring the structure of complex datasets and identifying patterns or clusters.

This repository contains a Python package for visualizing high-dimensional data using t-distributed Stochastic Neighbor Embedding (t-SNE) algorithm.

## Features

- Apply t-SNE to your high-dimensional data (especially image datasets).
- Visualize the results in 2D.
- Customize the visualization with various parameters
- Save the visualizations as image files.

# Gallery

<div class="container">
  <div class="row">
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/withluke_color_1_t_sne_2000x_color.png" title="Robovox dataset mic setup" class="img-fluid rounded " %}
      <div class="caption"><a href="https://www.instagram.com/withluke"><i class="fab fa-instagram"></i> withluke</a></div>
    </div>
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/withluke_color_1_grid_56x55_2000px_t_sne.png" title="Robovox dataset mic setup" class="img-fluid rounded " %}
      <div class="caption"><a href="https://www.instagram.com/withluke"><i class="fab fa-instagram"></i> withluke</a></div>
    </div>
  </div>

  <div class="row">
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/sasika_color_1_t_sne_2000x.png" title="Robovox dataset mic setup" class="img-fluid rounded z-depth-1" %}
      <div class="caption"><a href="https://www.instagram.com/random_captures_of_my_life"><i class="fab fa-instagram"></i> random_captures_of_my_life</a></div>
    </div>
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/sasika__color_1_grid_10x19_t_sne.png" title="Robovox dataset mic setup" class="img-fluid rounded z-depth-1" %}
      <div class="caption"><a href="https://www.instagram.com/random_captures_of_my_life"><i class="fab fa-instagram"></i> random_captures_of_my_life</a></div>
    </div>
  </div>

  <div class="row">
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/checkmyplants_color_1_t_sne_2000x_color.png" title="Robovox dataset mic setup" class="img-fluid rounded z-depth-1" %}
      <div class="caption"><a href="https://www.instagram.com/checkmyplants"><i class="fab fa-instagram"></i> checkmyplants</a></div>
    </div>
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/checkmyplants_color_4_grid_38x40_3000px_t_sne.png" title="Robovox dataset mic setup" class="img-fluid rounded z-depth-1" %}
      <div class="caption"><a href="https://www.instagram.com/checkmyplants"><i class="fab fa-instagram"></i> checkmyplants</a></div>
    </div>
  </div>

  <div class="row">
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/bjm_captures_color_1_t_sne_3000px_bg_color.png" title="Robovox dataset mic setup" class="img-fluid rounded z-depth-1" %}
      <div class="caption"><a href="https://www.instagram.com/bjm_captures"><i class="fab fa-instagram"></i> bjm_captures</a></div>
    </div>
    <div class="col">
      {% include figure.liquid loading="eager" path="assets/img/t_sne/bjm_captures_color_1_grid_10x21_3000px_t_sne.png" title="Robovox dataset mic setup" class="img-fluid rounded z-depth-1" %}
      <div class="caption"><a href="https://www.instagram.com/bjm_captures"><i class="fab fa-instagram"></i> bjm_captures</a></div>
    </div>
  </div>
</div>


## References

<div class="container">
  <p>[1] L.J.P. van der Maaten and G.E. Hinton, "Visualizing High-Dimensional Data Using t-SNE," Journal of Machine Learning Research, vol. 9, pp. 2579-2605, 2008. [Online]. Available: <a href="https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf">https://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf</a></p>
  <p>[2] G.E. Hinton and R.R. Salakhutdinov, "Reducing the Dimensionality of Data with Neural Networks," Science, vol. 313, no. 5786, pp. 504-507, 2006. [Online]. Available: <a href="https://www.cs.toronto.edu/~hinton/absps/tsne.pdf">https://www.cs.toronto.edu/~hinton/absps/tsne.pdf</a></p>
</div>
