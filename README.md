# EDP-Aware Mapping of LLM Computation Blocks on Multicore Architectures

This project studies how the placement and mapping of large language model (LLM) computation blocks across multicore CPU architectures can affect inference performance and energy efficiency. The objective is to reason about the energy–delay product (EDP), rather than optimizing execution time alone.

> **Project outcome:** The project summary reports a **57.5% reduction in energy–delay product (EDP)** and **34.8% faster inference**. Refer to the final report and presentation linked below for the experimental setup, methodology, and detailed results.

## Motivation

LLM inference consists of computation and memory-access patterns whose performance depends on how work is mapped to the underlying hardware. A mapping that reduces latency may not necessarily minimize energy consumption. EDP-aware mapping considers both dimensions:

\[
\mathrm{EDP} = \mathrm{Energy} \times \mathrm{Execution\ Time}
\]

The project investigates mapping choices with the goal of improving this combined efficiency metric.

## Project goals

- Explore computation-block mapping strategies for LLM workloads on multicore architectures.
- Evaluate mapping decisions using execution time, energy consumption, and energy–delay product.
- Compare the proposed approach against a baseline using consistent experimental measurements.
- Understand the trade-offs between inference performance and energy efficiency.

## Reported results

| Metric | Reported improvement |
|---|---:|
| Energy–delay product (EDP) | 57.5% reduction |
| Inference time | 34.8% faster |

These figures are project-level reported outcomes. Please consult the final report for the workload, machine configuration, baseline, measurement procedure, and full result tables.

## Project documents

The repository includes the project report and presentation:

- **[Final project report (PDF)](./SysML_Final_Project_Report%20(1).pdf)** — detailed project methodology and evaluation.
- **[Final presentation (PPTX)](./SysML%20Final%20Presentation.pptx)** — project overview and final results.
- [Phase I project report (PDF)](./SysML_Project_Phase_I.pdf)
- [Graded Phase I report (PDF)](./SysML_Project_Phase_I_graded.pdf)

## Repository contents

| File | Description |
|---|---|
| `SysML_Final_Project_Report (1).pdf` | Final project report |
| `SysML Final Presentation.pptx` | Final project presentation |
| `SysML_Project_Phase_I.pdf` | Phase I report |
| `SysML_Project_Phase_I_graded.pdf` | Graded Phase I report |

## Reproducibility

The current repository snapshot contains the reports and presentation listed above. It does not currently document a runnable source-code workflow or provide verified installation and execution commands, so this README does not invent them. See the report for the implemented methodology and experimental details.

## Authors

**Anmol Gupta**  
GitHub: [@anmolguptacse](https://github.com/anmolguptacse)

---

If you use or build upon this work, please cite the project report and clearly state any changes to the experimental setup.
