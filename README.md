# awesome-ai-accelerators
A list of the awesome compilers, programming, performance, and porting-related papers and tutorials for AI accelerators like Sambanova, Cerebras, Graphcore, Groq, etc.


## Contents
- [AI accelerator Companies](#ai-accelerator-companies)
- [Papers](#papers)
- [Tutorials](#tutorials)
- [Contribute](#contribute)

## AI Accelerator Companies
- [Cerebras](https://www.cerebras.net/)
- [Sambanova](https://sambanova.ai/)
- [Groq](https://groq.com/)
- [Graphcore](https://www.graphcore.ai/)

# To-Do Reading List

### New Representation
- [ ] [RVSDG: An Intermediate Representation for Optimizing Compilers](https://arxiv.org/pdf/1912.05036)
  - [ ] [Program feature impact on the treewidth of the RVSDG IR](https://ntnuopen.ntnu.no/ntnu-xmlui/handle/11250/2827695)
  - [ ] [Implementing RVSDG as a dialect of MLIR](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/3088035/no.ntnu:inspera:142737689:35303838.pdf?sequence=1)
### AMD AI Engine
- [ ] [An End-to-End Programming Model for AI Engine Architectures](https://dl.acm.org/doi/pdf/10.1145/3665283.3665294?casa_token=n7zkyyiiWxAAAAAA:E1oXHB4BPgg_tBP9ASSqUwVkzMs7y5j8XalEEsJfT2Ir8CiTMlaLePJm-v4h5SknK8Y0DqnuDr1A)
  - [ ] [Exploring the Versal AI Engines for Accelerating Stencil-based Atmospheric Advection Simulation] (https://dl.acm.org/doi/10.1145/3543622.3573047)
  - [ ] [AN END-TO-END PROGRAMMING MODEL FOR AI ENGINE ARCHITECTURES, THESIS](file:///Users/u1418973/Downloads/Levental_uchicago_0330D_17419.pdf)
  - [ ] [AI Engines and Their Applications](https://docs.amd.com/v/u/en-US/wp506-ai-engine) 

## Papers

- [Evaluating Emerging AI/ML Accelerators: IPU, RDU, and NVIDIA/AMD GPUs](https://arxiv.org/abs/2002.03794) by Hongwu Peng et al., arXiv 2024
- [Revet: A Language and Compiler for Dataflow Threads](https://arxiv.org/pdf/2302.06124) by Alexander C. Rucker et al., arXiv 2024
- [Generating SIMD Instructions for Cerebras CS-1 using Polyhedral Compilation Techniques](https://cerebras.net/wp-content/uploads/2021/04/IMPACT_2020_paper_3.pdf) by Sven Verdoolaege et.al IMPACT 2020
- [Benchmarking and In-depth Performance Study of Large Language Models on Habana Gaudi Processors](https://dl.acm.org/doi/10.1145/3624062.3624257) by Zhang et. al SC23(INTEL GAUDI)

## SC24 papers related to AI Accelerators
 - [Automated Code Generation of High-Order Stencils for a Dataflow Architecture](https://sc24.conference-program.com/presentation/?id=pap440&sess=sess403)
 - [Fast Molecular Dynamics on Wafer-Scale System](https://sc24.conference-program.com/presentation/?id=pap657&sess=sess384)
 - [Matrix-Free Finite-Volume Kernels on a Dataflow Architecture](https://sc24.conference-program.com/presentation/?id=pap439&sess=sess382)

## Survey papers
- [Survey of Machine Learning Accelerators](https://ieeexplore.ieee.org/document/9286149) by Albert Reuther et.al, HPEC 2020
- [A taxonomy for classification and comparison of dataflows for gnn accelerators](https://www.osti.gov/biblio/1817326) by Raveesh Garg et al., OSTI 2021

## Porting papers

### 2020
- [Fast Stencil-Code Computation on a Wafer-Scale Processor](https://arxiv.org/abs/2010.03660) by Kamil et al., 2020

### 2022
- [TensorFlow as a DSL for stencil-based computation on the Cerebras Wafer Scale Engine](https://arxiv.org/abs/2210.04795) by Nick Brown et al., 2022
- [Wafer-Scale Fast Fourier Transforms](https://arxiv.org/pdf/2209.15040) by Marcelo Orenes-Vera et al., arXiv 2022
- [Disruptive Changes in Field Equation Modeling A Simple Interface for Wafer Scale Engines](https://arxiv.org/pdf/2209.13768) by Mino Woo et al., 2022
- [Massively scalable stencil algorithm](https://arxiv.org/pdf/2204.03775) by Mathias et al., arXiv 2022

### 2023
- [Hardware Specialization: Estimating Monte Carlo Cross-Section Lookup Kernel Performance and Area](https://dl.acm.org/doi/10.1145/3624062.3625534) by Yoshii et al., SC 23
- [Efficient algorithms for Monte Carlo particle transport on AI accelerator hardware](https://arxiv.org/abs/2311.01739) by John Tramm et al., arXiv 2023
- [Scaling the “Memory Wall” for Multi-Dimensional Seismic Processing with Algebraic Compression on Cerebras CS-2 Systems](https://dl.acm.org/doi/10.1145/3581784.3627042) by Hatem et al., SC23

### 2024
- [Breaking the Molecular Dynamics Timescale Barrier Using a Wafer-Scale System](https://arxiv.org/abs/2405.07898) by Kylee Santos et al., arXiv 2024
- [2D Collective Communication for the Cerebras Wafer-Scale Engine](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/698365/1/bt_Louis_Schnyder.pdf) by Louis Schnyder Bachelor's Thesis ETHZ, 2024
- [CereSZ: Enabling and Scaling Error-bounded Lossy Compression on Cerebras CS-2](https://www.research-collection.ethz.ch/bitstream/handle/20.500.11850/698365/1/bt_Louis_Schnyder.pdf) by Shihui Song et al., HPDC 2024
- [Slide FFT on a homogeneous mesh in wafer-scale computing](https://arxiv.org/pdf/2401.05427) by Maurice H.P.M. van Putten et al., arXiv 2024
- [Near-Optimal Wafer-Scale Reduce](https://spcl.inf.ethz.ch/Publications/.pdf/luczynski-gianinazzi-hpdc-2024) by Piotr Luczynski et al., HPDC 2024
- [Automated Code Generation of High-Order Stencils for a Dataflow Architecture](https://sc24.conference-program.com/presentation/?id=pap440&sess=sess403)
- [Fast Molecular Dynamics on Wafer-Scale System](https://sc24.conference-program.com/presentation/?id=pap657&sess=sess384)
- [Matrix-Free Finite-Volume Kernels on a Dataflow Architecture](https://sc24.conference-program.com/presentation/?id=pap439&sess=sess382)

### Newly added

- [SPADA(tools)](https://arxiv.org/pdf/2511.09447)
- [Matrix Free Finite Volume Kernels on dataflow architectures(kernel)](https://arxiv.org/pdf/2408.03452)
- [Scalable Distributed High-Order Stencil Computations(25 point stencils)(kernel)](https://ieeexplore.ieee.org/document/10046080)
- [The Spatial Computer: A model for energy-efficient parallel computation(modelling)](https://arxiv.org/pdf/2205.04934)
- [Sparse Matrix Multiplication on Cerebras WSE-2: SpMM in Spatial Computing(kernel)](https://filipdob.ro/papers/ProjectCerebras.pdf)
- [Parallel Sparse Tensor-times-Vector on Cerebras WSE-2(MS Thesis)](https://repository.lib.ncsu.edu/server/api/core/bitstreams/ff6d682f-4e2a-433e-9552-716acc8ebd04/content)
- [An MLIR Lowering Pipeline for Stencils at Wafer-Scale(tools/compiler)](?)
- [Near Optimal Wafer Scale Reduce(communication optimization)](https://arxiv.org/pdf/2404.15888)
- [Automated Code Generation for High-Order Stencils for a dataflow Architecture(codegen/automation)](https://dl.acm.org/doi/pdf/10.1109/SC41406.2024.00025)
- [A COMPARISON OF THE CEREBRAS WAFER-SCALE INTEGRATION TECHNOLOGY WITH NVIDIA GPU-BASED SYSTEMS FOR ARTIFICIAL INTELLIGENCE](https://arxiv.org/pdf/2503.11698v1)


## Tutorials
- [Argonne ALCF Training](https://www.alcf.anl.gov/ai-testbed-training-workshops)
- [GraphCore EuroLLVM 22](https://www.youtube.com/watch?v=nr2ibjPg7bc&list=PL_R5A0lGi1AC5aYjEmBIAMMyibsENvvdU&index=13)

## Dataflow Graph Generation
- [DACE: Data-Centric Parallel Programming; Johannes de Fine Licht (ETH Zurich)](https://www.youtube.com/watch?v=t0T34AWDpgo)
- [StencilFlow](https://youtu.be/HZ6n0vctp2o?si=gz8AF8mi9RjtTUHI)
- [Portable, high-performance Python on CPUs, GPUs, FPGAs (XACC Winter school 2022)](https://www.youtube.com/watch?v=FGYGxI5BKcM)
- [Stateful Dataflow Multigraphs: Data-Centric Performance Portability on Heterogeneous Architectures](https://youtu.be/ujKZXUmFAlw?si=zo8x7xP3u-ovRyr7)
- [Bridging Control-Centric and Data-Centric Optimization](https://spcl.inf.ethz.ch/Publications/.pdf/dcir-cgo23.pdf)
- [A Data-Centric Optimization Framework for Machine Learning](https://dl.acm.org/doi/pdf/10.1145/3524059.3532364)
- [Lifting C Semantics for Dataflow Optimization](https://spcl.inf.ethz.ch/Publications/.pdf/calotoiu-c2dace.pdf)
- [Streaming Task Graph Scheduling for Dataflow Architectures](https://youtu.be/cAuihrBDt-Y?si=k_dEJfS5jWoj1E1B)
- [The spatial computer: A model for energy-efficient parallel computation](https://arxiv.org/pdf/2205.04934) by Lukas et al., arXiv 2023

## Dataflow learning
- [Dataflow for exascale, 2012 video](https://www.youtube.com/watch?v=rJ2MrtZPWFc)
- [Stanford Seminar - Multiscale Dataflow Computing: Competitive Advantage at the Exascale Frontier, Maxeler(A Groq acquired company now)](https://www.youtube.com/watch?v=Nwdu7QlFUnA) DataFlow hardware since 2000!


## Spatial Computing general literature
### Lectures and Talks

1. [**Prof. Onur Mutlu Lecture on Spatial Computing**](https://www.youtube.com/watch?v=8zbh4gWGa7I)
2. [**Industry Talk on Dataflow Architectures**](https://www.youtube.com/watch?v=Nwdu7QlFUnA)

### Podcasts

1. [**Spatial Computing Podcast**](https://www.youtube.com/watch?v=lTlpJ2Mz4zs)

### Conference Talks
1. [**ATPESC23 - Talk on Dataflow Architectures by Monsalve Diaz and Raskar**](https://extremecomputingtraining.anl.gov/wp-content/uploads/sites/96/2023/08/ATPESC-2023-Track-1-Talk-6-Monsalve-Diaz-Raskar-Dataflow-Architectures.pdf)

### Contribute
We encourage all contributions to this repository. Open an [issue](https://github.com/Sameeranjoshi/awesome-ai-accelerators/issues) or send a [pull request](https://github.com/Sameeranjoshi/awesome-ai-accelerators/pulls).
