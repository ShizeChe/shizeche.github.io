---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Home
---
<img src="/assets/shize.jpg" alt="Alt Text" width="200" height="auto" 
     style="float: left; margin: 0 30px 30px 0;" />

I'm a third-year Ph.D. student at the University of Pennsylvania, co-advised by [Prof. Gushu Li (Penn Quantum Systems Lab)](https://sites.google.com/view/gushuli) and [Prof. Anthony Sigillito (Penn Quantum Hardware Lab)](https://www.pennqubit.com). 

I earned B.S. in Electrical and Computer Engineering and minor in Computer Science from Carnegie Mellon University, during which I focused on digital logic design, computer architecture, and embedded systems.
<br style="clear: both;" />

## Research
I design hardware and software for controlling and simulating spin qubits in semiconductor quantum dot devices, with an emphasis on deploying them in experiments.

Currently, I’m building a custom control architecture on RFSoC that is specially optimized for the control requirements of quantum dot spin qubits. Previously, I developed a machine-learning simulation framework that can simulate device tuning from cold start, mirroring real experimental workflows, and an accelerated virtual-gate extraction algorithm that reduces the number of measurement points needed.

I also developed much of our in-house experimental software, including:
- a high-performance measurement system that decouples all the software-incurred latencies using multi-process parallelism implemented on shared memory
- a quantum compiler that maps gates to pulses, which has achieved high single-qubit fidelity in experiments (>99.9%).

## Publications
- **NeuroQD: A Learning-Based Simulation Framework for Quantum Dot Devices**  
  *Shize Che*, Junyu Zhou, Seongwoo Oh, Jonathan Hess, Noah Johnson, Mridul Pushp, Robert Spivey, Anthony Sigillito, Gushu Li.  
  [Preprint](https://arxiv.org/abs/2509.02872)

- **QTurbo: A Robust and Efficient Compiler for Analog Quantum Simulation**  
  Junyu Zhou, Yuhao Liu, *Shize Che*, Anupam Mitra, Efekan Kökcü, Ermal Rrapaj, Costin Iancu, Gushu Li.  
  *ASPLOS 2026* (to appear)

- **Fast Virtual Gate Extraction for Silicon Quantum Dot Devices**  
  *Shize Che*, Seongwoo Oh, Haoyun Qin, Yuhao Liu, Anthony Sigillito, Gushu Li.  
  *DAC 2024*

- **Fermihedral: On the Optimal Compilation for Fermion-to-Qubit Encoding**  
  Yuhao Liu, *Shize Che*, Junyu Zhou, Yunong Shi, Gushu Li.  
  *ASPLOS 2024*

- **Tartan Artibeus: A Batteryless, Computational Satellite Research Platform**  
  Bradley Denby, Emily Ruppel, Vaibhav Singh, *Shize Che*, Chad Taylor, Fayyaz Zaidi, Swarun Kumar, Zac Manchester, Brandon Lucia.  
  *SmallSat 2022*

