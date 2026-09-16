---
title: IWAHPCE 2024
description: "International Workshop on Arm-based HPC: Practice and Experience"
layout: archive
location: "Nagoya, Japan"
period: "January, 2024"
---

The IWAHPCE 2024 workshop was held in conjunction with [HPC Asia 2024](https://sighpc.ipsj.or.jp/HPCAsia2024/) in Nagoya, Japan, January 25-27, 2024.

## Workshop Overview

This workshop aims to provide the opportunity to share the practice and experience of high-performance computing systems using the Arm architecture and their performance and applications. The last few years have seen an explosion of 64-bit Arm-based processors targeted toward server and infrastructure workloads, often specializing in a specific domain such as HPC, cloud, and machine learning. Fujitsu's A64FX and Marvell's ThunderX2 have been used in several large-scale HPC systems, and Amazon's Graviton2 has been adopted by Amazon EC2. Moreover, Amazon's Graviton3, NVIDIA Grace CPU Superchip, and SiPearl's Rhea system-on-chip have recently been announced or become accessible. Sharing the practice and experiences using these Arm-based processors contributes to advancing high-performance computing technology for newly designed systems using emerging Arm-based processors.

## Workshop Program

| Time | Speaker(s) | Title |
| :--- | :--- | :--- |
| 09:00-09:05 | Miwako Tsuji | Opening |
| 09:05-09:15 | David Lecomber, Arm | Remarks |
| 09:15-09:45 | Ryohei Okazaki | **Invited talk: Next Arm Processor FUJITSU-MONAKA and Its Technologies** |
| 09:45-10:10 | Masaki Arai, Naoto Fukumoto, Hitoshi Murai | **Introducing software pipelining for the A64FX processor into LLVM** ([slides]({{ '/files/2024/arai-llvm-a64fx.pdf' | relative_url }})) |
| 10:10-10:35 | Romain Pereira, Adrien Roussel, Miwako Tsuji, Patrick Carribault, Mitsuhisa Sato, Hitoshi Murai, Thierry Gautier | **An Overview on Mixing MPI and OpenMP Dependent Tasking on A64FX** ([slides]({{ '/files/2024/mpc-fugaku.pdf' | relative_url }})) |
| 10:35-10:50 | | Break |
| 10:50-11:15 | Filippo Barbari, Federico Ficarelli, Daniele Cesarini | **High-throughput drug discovery on the Fujitsu A64FX architecture** ([slides]({{ '/files/2024/high-throughput-drug-discovery-a64fx.pdf' | relative_url }})) |
| 11:15-11:40 | Yan Kang, Sayan Ghosh, Mahmut Kandemir, Andres Marquez | **Impact of Write-Allocate Elimination on Fujitsu A64FX** ([slides]({{ '/files/2024/write-allocate-elimination-a64fx.pdf' | relative_url }})) |
| 11:40-12:05 | Nikolay A. Simakov, Matthew D. Jones, Thomas R. Furlani, Eva Siegmann, Robert J. Harrison | **First Impressions of the NVIDIA Grace CPU Superchip and NVIDIA Grace Hopper Superchip for Scientific Workloads** ([slides]({{ '/files/2024/gracehopper-benchmarks.pdf' | relative_url }})) |
| 12:05-12:30 | Fabio Banchelli, Joan Vinyals-Ylla-Catala, Josep Pocurull, Marc Clasca, Kilian Peiro, Filippo Spiga, Marta Garcia-Gasulla | **NVIDIA Grace Superchip Early Evaluation for HPC Applications** ([slides]({{ '/files/2024/nvidia-grace-superchip-early-evaluation.pdf' | relative_url }})) |

## Topics

Topics of interest included:

- HPC Applications
- Performance Analysis, Performance Modeling & Measurement
- SVE Vectorization analysis
- Programming Models & System Software
- Networking and accelerators such as GPUs
- Artificial Intelligence and Machine Learning
- Emerging Technologies

## Important Dates

- Submission deadline: 20 November 2023 (AoE)
- Notification: 6 December 2023 (AoE)
- Camera ready: 12 December 2023 (AoE)

Submission site: EasyChair IWAHPCE 2024.

## Organizers and Program Committee

### Organizer and Workshop Chair

- Miwako Tsuji, RIKEN R-CCS
- Eva Siegmann, Stony Brook University
- Filippo Spiga, NVIDIA

### Program Committee

- Adrian Jackson, The University of Edinburgh
- Daisuke Miyamoto, Amazon Web Services Japan G.K.
- Estela Suarez, JSC
- Eva Siegmann, Stony Brook University
- Filippo Spiga, NVIDIA
- Gilles Fourestey, EPFL
- Iacopo Colonnelli, University of Turin
- Jens Domke, RIKEN R-CCS
- Luca Fedeli, CEA
- Marco Aldinucci, University of Turin
- Min Li, Huawei
- Miwako Tsuji, RIKEN R-CCS
- Shinji Sumimoto, The University of Tokyo
- Tetsuya Odajima, Fujitsu
- Tom Deakin, University of Bristol
- Wael Elwasif, ORNL
- Yuetsu Kodama, RIKEN R-CCS
