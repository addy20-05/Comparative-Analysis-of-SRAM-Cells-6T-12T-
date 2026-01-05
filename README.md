# Comparative-Analysis-of-SRAM-Cells-6T-12T-
Comparative analysis of SRAM cell topologies (6T–12T) using Cadence Virtuoso, focusing on Static Noise Margin, DC power, and transient power to study stability–power trade-offs in VLSI memory design.


# SRAM Cell Analysis (6T–12T) using Cadence Virtuoso
 i)Project Overview

This repository presents a comparative analysis of SRAM cell topologies, including 6T, 7T, 8T, 10T, and 12T SRAM cells, designed and simulated using Cadence Virtuoso. The objective of this project is to study the trade-offs between stability, power consumption, and performance across different SRAM architectures under identical operating conditions.

SRAM plays a critical role in modern VLSI systems, and selecting the appropriate cell topology is essential for achieving reliable and energy-efficient memory designs.

 ii)Objectives

->Design SRAM cells (6T, 7T, 8T, 10T, 12T) at the transistor level

->Analyze Static Noise Margin (SNM) for stability evaluation

->Measure DC (static) power and transient (dynamic) power

->Compare design trade-offs between different SRAM architectures

->Identify suitable SRAM cells for low-power and high-reliability applications

 iii)Tools & Platform

->Cadence Virtuoso

->CMOS Technology (VDD = 1.8 V)

->DC and Transient Simulation Analysis

iv)SRAM Architectures Implemented

6T SRAM – Conventional and area-efficient

7T SRAM – Improved read stability with an additional transistor

8T SRAM – Decoupled read/write paths for enhanced robustness

10T SRAM – Differential read buffer for higher noise immunity

12T SRAM – Fully decoupled design offering maximum stability

v) Methodology

->SRAM schematics were designed in Cadence Virtuoso

->DC analysis was performed to obtain voltage transfer characteristics

->Butterfly curves were used to calculate Static Noise Margin (SNM)

->Transient simulations were carried out during read/write operations

->DC power and transient power were extracted

All SRAM cells were compared under identical conditions

vi) Results and Analysis
SRAM Cell	Transient Power (µW)	DC Power (µW)	NMH (V)	NML (V)
6T	77.73	4.72	0.938	0.611
7T	97.4	5.19	0.915	0.390
8T	251.7	40.69	0.825	0.611
10T	217.7	58.24	0.899	0.611
12T	296.9	55.62	1.06	0.420

vii) Inference

6T SRAM offers minimum area and power but lower noise margins

7T SRAM improves read stability with slight overhead

8T SRAM eliminates read disturb by isolating the read path

10T SRAM provides strong stability and higher noise immunity

12T SRAM achieves the highest SNM and is suitable for ultra-low-power, high-reliability applications


# Repository Structure

Design_and_Simulation

Results_and_Inference

README.md




Technology scaling to advanced nodes

Integration of error correction techniques
