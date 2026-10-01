# GGRV — Grupo de Gerência de Recursos e Virtualização · PUCRS

Research group on resource management and virtualization at PUCRS. Our work focuses on **performance interference** in consolidated cloud environments: how to measure it, classify it, and schedule around it, plus scalable graph algorithms.

Publications: https://www.inf.pucrs.br/~derose/code/code/publicacoes.html

## Projects

### IntP — interference profiling
Measuring, in short windows, how co-located workloads steal CPU, LLC, memory bandwidth, block I/O and network from each other. Topic: [`intp-family`](https://github.com/orgs/GGRV-PUCRS/repositories?q=topic%3Aintp-family)

| Repository | Description |
|---|---|
| [across-intp](https://github.com/GGRV-PUCRS/across-intp) | Comparison of SystemTap, procfs, bpftrace and eBPF/CO-RE implementations (Master's dissertation, PPGCC/PUCRS) |
| [original-intp](https://github.com/GGRV-PUCRS/original-intp) | Upstream SystemTap-based IntP, kept for reference |

### Interference-aware cloud scheduling
Simulation, classification and placement of workloads based on interference. Topic: [`interference-aware-cloud`](https://github.com/orgs/GGRV-PUCRS/repositories?q=topic%3Ainterference-aware-cloud)

| Repository | Description |
|---|---|
| [CloudSimInterference](https://github.com/GGRV-PUCRS/CloudSimInterference) | CloudSim/ContainerCloudSim extension for interference-aware scheduling (IADA) |
| [interference-classifier](https://github.com/GGRV-PUCRS/interference-classifier) | ML-driven interference classification for dynamic scheduling |
| [ciapa](https://github.com/GGRV-PUCRS/ciapa) | Capacity, Interference and Affinity aware Placement Algorithm |
| [node-tiers](https://github.com/GGRV-PUCRS/node-tiers) | Configurable multi-tier benchmark based on stress-ng |

### Dynamic community detection
| Repository | Description |
|---|---|
| [DynaMap](https://github.com/GGRV-PUCRS/DynaMap) | Dynamic community detection using the Map Equation |

## Browse by topic

- [`ggrv-pucrs`](https://github.com/orgs/GGRV-PUCRS/repositories?q=topic%3Aggrv-pucrs) — everything from the group
- [`intp-family`](https://github.com/orgs/GGRV-PUCRS/repositories?q=topic%3Aintp-family) — IntP and its derivatives
- [`interference-aware-cloud`](https://github.com/orgs/GGRV-PUCRS/repositories?q=topic%3Ainterference-aware-cloud) — interference-aware scheduling line
