<div align="center">

# Training-Free Target-Aware Refinement of 3D Gaussian Language Map

[Sibaek Lee](https://sibaek-lee.github.io/)<sup>1</sup>,
[Kyeongsu Kang](https://sites.google.com/view/thithin/)<sup>1</sup>,
[Seongbo Ha](https://riboha.github.io/)<sup>1</sup>,
[Yewon Jeon](https://yyonyy.github.io/)<sup>1</sup>,
[Joonyeol Choi](https://joonyeolchoiskku.github.io/)<sup>1</sup>,
[Daegeol Ko](https://daegeol.github.io/)<sup>1</sup>,
[Jaehyuk Hur](https://broadleaf-option-c34.notion.site/Jaehyuk-Hur-34660dadf71c4d3db77919610432e5c5)<sup>1</sup>,<br>
Taemin Choi<sup>2</sup>,
Minsu Kim<sup>2</sup>,
Hyungjoo Ahn<sup>2</sup>,
Wonsok Yoo<sup>2</sup>,
[Hyeonwoo Yu](https://bogus2000.github.io/)<sup>1</sup>

<sup>1</sup>Sungkyunkwan University &nbsp;&nbsp; <sup>2</sup>Samsung Electronics

<a href="https://lab-of-ai-and-robotics.github.io/target-aware-langmap/"><img src="https://img.shields.io/badge/Project-Page-blue" alt="Project Page"></a>

<img src="docs/static/images/fig_teaser.png" width="100%" alt="Teaser">

</div>

## Overview

We propose a training-free, target-aware refinement of an already-distilled 3D Gaussian language map. Guided by a text-promptable segmenter, the visual embedding inside each detected target region is blended with the target text embedding, with each target's injection strength obtained in closed form, so no hyperparameters need to be tuned. A centered read-out removes the query-agnostic bias that injection introduces, turning the refined map into a reliable source of language-goal locations for robot navigation.

## Code

Code will be released soon.
