# Genome-wide Profiling of H3K27me3 in Hemocytes of the Pacific White Shrimp (*Penaeus vannamei*)

## Overview

This repository is intended to hold the analysis scripts used in the study of the genome-wide H3K27me3 landscape in hemocytes of the Pacific white shrimp (*Penaeus vannamei*).

The repository is organized by analysis stage, from read mapping and peak calling to peak annotation, genomic visualization, functional enrichment, and Polycomb-related analysis.

> **Important:** This repository template was prepared from the supplied script filenames only. The script contents, programming languages, input/output paths, software versions, and parameters have not yet been inspected. Please verify and complete those details before making the repository public.

## Repository structure

| Directory | Contents |
|---|---|
| `01_mapping/` | Read/BAM mapping-related script(s) |
| `02_peak_calling/` | MACS3 peak-calling script |
| `03_peak_annotation/` | Peak annotation script |
| `04_peak_comparison/` | Peak comparison and overlap analyses |
| `05_genome_visualization/` | Genome-wide and figure-panel visualization scripts |
| `06_functional_enrichment/` | Gene Ontology (GO), GO visualization/DAG, and KEGG analyses |
| `07_polycomb_analysis/` | Polycomb-related analysis |
| `data/` | Small, shareable example or processed input files, if permitted |
| `results/` | Selected output tables and figures, if permitted |
| `docs/` | Additional methods, workflow notes, and supplementary documentation |

## Analysis workflow

The script filenames indicate the following broad workflow:

1. Mapping-related processing.
2. H3K27me3 peak calling.
3. Peak annotation.
4. Peak comparison.
5. Genome-wide visualization and figure preparation.
6. GO and KEGG functional enrichment analyses.
7. Polycomb-related analysis.

The exact order and dependencies should be confirmed by checking the commands and input/output files in each script.

## Script inventory

The original filenames supplied for this repository are listed below. Keep a copy of the original scripts until the organized versions have been checked.

| Suggested destination filename | Original filename |
|---|---|
| `01_mapping/01_mapping.txt` | `01_mapping.txt` |
| `02_peak_calling/02_peak_calling.txt` | `02_peak_calling.txt` |
| `03_peak_annotation/03_peak_annotation.txt` | `03_peak_annocation.txt` |
| `04_peak_comparison/04_peak_comparison_01.txt` | `04_peak_comparison.txt` |
| `04_peak_comparison/04_peak_comparison_02.txt` | `04_peak_comparison (2).txt` |
| `05_genome_visualization/05_genome_visualization.txt` | `05_genome_visualization.txt` |
| `05_genome_visualization/05_genome_visualization_01.txt` | `05_genome_visualization_01.txt` |
| `05_genome_visualization/05_genome_visualization_02.txt` | `05_genome_visualization_02.txt` |
| `05_genome_visualization/05_genome_visualization_03.txt` | `05_genome_visualization_03.txt` |
| `06_functional_enrichment/06_functional_enrichment_GO.txt` | `06_functional_enrichment_go.txt` |
| `06_functional_enrichment/06_functional_enrichment_GO_v2.txt` | `06_functional_enrichment_gov2.txt` |
| `06_functional_enrichment/06_functional_enrichment_KEGG.txt` | `06_functional_enrichment_KEGG.txt` |
| `07_polycomb_analysis/07_polycomb_analysis.txt` | `07_polycomb_analysis.txt` |

The two peak-comparison scripts and the four genome-visualization scripts are kept separate because their contents have not yet been compared. The two GO scripts are also kept separate; check whether one supersedes the other before deleting either.

## How to use this repository

1. Copy each original script into its suggested directory.
2. Inspect each script and identify its language (for example, Python, R, or shell).
3. If appropriate, change the extension to `.py`, `.R`, or `.sh`. Do not change the extension until the language is confirmed.
4. Replace computer-specific absolute paths with relative paths or clearly documented configuration variables.
5. Add comments describing each script's purpose, inputs, outputs, and key parameters.
6. Record software and package versions.
7. Run the workflow from a clean environment, where possible, to check reproducibility.

## Input data and large files

Do not commit private, restricted, or very large raw sequencing files (such as FASTQ or BAM files), reference genomes, or large intermediate files unless there is a clear reason and the repository's storage limits and data-sharing permissions allow it.

Instead, document:
- the public repository or accession where the data can be obtained;
- the reference genome assembly and annotation release;
- the required input filenames and expected formats;
- any preprocessing needed before running the scripts.

## Software and dependencies

A definitive dependency list cannot be provided until the scripts have been inspected. Add the relevant software names, versions, and package versions here after checking the scripts. Avoid listing software that is not actually used.

## Reproducibility checklist

- [ ] All scripts have descriptive names and correct file extensions.
- [ ] Script purpose, inputs, outputs, and parameters are documented.
- [ ] Absolute paths tied to an individual computer have been removed or explained.
- [ ] Reference genome and annotation versions are recorded.
- [ ] Software and package versions are recorded.
- [ ] Required input data are available or their download locations are documented.
- [ ] Scripts have been tested in the stated order.
- [ ] Output files and figures correspond to the manuscript.
- [ ] Data-sharing permissions and any sensitive information have been checked.

## Citation

If these scripts are used in a publication, please cite the associated research article:

**Manuscript:** Genome-wide profiling of H3K27me3 in hemocytes of the Pacific white shrimp (*Penaeus vannamei*).

Add the final author list, publication year, journal, DOI, and/or a formal citation here once available.

## License

Choose a license before public release. For example, an MIT license is commonly used for reusable code, but select a license that reflects the authors' intentions and institutional requirements. Do not assume that code or data can be openly redistributed without permission.

## Contact

Add the corresponding author's preferred institutional email address or project contact information before public release.
