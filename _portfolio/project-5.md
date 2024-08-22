---
title: "Transformer Attention Visualization"
excerpt: "Visualize the attention map in transformer architecture<br/><img src='/images/vit.png' width='300'>"
collection: portfolio
---
*December, 2021*

In this project, I analyzed the attention map in transformer architecture in two differnet tasks, image classification and image captioning.

For image classification, I visualized the attention map between the [class] token (as query vector) and all patches (as key vectors) from the last multi-head attention layer of vision transformer by comparing the weights of the attention layer. For image captioning, I visulaized cross-attention between images and generated caption from transformer decoder.

The results show that attention mechanism indeed learn the relation between language/text and visual information.

| Label    | Attention Map on image classification |
| :--------: | :-------: |
| Cat  | ![test](/images/vit_cat.png){: width="640px"} | 
| Dog  | ![test](/images/vit_dog.png){: width="640px"} | 
| Dog  | ![test](/images/vit_wolf.png){: width="640px"}|



| Attention Map on image captioning |
| :--------: |
| ![test](/images/vit_bike.png){: width="720px"} | 
| ![test](/images/vit_sheep.png){: width="720px"} | 
| ![test](/images/vit_umbrella.png){: width="720px"}|