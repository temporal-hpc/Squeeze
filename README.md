# Squeeze

## Citation

```
@article{QUEZADA202210,
title = {Squeeze: Efficient compact fractals for tensor core GPUs},
journal = {Future Generation Computer Systems},
volume = {135},
pages = {10-19},
year = {2022},
issn = {0167-739X},
doi = {https://doi.org/10.1016/j.future.2022.04.023},
url = {https://www.sciencedirect.com/science/article/pii/S0167739X22001522},
author = {Felipe A. Quezada and Cristóbal A. Navarro and Nancy Hitschfeld and Benjamin Bustos},
keywords = {Compact fractals, GPU, Tensor cores, Thread mapping, Compact space, Efficient simulation},
abstract = {This work presents Squeeze, an efficient compact fractal processing scheme for tensor core GPUs. By combining discrete-space transformations between compact and expanded forms, one can do data-parallel computation on a fractal with neighborhood access without needing to expand the fractal in memory. The space transformations are formulated as two GPU tensor-core accelerated thread maps, λ(ω) and ν(ω), which act as compact-to-expanded and expanded-to-compact space functions, respectively. The cost of the maps is O(log2logs(n)) time, with n being the side of a n×n embedding for the fractal in its expanded form, and s the linear scaling factor. The proposed approach works for any fractal that belongs to the Non-overlapping-Bounding-Boxes (NBB) class of discrete fractals, and can be extended to three dimensions as well. Experimental results using a discrete Sierpinski Triangle as a case study shows up to ∼12× of speedup and a memory reduction factor of up to ∼315× with respect to a GPU-based expanded-space bounding box approach. These results show that the proposed compact approach will allow the scientific community to efficiently tackle problems that up to now could not fit into GPU memory.}
}
```
