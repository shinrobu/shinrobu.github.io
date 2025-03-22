---
layout: page
title: TinyJAMBU C++ Compiler Analysis
description: A project to measure the performance of the TinyJAMBU cryptography algorithm on GCC and Clang compilers.
img: assets/img/tinyjambu.png
importance: 5
category: Work
related_publications: false
---

In this project, I delved into cryptography algorithms, mainly TinyJAMBU, and did a study on its performance between the GCC and Clang compiler in C++. Done in VirtualBox, Ubuntu 20.04 LTS.

### The specs of the computer used for this study are as follows:
- 9th Gen Intel Core i7-9750H 
- NVIDIA GeForce RTX 2070 Max-Q 
- 16GB DDR4 System Memory  
- 8GB GDDR6 Video Memory 

Each test ran utilizing 6 cores of the Intel i7-9750H processor, at 2592.01 MHz per CPU.

I utilized Anjan Roy's C++ [TinyJAMBU implementation](https://github.com/itzmeanjan/tinyjambu), along with [Google Benchmark](https://github.com/google/benchmark) for collecting the times and other data needed for analysis.

<div class="row">
    <div class="col-sm-6 col-md-4 mx-auto">
        {% include figure.liquid loading="eager" path="assets/img/tinyjambu.png" title="TinyJAMBU benchmark image" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>
<div class="caption">
    Screenshot of one of the benchmarks run in VirtualBox, Ubuntu 20.04 LTS.
</div>

The key finding was that Clang exhibited slightly better performance compared to GCC across various key sizes (128-bit, 192-bit, and 256-bit). 

You can read my full paper on the subject [here.](https://shinrobu.github.io/assets/TinyJAMBUCompilerPaper.pdf)