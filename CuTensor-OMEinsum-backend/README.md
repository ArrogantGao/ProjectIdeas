# CuTENSOR OMEinsum Backend
## Difficulty level
Advanced

## Advisor

Xuanzhao Gao (xz.gao@connect.ust.hk)
Jinguo Liu (cacate0129@gmail.com)

## Project Description

Tensor network contraction is a powerful tool for solving many problems in physics and machine learning.
`OMEinsum.jl` is one of the most popular packages for tensor network contraction in Julia.
However, the performance of `OMEinsum.jl` on gpu is not satisfactory, due to the limited performance of `CUDA.jl` as its currently gpu backend.

`CuTENSOR` is a new library for tensor network contraction on GPU, developed by NVIDIA, which is designed for high performance and easy to use. In this project, we will extend `OMEinsum.jl` to support CuTENSOR as a new backend.

### References
* Libraries: [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl), [OMEinsum.jl](https://github.com/under-Peter/OMEinsum.jl), and [CuTENSOR](https://docs.nvidia.com/cuda/cutensor/latest/index.html).

## Project Output Standard
An extension of `OMEinsum.jl` that adds a new backend for CuTENSOR.

## Technical requirements
* CUDA programming (professional),
* Julia language (basic).
