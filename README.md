# SMLIT
Semiconductor Manufacturing Logistics-Intensity Testbed

## Overview
SMLIT is an open testbed for semiconductor FAB logistics research.
It provides standardized logistics scenarios and an OHT simulator for evaluating logistics performance under different FAB scales and workload intensities.


## Key Features

- Standardized FAB logistics scenarios
- Multiple FAB scale levels
- Multiple logistics intensity levels
- Configurable OHT simulator
- REST API-based local server interface
- Configurable OHT fleet size and rail link costs
- Logistics performance analysis

## Scenario Design

SMLIT includes three FAB scales, each with three logistics intensity levels.

| FAB Scale | Low Intensity | Medium Intensity | High Intensity |
|---|---|---|---|
| Small | small-low | small-medium | small-high |
| Medium | medium-low | medium-medium | medium-high |
| Large | large-low | large-medium | large-high |

## Simulator

The SMLIT simulator models OHT-based logistics operations in semiconductor FABs. Users can configure simulation parameters such as the number of OHTs and link costs in the OHT rail network.

## Citation

If you use SMLIT in your research, please cite our paper:

## Acknowledgment

This work was supported by Carlo Corporation; the Technology Development Program (RS-2025-24535453) funded by the Ministry of SMEs and Startups (MSS, Korea); and the Institute for Information and Communications Technology Promotion grant (RS-2026-25519431) funded by the Korean government (MSIT); 

## Contact

Seongho Cho, +82-10-4333-6345, phillip4321@ajou.ac.kr