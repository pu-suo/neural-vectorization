# Math 300 Final Project 
This repository contains the files and notebooks for the Fall 2025 Math 300 final project. 

## Raster to Vector image converter
Vector SVG images are often better suited for digital use because of their scalable nature and ease of editing. However, most digital imagery currently is in raster pixel form. The conversion from raster to vector form is a challenging problem that traditional computer vision algorithms, such as Canny Edge Detection or Potrace, often struggle to produce satisfactory results due to noise within images, resulting in hollow high-vertex outputs that are difficult to edit. This project aims to solve this problem by utilizing a deep learning architecture that can benefit from centerline topology, as well as loss functions, rather than predefined rules for image conversion.

## Data Sources
Icon and Anime image data
- DeepSVG: https://github.com/alexandre01/deepsvg?tab=readme-ov-file
- Danbooru: https://huggingface.co/datasets/nyanko7/danbooru2023

## References
Carlier, A., Danelljan, M., Alahi, A., & Timofte, R. (2020). Deepsvg: A hierarchical generative network for vector graphics animation. Advances in Neural Information Processing Systems, 33, 16351-16361.

Tzu-Mao Li, Michal Lukáč, Michaël Gharbi, and Jonathan Ragan-Kelley. 2020. Differentiable vector graphics rasterization for editing and learning. ACM Trans. Graph. 39, 6, Article 193 (December 2020), 15 pages. https://doi.org/10.1145/3414685.3417871
