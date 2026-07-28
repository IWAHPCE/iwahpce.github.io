---
title: IWAHPCE 2023
description: "International Workshop on Arm-based HPC: Practice and Experience"
layout: archive
location: "Singapore"
period: "February, 2023"
---

The IWAHPCE 2023 workshop was held in conjunction with [HPC Asia 2023](https://www.sc-asia.org/hpc-asia-2023/) and SupercomputingAsia 2023 in Singapore, February 27-March 2, 2023.

## Workshop Overview

This workshop aims to provide the opportunity to share the practice and experience of high-performance computing systems using the Arm architecture and their performance and applications. The last few years have seen an explosion of 64-bit Arm-based processors targeted toward server and infrastructure workloads, often specializing in a specific domain such as HPC, cloud, and machine learning. Fujitsu's A64FX and Marvell's ThunderX2 have been used in several large-scale HPC systems, and Amazon's Graviton2 has been adopted by Amazon EC2. Moreover, Amazon's Graviton3, NVIDIA Grace CPU Superchip, and SiPearl's Rhea system-on-chip have recently been announced or become accessible. Sharing the practice and experiences using these Arm-based processors contributes to advancing high-performance computing technology for newly designed systems using emerging Arm-based processors.

This workshop was a proceedings-based workshop related to the series of workshops organized at ISC, SC, and the Arm Research Summit by groups including the [Arm HPC User Group (AHUG)](https://a-hug.org/).

## Workshop Program

**February 27, 2023**

| Time | Speaker(s) | Title |
| :--- | :--- | :--- |
| 08:30-08:35 | Miwako Tsuji, Mitsuhisa Sato | Opening remarks |
| 08:35-09:08 | Simon McIntosh-Smith | **Keynote: Experiences from 4 years of running a production Arm-based supercomputer** ([slides]({{ '/files/2023/mcintosh-smith.pdf' | relative_url }})) |
| 09:08-09:38 | Smeet Chheda, Anthony Curtis, Eva Siegmann, Barbara Chapman | **Performance Study on CPU based Machine Learning with PyTorch** ([slides]({{ '/files/2023/chheda-pytorch.pptx' | relative_url }})) |
| 09:38-10:08 | Wael Elwasif, William Godoy, Nick Hagerty, J. Austin Harris, Oscar Hernandez, Joo Balint, Kent Paul, Damien Lebrun-Grandie, Elijah MacCarthy, Veronica Melesse Vergara, Bronson Messer, Ross Miller, Sarp Oral, Sergei Bastrakov, Michael Bussmann, Alexander Debus, Klaus Steiniger, Jan Stephan, Rene Widera, Spencer Bryngelson, Henry Le Berre, Anand Radhakrishnan, Jeffrey Young, Sunita Chandrasekaran, Florina Ciorba, Osman Simsek, Kate Clark, Filippo Spiga, Jeff Hammond, Stone John, David Hardy, Sebastian Keller, Jean-Guillaume Piccinali, Christian Trott | **Application Experiences on a GPU-Accelerated Arm-based HPC Testbed** ([slides]({{ '/files/2023/wael-elwasif.pdf' | relative_url }})) |
| 10:08-10:30 | Fuyuka Yamada, Kentaro Kawakami, Kouji Kurihara, Kazuhito Matsuda, Tsuguchika Tabaru | **Optimization of NumPy Transcendental Functions for Arm SVE** ([slides]({{ '/files/2023/yamada-numpy-sve.pdf' | relative_url }})) |
| 10:30-11:00 | | Break |
| 11:00-11:22 | Issaku Kanamori, Keigo Nitadori, Hideo Matsufuru | **Wilson matrix kernel for lattice QCD on A64FX architecture** ([slides]({{ '/files/2023/kanamori-lattice-qcd.pdf' | relative_url }})) |
| 11:22-11:44 | Michael Hennecke, Motohiko Matsuda, Masahiro Nakao | **Evaluating DAOS Storage on ARM64 Clients** ([slides]({{ '/files/2023/hennecke-daos-arm64.pdf' | relative_url }})) |
| 11:44-12:06 | Mitsuhisa Sato, Miwako Tsuji | **OpenACC Execution Models for Manycore Processor with ARM** ([slides]({{ '/files/2023/sato-openacc-arm.pdf' | relative_url }})) |
| 12:06-12:28 | Nikolay A. Simakov, Robert L. Deleon, Joseph P. White, Matthew D. Jones, Thomas R. Furlani, Eva Siegmann, Robert J. Harrison | **Are we ready for broader adoption of ARM in the HPC community: Performance and Energy Efficiency Analysis of Benchmarks and Applications Executed on High-End ARM Systems** |
| 12:28-12:30 | | Closing remarks |

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

- Abstract and paper submission due: 19 December 2022
- Paper notification: 13 January 2023
- Final camera-ready paper submission due: 18 January 2023

Submission site: [EasyChair IWAHPCE 2023](https://easychair.org/cfp/IWAHPCE2023).

## Organizers and Program Committee

### Organizer and Workshop Chair

- Miwako Tsuji, RIKEN R-CCS
- Mitsuhisa Sato, RIKEN R-CCS

### Program Committee

- Jens Domke, RIKEN R-CCS
- Adrian Jackson, The University of Edinburgh
- Aaron Jezghani, Georgia Tech
- Yuetsu Kodama, RIKEN R-CCS
- Luca Fedeli, CEA
- Miquel Moreto, UPC-BSC
- Marc Perache, CEA
- Eva Siegmann, Stony Brook University

Questions about submissions were directed to iwahpce2023oc@ml.riken.jp.

## Original Repository

[arm-hpc-user-group/iwahpce-2023](https://github.com/arm-hpc-user-group/iwahpce-2023)
