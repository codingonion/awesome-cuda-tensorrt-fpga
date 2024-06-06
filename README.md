# Awesome-CUDA-TensorRT-FPGA
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

🔥🔥🔥 This repository lists some awesome public NVIDIA CUDA, cuBLAS, cuDNN, TensorRT, AMD ROCm and FPGA projects.

## Contents
- [Awesome-CUDA-TensorRT-FPGA](#awesome-cuda-tensorrt-fpga)
  - [Contents](#contents)
  - [Awesome List](#awesome-list)
    - [Awesome CUDA and TensorRT](#awesome-cuda-and-tensorrt)
    - [Awesome HDL and FPGA](#awesome-hdl-and-fpga)
  - [Learning Resources](#learning-resources)
    - [CUDA Learning](#cuda-learning)
    - [TensorRT Learning](#tensorrt-learning)
    - [ROCm Learning](#rocm-learning)
    - [FPGA Learning](#fpga-learning)
  - [Frameworks](#frameworks)
    - [CUDA and TensorRT Framework](#cuda-and-tensorrt-framework)
        - [GPU Interface](#gpu-interface)
            - [CPP Version](#cpp-version)
            - [Python version](#python-version)
            - [Rust Version](#rust-version)
            - [Julia Version](#julia-version)
        - [Scientific Computing Framework](#scientific-computing-framework)
        - [Machine Learning Framework](#machine-learning-framework)
        - [AI Inference Framework](#ai-inference-framework)
            - [C Implementation](#c-implementation)
            - [CPP Implementation](#cpp-implementation)
            - [Mojo Implementation](#mojo-implementation)
            - [Rust Implementation](#rust-implementation)
            - [zig Implementation](#zig-implementation)
            - [Go Implementation](#go-implementation)
            - [LLM Deployment Engine](#llm-deployment-engine)
            - [LLM Inference Benchmark](#llm-inference-benchmark)
        - [Multi-GPU Framework](#multi-gpu-framework)
        - [Robotics Framework](#robotics-framework)
        - [ZKP and Web3 Framework](#zkp-and-web3-framework)
    - [HDL and FPGA Framework](#hdl-and-fpga-framework)
        - [C HDL](#c-hdl)
        - [Scala HDL](#scala-hdl)
        - [Rust HDL](#rust-hdl)
        - [Python HDL](#python-hdl)
  - [Applications](#applications)
    - [CUDA and TensorRT Applications](#cuda-and-tensorrt-applications)
        - [Object Detection](#object-detection)
    - [FPGA Applications](#fpga-applications)
        - [Processor Chip](#processor-chip)
            - [CPU Chip](#cpu-chip)
                - [RISC-V Chip](#risc-v-chip)
            - [GPU Chip](#gpu-chip)
        - [IP Module](#ip-module)
            - [IP Generator](#ip-generator)
            - [PCIe Module](#pcie-module)
            - [DDR Module](#ddr-module)
            - [Ethernet Module](#ethernet-module)
            - [WIFI Module](#wifi-module)
            - [UART Module](#uart-module)
            - [USB Module](#usb-module)
            - [CAN-bus Module](#can-bus-module)
            - [AXI Module](#axi-module)
            - [HDMI Module](#hdmi-module)
            - [SD-card Module](#sd-card-module)
            - [NFC Module](#nfc-module)
            - [SATA Module](#sata-module)
            - [DAC Module](#dac-module)
        - [Camera Firmware](#camera-firmware)
        - [Spiking Neural Network](#spiking-neural-network)
        - [Convolutional Neural Network](#convolutional-neural-network)
        - [Object Detection](#object-detection)
        - [Visual SLAM](#visual-slam)
        - [Image Compression](#image-compression)
        - [Motor Control](#motor-control)
        - [Fixed-point](#fixed-point)
  - [Blogs](#blogs)
    - [HDL and FPGA Blogs](#hdl-and-fpga-blogs)
    - [CUDA and TensorRT Blogs](#cuda-and-tensorrt-blogs)
  - [Videos](#videos)
  - [Jobs and Interview](#jobs-and-interview)



## Awesome List

  - ### Awesome CUDA and TensorRT


    - [codingonion/awesome-cuda-tensorrt-fpga](https://github.com/codingonion/awesome-cuda-tensorrt-fpga) <img src="https://img.shields.io/github/stars/codingonion/awesome-cuda-tensorrt-fpga?style=social"/> : A collection of some awesome public NVIDIA CUDA, TensorRT, AMD ROCm and FPGA projects.

    - [Erkaman/Awesome-CUDA](https://github.com/Erkaman/Awesome-CUDA) <img src="https://img.shields.io/github/stars/Erkaman/Awesome-CUDA?style=social"/> : This is a list of useful libraries and resources for CUDA development.

    - [jslee02/awesome-gpgpu](https://github.com/jslee02/awesome-gpgpu) <img src="https://img.shields.io/github/stars/jslee02/awesome-gpgpu?style=social"/> : 😎 A curated list of awesome GPGPU (CUDA/OpenCL/Vulkan) resources.

    - [mikeroyal/CUDA-Guide](https://github.com/mikeroyal/CUDA-Guide) <img src="https://img.shields.io/github/stars/mikeroyal/CUDA-Guide?style=social"/> : A guide covering CUDA including the applications and tools that will make you a better and more efficient CUDA developer.

    - [tensorush/gpu-toolkit](https://github.com/tensorush/gpu-toolkit) <img src="https://img.shields.io/github/stars/tensorush/gpu-toolkit?style=social"/> : 🦚 🧰 Collection of basic GPU algorithms implemented in CUDA C++.


  - ### Awesome HDL and FPGA

    - [drom/awesome-hdl](https://github.com/drom/awesome-hdl) <img src="https://img.shields.io/github/stars/drom/awesome-hdl?style=social"/> : A curated list of amazingly awesome hardware description language projects.

    - [ben-marshall/awesome-open-hardware-verification](https://github.com/ben-marshall/awesome-open-hardware-verification) <img src="https://img.shields.io/github/stars/ben-marshall/awesome-open-hardware-verification?style=social"/> : A curated List of Free and Open Source hardware verification tools and frameworks.

    - [Vitorian/awesome-fpga](https://github.com/Vitorian/awesome-fpga) <img src="https://img.shields.io/github/stars/Vitorian/awesome-fpga?style=social"/> : A collection of resources on FPGA devices and development in general.

    - [kelu124/awesome-latticeFPGAs](https://github.com/kelu124/awesome-latticeFPGAs) <img src="https://img.shields.io/github/stars/kelu124/awesome-latticeFPGAs?style=social"/> : 📖 List of FPGA Lattice boards using open tools.

    - [FPGA-Systems/fpga-awesome-list](https://github.com/FPGA-Systems/fpga-awesome-list) <img src="https://img.shields.io/github/stars/FPGA-Systems/fpga-awesome-list?style=social"/> : fpga-awesome-list. Полезные ресурсы по тематике FPGA / ПЛИС.

    - [hdl/awesome](https://github.com/hdl/awesome) <img src="https://img.shields.io/github/stars/hdl/awesome?style=social"/> : A curated list of awesome resources for HDL design and verification.

    - [vhdl/awesome-vhdl](https://github.com/vhdl/awesome-vhdl) <img src="https://img.shields.io/github/stars/vhdl/awesome-vhdl?style=social"/> : A curated list of awesome VHDL IP cores, frameworks, libraries, software and resources.

    - [clin99/awesome-eda](https://github.com/clin99/awesome-eda) <img src="https://img.shields.io/github/stars/clin99/awesome-eda?style=social"/> : A curated list of EDA open source projects.

    - [iDoka/awesome-fpga-boards](https://github.com/iDoka/awesome-fpga-boards) <img src="https://img.shields.io/github/stars/iDoka/awesome-fpga-boards?style=social"/> : List of Repurposed FPGA boards which getting Second life in DYI or Hobby projects.

    - [TM90/awesome-hwd-tools](https://github.com/TM90/awesome-hwd-tools) <img src="https://img.shields.io/github/stars/TM90/awesome-hwd-tools?style=social"/> : A curated list of awesome open source hardware design tools.

    - [qninth/awesome-digital-ic](https://github.com/qninth/awesome-digital-ic) <img src="https://img.shields.io/github/stars/qninth/awesome-digital-ic?style=social"/> : A collection of great digital IC project/tutorial/website etc..

    - [emanueledelsozzo/awesome-fpga-programming](https://github.com/emanueledelsozzo/awesome-fpga-programming) <img src="https://img.shields.io/github/stars/emanueledelsozzo/awesome-fpga-programming?style=social"/> : A curated list of awesome languages and tools to program FPGAs.

    - [fukatani/awesome-hdl](https://github.com/fukatani/awesome-hdl) <img src="https://img.shields.io/github/stars/fukatani/awesome-hdl?style=social"/> : A curated list of awesome HDL, libraries, typical implementation and references.

    - [mikeroyal/VHDL-Guide](https://github.com/mikeroyal/VHDL-Guide) <img src="https://img.shields.io/github/stars/mikeroyal/VHDL-Guide?style=social"/> : A guide covering VHDL including the applications, libraries and tools that will make you a better and more efficient with VHDL development.

    - [mikeroyal/Verilog-SystemVerilog-Guide](https://github.com/mikeroyal/Verilog-SystemVerilog-Guide) <img src="https://img.shields.io/github/stars/mikeroyal/Verilog-SystemVerilog-Guide?style=social"/> : Verilog/SystemVerilog Guide. A guide covering Verilog & SystemVerilog including the applications, libraries and tools that will make you a better and more efficient developer by having a better understanding of how hardware works on the lowest level.

    - [analogdevicesinc/hdl](https://github.com/analogdevicesinc/hdl) <img src="https://img.shields.io/github/stars/analogdevicesinc/hdl?style=social"/> : HDL libraries and projects. [wiki.analog.com/resources/fpga/docs/hdl](https://wiki.analog.com/resources/fpga/docs/hdl)

    - [analogdevicesinc/hdl](https://github.com/FPGAwars/apio) <img src="https://img.shields.io/github/stars/FPGAwars/apio?style=social"/> : 🌱 Open source ecosystem for open FPGA boards. [github.com/FPGAwars/apio/wiki](https://github.com/FPGAwars/apio/wiki)




## Learning Resources

  - ### CUDA Learning

    - [NVIDIA CUDA Docs](https://docs.nvidia.com/cuda/) : CUDA Toolkit Documentation.

    - [NVIDIA/cuda-samples](https://github.com/NVIDIA/cuda-samples) <img src="https://img.shields.io/github/stars/NVIDIA/cuda-samples?style=social"/> : Samples for CUDA Developers which demonstrates features in CUDA Toolkit.

    - [NVIDIA/CUDALibrarySamples](https://github.com/NVIDIA/CUDALibrarySamples) <img src="https://img.shields.io/github/stars/NVIDIA/CUDALibrarySamples?style=social"/> : CUDA Library Samples.

    - [HeKun-NVIDIA/CUDA-Programming-Guide-in-Chinese](https://github.com/HeKun-NVIDIA/CUDA-Programming-Guide-in-Chinese) <img src="https://img.shields.io/github/stars/HeKun-NVIDIA/CUDA-Programming-Guide-in-Chinese?style=social"/> : This is a Chinese translation of the CUDA programming guide. 本项目为 CUDA C Programming Guide 的中文翻译版。

    - [codingonion/cuda-beginner-course-cpp-version](https://github.com/codingonion/cuda-beginner-course-cpp-version) <img src="https://img.shields.io/github/stars/codingonion/cuda-beginner-course-cpp-version?style=social"/> : bilibili视频【CUDA 12.1 并行编程入门(C++语言版)】配套代码。

    - [codingonion/cuda-beginner-course-python-version](https://github.com/codingonion/cuda-beginner-course-python-version) <img src="https://img.shields.io/github/stars/codingonion/cuda-beginner-course-python-version?style=social"/> : bilibili视频【CUDA 12.1 并行编程入门(Python语言版)】配套代码。

    - [codingonion/cuda-beginner-course-rust-version](https://github.com/codingonion/cuda-beginner-course-rust-version) <img src="https://img.shields.io/github/stars/codingonion/cuda-beginner-course-rust-version?style=social"/> : bilibili视频【CUDA 12.1 并行编程入门(Rust语言版)】配套代码。

    - [ulrichstern/cuda-convnet](https://github.com/ulrichstern/cuda-convnet) <img src="https://img.shields.io/github/stars/ulrichstern/cuda-convnet?style=social"/> : Alex Krizhevsky's original code from Google Code. "微信公众号「人工智能大讲堂」《[找到了AlexNet当年的源代码，没用框架，从零手撸CUDA/C++](https://mp.weixin.qq.com/s/plxXG8y5QlxSionyjyPXqw)》"。

    - [brucefan1983/CUDA-Programming](https://github.com/brucefan1983/CUDA-Programming) <img src="https://img.shields.io/github/stars/brucefan1983/CUDA-Programming?style=social"/> : Sample codes for my CUDA programming book.

    - [YouQixiaowu/CUDA-Programming-with-Python](https://github.com/YouQixiaowu/CUDA-Programming-with-Python) <img src="https://img.shields.io/github/stars/YouQixiaowu/CUDA-Programming-with-Python?style=social"/> :  关于书籍CUDA Programming使用了pycuda模块的Python版本的示例代码。

    - [QINZHAOYU/CudaSteps](https://github.com/QINZHAOYU/CudaSteps) <img src="https://img.shields.io/github/stars/QINZHAOYU/CudaSteps?style=social"/> : 基于《cuda编程-基础与实践》（樊哲勇 著）的cuda学习之路。

    - [sangyc10/CUDA-code](https://github.com/sangyc10/CUDA-code) <img src="https://img.shields.io/github/stars/sangyc10/CUDA-code?style=social"/> : B站视频教程【CUDA编程基础入门系列（持续更新）】配套代码。

    - [RussWong/CUDATutorial](https://github.com/RussWong/CUDATutorial) <img src="https://img.shields.io/github/stars/RussWong/CUDATutorial?style=social"/> : A CUDA tutorial to make people learn CUDA program from 0.

    - [DefTruth/cuda-learn-note](https://github.com/DefTruth/cuda-learn-note) <img src="https://img.shields.io/github/stars/DefTruth/cuda-learn-note?style=social"/> : 🎉CUDA 笔记 / 高频面试题汇总 / C++笔记，个人笔记，更新随缘: sgemm、sgemv、warp reduce、block reduce、dot product、elementwise、softmax、layernorm、rmsnorm、hist etc.

    - [Liu-xiandong/How_to_optimize_in_GPU](https://github.com/Liu-xiandong/How_to_optimize_in_GPU) <img src="https://img.shields.io/github/stars/Liu-xiandong/How_to_optimize_in_GPU?style=social"/> : This is a series of GPU optimization topics. Here we will introduce how to optimize the CUDA kernel in detail. I will introduce several basic kernel optimizations, including: elementwise, reduce, sgemv, sgemm, etc. The performance of these kernels is basically at or near the theoretical limit.

    - [BBuf/how-to-optim-algorithm-in-cuda](https://github.com/BBuf/how-to-optim-algorithm-in-cuda) <img src="https://img.shields.io/github/stars/BBuf/how-to-optim-algorithm-in-cuda?style=social"/> : This is a series of GPU optimization topics. Here we will introduce how to optimize the CUDA kernel in detail. I will introduce several basic kernel optimizations, including: elementwise, reduce, sgemv, sgemm, etc. The performance of these kernels is basically at or near the theoretical limit.

    - [enp1s0/ozIMMU](https://github.com/enp1s0/ozIMMU) <img src="https://img.shields.io/github/stars/enp1s0/ozIMMU?style=social"/> : FP64 equivalent GEMM via Int8 Tensor Cores using the Ozaki scheme. [arxiv.org/abs/2306.11975](https://arxiv.org/abs/2306.11975)

    - [Bruce-Lee-LY/matrix_multiply](https://github.com/Bruce-Lee-LY/matrix_multiply) <img src="https://img.shields.io/github/stars/Bruce-Lee-LY/matrix_multiply?style=social"/> : Several common methods of matrix multiplication are implemented on CPU and Nvidia GPU using C++11 and CUDA.

    - [Bruce-Lee-LY/cuda_hgemm](https://github.com/Bruce-Lee-LY/cuda_hgemm) <img src="https://img.shields.io/github/stars/Bruce-Lee-LY/cuda_hgemm?style=social"/> : Several optimization methods of half-precision general matrix multiplication (HGEMM) using tensor core with WMMA API and MMA PTX instruction.

    - [Bruce-Lee-LY/cuda_hgemv](https://github.com/Bruce-Lee-LY/cuda_hgemv) <img src="https://img.shields.io/github/stars/Bruce-Lee-LY/cuda_hgemv?style=social"/> : Several optimization methods of half-precision general matrix vector multiplication (HGEMV) using CUDA core.

    - [Cjkkkk/CUDA_gemm](https://github.com/Cjkkkk/CUDA_gemm) <img src="https://img.shields.io/github/stars/Cjkkkk/CUDA_gemm?style=social"/> : A simple high performance CUDA GEMM implementation.

    - [AyakaGEMM/Hands-on-GEMM](https://github.com/AyakaGEMM/Hands-on-GEMM) <img src="https://img.shields.io/github/stars/AyakaGEMM/Hands-on-GEMM?style=social"/> : A GEMM tutorial.

    - [AyakaGEMM/Hands-on-MLIR](https://github.com/AyakaGEMM/Hands-on-MLIR) <img src="https://img.shields.io/github/stars/AyakaGEMM/Hands-on-MLIR?style=social"/> : Hands-on-MLIR.

    - [zpzim/MSplitGEMM](https://github.com/zpzim/MSplitGEMM) <img src="https://img.shields.io/github/stars/zpzim/MSplitGEMM?style=social"/> : Large matrix multiplication in CUDA.

    - [jundaf2/CUDA-INT8-GEMM](https://github.com/jundaf2/CUDA-INT8-GEMM) <img src="https://img.shields.io/github/stars/jundaf2/CUDA-INT8-GEMM?style=social"/> : CUDA 8-bit Tensor Core Matrix Multiplication based on m16n16k16 WMMA API.

    - [chanzhennan/cuda_gemm_benchmark](https://github.com/chanzhennan/cuda_gemm_benchmark) <img src="https://img.shields.io/github/stars/chanzhennan/cuda_gemm_benchmark?style=social"/> : Base on gtest/benchmark, refer to [https://github.com/Liu-xiandong/How_to_optimize_in_GPU](https://github.com/Liu-xiandong/How_to_optimize_in_GPU).

    - [YuxueYang1204/CudaDemo](https://github.com/YuxueYang1204/CudaDemo) <img src="https://img.shields.io/github/stars/YuxueYang1204/CudaDemo?style=social"/> : Implement custom operators in PyTorch with cuda/c++.

    - [CoffeeBeforeArch/cuda_programming](https://github.com/CoffeeBeforeArch/cuda_programming) <img src="https://img.shields.io/github/stars/CoffeeBeforeArch/cuda_programming?style=social"/> : Code from the "CUDA Crash Course" YouTube series by CoffeeBeforeArch.

    - [rbaygildin/learn-gpgpu](https://github.com/rbaygildin/learn-gpgpu) <img src="https://img.shields.io/github/stars/rbaygildin/learn-gpgpu?style=social"/> : Algorithms implemented in CUDA + resources about GPGPU.

    - [godweiyang/NN-CUDA-Example](https://github.com/godweiyang/NN-CUDA-Example) <img src="https://img.shields.io/github/stars/godweiyang/NN-CUDA-Example?style=social"/> : Several simple examples for popular neural network toolkits calling custom CUDA operators.

    - [yhwang-hub/Matrix_Multiplication_Performance_Optimization](https://github.com/yhwang-hub/Matrix_Multiplication_Performance_Optimization) <img src="https://img.shields.io/github/stars/yhwang-hub/Matrix_Multiplication_Performance_Optimization?style=social"/> : Matrix Multiplication Performance Optimization.

    - [yao-jiashu/KernelCodeGen](https://github.com/yao-jiashu/KernelCodeGen) <img src="https://img.shields.io/github/stars/yao-jiashu/KernelCodeGen?style=social"/> : GEMM/Conv2d CUDA/HIP kernel code generation using MLIR.

    - [caiwanxianhust/ClusteringByCUDA](https://github.com/caiwanxianhust/ClusteringByCUDA) <img src="https://img.shields.io/github/stars/caiwanxianhust/ClusteringByCUDA?style=social"/> : 使用 CUDA C++ 实现的一系列聚类算法。

    - [PacktPublishing/Learn-CUDA-Programming](https://github.com/PacktPublishing/Learn-CUDA-Programming) <img src="https://img.shields.io/github/stars/PacktPublishing/Learn-CUDA-Programming?style=social"/> : Learn CUDA Programming, published by Packt.

    - [PacktPublishing/Hands-On-GPU-Accelerated-Computer-Vision-with-OpenCV-and-CUDA](https://github.com/PacktPublishing/Hands-On-GPU-Accelerated-Computer-Vision-with-OpenCV-and-CUDA) <img src="https://img.shields.io/github/stars/PacktPublishing/Hands-On-GPU-Accelerated-Computer-Vision-with-OpenCV-and-CUDA?style=social"/> : Hands-On GPU Accelerated Computer Vision with OpenCV and CUDA, published by Packt.

    - [PacktPublishing/Hands-On-GPU-Programming-with-Python-and-CUDA](https://github.com/PacktPublishing/Hands-On-GPU-Programming-with-Python-and-CUDA) <img src="https://img.shields.io/github/stars/PacktPublishing/Hands-On-GPU-Programming-with-Python-and-CUDA?style=social"/> : Hands-On GPU Programming with Python and CUDA, published by Packt.










  - ### TensorRT Learning

    - [NVIDIA TensorRT Docs](https://docs.nvidia.com/deeplearning/tensorrt/) : NVIDIA Deep Learning TensorRT Documentation.

    - [TensorRT](https://github.com/NVIDIA/TensorRT) <img src="https://img.shields.io/github/stars/NVIDIA/TensorRT?style=social"/> : NVIDIA® TensorRT™ is an SDK for high-performance deep learning inference on NVIDIA GPUs. This repository contains the open source components of TensorRT. [developer.nvidia.com/tensorrt](https://developer.nvidia.com/tensorrt)

    - [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) <img src="https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM?style=social"/> : TensorRT-LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs) and build TensorRT engines that contain state-of-the-art optimizations to perform inference efficiently on NVIDIA GPUs. TensorRT-LLM also contains components to create Python and C++ runtimes that execute those TensorRT engines. [nvidia.github.io/TensorRT-LLM](https://nvidia.github.io/TensorRT-LLM)

    - [HeKun-NVIDIA/TensorRT-Developer_Guide_in_Chinese](https://github.com/HeKun-NVIDIA/TensorRT-Developer_Guide_in_Chinese) <img src="https://img.shields.io/github/stars/HeKun-NVIDIA/TensorRT-Developer_Guide_in_Chinese?style=social"/> : 本项目是NVIDIA TensorRT的中文版开发手册， 有个人翻译并添加自己的理解。

    - [kalfazed/tensorrt_starter](https://github.com/kalfazed/tensorrt_starter) <img src="https://img.shields.io/github/stars/kalfazed/tensorrt_starter?style=social"/> : This repository give a guidline to learn CUDA and TensorRT from the beginning.



  - ### ROCm Learning

    - [AMD ROCm Docs](https://rocm.docs.amd.com) : AMD ROCm™ documentation.


  - ### FPGA Learning

    - [sipeed/TangPrimer-20K-example](https://github.com/sipeed/TangPrimer-20K-example) <img src="https://img.shields.io/github/stars/sipeed/TangPrimer-20K-example?style=social"/> : AIoT opensource hardware platform. TangPrimer-20K-example project.

    - [BrunoLevy/learn-fpga](https://github.com/BrunoLevy/learn-fpga) <img src="https://img.shields.io/github/stars/BrunoLevy/learn-fpga?style=social"/> : About Learning FPGA, yosys, nextpnr, and RISC-V

    - [WangXuan95/ZedBoard-Tutorial](https://github.com/WangXuan95/ZedBoard-Tutorial) <img src="https://img.shields.io/github/stars/WangXuan95/ZedBoard-Tutorial?style=social"/> : Vivado+PetaLinux 系统搭建教程 —— 基于 Zedboard.

    - [WangXuan95/UniPlug-FPGA](https://github.com/WangXuan95/UniPlug-FPGA) <img src="https://img.shields.io/github/stars/WangXuan95/UniPlug-FPGA?style=social"/> : 体积小、低成本、易用、扩展性强的 FPGA 核心板。



## Frameworks

  - ### CUDA and TensorRT Framework

    - #### GPU Interface
      ##### GPU接口

        - ##### CPP Version

            - [CCCL](https://github.com/NVIDIA/cccl) <img src="https://img.shields.io/github/stars/NVIDIA/cccl?style=social"/> : CUDA C++ Core Libraries. The concept for the CUDA C++ Core Libraries (CCCL) grew organically out of the Thrust, CUB, and libcudacxx projects that were developed independently over the years with a similar goal: to provide high-quality, high-performance, and easy-to-use C++ abstractions for CUDA developers.

            - [HIP](https://github.com/ROCm/HIP) <img src="https://img.shields.io/github/stars/ROCm/HIP?style=social"/> : HIP: C++ Heterogeneous-Compute Interface for Portability. HIP is a C++ Runtime API and Kernel Language that allows developers to create portable applications for AMD and NVIDIA GPUs from single source code. [rocmdocs.amd.com/projects/HIP/](https://rocmdocs.amd.com/projects/HIP/)


        - ##### Python Version

            - [CuPy](https://github.com/cupy/cupy) <img src="https://img.shields.io/github/stars/cupy/cupy?style=social"/> : CuPy : NumPy & SciPy for GPU. [cupy.dev](https://cupy.dev/)

            - [PyCUDA](https://github.com/inducer/pycuda) <img src="https://img.shields.io/github/stars/inducer/pycuda?style=social"/> : PyCUDA: Pythonic Access to CUDA, with Arrays and Algorithms. [mathema.tician.de/software/pycuda](http://mathema.tician.de/software/pycuda)



        - ##### Rust Version

            - [jessfraz/advent-of-cuda](https://github.com/jessfraz/advent-of-cuda) <img src="https://img.shields.io/github/stars/jessfraz/advent-of-cuda?style=social"/> : Doing advent of code with CUDA and rust.

            - [Bend](https://github.com/HigherOrderCO/Bend) <img src="https://img.shields.io/github/stars/HigherOrderCO/Bend?style=social"/> : A massively parallel, high-level programming language.[higherorderco.com](https://higherorderco.com/)

            - [HVM](https://github.com/HigherOrderCO/HVM) <img src="https://img.shields.io/github/stars/HigherOrderCO/HVM?style=social"/> : A massively parallel, optimal functional runtime in Rust.[higherorderco.com](https://higherorderco.com/)

            - [ZLUDA](https://github.com/vosen/ZLUDA) <img src="https://img.shields.io/github/stars/vosen/ZLUDA?style=social"/> : CUDA on AMD GPUs.

            - [Rust-CUDA](https://github.com/Rust-GPU/Rust-CUDA) <img src="https://img.shields.io/github/stars/Rust-GPU/Rust-CUDA?style=social"/> : Ecosystem of libraries and tools for writing and executing fast GPU code fully in Rust.

            - [cudarc](https://github.com/coreylowman/cudarc) <img src="https://img.shields.io/github/stars/coreylowman/cudarc?style=social"/> : cudarc: minimal and safe api over the cuda toolkit.

            - [bindgen_cuda](https://github.com/Narsil/bindgen_cuda) <img src="https://img.shields.io/github/stars/Narsil/bindgen_cuda?style=social"/> : Similar crate than [bindgen](https://github.com/rust-lang/rust-bindgen) in philosophy. It will help create automatic bindgen to cuda kernels source files and make them easier to use directly from Rust.

            - [cuda-driver](https://github.com/YdrMaster/cuda-driver) <img src="https://img.shields.io/github/stars/YdrMaster/cuda-driver?style=social"/> : 基于 CUDA Driver API 的 cuda 运行时环境。

            - [async-cuda](https://github.com/oddity-ai/async-cuda) <img src="https://img.shields.io/github/stars/oddity-ai/async-cuda?style=social"/> : Asynchronous CUDA for Rust.

            - [async-tensorrt](https://github.com/oddity-ai/async-tensorrt) <img src="https://img.shields.io/github/stars/oddity-ai/async-tensorrt?style=social"/> : Asynchronous TensorRT for Rust.

            - [krnl](https://github.com/charles-r-earp/krnl) <img src="https://img.shields.io/github/stars/charles-r-earp/krnl?style=social"/> : Safe, portable, high performance compute (GPGPU) kernels.

            - [custos](https://github.com/elftausend/custos) <img src="https://img.shields.io/github/stars/elftausend/custos?style=social"/> : A minimal OpenCL, CUDA, WGPU and host CPU array manipulation engine / framework.

            - [spinorml/nvlib](https://github.com/spinorml/nvlib) <img src="https://img.shields.io/github/stars/spinorml/nvlib?style=social"/> : Rust interoperability with NVIDIA CUDA NVRTC and Driver.

            - [DoeringChristian/cuda-rs](https://github.com/DoeringChristian/cuda-rs) <img src="https://img.shields.io/github/stars/DoeringChristian/cuda-rs?style=social"/> : Cuda Bindings for rust generated with bindgen-cli (similar to cust_raw).

            - [romankoblov/rust-nvrtc](https://github.com/romankoblov/rust-nvrtc) <img src="https://img.shields.io/github/stars/romankoblov/rust-nvrtc?style=social"/> : NVRTC bindings for RUST.

            - [solkitten/astro-cuda](https://github.com/solkitten/astro-cuda) <img src="https://img.shields.io/github/stars/solkitten/astro-cuda?style=social"/> : CUDA Driver API bindings for Rust.

            - [bokutotu/curs](https://github.com/bokutotu/curs) <img src="https://img.shields.io/github/stars/bokutotu/curs?style=social"/> : cuda&cublas&cudnn wrapper for Rust.

            - [rust-cuda/cuda-sys](https://github.com/rust-cuda/cuda-sys) <img src="https://img.shields.io/github/stars/rust-cuda/cuda-sys?style=social"/> : Rust binding to CUDA APIs.

            - [bheisler/RustaCUDA](https://github.com/bheisler/RustaCUDA) <img src="https://img.shields.io/github/stars/bheisler/RustaCUDA?style=social"/> : Rusty wrapper for the CUDA Driver API.

            - [tmrob2/cuda2rust_sandpit](https://github.com/tmrob2/cuda2rust_sandpit) <img src="https://img.shields.io/github/stars/tmrob2/cuda2rust_sandpit?style=social"/> : Minimal examples to get CUDA linear algebra programs working with Rust using CC & FFI.

            - [PhDP/rust-cuda-template](https://github.com/PhDP/rust-cuda-template) <img src="https://img.shields.io/github/stars/PhDP/rust-cuda-template?style=social"/> : Simple template for Rust + CUDA.

            - [neka-nat/cuimage](https://github.com/neka-nat/cuimage) <img src="https://img.shields.io/github/stars/neka-nat/cuimage?style=social"/> : Rust implementation of image processing library with CUDA.

            - [yanghaku/cuda-driver-sys](https://github.com/yanghaku/cuda-driver-sys) <img src="https://img.shields.io/github/stars/yanghaku/cuda-driver-sys?style=social"/> : Rust binding to CUDA Driver APIs.

            - [Canyon-ml/canyon-sys](https://github.com/Canyon-ml/canyon-sys) <img src="https://img.shields.io/github/stars/Canyon-ml/canyon-sys?style=social"/> : Rust Bindings for Cuda, CuDNN.

            - [cea-hpc/HARP](https://github.com/cea-hpc/HARP) <img src="https://img.shields.io/github/stars/cea-hpc/HARP?style=social"/> : Small tool for profiling the performance of hardware-accelerated Rust code using OpenCL and CUDA.

            - [Conqueror712/CUDA-Simulator](https://github.com/Conqueror712/CUDA-Simulator) <img src="https://img.shields.io/github/stars/Conqueror712/CUDA-Simulator?style=social"/> : A self-developed version of the user-mode CUDA emulator project and a learning repository for Rust.

            - [cszach/rust-cuda-template](https://github.com/cszach/rust-cuda-template) <img src="https://img.shields.io/github/stars/cszach/rust-cuda-template?style=social"/> : A Rust CUDA template with detailed instructions.

            - [exor2008/fluid-simulator](https://github.com/exor2008/fluid-simulator) <img src="https://img.shields.io/github/stars/exor2008/fluid-simulator?style=social"/> : Rust CUDA fluid simulator.

            - [chichieinstein/rustycuda](https://github.com/chichieinstein/rustycuda) <img src="https://img.shields.io/github/stars/chichieinstein/rustycuda?style=social"/> : Convenience functions for generic handling of CUDA resources on the Rust side.

            - [Jafagervik/cruda](https://github.com/Jafagervik/cruda) <img src="https://img.shields.io/github/stars/Jafagervik/cruda?style=social"/> : CRUDA - Writing rust with cuda.

            - [lennyerik/cutransform](https://github.com/lennyerik/cutransform) <img src="https://img.shields.io/github/stars/lennyerik/cutransform?style=social"/> : CUDA kernels in any language supported by LLVM.

           - [cjordan/hip-sys](https://github.com/cjordan/hip-sys) <img src="https://img.shields.io/github/stars/cjordan/hip-sys?style=social"/> : Rust bindings for HIP.

            - [rust-gpu](https://github.com/EmbarkStudios/rust-gpu) <img src="https://img.shields.io/github/stars/EmbarkStudios/rust-gpu?style=social"/> : 🐉 Making Rust a first-class language and ecosystem for GPU shaders 🚧 [shader.rs](https://shader.rs/)

            - [wgpu](https://github.com/gfx-rs/wgpu) <img src="https://img.shields.io/github/stars/gfx-rs/wgpu?style=social"/> : Safe and portable GPU abstraction in Rust, implementing WebGPU API. [wgpu.rs](https://wgpu.rs/)

            - [Vulkano](https://github.com/vulkano-rs/vulkano) <img src="https://img.shields.io/github/stars/vulkano-rs/vulkano?style=social"/> : Safe and rich Rust wrapper around the Vulkan API. Vulkano is a Rust wrapper around [the Vulkan graphics API](https://www.vulkan.org/). It follows the Rust philosophy, which is that as long as you don't use unsafe code you shouldn't be able to trigger any undefined behavior. In the case of Vulkan, this means that non-unsafe code should always conform to valid API usage.

            - [Ash](https://github.com/ash-rs/ash) <img src="https://img.shields.io/github/stars/ash-rs/ash?style=social"/> : Vulkan bindings for Rust.

            - [ocl](https://github.com/cogciprocate/ocl) <img src="https://img.shields.io/github/stars/cogciprocate/ocl?style=social"/> : OpenCL for Rust.

            - [opencl3](https://github.com/kenba/opencl3) <img src="https://img.shields.io/github/stars/kenba/opencl3?style=social"/> : A Rust implementation of the Khronos [OpenCL 3.0](https://registry.khronos.org/OpenCL/) API.





        - ##### Julia Version

            - [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl) <img src="https://img.shields.io/github/stars/JuliaGPU/CUDA.jl?style=social"/> : CUDA programming in Julia. [juliagpu.org/](https://juliagpu.org/)

            - [AMDGPU.jl](https://github.com/JuliaGPU/AMDGPU.jl) <img src="https://img.shields.io/github/stars/JuliaGPU/AMDGPU.jl?style=social"/> : AMD GPU (ROCm) programming in Julia.



    - #### Scientific Computing Framework
      ##### 科学计算框架

        - [cuBLAS](https://developer.nvidia.com/cublas) : Basic Linear Algebra on NVIDIA GPUs. NVIDIA cuBLAS is a GPU-accelerated library for accelerating AI and HPC applications. It includes several API extensions for providing drop-in industry standard BLAS APIs and GEMM APIs with support for fusions that are highly optimized for NVIDIA GPUs. The cuBLAS library also contains extensions for batched operations, execution across multiple GPUs, and mixed- and low-precision execution with additional tuning for the best performance.

        - [CUTLASS](https://github.com/NVIDIA/cutlass) <img src="https://img.shields.io/github/stars/NVIDIA/cutlass?style=social"/> : CUDA Templates for Linear Algebra Subroutines.

        - [MatX](https://github.com/NVIDIA/MatX) <img src="https://img.shields.io/github/stars/NVIDIA/MatX?style=social"/> : MatX - GPU-Accelerated Numerical Computing in Modern C++. An efficient C++17 GPU numerical computing library with Python-like syntax. [nvidia.github.io/MatX](https://nvidia.github.io/MatX)

        - [CuPy](https://github.com/cupy/cupy) <img src="https://img.shields.io/github/stars/cupy/cupy?style=social"/> : CuPy : NumPy & SciPy for GPU. [cupy.dev](https://cupy.dev/)

        - [GenericLinearAlgebra.jl](https://github.com/JuliaLinearAlgebra/GenericLinearAlgebra.jl) <img src="https://img.shields.io/github/stars/JuliaLinearAlgebra/GenericLinearAlgebra.jl?style=social"/> : Generic numerical linear algebra in Julia.

        - [custos-math](https://github.com/elftausend/custos-math) <img src="https://img.shields.io/github/stars/elftausend/custos-math?style=social"/> : This crate provides CUDA, OpenCL, CPU (and Stack) based matrix operations using [custos](https://github.com/elftausend/custos).



    - #### Machine Learning Framework

        - [cuDNN](https://developer.nvidia.com/cudnn) : The NVIDIA CUDA® Deep Neural Network library (cuDNN) is a GPU-accelerated library of primitives for [deep neural networks](https://developer.nvidia.com/deep-learning). cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, attention, matmul, pooling, and normalization.

        - [PyTorch](https://github.com/pytorch/pytorch) <img src="https://img.shields.io/github/stars/pytorch/pytorch?style=social"/> : Tensors and Dynamic neural networks in Python with strong GPU acceleration. [pytorch.org](https://pytorch.org/)

        - [PaddlePaddle](https://github.com/PaddlePaddle/Paddle) <img src="https://img.shields.io/github/stars/PaddlePaddle/Paddle?style=social"/> : PArallel Distributed Deep LEarning: Machine Learning Framework from Industrial Practice （『飞桨』核心框架，深度学习&机器学习高性能单机、分布式训练和跨平台部署）. [www.paddlepaddle.org/](http://www.paddlepaddle.org/)

        - [flashlight/flashlight](https://github.com/flashlight/flashlight) <img src="https://img.shields.io/github/stars/flashlight/flashlight?style=social"/> : A C++ standalone library for machine learning. [fl.readthedocs.io/en/latest/](https://fl.readthedocs.io/en/latest/)

        - [NVlabs/tiny-cuda-nn](https://github.com/NVlabs/tiny-cuda-nn) <img src="https://img.shields.io/github/stars/NVlabs/tiny-cuda-nn?style=social"/> : Lightning fast C++/CUDA neural network framework.

        - [yhwang-hub/dl_model_infer](https://github.com/yhwang-hub/dl_model_infer) <img src="https://img.shields.io/github/stars/yhwang-hub/dl_model_infer?style=social"/> : his is a c++ version of the AI reasoning library. Currently, it only supports the reasoning of the tensorrt model. The follow-up plan supports the c++ reasoning of frameworks such as Openvino, NCNN, and MNN. There are two versions for pre- and post-processing, c++ version and cuda version. It is recommended to use the cuda version., This repository provides accelerated deployment cases of deep learning CV popular models, and cuda c supports dynamic-batch image process, infer, decode, NMS.


    - #### AI Inference Framework
      ##### AI推理框架

        - ##### C Implementation

            - [llm.c](https://github.com/karpathy/llm.c) <img src="https://img.shields.io/github/stars/karpathy/llm.c?style=social"/> : LLM training in simple, pure C/CUDA. There is no need for 245MB of PyTorch or 107MB of cPython. For example, training GPT-2 (CPU, fp32) is ~1,000 lines of clean code in a single file. It compiles and runs instantly, and exactly matches the PyTorch reference implementation.

            - [llama2.c](https://github.com/karpathy/llama2.c) <img src="https://img.shields.io/github/stars/karpathy/llama2.c?style=social"/> : Inference Llama 2 in one file of pure C. Train the Llama 2 LLM architecture in PyTorch then inference it with one simple 700-line C file (run.c).


        - ##### CPP Implementation

            - [TensorRT](https://github.com/NVIDIA/TensorRT) <img src="https://img.shields.io/github/stars/NVIDIA/TensorRT?style=social"/> : NVIDIA® TensorRT™ is an SDK for high-performance deep learning inference on NVIDIA GPUs. This repository contains the open source components of TensorRT. [developer.nvidia.com/tensorrt](https://developer.nvidia.com/tensorrt)

            - [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM) <img src="https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM?style=social"/> : TensorRT-LLM provides users with an easy-to-use Python API to define Large Language Models (LLMs) and build TensorRT engines that contain state-of-the-art optimizations to perform inference efficiently on NVIDIA GPUs. TensorRT-LLM also contains components to create Python and C++ runtimes that execute those TensorRT engines. [nvidia.github.io/TensorRT-LLM](https://nvidia.github.io/TensorRT-LLM)

            - [gemma.cpp](https://github.com/google/gemma.cpp) <img src="https://img.shields.io/github/stars/google/gemma.cpp?style=social"/> :  gemma.cpp is a lightweight, standalone C++ inference engine for the Gemma foundation models from Google.

            - [llama.cpp](https://github.com/ggerganov/llama.cpp) <img src="https://img.shields.io/github/stars/ggerganov/llama.cpp?style=social"/> : Inference of [LLaMA](https://github.com/facebookresearch/llama) model in pure C/C++.

            - [whisper.cpp](https://github.com/ggerganov/whisper.cpp) <img src="https://img.shields.io/github/stars/ggerganov/whisper.cpp?style=social"/> : High-performance inference of [OpenAI's Whisper](https://github.com/openai/whisper) automatic speech recognition (ASR) model.

            - [ChatGLM.cpp](https://github.com/li-plus/chatglm.cpp) <img src="https://img.shields.io/github/stars/li-plus/chatglm.cpp?style=social"/> : C++ implementation of [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) and [ChatGLM2-6B](https://github.com/THUDM/ChatGLM2-6B).

            - [MegEngine/InferLLM](https://github.com/MegEngine/InferLLM) <img src="https://img.shields.io/github/stars/MegEngine/InferLLM?style=social"/> : InferLLM is a lightweight LLM model inference framework that mainly references and borrows from the llama.cpp project.

            - [DeployAI/nndeploy](https://github.com/DeployAI/nndeploy) <img src="https://img.shields.io/github/stars/DeployAI/nndeploy?style=social"/> : nndeploy是一款模型端到端部署框架。以多端推理以及基于有向无环图模型部署为内核，致力为用户提供跨平台、简单易用、高性能的模型部署体验。[nndeploy-zh.readthedocs.io/zh/latest/](https://nndeploy-zh.readthedocs.io/zh/latest/)

            - [zjhellofss/KuiperInfer (自制深度学习推理框架)](https://github.com/zjhellofss/KuiperInfer) <img src="https://img.shields.io/github/stars/zjhellofss/KuiperInfer?style=social"/> :  带你从零实现一个高性能的深度学习推理库，支持llama 、Unet、Yolov5、Resnet等模型的推理。Implement a high-performance deep learning inference library step by step.

            - [skeskinen/llama-lite](https://github.com/skeskinen/llama-lite) <img src="https://img.shields.io/github/stars/skeskinen/llama-lite?style=social"/> : Embeddings focused small version of Llama NLP model.

            - [Const-me/Whisper](https://github.com/Const-me/Whisper) <img src="https://img.shields.io/github/stars/Const-me/Whisper?style=social"/> : High-performance GPGPU inference of OpenAI's Whisper automatic speech recognition (ASR) model.

            - [wangzhaode/ChatGLM-MNN](https://github.com/wangzhaode/ChatGLM-MNN) <img src="https://img.shields.io/github/stars/wangzhaode/ChatGLM-MNN?style=social"/> : Pure C++, Easy Deploy ChatGLM-6B.

            - [ztxz16/fastllm](https://github.com/ztxz16/fastllm) <img src="https://img.shields.io/github/stars/ztxz16/fastllm?style=social"/> : 纯c++实现，无第三方依赖的大模型库，支持CUDA加速，目前支持国产大模型ChatGLM-6B，MOSS; 可以在安卓设备上流畅运行ChatGLM-6B。

            - [davidar/eigenGPT](https://github.com/davidar/eigenGPT) <img src="https://img.shields.io/github/stars/davidar/eigenGPT?style=social"/> : Minimal C++ implementation of GPT2.

            - [Tlntin/Qwen-TensorRT-LLM](https://github.com/Tlntin/Qwen-TensorRT-LLM) <img src="https://img.shields.io/github/stars/Tlntin/Qwen-TensorRT-LLM?style=social"/> : 使用TRT-LLM完成对Qwen-7B-Chat实现推理加速。

            - [FeiGeChuanShu/trt2023](https://github.com/FeiGeChuanShu/trt2023) <img src="https://img.shields.io/github/stars/FeiGeChuanShu/trt2023?style=social"/> : NVIDIA TensorRT Hackathon 2023复赛选题：通义千问Qwen-7B用TensorRT-LLM模型搭建及优化。

            - [TRT2022/trtllm-llama](https://github.com/TRT2022/trtllm-llama) <img src="https://img.shields.io/github/stars/TRT2022/trtllm-llama?style=social"/> : ☢️ TensorRT 2023复赛——基于TensorRT-LLM的Llama模型推断加速优化。



        - ##### Mojo Implementation

            - [llama2.mojo](https://github.com/tairov/llama2.mojo) <img src="https://img.shields.io/github/stars/tairov/llama2.mojo?style=social"/> : Inference Llama 2 in one file of pure 🔥

            - [dorjeduck/llm.mojo](https://github.com/dorjeduck/llm.mojo) <img src="https://img.shields.io/github/stars/dorjeduck/llm.mojo?style=social"/> : port of Andrjey Karpathy's llm.c to Mojo.


        - ##### Rust Implementation

            - [Candle](https://github.com/huggingface/candle) <img src="https://img.shields.io/github/stars/huggingface/candle?style=social"/> : Minimalist ML framework for Rust.

            - [Safetensors](https://github.com/huggingface/safetensors) <img src="https://img.shields.io/github/stars/huggingface/safetensors?style=social"/> : Simple, safe way to store and distribute tensors. [huggingface.co/docs/safetensors](https://huggingface.co/docs/safetensors/index)

            - [Tokenizers](https://github.com/huggingface/tokenizers) <img src="https://img.shields.io/github/stars/huggingface/tokenizers?style=social"/> : 💥 Fast State-of-the-Art Tokenizers optimized for Research and Production. [huggingface.co/docs/tokenizers](https://huggingface.co/docs/tokenizers/index)

            - [Burn](https://github.com/burn-rs/burn) <img src="https://img.shields.io/github/stars/burn-rs/burn?style=social"/> : Burn - A Flexible and Comprehensive Deep Learning Framework in Rust. [burn-rs.github.io/](https://burn-rs.github.io/)

            - [dfdx](https://github.com/coreylowman/dfdx) <img src="https://img.shields.io/github/stars/coreylowman/dfdx?style=social"/> : Deep learning in Rust, with shape checked tensors and neural networks.

            - [luminal](https://github.com/jafioti/luminal) <img src="https://img.shields.io/github/stars/jafioti/luminal?style=social"/> : Deep learning at the speed of light. [www.luminalai.com/](https://www.luminalai.com/)

            - [crabml](https://github.com/crabml/crabml) <img src="https://img.shields.io/github/stars/crabml/crabml?style=social"/> : crabml is focusing on the reimplementation of GGML using the Rust programming language.

            - [TensorFlow Rust](https://github.com/tensorflow/rust) <img src="https://img.shields.io/github/stars/tensorflow/rust?style=social"/> : Rust language bindings for TensorFlow.

            - [tch-rs](https://github.com/LaurentMazare/tch-rs) <img src="https://img.shields.io/github/stars/LaurentMazare/tch-rs?style=social"/> : Rust bindings for the C++ api of PyTorch.

            - [rustai-solutions/candle_demo_openchat_35](https://github.com/rustai-solutions/candle_demo_openchat_35) <img src="https://img.shields.io/github/stars/rustai-solutions/candle_demo_openchat_35?style=social"/> : candle_demo_openchat_35.

            - [llama2.rs](https://github.com/srush/llama2.rs) <img src="https://img.shields.io/github/stars/srush/llama2.rs?style=social"/> : A fast llama2 decoder in pure Rust.

            - [Llama2-burn](https://github.com/Gadersd/llama2-burn) <img src="https://img.shields.io/github/stars/Gadersd/llama2-burn?style=social"/> : Llama2 LLM ported to Rust burn.

            - [gaxler/llama2.rs](https://github.com/gaxler/llama2.rs) <img src="https://img.shields.io/github/stars/gaxler/llama2.rs?style=social"/> : Inference Llama 2 in one file of pure Rust 🦀

            - [whisper-burn](https://github.com/Gadersd/whisper-burn) <img src="https://img.shields.io/github/stars/Gadersd/whisper-burn?style=social"/> : A Rust implementation of OpenAI's Whisper model using the burn framework.

            - [stable-diffusion-burn](https://github.com/Gadersd/stable-diffusion-burn) <img src="https://img.shields.io/github/stars/Gadersd/stable-diffusion-burn?style=social"/> : Stable Diffusion v1.4 ported to Rust's burn framework.

            - [coreylowman/llama-dfdx](https://github.com/coreylowman/llama-dfdx) <img src="https://img.shields.io/github/stars/coreylowman/llama-dfdx?style=social"/> : [LLaMa 7b](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/) with CUDA acceleration implemented in rust. Minimal GPU memory needed!

            - [tazz4843/whisper-rs](https://github.com/tazz4843/whisper-rs) <img src="https://img.shields.io/github/stars/tazz4843/whisper-rs?style=social"/> : Rust bindings to [whisper.cpp](https://github.com/ggerganov/whisper.cpp).

            - [rustformers/llm](https://github.com/rustformers/llm) <img src="https://img.shields.io/github/stars/rustformers/llm?style=social"/> : Run inference for Large Language Models on CPU, with Rust 🦀🚀🦙.

            - [Chidori](https://github.com/ThousandBirdsInc/chidori) <img src="https://img.shields.io/github/stars/ThousandBirdsInc/chidori?style=social"/> : A reactive runtime for building durable AI agents. [docs.thousandbirds.ai](https://docs.thousandbirds.ai/).

            - [llm-chain](https://github.com/sobelio/llm-chain) <img src="https://img.shields.io/github/stars/sobelio/llm-chain?style=social"/> : llm-chain is a collection of Rust crates designed to help you work with Large Language Models (LLMs) more effectively. [llm-chain.xyz](https://llm-chain.xyz/)

            - [Atome-FE/llama-node](https://github.com/Atome-FE/llama-node) <img src="https://img.shields.io/github/stars/Atome-FE/llama-node?style=social"/> : Believe in AI democratization. llama for nodejs backed by llama-rs and llama.cpp, work locally on your laptop CPU. support llama/alpaca/gpt4all/vicuna model. [www.npmjs.com/package/llama-node](https://www.npmjs.com/package/llama-node)

            - [Noeda/rllama](https://github.com/Noeda/rllama) <img src="https://img.shields.io/github/stars/Noeda/rllama?style=social"/> : Rust+OpenCL+AVX2 implementation of LLaMA inference code.

            - [lencx/ChatGPT](https://github.com/lencx/ChatGPT) <img src="https://img.shields.io/github/stars/lencx/ChatGPT?style=social"/> : 🔮 ChatGPT Desktop Application (Mac, Windows and Linux). [NoFWL](https://app.nofwl.com/).

            - [Synaptrix/ChatGPT-Desktop](https://github.com/Synaptrix/ChatGPT-Desktop) <img src="https://img.shields.io/github/stars/Synaptrix/ChatGPT-Desktop?style=social"/> : Fuel your productivity with ChatGPT-Desktop - Blazingly fast and supercharged!

            - [Poordeveloper/chatgpt-app](https://github.com/Poordeveloper/chatgpt-app) <img src="https://img.shields.io/github/stars/Poordeveloper/chatgpt-app?style=social"/> : A ChatGPT App for all platforms. Built with Rust + Tauri + Vue + Axum.

            - [mxismean/chatgpt-app](https://github.com/mxismean/chatgpt-app) <img src="https://img.shields.io/github/stars/mxismean/chatgpt-app?style=social"/> : Tauri 项目：ChatGPT App.

            - [sonnylazuardi/chat-ai-desktop](https://github.com/sonnylazuardi/chat-ai-desktop) <img src="https://img.shields.io/github/stars/sonnylazuardi/chat-ai-desktop?style=social"/> : Chat AI Desktop App. Unofficial ChatGPT desktop app for Mac & Windows menubar using Tauri & Rust.

            - [yetone/openai-translator](https://github.com/yetone/openai-translator) <img src="https://img.shields.io/github/stars/yetone/openai-translator?style=social"/> : The translator that does more than just translation - powered by OpenAI.

            - [m1guelpf/browser-agent](https://github.com/m1guelpf/browser-agent) <img src="https://img.shields.io/github/stars/m1guelpf/browser-agent?style=social"/> : A browser AI agent, using GPT-4. [docs.rs/browser-agent](https://docs.rs/browser-agent/latest/browser_agent/)

            - [sigoden/aichat](https://github.com/sigoden/aichat) <img src="https://img.shields.io/github/stars/sigoden/aichat?style=social"/> : Using ChatGPT/GPT-3.5/GPT-4 in the terminal.

            - [uiuifree/rust-openai-chatgpt-api](https://github.com/uiuifree/rust-openai-chatgpt-api) <img src="https://img.shields.io/github/stars/uiuifree/rust-openai-chatgpt-api?style=social"/> : "rust-openai-chatgpt-api" is a Rust library for accessing the ChatGPT API, a powerful NLP platform by OpenAI. The library provides a simple and efficient interface for sending requests and receiving responses, including chat. It uses reqwest and serde for HTTP requests and JSON serialization.

            - [1595901624/gpt-aggregated-edition](https://github.com/1595901624/gpt-aggregated-edition) <img src="https://img.shields.io/github/stars/1595901624/gpt-aggregated-edition?style=social"/> : 聚合ChatGPT官方版、ChatGPT免费版、文心一言、Poe、chatchat等多平台，支持自定义导入平台。

            - [Cormanz/smartgpt](https://github.com/Cormanz/smartgpt) <img src="https://img.shields.io/github/stars/Cormanz/smartgpt?style=social"/> : A program that provides LLMs with the ability to complete complex tasks using plugins.

            - [femtoGPT](https://github.com/keyvank/femtoGPT) <img src="https://img.shields.io/github/stars/keyvank/femtoGPT?style=social"/> : femtoGPT is a pure Rust implementation of a minimal Generative Pretrained Transformer. [discord.gg/wTJFaDVn45](https://github.com/keyvank/femtoGPT)

            - [shafishlabs/llmchain-rs](https://github.com/shafishlabs/llmchain-rs) <img src="https://img.shields.io/github/stars/shafishlabs/llmchain-rs?style=social"/> : 🦀Rust + Large Language Models - Make AI Services Freely and Easily. Inspired by LangChain.

            - [flaneur2020/llama2.rs](https://github.com/flaneur2020/llama2.rs) <img src="https://img.shields.io/github/stars/flaneur2020/llama2.rs?style=social"/> : An rust reimplementatin of [https://github.com/karpathy/llama2.c](https://github.com/karpathy/llama2.c).

            - [Heng30/chatbox](https://github.com/Heng30/chatbox) <img src="https://img.shields.io/github/stars/Heng30/chatbox?style=social"/> : A Chatbot for OpenAI ChatGPT. Based on Slint-ui and Rust.

            - [fairjm/dioxus-openai-qa-gui](https://github.com/fairjm/dioxus-openai-qa-gui) <img src="https://img.shields.io/github/stars/fairjm/dioxus-openai-qa-gui?style=social"/> : a simple openai qa desktop app built with dioxus.

            - [purton-tech/bionicgpt](https://github.com/purton-tech/bionicgpt) <img src="https://img.shields.io/github/stars/purton-tech/bionicgpt?style=social"/> : Accelerate LLM adoption in your organisation. Chat with your confidential data safely and securely. [bionic-gpt.com](https://bionic-gpt.com/)




        - #### Zig Implementation

            - [llama2.zig](https://github.com/cgbur/llama2.zig) <img src="https://img.shields.io/github/stars/cgbur/llama2.zig?style=social"/> : Inference Llama 2 in one file of pure Zig.

            - [renerocksai/gpt4all.zig](https://github.com/renerocksai/gpt4all.zig) <img src="https://img.shields.io/github/stars/renerocksai/gpt4all.zig?style=social"/> : ZIG build for a terminal-based chat client for an assistant-style large language model with ~800k GPT-3.5-Turbo Generations based on LLaMa.

            - [EugenHotaj/zig_inference](https://github.com/EugenHotaj/zig_inference) <img src="https://img.shields.io/github/stars/EugenHotaj/zig_inference?style=social"/> : Neural Network Inference Engine in Zig.


        - ##### Go Implementation

            - [Ollama](https://github.com/ollama/ollama/) <img src="https://img.shields.io/github/stars/ollama/ollama?style=social"/> : Get up and running with Llama 2, Mistral, Gemma, and other large language models. [ollama.com](https://ollama.com/)


            - [go-skynet/LocalAI](https://github.com/go-skynet/LocalAI) <img src="https://img.shields.io/github/stars/go-skynet/LocalAI?style=social"/> : 🤖 Self-hosted, community-driven, local OpenAI-compatible API. Drop-in replacement for OpenAI running LLMs on consumer-grade hardware. Free Open Source OpenAI alternative. No GPU required. LocalAI is an API to run ggml compatible models: llama, gpt4all, rwkv, whisper, vicuna, koala, gpt4all-j, cerebras, falcon, dolly, starcoder, and many other. [localai.io](https://localai.io/)


        - ##### LLM Deployment Engine

            - [vllm-project/vllm](https://github.com/vllm-project/vllm) <img src="https://img.shields.io/github/stars/vllm-project/vllm?style=social"/> : A high-throughput and memory-efficient inference and serving engine for LLMs. [vllm.readthedocs.io](https://vllm.readthedocs.io/en/latest/)

            - [MLC LLM](https://github.com/mlc-ai/mlc-llm) <img src="https://img.shields.io/github/stars/mlc-ai/mlc-llm?style=social"/> : Enable everyone to develop, optimize and deploy AI models natively on everyone's devices. [mlc.ai/mlc-llm](https://mlc.ai/mlc-llm/)

            - [Lamini](https://github.com/lamini-ai/lamini) <img src="https://img.shields.io/github/stars/lamini-ai/lamini?style=social"/> : Lamini: The LLM engine for rapidly customizing models 🦙.

            - [datawhalechina/self-llm](https://github.com/datawhalechina/self-llm) <img src="https://img.shields.io/github/stars/datawhalechina/self-llm?style=social"/> :  《开源大模型食用指南》基于Linux环境快速部署开源大模型，更适合中国宝宝的部署教程。

        - ##### LLM Inference Benchmark

            - [ninehills/llm-inference-benchmark](https://github.com/ninehills/llm-inference-benchmark) <img src="https://img.shields.io/github/stars/ninehills/llm-inference-benchmark?style=social"/> : LLM Inference benchmark.


    - #### Multi-GPU Framework
      ##### 多GPU框架

        - [NVIDIA/nccl](https://github.com/NVIDIA/nccl) <img src="https://img.shields.io/github/stars/NVIDIA/nccl?style=social"/> : Optimized primitives for collective multi-GPU communication.

        - [wilicc/gpu-burn](https://github.com/wilicc/gpu-burn) <img src="https://img.shields.io/github/stars/wilicc/gpu-burn?style=social"/> : Multi-GPU CUDA stress test.



    - #### Robotics Framework
      ##### 机器人框架


        - [Cupoch](https://github.com/neka-nat/cupoch) <img src="https://img.shields.io/github/stars/neka-nat/cupoch?style=social"/> : Robotics with GPU computing.



    - #### ZKP and Web3 Framework
      ##### 零知识证明和Web3框架

        - [Tachyon](https://github.com/kroma-network/tachyon) <img src="https://img.shields.io/github/stars/kroma-network/tachyon?style=social"/> : Modular ZK(Zero Knowledge) backend accelerated by GPU.

        - [Blitzar](https://github.com/spaceandtimelabs/blitzar) <img src="https://img.shields.io/github/stars/spaceandtimelabs/blitzar?style=social"/> : Zero-knowledge proof acceleration with GPUs for C++ and Rust. [www.spaceandtime.io/](https://www.spaceandtime.io/)

        - [blitzar-rs](https://github.com/spaceandtimelabs/blitzar-rs) <img src="https://img.shields.io/github/stars/spaceandtimelabs/blitzar-rs?style=social"/> : High-Level Rust wrapper for the blitzar-sys crate. [www.spaceandtime.io/](https://www.spaceandtime.io/)

        - [ICICLE](https://github.com/ingonyama-zk/icicle) <img src="https://img.shields.io/github/stars/ingonyama-zk/icicle?style=social"/> : ICICLE is a library for ZK acceleration using CUDA-enabled GPUs.










  - ### HDL and FPGA Framework

    - #### C HDL

        - [LiteX](https://github.com/enjoy-digital/litex) <img src="https://img.shields.io/github/stars/enjoy-digital/litex?style=social"/> : The LiteX framework provides a convenient and efficient infrastructure to create FPGA Cores/SoCs, to explore various digital design architectures and create[full FPGA based systems](https://github.com/enjoy-digital/litex/wiki/Projects).


    - #### Scala HDL

        - [Chisel](https://github.com/chipsalliance/chisel) <img src="https://img.shields.io/github/stars/chipsalliance/chisel3?style=social"/> : Chisel: A Modern Hardware Design Language. [www.chisel-lang.org/](www.chisel-lang.org/)

        - [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) <img src="https://img.shields.io/github/stars/SpinalHDL/SpinalHDL?style=social"/> : Scala based HDL.



    - #### Rust HDL

        - [Veryl](https://github.com/dalance/veryl) <img src="https://img.shields.io/github/stars/dalance/veryl?style=social"/> : Veryl: A Modern Hardware Description Language.

        - [RustHDL](https://github.com/samitbasu/rust-hdl) <img src="https://img.shields.io/github/stars/samitbasu/rust-hdl?style=social"/> : A framework for writing FPGA firmware using the Rust Programming Language.

        - [VHDL-LS/rust_hdl](https://github.com/VHDL-LS/rust_hdl) <img src="https://img.shields.io/github/stars/VHDL-LS/rust_hdl?style=social"/> : This repository contains a fast VHDL language server and analysis library written in Rust.

        - [yupferris/kaze](https://github.com/yupferris/kaze) <img src="https://img.shields.io/github/stars/yupferris/kaze?style=social"/> : An [HDL](https://en.wikipedia.org/wiki/Hardware_description_language) embedded in Rust. kaze provides an API to describe Modules composed of Signals, which can then be used to generate Rust simulator code or Verilog modules.

        - [dalance/sv-parser](https://github.com/dalance/sv-parser) <img src="https://img.shields.io/github/stars/dalance/sv-parser?style=social"/> : SystemVerilog parser library fully compliant with IEEE 1800-2017.

        - [dalance/svls](https://github.com/dalance/svls) <img src="https://img.shields.io/github/stars/dalance/svls?style=social"/> : SystemVerilog language server.

        - [dalance/svlint](https://github.com/dalance/svlint) <img src="https://img.shields.io/github/stars/dalance/svlint?style=social"/> : SystemVerilog linter.

        - [vivekmalneedi/veridian](https://github.com/vivekmalneedi/veridian) <img src="https://img.shields.io/github/stars/vivekmalneedi/veridian?style=social"/> : A SystemVerilog Language Server.

        - [zachjs/sv2v](https://github.com/zachjs/sv2v) <img src="https://img.shields.io/github/stars/zachjs/sv2v?style=social"/> : SystemVerilog to Verilog conversion.


    - #### Python HDL

        - [nMigen](https://github.com/amaranth-lang/amaranth) <img src="https://img.shields.io/github/stars/amaranth-lang/amaranth?style=social"/> : A modern hardware definition language and toolchain based on Python.

        - [Migen](https://github.com/m-labs/migen) <img src="https://img.shields.io/github/stars/m-labs/migen?style=social"/> : A Python toolbox for building complex digital hardware.

        - [MyHDL](https://github.com/myhdl/myhdl) <img src="https://img.shields.io/github/stars/myhdl/myhdl?style=social"/> : MyHDL is a free, open-source package for using Python as a hardware description and verification language.

        - [Magma](https://github.com/phanrahan/magma/) <img src="https://img.shields.io/github/stars/phanrahan/magma?style=social"/> : Magma is a hardware design language embedded in python.

        - [PyRTL](https://github.com/UCSBarchlab/PyRTL) <img src="https://img.shields.io/github/stars/UCSBarchlab/PyRTL?style=social"/> : PyRTL provides a collection of classes for pythonic register-transfer level design, simulation, tracing, and testing suitable for teaching and research.

        - [Veriloggen](https://github.com/PyHDI/veriloggen) <img src="https://img.shields.io/github/stars/PyHDI/veriloggen?style=social"/> : Veriloggen: A Mixed-Paradigm Hardware Construction Framework.

        - [HWT](https://github.com/Nic30/hwt) <img src="https://img.shields.io/github/stars/Nic30/hwt?style=social"/> : VHDL/Verilog/SystemC code generator, simulator API written in python/c++.

        - [HDL21](https://github.com/dan-fritchman/Hdl21) <img src="https://img.shields.io/github/stars/dan-fritchman/Hdl21?style=social"/> : Analog Hardware Description Library in Python.






## Applications

  - ### CUDA and TensorRT Applications

    - #### Object Detection

        - [laugh12321/TensorRT-YOLO](https://github.com/laugh12321/TensorRT-YOLO) <img src="https://img.shields.io/github/stars/laugh12321/TensorRT-YOLO?style=social"/> : 🚀 TensorRT-YOLO: Support YOLOv3, YOLOv5, YOLOv6, YOLOv7, YOLOv8, YOLOv9, YOLOv10, PP-YOLOE using TensorRT acceleration with EfficientNMS! TensorRT-YOLO 是一个支持 YOLOv3、YOLOv5、YOLOv6、YOLOv7、YOLOv8、YOLOv9、YOLOv10、PP-YOLOE 和 PP-YOLOE+ 的推理加速项目，使用 NVIDIA TensorRT 进行优化。项目不仅集成了 EfficientNMS TensorRT 插件以增强后处理效果，还使用了 CUDA 核函数来加速前处理过程。TensorRT-YOLO 提供了 C++ 和 Python 推理的支持，旨在提供快速而优化的目标检测解决方案。

        - [Melody-Zhou/tensorRT_Pro-YOLOv8](https://github.com/Melody-Zhou/tensorRT_Pro-YOLOv8) <img src="https://img.shields.io/github/stars/Melody-Zhou/tensorRT_Pro-YOLOv8?style=social"/> : This repository is based on shouxieai/tensorRT_Pro, with adjustments to support YOLOv8.

        - [kalfazed/tensorrt_starter](https://github.com/kalfazed/tensorrt_starter) <img src="https://img.shields.io/github/stars/kalfazed/tensorrt_starter?style=social"/> : This repository give a guidline to learn CUDA and TensorRT from the beginning.

        - [shouxieai/tensorRT_Pro](https://github.com/shouxieai/tensorRT_Pro) <img src="https://img.shields.io/github/stars/shouxieai/tensorRT_Pro?style=social"/> : C++ library based on tensorrt integration.

        - [shouxieai/infer](https://github.com/shouxieai/infer) <img src="https://img.shields.io/github/stars/shouxieai/infer?style=social"/> : A new tensorrt integrate. Easy to integrate many tasks.

        - [triple-Mu/YOLOv8-TensorRT](https://github.com/triple-Mu/YOLOv8-TensorRT) <img src="https://img.shields.io/github/stars/triple-Mu/YOLOv8-TensorRT?style=social"/> : YOLOv8 using TensorRT accelerate !

        - [FeiYull/TensorRT-Alpha](https://github.com/FeiYull/TensorRT-Alpha) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/torch2trt?style=social"/> : 🔥🔥🔥TensorRT for YOLOv8、YOLOv8-Pose、YOLOv8-Seg、YOLOv8-Cls、YOLOv7、YOLOv6、YOLOv5、YOLONAS......🚀🚀🚀CUDA IS ALL YOU NEED.🍎🍎🍎

        - [cyrusbehr/YOLOv8-TensorRT-CPP](https://github.com/cyrusbehr/YOLOv8-TensorRT-CPP) <img src="https://img.shields.io/github/stars/cyrusbehr/YOLOv8-TensorRT-CPP?style=social"/> : YOLOv8 TensorRT C++ Implementation. A C++ Implementation of YoloV8 using TensorRT Supports object detection, semantic segmentation, and body pose estimation.

        - [VIDIA-AI-IOT/torch2trt](https://github.com/NVIDIA-AI-IOT/torch2trt) <img src="https://img.shields.io/github/stars/NVIDIA-AI-IOT/torch2trt?style=social"/> : An easy to use PyTorch to TensorRT converter.

        - [zhiqwang/yolort](https://github.com/zhiqwang/yolort) <img src="https://img.shields.io/github/stars/zhiqwang/yolort?style=social"/> : yolort is a runtime stack for yolov5 on specialized accelerators such as tensorrt, libtorch, onnxruntime, tvm and ncnn. [zhiqwang.com/yolort](https://zhiqwang.com/yolort/)

        - [Linaom1214/TensorRT-For-YOLO-Series](https://github.com/Linaom1214/TensorRT-For-YOLO-Series) <img src="https://img.shields.io/github/stars/Linaom1214/TensorRT-For-YOLO-Series?style=social"/> : YOLO Series TensorRT Python/C++. tensorrt for yolo series (YOLOv8, YOLOv7, YOLOv6....), nms plugin support.

        - [wang-xinyu/tensorrtx](https://github.com/wang-xinyu/tensorrtx) <img src="https://img.shields.io/github/stars/wang-xinyu/tensorrtx?style=social"/> : TensorRTx aims to implement popular deep learning networks with tensorrt network definition APIs.



        - [DefTruth/lite.ai.toolkit](https://github.com/DefTruth/lite.ai.toolkit) <img src="https://img.shields.io/github/stars/DefTruth/lite.ai.toolkit?style=social"/> : 🛠 A lite C++ toolkit of awesome AI models with ONNXRuntime, NCNN, MNN and TNN. YOLOX, YOLOP, YOLOv6, YOLOR, MODNet, YOLOX, YOLOv7, YOLOv5. MNN, NCNN, TNN, ONNXRuntime. “🛠Lite.Ai.ToolKit: 一个轻量级的C++ AI模型工具箱，用户友好（还行吧），开箱即用。已经包括 100+ 流行的开源模型。这是一个根据个人兴趣整理的C++工具箱，, 涵盖目标检测、人脸检测、人脸识别、语义分割、抠图等领域。”

        - [PaddlePaddle/FastDeploy](https://github.com/PaddlePaddle/FastDeploy) <img src="https://img.shields.io/github/stars/PaddlePaddle/FastDeploy?style=social"/> : ⚡️An Easy-to-use and Fast Deep Learning Model Deployment Toolkit for ☁️Cloud 📱Mobile and 📹Edge. Including Image, Video, Text and Audio 20+ main stream scenarios and 150+ SOTA models with end-to-end optimization, multi-platform and multi-framework support.

        - [enazoe/yolo-tensorrt](https://github.com/enazoe/yolo-tensorrt) <img src="https://img.shields.io/github/stars/enazoe/yolo-tensorrt?style=social"/> : TensorRT8.Support Yolov5n,s,m,l,x .darknet -> tensorrt. Yolov4 Yolov3 use raw darknet *.weights and *.cfg fils. If the wrapper is useful to you,please Star it.

        - [guojianyang/cv-detect-robot](https://github.com/guojianyang/cv-detect-robot) <img src="https://img.shields.io/github/stars/guojianyang/cv-detect-robot?style=social"/> : 🔥🔥🔥🔥🔥🔥Docker NVIDIA Docker2 YOLOV5 YOLOX YOLO Deepsort TensorRT ROS Deepstream Jetson Nano TX2 NX for High-performance deployment(高性能部署)。

        - [BlueMirrors/Yolov5-TensorRT](https://github.com/BlueMirrors/Yolov5-TensorRT) <img src="https://img.shields.io/github/stars/BlueMirrors/Yolov5-TensorRT?style=social"/> : Yolov5 TensorRT Implementations.

        - [lewes6369/TensorRT-Yolov3](https://github.com/lewes6369/TensorRT-Yolov3) <img src="https://img.shields.io/github/stars/lewes6369/TensorRT-Yolov3?style=social"/> : TensorRT for Yolov3.

        - [CaoWGG/TensorRT-YOLOv4](https://github.com/CaoWGG/TensorRT-YOLOv4) <img src="https://img.shields.io/github/stars/CaoWGG/TensorRT-YOLOv4?style=social"/> :tensorrt5, yolov4, yolov3,yolov3-tniy,yolov3-tniy-prn.

        - [isarsoft/yolov4-triton-tensorrt](https://github.com/isarsoft/yolov4-triton-tensorrt) <img src="https://img.shields.io/github/stars/isarsoft/yolov4-triton-tensorrt?style=social"/> : YOLOv4 on Triton Inference Server with TensorRT.

        - [TrojanXu/yolov5-tensorrt](https://github.com/TrojanXu/yolov5-tensorrt) <img src="https://img.shields.io/github/stars/TrojanXu/yolov5-tensorrt?style=social"/> : A tensorrt implementation of yolov5.

        - [tjuskyzhang/Scaled-YOLOv4-TensorRT](https://github.com/tjuskyzhang/Scaled-YOLOv4-TensorRT) <img src="https://img.shields.io/github/stars/tjuskyzhang/Scaled-YOLOv4-TensorRT?style=social"/> : Implement yolov4-tiny-tensorrt, yolov4-csp-tensorrt, yolov4-large-tensorrt(p5, p6, p7) layer by layer using TensorRT API.

        - [Syencil/tensorRT](https://github.com/Syencil/tensorRT) <img src="https://img.shields.io/github/stars/Syencil/tensorRT?style=social"/> : TensorRT-7 Network Lib 包括常用目标检测、关键点检测、人脸检测、OCR等 可训练自己数据。

        - [SeanAvery/yolov5-tensorrt](https://github.com/SeanAvery/yolov5-tensorrt) <img src="https://img.shields.io/github/stars/SeanAvery/yolov5-tensorrt?style=social"/> : YOLOv5 in TensorRT.

        - [Monday-Leo/YOLOv7_Tensorrt](https://github.com/Monday-Leo/YOLOv7_Tensorrt) <img src="https://img.shields.io/github/stars/Monday-Leo/YOLOv7_Tensorrt?style=social"/> : A simple implementation of Tensorrt YOLOv7.

        - [ibaiGorordo/ONNX-YOLOv6-Object-Detection](https://github.com/ibaiGorordo/ONNX-YOLOv6-Object-Detection) <img src="https://img.shields.io/github/stars/ibaiGorordo/ONNX-YOLOv6-Object-Detection?style=social"/> : Python scripts performing object detection using the YOLOv6 model in ONNX.

        - [ibaiGorordo/ONNX-YOLOv7-Object-Detection](https://github.com/ibaiGorordo/ONNX-YOLOv7-Object-Detection) <img src="https://img.shields.io/github/stars/ibaiGorordo/ONNX-YOLOv7-Object-Detection?style=social"/> : Python scripts performing object detection using the YOLOv7 model in ONNX.

        - [triple-Mu/yolov7](https://github.com/triple-Mu/yolov7) <img src="https://img.shields.io/github/stars/triple-Mu/yolov7?style=social"/> : End2end TensorRT YOLOv7.

        - [hewen0901/yolov7_trt](https://github.com/hewen0901/yolov7_trt) <img src="https://img.shields.io/github/stars/hewen0901/yolov7_trt?style=social"/> : yolov7目标检测算法的c++ tensorrt部署代码。

        - [tsutof/tiny_yolov2_onnx_cam](https://github.com/tsutof/tiny_yolov2_onnx_cam) <img src="https://img.shields.io/github/stars/tsutof/tiny_yolov2_onnx_cam?style=social"/> : Tiny YOLO v2 Inference Application with NVIDIA TensorRT.

        - [Monday-Leo/Yolov5_Tensorrt_Win10](https://github.com/Monday-Leo/Yolov5_Tensorrt_Win10) <img src="https://img.shields.io/github/stars/Monday-Leo/Yolov5_Tensorrt_Win10?style=social"/> : A simple implementation of tensorrt yolov5 python/c++🔥

        - [Wulingtian/yolov5_tensorrt_int8](https://github.com/Wulingtian/yolov5_tensorrt_int8) <img src="https://img.shields.io/github/stars/Wulingtian/yolov5_tensorrt_int8?style=social"/> : TensorRT int8 量化部署 yolov5s 模型，实测3.3ms一帧！

        - [Wulingtian/yolov5_tensorrt_int8_tools](https://github.com/Wulingtian/yolov5_tensorrt_int8_tools) <img src="https://img.shields.io/github/stars/Wulingtian/yolov5_tensorrt_int8_tools?style=social"/> : tensorrt int8 量化yolov5 onnx模型。

        - [MadaoFY/yolov5_TensorRT_inference](https://github.com/MadaoFY/yolov5_TensorRT_inference) <img src="https://img.shields.io/github/stars/MadaoFY/yolov5_TensorRT_inference?style=social"/> : 记录yolov5的TensorRT量化及推理代码，经实测可运行于Jetson平台。

        - [ibaiGorordo/ONNX-YOLOv8-Object-Detection](https://github.com/ibaiGorordo/ONNX-YOLOv8-Object-Detection) <img src="https://img.shields.io/github/stars/ibaiGorordo/ONNX-YOLOv8-Object-Detection?style=social"/> : Python scripts performing object detection using the YOLOv8 model in ONNX.

        - [we0091234/yolov8-tensorrt](https://github.com/we0091234/yolov8-tensorrt) <img src="https://img.shields.io/github/stars/we0091234/yolov8-tensorrt?style=social"/> : yolov8 tensorrt 加速.

        - [FeiYull/yolov8-tensorrt](https://github.com/FeiYull/yolov8-tensorrt) <img src="https://img.shields.io/github/stars/FeiYull/yolov8-tensorrt?style=social"/> : YOLOv8的TensorRT+CUDA加速部署，代码可在Win、Linux下运行。

        - [cvdong/YOLO_TRT_SIM](https://github.com/cvdong/YOLO_TRT_SIM) <img src="https://img.shields.io/github/stars/cvdong/YOLO_TRT_SIM?style=social"/> : 🐇 一套代码同时支持YOLO X, V5, V6, V7, V8 TRT推理 ™️ 🔝 ,前后处理均由CUDA核函数实现 CPP/CUDA🚀

        - [cvdong/YOLO_TRT_PY](https://github.com/cvdong/YOLO_TRT_PY) <img src="https://img.shields.io/github/stars/cvdong/YOLO_TRT_PY?style=social"/> : 🐰 一套代码同时支持YOLOV5, V6, V7, V8 TRT推理 ™️ PYTHON ✈️

        - [Psynosaur/Jetson-SecVision](https://github.com/Psynosaur/Jetson-SecVision) <img src="https://img.shields.io/github/stars/Psynosaur/Jetson-SecVision?style=social"/> : Person detection for Hikvision DVR with AlarmIO ports, uses TensorRT and yolov4.

        - [tatsuya-fukuoka/yolov7-onnx-infer](https://github.com/tatsuya-fukuoka/yolov7-onnx-infer) <img src="https://img.shields.io/github/stars/tatsuya-fukuoka/yolov7-onnx-infer?style=social"/> : Inference with yolov7's onnx model.

        - [MadaoFY/yolov5_TensorRT_inference](https://github.com/MadaoFY/yolov5_TensorRT_inference) <img src="https://img.shields.io/github/stars/MadaoFY/yolov5_TensorRT_inference?style=social"/> : 记录yolov5的TensorRT量化及推理代码，经实测可运行于Jetson平台。

        - [ervgan/yolov5_tensorrt_inference](https://github.com/ervgan/yolov5_tensorrt_inference) <img src="https://img.shields.io/github/stars/ervgan/yolov5_tensorrt_inference?style=social"/> : TensorRT cpp inference for Yolov5 model. Supports yolov5 v1.0, v2.0, v3.0, v3.1, v4.0, v5.0, v6.0, v6.2, v7.0.




  - ### FPGA Applications

    - #### Processor Chip

        - ##### CPU Chip

            - ###### RISC-V Chip

                - [XiangShan (香山)](https://github.com/OpenXiangShan/XiangShan) <img src="https://img.shields.io/github/stars/OpenXiangShan/XiangShan?style=social"/> : XiangShan (香山) is an open-source high-performance RISC-V processor project. "Towards Developing High Performance RISC-V Processors Using Agile Methodology". (**[MICRO 2022](https://ieeexplore.ieee.org/abstract/document/9923860/)**)

                - [Rocket Chip](https://github.com/chipsalliance/rocket-chip) <img src="https://img.shields.io/github/stars/chipsalliance/rocket-chip?style=social"/> : Rocket Chip Generator 🚀. This repository contains the Rocket chip generator necessary to instantiate the RISC-V Rocket Core.

                - [MoonbaseOtago/vroom](https://github.com/MoonbaseOtago/vroom) <img src="https://img.shields.io/github/stars/MoonbaseOtago/vroom?style=social"/> : VRoom! RISC-V CPU. A new high-end RISC-V implementation.

                - [SpinalHDL/VexRiscv](https://github.com/SpinalHDL/VexRiscv) <img src="https://img.shields.io/github/stars/SpinalHDL/VexRiscv?style=social"/> : SpinalHDL/VexRiscv.

                - [DarkRISCV](https://github.com/darklife/darkriscv) <img src="https://img.shields.io/github/stars/darklife/darkriscv?style=social"/> : opensouce RISC-V cpu core implemented in Verilog from scratch in one night!

                - [stnolting/neorv32](https://github.com/stnolting/neorv32) <img src="https://img.shields.io/github/stars/stnolting/neorv32?style=social"/> : The NEORV32 RISC-V Processor. 🖥️ A tiny, customizable and highly extensible MCU-class 32-bit RISC-V soft-core CPU and microcontroller-like SoC written in platform-independent VHDL.

                - [ZipCPU/zipcpu](https://github.com/ZipCPU/zipcpu) <img src="https://img.shields.io/github/stars/ZipCPU/zipcpu?style=social"/> : The Zip CPU is a small, light-weight, RISC CPU.

                - [olofk/serv](https://github.com/olofk/serv) <img src="https://img.shields.io/github/stars/olofk/serv?style=social"/> : SERV - The SErial RISC-V CPU.

                - [riscv-mcu/e203_hbirdv2](https://github.com/riscv-mcu/e203_hbirdv2) <img src="https://img.shields.io/github/stars/riscv-mcu/e203_hbirdv2?style=social"/> : The Ultra-Low Power RISC-V Core. [doc.nucleisys.com/hbirdv2](https://doc.nucleisys.com/hbirdv2/)

                - [ultraembedded/riscv](https://github.com/ultraembedded/riscv) <img src="https://img.shields.io/github/stars/ultraembedded/riscv?style=social"/> : RISC-V CPU Core (RV32IM).

                - [ultraembedded/biriscv](https://github.com/ultraembedded/biriscv) <img src="https://img.shields.io/github/stars/ultraembedded/biriscv?style=social"/> : 32-bit Superscalar RISC-V CPU.

                - [WangXuan95/USTC-RVSoC](https://github.com/WangXuan95/USTC-RVSoC) <img src="https://img.shields.io/github/stars/ZipCPU/wbuart32?style=social"/> : An FPGA-based RISC-V CPU+SoC with a simple and extensible peripheral bus. 基于FPGA的RISC-V CPU+SoC，包含一个简单且可扩展的外设总线。

                - [FPGAwars/FLIX-V](https://github.com/FPGAwars/FLIX-V) <img src="https://img.shields.io/github/stars/FPGAwars/FLIX-V?style=social"/> : FLIX-V: FPGA, Linux and RISC-V.




        - ##### GPU Chip

            - [Ventus(承影)](https://github.com/THU-DSP-LAB/ventus-gpgpu) <img src="https://img.shields.io/github/stars/THU-DSP-LAB/ventus-gpgpu?style=social"/> : Ventus(承影) GPGPU. GPGPU processor supporting RISCV-V extension, developed with [Chisel](https://github.com/chipsalliance/chisel) HDL.

            - [jbush001/NyuziProcessor](https://github.com/jbush001/NyuziProcessor) <img src="https://img.shields.io/github/stars/jbush001/NyuziProcessor?style=social"/> : Nyuzi is an experimental GPGPU processor focused on compute intensive tasks. It includes a synthesizable hardware design written in System Verilog, an instruction set emulator, an LLVM based C/C++ compiler, software libraries, and tests.





    - #### IP Module


        - ##### IP Generator

            - [lnis-uofu/OpenFPGA](https://github.com/lnis-uofu/OpenFPGA) <img src="https://img.shields.io/github/stars/lnis-uofu/OpenFPGA?style=social"/> : The award-winning OpenFPGA framework is the first open-source FPGA IP generator with silicon proofs supporting highly-customizable FPGA architectures. OpenFPGA provides complete EDA support for customized FPGAs, including Verilog-to-bitstream generation and self-testing verification. OpenFPGA opens the door to democratizing FPGA technology and EDA techniques with agile prototyping approaches and constantly evolving EDA tools for chip designers and researchers. [openfpga.readthedocs.io/en/master/](openfpga.readthedocs.io/en/master/). "OpenFPGA: An Open-Source Framework for Agile Prototyping Customizable FPGAs". (**[IEEE Micro, 2020](https://ieeexplore.ieee.org/abstract/document/9098028/)**)



        - ##### PCIe Module

            - [WangXuan95/Xilinx-FPGA-PCIe-XDMA-Tutorial](https://github.com/WangXuan95/Xilinx-FPGA-PCIe-XDMA-Tutorial) <img src="https://img.shields.io/github/stars/WangXuan95/Xilinx-FPGA-PCIe-XDMA-Tutorial?style=social"/> : Xilinx FPGA PCIe 保姆级教程 ——基于 PCIe XDMA IP核。

            - [Reconfigurable-Computing/Xilinx-FPGA-PCIe-XDMA-Tutorial](https://github.com/Reconfigurable-Computing/Xilinx-FPGA-PCIe-XDMA-Tutorial) <img src="https://img.shields.io/github/stars/Reconfigurable-Computing/Xilinx-FPGA-PCIe-XDMA-Tutorial?style=social"/> : Xilinx FPGA PCIe 保姆级教程 ——基于 PCIe XDMA IP核。

            - [enjoy-digital/litepcie](https://github.com/enjoy-digital/litepcie) <img src="https://img.shields.io/github/stars/enjoy-digital/litepcie?style=social"/> : LitePCIe provides a small footprint and configurable PCIe core.

            - [alexforencich/verilog-pcie](https://github.com/alexforencich/verilog-pcie) <img src="https://img.shields.io/github/stars/alexforencich/verilog-pcie?style=social"/> : Verilog PCI Express Components Readme.



        - ##### DDR Module

            - [ultraembedded/core_ddr3_controller](https://github.com/ultraembedded/core_ddr3_controller) <img src="https://img.shields.io/github/stars/ultraembedded/core_ddr3_controller?style=social"/> : A DDR3 memory controller in Verilog for various FPGAs.

            - [WangXuan95/FPGA-DDR-SDRAM](https://github.com/WangXuan95/FPGA-DDR-SDRAM) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-DDR-SDRAM?style=social"/> : An AXI4-based DDR1 controller to realize mass, cheap memory for FPGA. 基于FPGA的DDR1控制器，为低端FPGA嵌入式系统提供廉价、大容量的存储。

            - [adibis/DDR2_Controller](https://github.com/adibis/DDR2_Controller) <img src="https://img.shields.io/github/stars/adibis/DDR2_Controller?style=social"/> : DDR2 memory controller written in Verilog.

            - [BrianHGinc/BrianHG-DDR3-Controller](https://github.com/BrianHGinc/BrianHG-DDR3-Controller) <img src="https://img.shields.io/github/stars/BrianHGinc/BrianHG-DDR3-Controller?style=social"/> : DDR3 Controller v1.60, 16 read/write ports, configurable widths, priority, auto-burst size & cache on each port. VGA/HDMI multiwindow video controller with alpha-blended layers. Docs & TBs included.

            - [someone755/ddr3-controller](https://github.com/someone755/ddr3-controller) <img src="https://img.shields.io/github/stars/someone755/ddr3-controller?style=social"/> : A DDR3(L) PHY and controller, written in Verilog, for Xilinx 7-Series FPGAs.

            - [WangXuan95/FPGA-DDR-SDRAM](https://github.com/WangXuan95/FPGA-DDR-SDRAM) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-DDR-SDRAM?style=social"/> : An AXI4-based DDR1 controller to realize mass, cheap memory for FPGA. 基于FPGA的DDR1控制器，为低端FPGA嵌入式系统提供廉价、大容量的存储。






        - ##### Ethernet Module

        - [alexforencich/verilog-ethernet](https://github.com/alexforencich/verilog-ethernet) <img src="https://img.shields.io/github/stars/alexforencich/verilog-ethernet?style=social"/> : Verilog Ethernet components for FPGA implementation.



        - ##### WIFI Module

        - [openwifi](https://github.com/open-sdr/openwifi) <img src="https://img.shields.io/github/stars/open-sdr/openwifi?style=social"/> : open-source IEEE 802.11 WiFi baseband FPGA (chip) design: driver, software.



        - ##### UART Module

            - [ZipCPU/wbuart32](https://github.com/ZipCPU/wbuart32) <img src="https://img.shields.io/github/stars/ZipCPU/wbuart32?style=social"/> : A simple, basic, formally verified UART controller.

            - [WangXuan95/Verilog-UART](https://github.com/WangXuan95/Verilog-UART) <img src="https://img.shields.io/github/stars/WangXuan95/Verilog-UART?style=social"/> : 3 independent modules for FPGA: UART receiver, UART transmitter, UART interactive debugger. 3个独立模块：UART接收器、UART发送器、UART交互式调试器。




        - ##### USB Module

            - [WangXuan95/FPGA-USB-Device](https://github.com/WangXuan95/FPGA-USB-Device) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-USB-Device?style=social"/> : An FPGA-based USB full-speed device core to implement USB-serial, USB-camera, USB-audio, USB-disk, USB-keyboard, etc. It requires only 3 FPGA common IOs rather than additional chips. 基于FPGA的USB full-speed device端控制器，可实现USB串口、USB摄像头、USB音频、U盘、USB键盘等设备，只需要3个FPGA普通IO，而不需要额外的接口芯片。



        - ##### CAN-bus Module

            - [WangXuan95/FPGA-CAN](https://github.com/WangXuan95/FPGA-CAN) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-CAN?style=social"/> : An FPGA-based lightweight CAN bus controller. 基于FPGA的轻量级CAN总线控制器。


        - ##### AXI Module

            - [pulp-platform/axi](https://github.com/pulp-platform/axi) <img src="https://img.shields.io/github/stars/pulp-platform/axi?style=social"/> : AXI SystemVerilog synthesizable IP modules and verification infrastructure for high-performance on-chip communication.



        - ##### HDMI Module

            - [hdl-util/hdmi](https://github.com/hdl-util/hdmi) <img src="https://img.shields.io/github/stars/hdl-util/hdmi?style=social"/> : Send video/audio over HDMI on an FPGA. [purisa.me/blog/hdmi-released/](https://purisa.me/blog/hdmi-released/)




        - ##### SD-card Module

            - [WangXuan95/FPGA-SDcard-Reader](https://github.com/WangXuan95/FPGA-SDcard-Reader) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-SDcard-Reader?style=social"/> : An FPGA-based SD-card reader to read files from FAT16 or FAT32 formatted SD-cards. 基于FPGA的SD卡读取器，可以从FAT16或FAT32格式的SD卡中读取文件。


            - [WangXuan95/FPGA-SDcard-Reader-SPI](https://github.com/WangXuan95/FPGA-SDcard-Reader-SPI) <img src="https://img.shields.io/github/stars/FPGA-SDcard-Reader-SPI?style=social"/> : An FPGA-based SD-card reader via SPI bus, which can read files from FAT16 or FAT32 formatted SD-cards. 基于FPGA的SD卡读取器(通过SPI总线)，可以从FAT16或FAT32格式的SD卡中读取文件。


            - [WangXuan95/FPGA-SDfake](https://github.com/WangXuan95/FPGA-SDfake) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-SDfake?style=social"/> : Imitate SDcard using FPGAs. 使用FPGA模拟(伪装) SD卡。





        - ##### NFC Module

        - [WangXuan95/FPGA-NFC](https://github.com/WangXuan95/FPGA-NFC) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-NFC?style=social"/> : Build an NFC (RFID) card reader using FPGA and simple circuit instead of RFID-specfic chip. 用FPGA+分立器件电路搭建一个NFC(RFID)读卡器，不需要专门的RFID芯片。





        - ##### SATA Module

            - [WangXuan95/FPGA-SATA-HBA](https://github.com/WangXuan95/FPGA-SATA-HBA) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-SATA-HBA?style=social"/> : A SATA host (HBA) core based on Xilinx FPGA with GTH. Easy to read/write hard disk. 一个基于Xilinx FPGA中的GTH的SATA host控制器，用来读写硬盘。



        - ##### DAC Module

            - [WangXuan95/FPGA-DAC-R2R-PWM](https://github.com/WangXuan95/FPGA-DAC-R2R-PWM) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-DAC-R2R-PWM?style=social"/> : FPGA-based 14bit DAC with resistance network and PWM.










    - #### Camera Firmware

        - [apertus-open-source-cinema/axiom-firmware](https://github.com/apertus-open-source-cinema/axiom-firmware) <img src="https://img.shields.io/github/stars/apertus-open-source-cinema/axiom-firmware?style=social"/> : AXIOM Beta Software. Firmware required to boot & operate the [apertus° AXIOM Beta Camera](https://www.apertus.org/axiom-beta). "微信公众号「OpenFPGA」《[世界上最伟大的开源作品-基于FPGA的开源摄影机--Axiom Camera](https://mp.weixin.qq.com/s/MVLeBwgpCvKlrqwaNzv4dA)》"。




    - #### Spiking Neural Network

        - [ChFrenkel/tinyODIN](https://github.com/ChFrenkel/tinyODIN) <img src="https://img.shields.io/github/stars/ChFrenkel/tinyODIN?style=social"/> : tinyODIN Low-Cost Digital Spiking Neural Network (SNN) Processor.

        - [ChFrenkel/ODIN](https://github.com/ChFrenkel/ODIN) <img src="https://img.shields.io/github/stars/ChFrenkel/ODIN?style=social"/> : ODIN Spiking Neural Network (SNN) Processor.

        - [ChFrenkel/ReckOn](https://github.com/ChFrenkel/ReckOn) <img src="https://img.shields.io/github/stars/ChFrenkel/ReckOn?style=social"/> : ReckOn: A Spiking RNN Processor Enabling On-Chip Learning over Second-Long Timescales.



    - #### Convolutional Neural Network

        - [Xilinx/Vitis-AI](https://github.com/Xilinx/Vitis-AI/tree/master/demo) <img src="https://img.shields.io/github/stars/Xilinx/Vitis-AI?style=social"/> : Vitis AI offers a unified set of high-level C++/Python programming APIs to run AI applications across edge-to-cloud platforms, including DPU for Alveo, and DPU for Zynq Ultrascale+ MPSoC and Zynq-7000. It brings the benefits to easily port AI applications from cloud to edge and vice versa. 10 samples in [VART Samples](https://github.com/Xilinx/Vitis-AI/tree/master/demo/VART) are available to help you get familiar with the unfied programming APIs. [Vitis-AI-Library](https://github.com/Xilinx/Vitis-AI/tree/master/demo/Vitis-AI-Library) provides an easy-to-use and unified interface by encapsulating many efficient and high-quality neural networks.

        - [tensil-ai/tensil](https://github.com/tensil-ai/tensil) <img src="https://img.shields.io/github/stars/tensil-ai/tensil?style=social"/> : Open source machine learning accelerators. [www.tensil.ai](https://www.tensil.ai/)

        - [19801201/SpinalHDL_CNN_Accelerator](https://github.com/19801201/SpinalHDL_CNN_Accelerator) <img src="https://img.shields.io/github/stars/19801201/SpinalHDL_CNN_Accelerator?style=social"/> : CNN accelerator implemented with Spinal HDL.

        - [ZFTurbo/MobileNet-in-FPGA](https://github.com/ZFTurbo/MobileNet-in-FPGA) <img src="https://img.shields.io/github/stars/ZFTurbo/MobileNet-in-FPGA?style=social"/> : Generator of verilog description for FPGA MobileNet implementation.

        - [MasLiang/CNN-On-FPGA](https://github.com/MasLiang/CNN-On-FPGA) <img src="https://img.shields.io/github/stars/MasLiang/CNN-On-FPGA?style=social"/> : This is the code of the CNN on FPGA.But this can only be used for reference at present for some files are write coarsly using ISE.

        - [PipeCNN](https://github.com/doonny/PipeCNN) <img src="https://img.shields.io/github/stars/doonny/PipeCNN?style=social"/> : PipeCNN is an OpenCL-based FPGA Accelerator for Large-Scale Convolutional Neural Networks (CNNs).





    - #### Object Detection

        - [dhm2013724/yolov2_xilinx_fpga](https://github.com/dhm2013724/yolov2_xilinx_fpga) <img src="https://img.shields.io/github/stars/dhm2013724/yolov2_xilinx_fpga?style=social"/> : YOLOv2 Accelerator in Xilinx's Zynq-7000 Soc(PYNQ-z2, Zedboard and ZCU102). (**[硕士论文 2019](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CMFD&dbname=CMFDTEMP&filename=1019228234.nh&uid=WEEvREcwSlJHSldRa1FhdXNXaEhoOGhUTzA5T0tESzdFZ2pyR1NJR1ZBaz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MjE5NTN5dmdXN3JBVkYyNkY3RzZGdFBQcTVFYlBJUjhlWDFMdXhZUzdEaDFUM3FUcldNMUZyQ1VSTE9lWnVkdUY=), [电子技术应用 2019](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDLAST2019&filename=DZJY201908009&uid=WEEvREcwSlJHSldRa1FhdXNXaEhoOGhUTzA5T0tESzdFZ2pyR1NJR1ZBaz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MDU0NDJDVVJMT2VadWR1Rnl2Z1c3ck1JVGZCZDdHNEg5ak1wNDlGYllSOGVYMUx1eFlTN0RoMVQzcVRyV00xRnI=), [计算机科学与探索 2019](https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFQ&dbname=CJFDTEMP&filename=KXTS201910005&uid=WEEvREcwSlJHSldRa1FhdXNXaEhoOGhUTzA5T0tESzdFZ2pyR1NJR1ZBaz0=$9A4hF_YAuvQ5obgVAqNKPCYcEjKensW4IQMovwHtwkF4VYPoHbKxJw!!&v=MjkwNzdXTTFGckNVUkxPZVp1ZHVGeXZnVzdyT0xqWGZmYkc0SDlqTnI0OUZZWVI4ZVgxTHV4WVM3RGgxVDNxVHI=)**)

        - [Yu-Zhewen/Tiny_YOLO_v3_ZYNQ](https://github.com/Yu-Zhewen/Tiny_YOLO_v3_ZYNQ) <img src="https://img.shields.io/github/stars/Yu-Zhewen/Tiny_YOLO_v3_ZYNQ?style=social"/> : Implement Tiny YOLO v3 on ZYNQ. "A Parameterisable FPGA-Tailored Architecture for YOLOv3-Tiny". (**[ARC 2020](https://link.springer.com/chapter/10.1007/978-3-030-44534-8_25)**)

        - [HSqure/ultralytics-pt-yolov3-vitis-ai-edge](https://github.com/HSqure/ultralytics-pt-yolov3-vitis-ai-edge) <img src="https://img.shields.io/github/stars/HSqure/ultralytics-pt-yolov3-vitis-ai-edge?style=social"/> : This demo is only used for inference testing of Vitis AI v1.4 and quantitative compilation of DPU. It is compatible with the training results of [ultralytics/yolov3](https://github.com/ultralytics/yolov3) v9.5.0 (it needs to use the model saving method of Pytorch V1.4).

        - [mcedrdiego/Kria_yolov3_ppe](https://github.com/mcedrdiego/Kria_yolov3_ppe) <img src="https://img.shields.io/github/stars/mcedrdiego/Kria_yolov3_ppe?style=social"/> : Kria KV260 Real-Time Personal Protective Equipment Detection. "Deep Learning for Site Safety: Real-Time Detection of Personal Protective Equipment". (**[Automation in Construction 2020](https://www.sciencedirect.com/science/article/abs/pii/S0926580519308325)**)

        - [xlsjdjdk/Ship-Detection-based-on-YOLOv3-and-KV260](https://github.com/xlsjdjdk/Ship-Detection-based-on-YOLOv3-and-KV260) <img src="https://img.shields.io/github/stars/xlsjdjdk/Ship-Detection-based-on-YOLOv3-and-KV260?style=social"/> : This is the entry project of the Xilinx Adaptive Computing Challenge 2021. It uses YOLOv3 for ship target detection in optical remote sensing images, and deploys DPU on the KV260 platform to achieve hardware acceleration.

        - [Pomiculture/YOLOv4-Vitis-AI](https://github.com/Pomiculture/YOLOv4-Vitis-AI) <img src="https://img.shields.io/github/stars/Pomiculture/YOLOv4-Vitis-AI?style=social"/> : Custom YOLOv4 for apple recognition (clean/damaged) on Alveo U280 accelerator card using Vitis AI framework.

        - [mkshuvo2/ZCU104_YOLOv3_Post_Processing](https://github.com/mkshuvo2/ZCU104_YOLOv3_Post_Processing) <img src="https://img.shields.io/github/stars/mkshuvo2/ZCU104_YOLOv3_Post_Processing?style=social"/> : Tensor outputs form Vitis AI Runner Class for YOLOv3.

        - [puffdrum/v4tiny_pt_quant](https://github.com/puffdrum/v4tiny_pt_quant) <img src="https://img.shields.io/github/stars/puffdrum/v4tiny_pt_quant?style=social"/> : quantization for yolo with xilinx/vitis-ai-pytorch.

        - [chanshann/LITE_YOLOV3_TINY_VITISAI](https://github.com/chanshann/LITE_YOLOV3_TINY_VITISAI) <img src="https://img.shields.io/github/stars/chanshann/LITE_YOLOV3_TINY_VITISAI?style=social"/> : LITE_YOLOV3_TINY_VITISAI.

        - [LukiBa/zybo_yolo](https://github.com/LukiBa/zybo_yolo) <img src="https://img.shields.io/github/stars/LukiBa/zybo_yolo?style=social"/> : YOLO example implementation using Intuitus CNN accelerator on ZYBO ZYNQ-7000 FPGA board.

        - [matsuda-slab/YOLO_ZYNQ_MASTER](https://github.com/matsuda-slab/YOLO_ZYNQ_MASTER) <img src="https://img.shields.io/github/stars/matsuda-slab/YOLO_ZYNQ_MASTER?style=social"/> : Implementation of YOLOv3-tiny on FPGA.

        - [AramisOposich/tiny_YOLO_Zedboard](https://github.com/AramisOposich/tiny_YOLO_Zedboard) <img src="https://img.shields.io/github/stars/AramisOposich/tiny_YOLO_Zedboard?style=social"/> : tiny_YOLO_Zedboard.

        - [FerberZhang/Yolov2-FPGA-CNN-](https://github.com/FerberZhang/Yolov2-FPGA-CNN-) <img src="https://img.shields.io/github/stars/FerberZhang/Yolov2-FPGA-CNN-?style=social"/> : A demo for accelerating YOLOv2 in xilinx's fpga PYNQ.

        - [Prithvi-Velicheti/FPGA-Accelerator-for-TinyYolov3](https://github.com/Prithvi-Velicheti/FPGA-Accelerator-for-TinyYolov3) <img src="https://img.shields.io/github/stars/Prithvi-Velicheti/FPGA-Accelerator-for-TinyYolov3?style=social"/> : An FPGA-Accelerator-for-TinyYolov3.

        - [ChainZeeLi/FPGA_DPU](https://github.com/ChainZeeLi/FPGA_DPU) <img src="https://img.shields.io/github/stars/ChainZeeLi/FPGA_DPU?style=social"/> : This project is to implement YOLO v3 on Xilinx FPGA with DPU.

        - [xbdxwyh/yolov3_fpga_project](https://github.com/xbdxwyh/yolov3_fpga_project) <img src="https://img.shields.io/github/stars/xbdxwyh/yolov3_fpga_project?style=social"/> : yolov3_fpga_project.

        - [ZLkanyo009/Yolo-compression-and-deployment-in-FPGA](https://github.com/ZLkanyo009/Yolo-compression-and-deployment-in-FPGA) <img src="https://img.shields.io/github/stars/ZLkanyo009/Yolo-compression-and-deployment-in-FPGA?style=social"/> : 基于FPGA量化的人脸口罩检测。

        - [xiying-boy/yolov3-AX7350](https://github.com/xiying-boy/yolov3-AX7350) <img src="https://img.shields.io/github/stars/xiying-boy/yolov3-AX7350?style=social"/> : 基于HLS_YOLOV3的驱动文件。

        - [himewel/yolowell](https://github.com/himewel/yolowell) <img src="https://img.shields.io/github/stars/himewel/yolowell?style=social"/> : A set of hardware architectures to build a co-design of convolutional neural networks inference at FPGA devices.

        - [embedeep/Free-TPU](https://github.com/embedeep/Free-TPU) <img src="https://img.shields.io/github/stars/embedeep/Free-TPU?style=social"/> : Free TPU for FPGA with Lenet, MobileNet, Squeezenet, Resnet, Inception V3, YOLO V3, and ICNet. Deep learning acceleration using Xilinx zynq (Zedboard or ZC702 ) or kintex-7 to solve image classification, detection, and segmentation problem.

        - [yarakigit/design_contest_yolo_change_ps_to_pl](https://github.com/yarakigit/design_contest_yolo_change_ps_to_pl) <img src="https://img.shields.io/github/stars/yarakigit/design_contest_yolo_change_ps_to_pl?style=social"/> : Converts pytorch yolo format weights to C header files for bare-metal (FPGA implementation).

        - [adamgallas/fpga_accelerator_yolov3tiny](https://github.com/adamgallas/fpga_accelerator_yolov3tiny) <img src="https://img.shields.io/github/stars/adamgallas/fpga_accelerator_yolov3tiny?style=social"/> : fpga_accelerator_yolov3tiny.

        - [ylk678910/tiny-yolov3-fpga](https://github.com/ylk678910/tiny-yolov3-fpga) <img src="https://img.shields.io/github/stars/ylk678910/tiny-yolov3-fpga?style=social"/> : Use an all-programmable SoC board to implement locating and tracking tasks. The hardware algorithm, a row-stationary-like strategy, can parallel calculate and reduce the storage buffer area on FPGA.

        - [zhen8838/K210_Yolo_framework](https://github.com/zhen8838/K210_Yolo_framework) <img src="https://img.shields.io/github/stars/zhen8838/K210_Yolo_framework?style=social"/> : Yolo v3 framework base on tensorflow, support multiple models, multiple datasets, any number of output layers, any number of anchors, model prune, and portable model to K210 !

        - [SEASKY-Master/SEASKY_K210](https://github.com/SEASKY-Master/SEASKY_K210) <img src="https://img.shields.io/github/stars/SEASKY-Master/SEASKY_K210?style=social"/> : K210 PCB YOLO.

        - [SEASKY-Master/Yolo-for-k210](https://github.com/SEASKY-Master/Yolo-for-k210) <img src="https://img.shields.io/github/stars/SEASKY-Master/Yolo-for-k210?style=social"/> : Yolo-for-k210.

        - [TonyZ1Min/yolo-for-k210](https://github.com/TonyZ1Min/yolo-for-k210) <img src="https://img.shields.io/github/stars/TonyZ1Min/yolo-for-k210?style=social"/> : keras-yolo-for-k210.

        - [vseasky/yolo-for-k210](https://github.com/vseasky/yolo-for-k210) <img src="https://img.shields.io/github/stars/vseasky/yolo-for-k210?style=social"/> : Yolo-for-k210.

        - [shilicon/kr260_robotic_arm](https://github.com/shilicon/kr260_robotic_arm) <img src="https://img.shields.io/github/stars/shilicon/kr260_robotic_arm?style=social"/> : A robotic arm controller design based on AMD/Xilinx KR260 FPGA dev-kit. 这是一个在AMD/Xilinx Kria KR260 FPGA板卡上实现机械臂抓取物体的工程。



    - #### Visual SLAM

        - [sdoira/U96-SLAM](https://github.com/sdoira/U96-SLAM) <img src="https://img.shields.io/github/stars/sdoira/U96-SLAM?style=social"/> : Visual SLAM on Ultra96-V2.




    - #### Image Compression

        - [WangXuan95/FPGA-JPEG-LS-encoder](https://github.com/WangXuan95/FPGA-JPEG-LS-encoder) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-JPEG-LS-encoder?style=social"/> : An FPGA-based JPEG-LS encoder, which provides lossless and near-lossless image compression with high compression ratios. 基于FPGA的JPEG-LS编码器，可实现高压缩率的无损/近无损图象压缩。

        - [WangXuan95/FPGA-MPEG2-encoder](https://github.com/WangXuan95/FPGA-MPEG2-encoder) <img src="https://img.shields.io/github/stars/WangXuan95/FPGA-MPEG2-encoder?style=social"/> : FPGA-based high performance MPEG2 encoder for video compression. 基于 FPGA 的高性能 MPEG2 视频编码器，可实现视频压缩。

        - [WangXuan95/UH-JLS](https://github.com/WangXuan95/UH-JLS) <img src="https://img.shields.io/github/stars/WangXuan95/UH-JLS?style=social"/> : FPGA-based Ultra-High Throughput JPEG-LS encoder, which provides lossless image compression. 一个超高性能的FPGA JPEG-LS编码器，用来进行无损图象压缩。






    - #### Motor Control

        - [WangXuan95/FPGA-FOC](https://github.com/WangXuan95/FPGA-FOC) <img src="https://img.shields.io/github/stars/FPGA-FOC?style=social"/> : FPGA-based Field Oriented Control (FOC) for driving BLDC/PMSM motor. 基于FPGA的FOC控制器，用于驱动BLDC/PMSM电机。




    - #### Fixed-point

        - [WangXuan95/Verilog-FixedPoint](https://github.com/WangXuan95/Verilog-FixedPoint) <img src="https://img.shields.io/github/stars/Verilog-FixedPoint?style=social"/> : A Verilog fixed-point lib: custom bit width, arithmetic, converting to float, with single cycle & pipeline version. 一个Verilog定点数库，提供算术运算、与浮点数的互相转换，包含单周期和流水线两种实现。







## Blogs

  - ### HDL and FPGA Blogs

    - [bilibili「老石谈芯」| 微信公众号「老石谈芯」](https://space.bilibili.com/612932327)
        - [2020-06-27，FPGA芯片在人工智能时代的独特优势](https://www.bilibili.com/video/BV1EK4y1s7wP/?spm_id_from=333.788)
        - [2020-07-05，FPGA芯片发展的三个阶段](https://www.bilibili.com/video/BV1Q5411W7sW/?spm_id_from=333.788)
        - [2020-08-10，什么是数据中心？](https://www.bilibili.com/video/BV1h54y1i7u3/?spm_id_from=333.999.0.0)
        - [2020-09-20，【芯片科普】国产芯片的明显短板：FPGA](https://www.bilibili.com/video/BV1ih411X7QD/?spm_id_from=333.788)
        - [2020-11-04，入行十年，我总结了这份FPGA学习路线：搞定这四点，你也能轻松进阶](https://www.bilibili.com/video/BV1aK4y1E7nc/?spm_id_from=333.788)
        - [2020-11-30，芯片工程师的一天 | 我如何每天高效工作12小时](https://www.bilibili.com/video/BV1Fv411b7gs/?spm_id_from=333.999.0.0)
        - [2020-12-27，想去一线大厂做FPGA芯片开发？这些是你该学的知识](https://www.bilibili.com/video/BV11y4y1i7Lv/?spm_id_from=333.788)
        - [2021-01-11，【芯片前沿】英特尔的这个AI芯片，性能如何超过英伟达20倍？](https://www.bilibili.com/video/BV11U4y1x7hH/?spm_id_from=333.788)
        - [2021-01-17，为什么我不需要一个“完美”的桌面？ | 附完整桌面设备清单](https://www.bilibili.com/video/BV1Jh411y7WS/?spm_id_from=333.999.0.0)
        - [2021-03-07，这就是最棒的效率软件！如果不是，我倒想试试你的 | Notion使用技巧分享](https://www.bilibili.com/video/BV1aV411v7te/?spm_id_from=333.999.0.0)
        - [2021-04-04，微软如何成为FPGA芯片的全球第一大客户 | 深度解析微软Catapult FPGA项目](https://www.bilibili.com/video/BV1ny4y1x7ix/?spm_id_from=333.788)
        - [2021-04-26，【Vlog】芯片工程师休息的一天 | 高效放松身心的五个方法](https://www.bilibili.com/video/BV1GZ4y1F7z7/?spm_id_from=333.999.0.0)
        - [2021-06-15，我用了两年，写了一本没有代码的芯片书](https://www.bilibili.com/video/BV1Zv411p74J/?spm_id_from=333.788)
        - [2021-07-04，揭秘“香山”：高性能开源RISC-V处理器 | 对话中科院计算所包云岗研究员](https://www.bilibili.com/video/BV1Mf4y1b7hm/?spm_id_from=333.999.0.0)
        - [2021-07-28，【芯片硬核】如何设计一个高性能CPU？](https://www.bilibili.com/video/BV1t341167VV/?spm_id_from=333.999.0.0)
        - [2021-12-03，【芯片硬核】学习模数转换芯片ADC？这些是你该掌握的知识](https://www.bilibili.com/video/BV11r4y1Q7EJ/?spm_id_from=333.999.0.0)
        - [2022-02-12，如何用Notion保持全年自律？你该试试这个原则](https://www.bilibili.com/video/BV1Gb4y177no/?spm_id_from=333.999.0.0)
        - [2022-03-20，风口来了？一个视频讲透电子信息类所有专业/行业！](https://www.bilibili.com/video/BV1g44y1N7iQ/?spm_id_from=333.999.0.0)
        - [2022-03-26，AMD天价收购赛灵思，竟是为了这个芯片？](https://www.bilibili.com/video/BV17L411A7Cw/?spm_id_from=333.788)
        - [2022-11-25，第一次看到光刻机，竟然这样？！](https://www.bilibili.com/video/BV1Av4y1272D/?spm_id_from=333.999.0.0)
        - [2022-12-11，用软件开发FPGA：机械臂设计保姆级教程+源码](https://www.bilibili.com/video/BV1se411P7Xv/?spm_id_from=333.788)
        - [2023-04-21，聊聊我发的论文：如何将芯片验证速度提升4万倍？用FPGA！](https://www.bilibili.com/video/BV1Do4y1b7mC/?spm_id_from=333.999.0.0)
        - [2019-01-28，什么是FPGA工程师的核心竞争力](https://mp.weixin.qq.com/s/tMl3GNRxqjY5IX36YhOY4w)
        - [2020-02-28，FPGA最有影响力的25个研究成果 – 系统架构篇](https://mp.weixin.qq.com/s/2ctLcsJf9GifaRchpvoAug)
        - [2020-03-02，FPGA20年最有影响力的25个研究成果 – 微架构篇](https://mp.weixin.qq.com/s/a0rGav-SFF-d7r2pe1tsJQ)
        - [2020-11-09，入行10年后，我总结了这份FPGA学习路线](https://mp.weixin.qq.com/s/x_hTZQIxFsKmsaEn4DMUcQ)
        - [2021-01-18，Stratix10 NX：超越GPU的人工智能时代“最强”FPGA？](https://mp.weixin.qq.com/s/Ftv0IDQ3rTpW85wGLwsSGw)
        - [2021-07-20，芯片开发语言：Verilog在左，Chisel在右](https://mp.weixin.qq.com/s/EKzYUofPaN-3CDG8LEl4HA)
        - [2021-10-30，我在隔离酒店，“做了”一个AI视觉加速器](https://mp.weixin.qq.com/s/chBWjUdBRRfZOSs74lWmNQ)
        - [2021-12-16，未来的十年，是中国芯片行业的黄金十年](https://mp.weixin.qq.com/s/aCebZn6P0SDelZ1YkNDcDQ)
        - [2022-02-14，你能教教我们，二本如何去中科院实习吗？](https://mp.weixin.qq.com/s/hteiQebZizHKJaVLvEx5_A)
        - [2022-02-17，490亿刀！AMD收购赛灵思，动了谁的蛋糕？](https://mp.weixin.qq.com/s/A3OTAvVA_BiUghJ_X6lljQ)
        - [2022-04-07，ACAP：不是FPGA，胜似FPGA](https://mp.weixin.qq.com/s/FvS9QkT7SV4pK4gc86vovg)
        - [2022-05-18，裸辞回国+放弃百w年薪，我是不是疯了？](https://mp.weixin.qq.com/s/j100HqS__26h_zhUml5pQg)
        - [2022-08-01，如何设计一个RISC-V处理器？](https://mp.weixin.qq.com/s/ordM_ITgTBW61RHGld1HAw)
        - [2022-12-14，用软件开发FPGA：机械臂设计保姆级教程](https://mp.weixin.qq.com/s/s3rES6-aDKscRvVR2LZlAw)
        - [2023-01-10，我的2022年度总结](https://mp.weixin.qq.com/s/BVkRQFBYZG4jBDmuQiTBoQ)
        - [2023-04-09，ChatGPT爆火，为什么英伟达又赢麻了？](https://www.bilibili.com/video/BV1na4y1T732/?spm_id_from=333.999.0.0)
        - [2023-04-25，芯片从业者：你们的好日子在后头](https://mp.weixin.qq.com/s/O4DoYkP5tHfxdZA783U81A)
        - [2023-05-22，全网最深度分析：OPPO五百亿造芯梦碎，哲库是个错误吗？](https://www.bilibili.com/video/BV1az4y1b7cW/?spm_id_from=333.999.0.0)
        - [2023-05-23，【万字长文】论OPPO哲库的倒下](https://mp.weixin.qq.com/s/3KKJTfVebz03JzkNhY3p3w)
    - 微信公众号「OpenFPGA」
        - [2022-01-14，谈谈Verilog和SystemVerilog简史，FPGA设计是否需要学习SystemVerilog](https://mp.weixin.qq.com/s/ARVI4NUXFNG540VLTfglcg)
        - [2022-05-31，优秀的 Verilog/FPGA开源项目介绍（二十四）- 脉冲神经网络 (SNN)](https://mp.weixin.qq.com/s/-sCsRLK7uh5jZZ4FSc1t6g)
        - [2023-01-06，优秀的 Verilog/FPGA开源项目介绍（三十六）-RISC-V（新增一）](https://mp.weixin.qq.com/s/cbgGrGdKS1tUBQc1j3Fhpw)
        - [2023-01-30，从FPGA说起的深度学习（一）](https://mp.weixin.qq.com/s/oDmwGnVEaZvLSoSincjLFA)
        - [2023-02-08，从FPGA说起的深度学习（二）](https://mp.weixin.qq.com/s/4faZFvilJjPJyjHnARF0og)
        - [2023-02-15，从FPGA说起的深度学习（三）](https://mp.weixin.qq.com/s/ecSer6VrTAsh_6_J5jEidQ)
        - [2023-03-02，从FPGA说起的深度学习（四）](https://mp.weixin.qq.com/s/cjObRscNt1rs-RMAqHbnTg)
        - [2023-03-10，从FPGA说起的深度学习（五）](https://mp.weixin.qq.com/s/WoSe5hn_G-2jQU31lvd9SQ)
        - [2023-04-12，从FPGA说起的深度学习（六）-任务并行性](https://mp.weixin.qq.com/s/P6M4nd-svjC95J9qIy_4yQ)
        - [2023-04-17，从FPGA说起的深度学习（七）-循环并行化](https://mp.weixin.qq.com/s/xe-SHMNI8a5iH7jrkDB1pA)
        - [2023-04-28，从FPGA说起的深度学习（八）-数据并行性](https://mp.weixin.qq.com/s/1B0QellaAcL_vXRpUNgUcg)
        - [2023-05-06，从FPGA说起的深度学习（九）- 优化最终章](https://mp.weixin.qq.com/s/EyK6nO09FxzHFJTM7TjwTQ)
        - [2023-05-10，从FPGA说起的深度学习（十）](https://mp.weixin.qq.com/s/5vCvRRyyPfm6TEa9TmEsww)
        - [2023-03-13，在FPGA设计中怎么应用ChatGPT？](https://mp.weixin.qq.com/s/BvCFoAi9tAvSs4QS4BFRdA)
        - [2023-03-17，卧槽，这才是最强Verilog刷题网站！](https://mp.weixin.qq.com/s/vRBxv3-2GOclFeELhdT62w)
        - [2023-03-17，还在为没有项目做发愁？这几个神级开源网站，都是FPGA/IC项目](https://mp.weixin.qq.com/s/mbx8l6nRilcVOMjMQU7iUA)
        - [2023-03-20，【国产FPGA】国产FPGA搭建图像处理平台](https://mp.weixin.qq.com/s/Azg69UrhiwKrRtgzaJlCZg)
        - [2023-03-22，【开源硬件】FPGA PCIe加速卡开源硬件及例程（RIFFA\XDMA\HDMI\SDI）介绍](https://mp.weixin.qq.com/s/t7gTzUN2Z6l_fGWyk0gODg)
        - [2023-03-23，想用FPGA加速神经网络，这两个开源项目你必须要了解](https://mp.weixin.qq.com/s/n9GREgdKNyRrJy9-mSX8wg)
        - [2023-03-27，ChatGPT推荐的开源项目，到底靠不靠谱？](https://mp.weixin.qq.com/s/_ERFebXaLUbF3EQs_ZyPIQ)
        - [2023-03-31，牛客网发布了全新数字逻辑题库！会不会导致今年FPGA/IC行业更卷？！！](https://mp.weixin.qq.com/s/3aMAveRN6rakI30NuNydxQ)
        - [2023-04-03，FPGA有哪些优质的带源码的IP开源网站?](https://mp.weixin.qq.com/s/-JdGJyUVznAHhqKyr_xM2A)
        - [2023-04-06，世界上最伟大的开源作品-基于FPGA的开源摄影机--Axiom Camera](https://mp.weixin.qq.com/s/MVLeBwgpCvKlrqwaNzv4dA)
        - [2023-04-19，基于 FPGA 的低成本、低延时成像系统](https://mp.weixin.qq.com/s/kSC5Y_0vpmMhy718PhUVsw)
        - [2023-04-21，MIPI摄像头工程=7系列FPGA + OV5640(MIPI) + 15 分钟 + VITIS](https://mp.weixin.qq.com/s/h3hbl7pynhml2t4sOg9tHw)
        - [2023-04-24，在 FPGA 上快速构建 PID 算法](https://mp.weixin.qq.com/s/ozFDxLCCqYkusHCbC0QajQ)
        - [2023-04-24，Verilog“七宗罪”](https://mp.weixin.qq.com/s/mVcp4AJPXk7zmNfEjHNiBw)
        - [2023-05-08，FPGA上的视觉 SLAM](https://mp.weixin.qq.com/s/S2wicdaN_3kkJbexLuQGMw)
        - [2023-05-22，数字硬件建模SystemVerilog总结（完结篇）](https://mp.weixin.qq.com/s/9dHz9aqAM7WRaCUu4QYkpA)
        - [2023-05-22，OpenFPGA系列文章总结](https://mp.weixin.qq.com/s/yea1JY2dVy1GqzAc66RRVA)
    - 微信公众号「FPGA之旅」
        - [2022-08-29，FPGA点亮LED灯](https://mp.weixin.qq.com/s/OtBMm6iy8jrpHAl-FUI7XA)
        - [2022-08-29，FPGA实现按键模块](https://mp.weixin.qq.com/s/wgOKGlKHXeyX2FNhTRzfIA)
        - [2022-08-29，FPGA实现UART串口通信](https://mp.weixin.qq.com/s/N_BaLoVY97LdoWiL8XlSNQ)
        - [2022-08-16，FPGA实现串口多比特发送接收模块](https://mp.weixin.qq.com/s/-SgBkJTbW-nRkG_eqjatWQ)
        - [2022-08-20，FPGA实现IIC协议](https://mp.weixin.qq.com/s/3qwZRqjHEZzj4V8uMo0T4g)
        - [2022-08-29，FPGA实现数码管显示](https://mp.weixin.qq.com/s/mcT0rhKOOhjV5KOwDxi8zA)
        - [2022-02-26，FPGA数字时钟](https://mp.weixin.qq.com/s/ZqE81Ciw8NHc0hu2FyvKzQ)
        - [2022-08-30，FPGA实现DS18B20温度采集](https://mp.weixin.qq.com/s/medhKIQCo-KB904mXzwmpw)
        - [2022-08-31，FPGA驱动OLED屏幕](https://mp.weixin.qq.com/s/HPubkS3-EVhbcsShtyBCIQ)
        - [2022-09-04，串口上位机模拟OLED屏](https://mp.weixin.qq.com/s/_6IMXK_hM0udLnciTAc75A)
        - [2022-09-06，FPGA驱动OLED显示字符](https://mp.weixin.qq.com/s/5EpWq_-2dbDlKml-shzmKQ)
        - [2022-09-07，FPGA采集DHT11温湿度](https://mp.weixin.qq.com/s/D2uBEG6cA4Q9kqO6mWcsgA)
        - [2022-09-08，FPGA在OLED上显示DHT11数据](https://mp.weixin.qq.com/s/MKEMUNB7Bvc40aBPHt6dJQ)
        - [2022-09-14，FPGA解析红外遥控信号](https://mp.weixin.qq.com/s/8ozdSrNjoYQrfiQjhRhj_w)
        - [2022-09-24，FPGA实现超声波测距](https://mp.weixin.qq.com/s/5YYTZtk8WSU25LwgbpiaTw)
        - [2022-10-02，FPGA舵机驱动](https://mp.weixin.qq.com/s/j0fv2Lhz4myCcJ70tumDtA)
        - [2022-10-06，FPGA驱动VGA显示屏](https://mp.weixin.qq.com/s/HFHb4kDVQe3cm93JKnVb5A)
        - [2022-10-09，OV5640摄像头简介与SCCB时序](https://mp.weixin.qq.com/s/Yr4-88xnwLqQKpCXEa7ysQ)
        - [2022-10-14，FPGA驱动OV5640上电及初始化](https://mp.weixin.qq.com/s/m0JAqdng35-FC8E5pItlQA)
        - [2022-10-16，FPGA实现SDRAM控制器](https://mp.weixin.qq.com/s/gPttDvm6XVBrimx1AAKvhQ)
        - [2022-10-22，串口VGA搭配SDRAM_FIFO显示图片](https://mp.weixin.qq.com/s/C5tK3S8KJL2hHQam-6E-sA)
        - [2022-11-06，​FPGA实现Sobel算法进行边沿检测](https://mp.weixin.qq.com/s/aF0-jXrvwIva03-wX9Sh3Q)
        - [2022-12-03，​FPGA的工作原理，一篇全掌握！](https://mp.weixin.qq.com/s/pE-M9acv_oiIyMnr0gAomw)
        - [2023-05-20，​FPGA实现MPU6050姿态解算](https://mp.weixin.qq.com/s/9s5y4Z4jJcEK_vp5B84x0Q)
    - 微信公众号「FPGA技术江湖」
        - [2020-07-24，基于FPGA的单目内窥镜定位系统设计（上）](https://mp.weixin.qq.com/s/ASGphfySxZ0Nh2_D-11pcA)
        - [2020-07-25，​基于FPGA的单目内窥镜定位系统设计（中）](https://mp.weixin.qq.com/s/P_SITtBMvUdjPaCQZYuGWw)
        - [2020-07-26，基于FPGA的单目内窥镜定位系统设计（下）](https://mp.weixin.qq.com/s/sPPhouAym54zXdDNWYqZJg)
        - [2023-02-12，​往期精选：基于FPGA的电子计算器系统设计（附代码）](https://mp.weixin.qq.com/s/SW1YBrB6ujVuAO3YjS1ywQ)
        - [2023-02-14，​国产芯片生态图谱（2022最新版）](https://mp.weixin.qq.com/s/CJW3aARsnyHSc6Iw8eRLJg)
        - [2023-04-21，​万能芯片 — FPGA](https://mp.weixin.qq.com/s/RVDMBGV605msuDbyGscf4Q)
        - [2023-04-28，​为什么需要FPGA原型验证？](https://mp.weixin.qq.com/s/DafVnlzemBQojsorGJ0W5w)
        - [2023-05-11，​基于FPGA的实时图像边缘检测系统设计（附代码）](https://mp.weixin.qq.com/s/28TuVKvuaTBV1cv37yNRCw)
        - [2023-05-16，​基于FPGA的单目内窥镜定位系统设计（附代码）](https://mp.weixin.qq.com/s/D0_AIic00y4y1Ice0iUsTA)
        - [2023-05-18，​基于FPGA的CAN总线控制器的设计](https://mp.weixin.qq.com/s/myvp55su7TltPGTYwMZuaQ)
        - [2023-05-22，基于FPGA的以太网控制器（MAC）设计](https://mp.weixin.qq.com/s/i7yXX3M-kn7nGLI_9LTzSw)
        - [2023-05-23，如何在 FPGA 中做数学运算](https://mp.weixin.qq.com/s/N0kc-hrOTDywgfwy6SQ6JA)
    - 微信公众号「疯狂的FPGA」
        - [2023-03-09，《FPGA图像加速》第二章-bilibili回播入口](https://mp.weixin.qq.com/s/GEKZkMgKLYlhMSR6TCyUhQ)
        - [2023-04-11，国内唯一的纯FPGA论坛，发布](https://mp.weixin.qq.com/s/a6vliiR-XOftaBA-r6fGYw)
        - [2023-04-21，从入门到放弃，坚持一年时间很难](https://mp.weixin.qq.com/s/O2Cv3qIOnkA8Qhgg6r9o4w)
    - 微信公众号「FPGA探索者」
        - [2023-04-06，往年FPGA、数字IC实习秋招面试汇总贴 + 复习建议，收藏！](https://mp.weixin.qq.com/s/mAs857VDUrUtLA2fytlT9A)
    - 微信公众号「FPGA之家」
        - [2023-01-20，FPGA相关知识系统介绍](https://mp.weixin.qq.com/s/WF6uofAdSzMRPeEZ029KLQ)
        - [2023-04-23，Xilinx FPGA的约束设计和时序分析总结](https://mp.weixin.qq.com/s/aZHdhqwzlREjXwg8Sjq2oA)
        - [2023-04-28，FPGA设计原则总结](https://mp.weixin.qq.com/s/rBGuQR0OlmfkKXf3rVHCbw)
    - 微信公众号「深蓝AI」
        - [2023-04-05，稚晖君的机器人创业团队招聘](https://mp.weixin.qq.com/s/zu0JMOdWYk79YRMdr1Q3gg)
    - 微信公众号「AIIC Xidian」
        - [2022-10-16，研读|基于FPGA脉冲神经网络模型设计与实现](https://mp.weixin.qq.com/s/kkFeerMgtdnj--7AoOHV4A)
        - [2023-05-18，研读|基于FPGA的卷积神经网络交通信号灯分类的设计与实现](https://mp.weixin.qq.com/s/UX-d2RdXeR6KtwmFEjshTA)
    - 微信公众号「FPGA设计论坛」
        - [2023-03-08，未来的高性能FPGA是否会优于GPU？](https://mp.weixin.qq.com/s/-UvhpvHid8GwzC4y5_WTLg)
        - [2023-04-22，FPGA与处理器技术的的应用领域](https://mp.weixin.qq.com/s/k9JeLNyHVkQfIBPmEzVtdw)
        - [2023-04-26，采用FPGA实现FFT算法](https://mp.weixin.qq.com/s/giscBXdTA3vD7qedXgbyZA)
        - [2023-05-18，基于ARM的FPGA嵌入式系统实现](https://mp.weixin.qq.com/s/UnzTIvgCxwWRTtH3342BJA)
    - 微信公众号「数字IC打工人」
        - [2023-03-17，【行业干货】IC各细分领域公司简介以及薪资调研（GPU篇）](https://mp.weixin.qq.com/s/ZPuqE9wWu_jCQNFXPwGyzA)
    - 微信公众号「中国计算机学会」
        - [2023-04-10，FPGA在人工智能时代的独特优势｜SPP第38期](https://mp.weixin.qq.com/s/NleJburD5jvst8ijJUXcNQ)
    - 微信公众号「硬件起源」
        - [2023-03-17，国产化浪潮中的国产FPGA](https://mp.weixin.qq.com/s/P2JjulFeOaHDwBvOJpROnQ)
    - 微信公众号「芯东西」
        - [2023-04-07，雷军投资的第一家芯片公司，上市了！](https://mp.weixin.qq.com/s/eLwBoiFlzTnn7rsdtQaIxQ)
        - [2023-04-10，把GPT时代引擎拉满，国产AI大算力芯片换道狂飙](https://mp.weixin.qq.com/s/IBsY3Mwdnj4U-9hI4weqzA)
        - [2023-06-06，全球第二，英伟达市值突破3万亿！人均贡献1亿美金，黄仁勋用1年走完库克3.4年的路](https://mp.weixin.qq.com/s/D-r8JCV-MrNSH04yFKUg4g)
    - 微信公众号「IT服务圈儿」
        - [2023-04-09，摩尔定律之父94岁仙逝！悼念一代半导体先驱、英特尔创始人戈登·摩尔](https://mp.weixin.qq.com/s/Xn_HE9O3nBLtNIk3zZfqrQ)
    - 微信公众号「电子工程专辑」
        - [2023-04-07，详细解读AspenCore 2023 中国IC设计 Fabless100 排行榜](https://mp.weixin.qq.com/s/xHC8otX8lvnjei5bxkqkxA)
    - 微信公众号「建约车评」
        - [2023-03-29，从智能电车到AI计算机](https://mp.weixin.qq.com/s/qwyJMhYE4Nv7J0QoVxW1gA)
    - 微信公众号「ittbank」
        - [2023-04-10，万能芯片 —— FPGA](https://mp.weixin.qq.com/s/1cBSgtkZ0lK9Gx8xs49yZQ)
    - 微信公众号「半导体芯闻」
        - [2023-04-18，RISC–V市场迎来芯片巨头](https://mp.weixin.qq.com/s/2Hm9b3JHXaB234E1Yc9mFw)
    - 微信公众号「AI智胜未来」
        - [2023-04-17，我国人工智能硬件产业现状分析](https://mp.weixin.qq.com/s/IdYCjJgxCrP_cTVff6zuzw)
    - 微信公众号「机器之心」
        - [2022-07-04，超低功耗AI芯片：神经脉冲只需同类神经网络能量的0.02%](https://mp.weixin.qq.com/s/aVV4JyxblCYD6PWPsnnGuQ)
        - [2024-05-12，从零开始手搓GPU，照着英伟达CUDA来，只用两个星期](https://mp.weixin.qq.com/s/gDWQGs4MyVWqsmONdEqvpQ)
    - 微信公众号「半导体行业观察」
        - [2023-02-09，“没有什么能阻止RISC-V”](https://mp.weixin.qq.com/s/zBKU4z5Vh4zKUigUNq-bHg)
        - [2023-03-24，对标EDA三巨头，思尔芯推出国产硬件仿真系统](https://mp.weixin.qq.com/s/kU2bKAnloDhpYB1eMy_lGw)
    - 微信公众号「嵌入式Linux」
        - [2023-03-03，很快，RISC-V芯片将无处不在](https://mp.weixin.qq.com/s/H-F5cZ7e-0XMDwSXGy_uAA)
    - 微信公众号「硅农亚历山大」
        - [2023-02-28，RV双周报：RISC-V进入高性能计算元年，微软.NET Runtime初步支持RV架构(第54期-20230228)](https://mp.weixin.qq.com/s/kkVWz76Exy-ZNz8tOegeaQ)
    - 微信公众号「传感器专家网」
        - [2023-02-02，传感器上《新闻联播》了！被列为10大科技之首，重要性堪比芯片](https://mp.weixin.qq.com/s/lBCx60toLJl02VFYR2jJzA)
    - 微信公众号「泰晓科技」
        - [2023-01-20，访谈 | RISC-V 开发板 AI 应用开发实践](https://mp.weixin.qq.com/s/rDaYQTrD7mVHVVaEV3hLXw)
    - 微信公众号「佐思汽车研究」
        - [2023-03-30，智能汽车全景图—核心芯片微门户](https://mp.weixin.qq.com/s/pYDFF77MaLxu4nCYwDha7w)
    - 微信公众号「FPGA研究院」
        - [2023-04-26，基于FPGA实现FIR数字滤波电路的设计及应用](https://mp.weixin.qq.com/s/zEDwSMapNXg86qH5MtPYsQ)
    - 微信公众号「FPGA开发圈」
        - [2023-04-28，FPGA掀起新一轮卡位战？](https://mp.weixin.qq.com/s/myUH8DNVS0uQlY6Anz446g)
    - 微信公众号「OpenIC」
        - [2023-05-13，OPPO 造芯500亿大败局，中国“芯”何去何从？](https://mp.weixin.qq.com/s/t4nmKkiYemr1u_Xdb5F4aQ)
        - [2023-05-14，OPPO关停自研芯片业务，背后原因几何？](https://mp.weixin.qq.com/s/sl4KmokOAyDw5mnMhA-T4g)
    - 微信公众号「腾讯科技」
        - [2023-05-20，揭秘Meta的AI武器库：有两款自研芯片，还有一台超算](https://mp.weixin.qq.com/s/QU1Sgg_WAzZjNbUbvBJp2Q)




  - ### CUDA and TensorRT Blogs

    - 微信公众号「NVIDIA英伟达」
        - [2023-10-27，现已公开发布！欢迎使用 NVIDIA TensorRT-LLM 优化大语言模型推理](https://mp.weixin.qq.com/s/QaSbvyAmI6XXtr0y6W4LNQ)
        - [2024-06-03，COMPUTEX 2024 | “加速一切”，NVIDIA CEO 黄仁勋在 COMPUTEX 开幕前发表主题演讲](https://mp.weixin.qq.com/s/usHo79-ssQiX0Rt5dvJ-sQ)
    - 微信公众号「NVIDIA英伟达企业解决方案」
        - [2024-04-24，NVIDIA GPU 架构下的 FP8 训练与推理](https://mp.weixin.qq.com/s/KV4XC9WT-8mfpmEzflIuvw)
    - 微信公众号「AI不止算法」
        - [2024-03-20，C++模板推导再炫技：统一AI各个device各个kernel的调用和分发](https://mp.weixin.qq.com/s/r1XFocdVrfuArDWzpBYdAg)
        - [2024-04-09，全网首篇从tensorRT-LLM MoE CUDA kernel角度理解Mixtral-8x7b的推理加速及展望](https://mp.weixin.qq.com/s/3PsVUba-kTLIHK_s0RA2ow)
        - [2024-05-10，全面探究GPU SM内CUDA core-Tensor core能否同时计算？(上篇)](https://mp.weixin.qq.com/s/YASkRa12Ecr6fLtupP1WHg)
        - [2024-05-16，全面探究GPU SM内CUDA core-Tensor core能否同时计算？(下篇)](https://mp.weixin.qq.com/s/Jcu_HkAMiMXYagBjNhSCZQ)
    - 微信公众号「大猿搬砖简记」
        - [2024-03-11，图解Mixtral 8 * 7b推理优化原理与源码实现](https://mp.weixin.qq.com/s/jjZQ4A-rvk_e-woKLlNTVQ)
        - [2024-03-29，图解大模型计算加速系列之：vLLM核心技术PagedAttention原理](https://mp.weixin.qq.com/s/-5EniAmFf1v9RdxI5-CwiQ)
        - [2024-04-06，图解大模型计算加速系列：vLLM源码解析1，整体架构](https://mp.weixin.qq.com/s/r_t6_zMvPT7za82MZX4oRA)
        - [2024-04-12，图解大模型计算加速系列：vLLM源码解析2，调度器策略(Scheduler)](https://mp.weixin.qq.com/s/UCdqQUM_9a36uXkO36wpSg)
        - [2024-04-19，从啥也不会到Cuda GEMM优化](https://mp.weixin.qq.com/s/YLrsu1KAhzG8gFQ2L-TaMA)
    - 微信公众号「oldpan博客」
        - [2024-03-19，NVIDIA大语言模型落地的全流程解析](https://mp.weixin.qq.com/s/-sNnuDvkucUB_9K9RBfDEw)
        - [2024-03-20，TensorRT-LLM初探（二）简析了结构，用的更明白](https://mp.weixin.qq.com/s/Jk-AK84sllBbkDDpvkv62w)
        - [2024-03-21，高性能 LLM 推理框架的设计与实现](https://mp.weixin.qq.com/s/zys9KvQWbbdRHkOyhzZqUw)
        - [2024-04-15，[深入分析CUTLASS系列] 0x01 cutlass 源码分析(零) --- 软件架构(附ncu性能分析方法)](https://mp.weixin.qq.com/s/sLvZoWgILuRnvyiimMgeaQ)
        - [2024-04-21，搞懂 NVIDIA GPU 性能指标 很容易弄混的一个概念： Utilization vs Saturation](https://mp.weixin.qq.com/s/6PcF2RwGdm1G0JllGSS3jw)
        - [2024-04-22，快速提升性能，如何更好地使用GPU（上）](https://mp.weixin.qq.com/s/dUj058iBzYm-J2vlS5DfNA)
        - [2024-05-14，快速提升性能，如何更好地使用GPU（下）](https://mp.weixin.qq.com/s/NPcCHlLjBZeUiAhQOHX5qA)
        - [2024-05-22，大模型精度（FP16，FP32，BF16）详解与实践](https://mp.weixin.qq.com/s/95CUl1bGN-fSvmAbH0O-DA)
    - 微信公众号「DeepPrompting」
        - [2024-01-09，LLM推理库TensorRT-LLM深入分析](https://mp.weixin.qq.com/s/hI6maWtVGHnTi0uGPj6tmA)
        - [2024-04-10，一文上手 Tensor Core指令级编程](https://mp.weixin.qq.com/s/Gi8ExdfErUkfWu3oRyKvBw)
        - [2024-04-25，动手实现混合精度矩阵乘CUDA内核](https://mp.weixin.qq.com/s/JGYFOsPvUSNMQWjR1gKOOg)
        - [2024-04-26，一文了解CUDA矩阵乘编程](https://mp.weixin.qq.com/s/vG7d7-tAt-mXOgRSb-jZRA)
    - 微信公众号「澎峰科技PerfXLab」
        - [2023-05-24，深入浅出GPU优化系列：GEMM优化（一）](https://mp.weixin.qq.com/s/4aPW_93IV54lzs5JRn0JiA)
        - [2023-06-02，深入浅出GPU优化系列：GEMM优化（二）](https://mp.weixin.qq.com/s/1q5ocZ7vDDsvew3HNo_9Vg)
        - [2023-06-16，深入浅出GPU优化系列：GEMM优化（三）](https://mp.weixin.qq.com/s/13Nw6fubNLOMFR3ROc0z0w)
    - 微信公众号「机器学习研究组订阅」
        - [2017-12-07，【推荐】CUTLASS：CUDA C++高性能线性代数运算库](https://mp.weixin.qq.com/s/EDmbQ4y3nnkYiHhl3HG_HA)
    - 微信公众号「自动驾驶之心」
        - [2024-02-28，熬了几个通宵，我写了份CUDA新手入门代码](https://mp.weixin.qq.com/s/UXIzQ9SYhtN4q8VfzNXDqA)
        - [2024-05-13，Shared memory！CUDA数据拷贝速度拉满~](https://mp.weixin.qq.com/s/P5CdO3QCSQKuj3nWjS_2yA)
    - 微信公众号「Meet DSA」
        - [2024-03-29，大语言模型硬件加速器综述](https://mp.weixin.qq.com/s/rtq8e_zVUWLc-vkT4V0qzQ)
    - 微信公众号「AI寒武纪」
        - [2024-04-10，【太疯狂了】用 1000 行纯 C 代码实现 GPT-2 训练：Andrej Karpathy重塑LLM训练格局](https://mp.weixin.qq.com/s/hNKWVqepbega6YPf48b8ag)
        - [2024-04-14，【全球黑客加持】Karpathy 1000行纯C训练大模型速度已追平PyTorch](https://mp.weixin.qq.com/s/VvwDhMmq80yN-Wcb8s3aiQ)
    - 微信公众号「关于NLP那些你不知道的事」
        - [2024-01-26，基于TensorRT-LLM的大模型部署(速通笔记)](https://mp.weixin.qq.com/s/2d6ihFFDTDfppYbjtBPHMw)
    - 微信公众号「InfoQ」
        - [2024-04-09，“真男人就应该用 C 编程”！用 1000 行 C 代码手搓了一个大模型，Mac 即可运行，特斯拉前AI总监爆火科普 LLM](https://mp.weixin.qq.com/s/qb0dhdFnXZS4LeW2mvG6fg)
    - 微信公众号「机器之心」
        - [2024-04-09，纯C语言手搓GPT-2，前OpenAI、特斯拉高管新项目火了](https://mp.weixin.qq.com/s/YMuq9Jo9Nibl1QFbLNxazg)
        - [2024-05-20，首个GPU高级语言，大规模并行就像写Python，已获8500 Star](https://mp.weixin.qq.com/s/dC7Z5Rk05sM7ND7bYUsrZA)
    - 微信公众号「新智元」
        - [2023-09-10，H100推理飙升8倍！英伟达官宣开源TensorRT-LLM，支持10+模型](https://mp.weixin.qq.com/s/xcNQBG69XkS6mOstzqROAw)
        - [2024-04-07，Llama提速500%！谷歌美女程序员手搓矩阵乘法内核](https://mp.weixin.qq.com/s/2ROw_Tmmh4NHf8WOiwnJLg)
        - [2024-04-09，1000行C语言搓出GPT-2！AI大神Karpathy新项目刚上线就狂揽2.5k星](https://mp.weixin.qq.com/s/_W2GlbO8nAfpLPtRtQJ-yw)
    - 微信公众号「GitHubStore」
        - [2024-04-11，llm.c：实现了大语言模型(LLM)训练的简单、纯 C/CUDA 版本，无需 PyTorch 或 cPython](https://mp.weixin.qq.com/s/7cHYDBHqs8ClkijI-Fya9A)
    - 微信公众号「云云众生s」
        - [2024-04-17，NVIDIA希望有更多支持CUDA的编程语言](https://mp.weixin.qq.com/s/jABUruiJwjhGstbPG3U2Fw)
    - 微信公众号「手写AI」
        - [2022-10-16，TensorRT/CUDA超全代码资料仓库](https://mp.weixin.qq.com/s/WXZXVlAohZn2YJ490pddpQ)
    - 微信公众号「美团技术团队」
        - [2024-04-11，美团外卖基于GPU的向量检索系统实践](https://mp.weixin.qq.com/s/pPl-anyQnFNFkmBlVsrBpA)
    - 微信公众号「GiantPandaCV」
        - [2024-04-20，Tensor Cores 使用介绍](https://mp.weixin.qq.com/s/Mr-yR_YW5nNKV2dSrr5U2Q)
    - 微信公众号「GitHubFun网站」
        - [2024-04-20，英伟达开源人工智能代数库：线性代数子例程的 CUDA 模板](https://mp.weixin.qq.com/s/CwTnG89-tc1HaapvbU0D6g)
    - 微信公众号「大模型生态圈」
        - [2024-03-18，LLM百倍推理加速之量化篇](https://mp.weixin.qq.com/s/jbpVBZLZ0AkrP7bacY5mKw)
        - [2024-03-22，LLM推理：GPU资源和推理框架选择](https://mp.weixin.qq.com/s/qUaLOXZmk1xyGHGKX4ZtpQ)
        - [2024-03-27，LLM 推理加速方式汇总](https://mp.weixin.qq.com/s/IlaQw6Ut25NNoTZkxs63Vg)
        - [2024-04-26，LLM推理量化：FP8 VS INT8](https://mp.weixin.qq.com/s/e7QZC1qNkETXNXZpcD9cRg)
        - [2024-04-28，Nvidia GPU池化-远程GPU](https://mp.weixin.qq.com/s/tFdtYy5L_0V85OTvlPVK0A)
        - [2024-05-01，Nvidia Tensor Core 初探](https://mp.weixin.qq.com/s/VAuk2WdFqiW4ujV0A3-8HA)
        - [2024-05-24，Pytorch 显存管理机制与显存占用分析方法](https://mp.weixin.qq.com/s/QufR1esHGc3qkwgW6sAM-Q)
        - [2024-06-02，[LLM推理优化][万字]TensorRT-LLM部署调优-指北](https://mp.weixin.qq.com/s/PGOleShWEjHCPpw1wuV7SA)
    - 微信公众号「苏哲管理咨询」
        - [2024-02-25，英伟达（NVIDA）崛起不平凡之路--老黄全球AI芯片新帝国简史](https://mp.weixin.qq.com/s/4c8FtVeJmNlXL6akj5lj8A)
    - 微信公众号「后来遇见AI」
        - [2022-08-08，【机器学习】K均值聚类算法原理](https://mp.weixin.qq.com/s/o9bl1M9G1cOSYzzTZ3eYxw)
        - [2022-08-11，【CUDA编程】基于CUDA的Kmeans算法的简单实现](https://mp.weixin.qq.com/s/2PfocGm9l84l5Jj1vYF5bg)
        - [2024-01-23，【CUDA编程】基于 CUDA 的 Kmeans 算法的进阶实现（一）](hhttps://mp.weixin.qq.com/s/5Kr8ltlzy1nL7aeGrETYvA)
        - [2024-01-24，【CUDA编程】基于 CUDA 的 Kmeans 算法的进阶实现（二）](https://mp.weixin.qq.com/s/xPN5cupqt4B-JrX6KUNJrw)
        - [2024-04-08，【CUDA编程】CUDA 统一内存](https://mp.weixin.qq.com/s/DynVo_Mu7pUQxRLHH3ii9Q)
    - 微信公众号「江大白」
        - [2024-04-12，深入浅出，PyTorch模型int8量化原理拆解](https://mp.weixin.qq.com/s/j2QS3LdudrrlyZYQkVrl5Q)
        - [2024-04-13，CUDA模型部署实战，自己写的CUDA矩阵乘法能优化到多快？](https://mp.weixin.qq.com/s/ySfGSHyLrW5cRG17-B14rQ)
        - [2024-04-22，CUDA编程中，Tensor Cores的详细拆解](https://mp.weixin.qq.com/s/uDWOg9-pRudcvroZADsIbg)
    - 微信公众号「Tim在路上」
        - [2024-03-25，理解NVIDIA GPU 性能：利用率与饱和度](https://mp.weixin.qq.com/s/4_An51JuRGWTU0dLgZYHpQ)
        - [2024-04-30，加速矩阵计算：英伟达TensorCore架构演进与原理最全解析](https://mp.weixin.qq.com/s/dwT1Fl6F4V1MvWGgt1ac0Q)
        - [2024-05-15，揭秘 Tensor Core 底层：如何让AI计算速度飞跃](https://mp.weixin.qq.com/s/UL7CLWp3cmdUgGILr4iVzA)
        - [2024-05-27，浅析GPU分布式通信技术-PCle、NVLink、NVSwitch](https://mp.weixin.qq.com/s/ZllBWNqBwiY-Cb0UFIkwVg)
    - 微信公众号「潮观世界」
        - [2024-04-19，AI 推理：CPU 的崛起](https://mp.weixin.qq.com/s/rpdCT1fj2E3GKknfygAWRw)
    - 微信公众号「DeepDriving」
        - [2023-07-21，AI模型部署 | TensorRT模型INT8量化的Python实现](https://mp.weixin.qq.com/s/IQTCUs8CcfgHxJCyV6cm3w)
    - 微信公众号「GPUS开发者」
        - [2024-05-07，基于NVIDIA Jetson AGX Orin和Audio2Face做一个AI聊天数字人](https://mp.weixin.qq.com/s/7z0uU58IxwoXcI4bZ3z68g)
        - [2024-05-14，CUDA与OpenCL：并行计算革命的冲突与未来](https://mp.weixin.qq.com/s/h0nBvuV8nnfsbX1mjXAXVw)
    - 微信公众号「人工智能大讲堂」
        - [2024-05-11，我找到了AlexNet当年的源代码，没用框架，从零手撸CUDA/C++](https://mp.weixin.qq.com/s/plxXG8y5QlxSionyjyPXqw)
    - 微信公众号「未来科技潮」
        - [2024-04-10，针对大型语言模型的高效CUDA优化可实现性能翻倍提升](https://mp.weixin.qq.com/s/FtJpRrfnFACM37p9fQv3cw)
    - 微信公众号「AI道上」
        - [2024-04-19，英伟达坚持了16年的CUDA，到底是什么](https://mp.weixin.qq.com/s/nsBxZe_UXdvwfQ7DmCFuQg)
    - 微信公众号「科技译览」
        - [2024-04-09，100行C代码重塑深度学习：用纯C/CUDA打造的极简LLM训练](https://mp.weixin.qq.com/s/Th3RX3_FS5git0qJEcu4ZA)
    - 微信公众号「小白学视觉」
        - [2024-03-29，图像预处理库CV-CUDA开源了，打破预处理瓶颈，提升推理吞吐量20多倍](https://mp.weixin.qq.com/s/Zn4yI1xu2TuXZkJCzQt_yA)
    - 微信公众号「卡巴斯」
        - [2024-02-26，GPU（一）GPU简介](https://mp.weixin.qq.com/s/V4mMjzQ261kk6qmyH-STUQ)
    - 微信公众号「码砖杂役」
        - [2024-04-03，【CUDA】一文讲清流与并发，讲不清我重讲](https://mp.weixin.qq.com/s/-eJOdG7A-bvum9GFkiNIoQ)
        - [2024-05-02，【【CUDA】一文讲清共享内存和常量内存](https://mp.weixin.qq.com/s/qcynKSz2zQQQ2Ylk_sSorw)
    - 微信公众号「星想法」
        - [2022-09-19，零知识证明 - FPGA vs. GPU](https://mp.weixin.qq.com/s/SjoeQHboe2RI4EJKfpMjKw)
    - 微信公众号「太极图形」
        - [2022-06-16，减少重复造轮子，帮你解放生产力的「小矩阵功能」来啦！](https://mp.weixin.qq.com/s/5PGXUxcUMSfsbVbrennUFA)
    - 微信公众号「GiantPandaCV」
        - [2024-05-27，[并行训练]Context Parallelism的原理与代码浅析](https://mp.weixin.qq.com/s/vXWUUtAQNkBUpgDIJV8C0w)
    - 微信公众号「硅星人Pro」
        - [2024-06-03，黄仁勋：英伟达将一年推一款全新芯片，没有英伟达就没有今天AI的一切（附最新演讲全文）](https://mp.weixin.qq.com/s/Uc6heL537JNn63JXsDSVOg)
    - 微信公众号「3D视觉之心」
        - [2024-06-01，传统SLAM使用CUDA加速是否有比较大的优势呢？](https://mp.weixin.qq.com/s/5SlVcsDJd8VvABo6wCe4AQ)
    - 微信公众号「中国企业家杂志」
        - [2024-06-01，黄仁勋：不喜欢裁员，我宁愿“折磨”他们｜中企荐读](https://mp.weixin.qq.com/s/8jIgJPsWuCnj92wa61llSw)


## Videos

  - bilibili「权双」
    - [2023-07-14，CUDA编程基础入门系列（持续更新）](https://www.bilibili.com/video/BV1sM4y1x7of)



## Jobs and Interview

  - 微信公众号「高通内推王」
    - [2023-12-21，[英伟达内推] 英*达面试过程全面剖析](https://mp.weixin.qq.com/s/GoZKlLfdoGN9ngbe_PzG7w)
    - [2024-04-16，一份英伟达的offer，一年能到手多少钱](https://mp.weixin.qq.com/s/dZAG-AXbZkGi9CJQZMhCNA)
    - [2024-04-22，英伟达大力建设智能驾驶中心，扩大招聘，欢迎来内推](https://mp.weixin.qq.com/s/I17_SxwUFWJnyc2gkLobjQ)
  - 微信公众号「美团技术团队」
    - [2024-03-21，美团自动配送车2024春季招聘 | 社招专场](https://mp.weixin.qq.com/s/2e0g-7fD8Fbp65LbjGdVnA)
  - 微信公众号「大模型生态圈」
    - [2024-04-21，推理部署工程师面试题库](https://mp.weixin.qq.com/s/q46vKFPlQhcN7LyZNTRhXA)
  - 微信公众号「神仙外企」
    - [2024-05-14，半导体外企 | NVIDIA英伟达招聘！13薪，月薪20-80k，含非技术岗，内部定制礼品，22周全薪产假](https://mp.weixin.qq.com/s/VhrKxKGDqCiQmXLisX88yA)
  - 微信公众号「Cver」
    - [2024-06-01，英伟达算法岗面试，问的贼细！](https://mp.weixin.qq.com/s/dwXC572U9u5SAmJPnyjHXA)
  - [知乎「Tim在路上​」](https://www.zhihu.com/people/lao-zhang-cao-mei-yuan)
    - [2024-01-18，国内大厂GPU CUDA高频面试问题汇总（含部分答案）](https://zhuanlan.zhihu.com/p/678602674)