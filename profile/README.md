# Genome Function Initiative Oxford

**Understanding genome function through collaborative research and open computational tools.**

A collaboration between the [Hughes Group](https://www.rdm.ox.ac.uk/about/our-divisions/nuffield-division-of-clinical-laboratory-sciences/nuffield-division-of-clinical-laboratory-sciences-research/hughes-group) and the [Davies Group](https://www.imm.ox.ac.uk/research/research-groups/davies-group-genome-function-and-advanced-cellular-therapy-development), based at the [MRC Weatherall Institute of Molecular Medicine (MRC WIMM)](https://www.imm.ox.ac.uk/), University of Oxford. Our projects are supported by the Wellcome Discovery Award.

---

## Research software

Tools and workflows developed by our group for reproducible genomic analysis.

### Sequencing workflows

- **[UpStreamPipeline](https://github.com/Genome-Function-Initiative-Oxford/UpStreamPipeline)** — Snakemake workflows that take raw sequencing data, usually FASTQ files, to interpretable outputs such as bigWig tracks. Built to help wet-lab researchers run reproducible analyses without needing prior bioinformatics experience.

  - **CATCH-UP** — High-throughput bulk ATAC-seq and ChIP-seq analysis. [Publication](https://doi.org/10.3791/65633) · JoVE, 22 September 2023.
  - **Calibrated ChIP-seq** — Supports rigorous comparisons across experimental and biological conditions.
  - **tCaptureC** — Analyses Capture-C and Tiled Capture-C data.
  - **Bulk RNA-seq** — Analyses bulk RNA-seq data using STAR.
- **[scATAC-Pseudobulk-Pipeline](https://github.com/Genome-Function-Initiative-Oxford/scATAC-Pseudobulk-Pipeline)** — Splits single-cell ATAC-seq BAM files into pseudobulk replicates, then generates indexes, bigWigs and peak calls.

### Regulatory genomics and variant interpretation

- **[ALTSPLICE](https://github.com/Genome-Function-Initiative-Oxford/ALTSPLICE)** — Neural network models for predicting alternative splicing. Related publication: [Structural and non-coding variants increase the diagnostic yield of clinical whole genome sequencing for rare diseases](https://doi.org/10.1186/s13073-023-01240-0).
- **[CREST-GV](https://github.com/Genome-Function-Initiative-Oxford/CREST-GV)** — Ranks cell types for genetic variants by measuring enrichment in open chromatin profiles. Includes cell-type peak data and supports appropriately formatted in-house data. Preprint: [CREST-GV: Cell types Ranking and Enrichment Score for selecTive Genetic Variants](https://doi.org/10.1101/2025.07.29.25332311).
- **[MCCGeneSkew](https://github.com/Genome-Function-Initiative-Oxford/MCCGeneSkew)** — Detects allele-specific skew in POINT-seq data, using phased variants to assess allelic signal in genes linked to Micro-Capture-C regions. Related preprint: [Machine Learning and Micro Capture-C resolve GWAS associations revealing endothelial stress pathways in Coronary Artery Disease](https://doi.org/10.64898/2025.12.18.25342557).
- **[REnformer](https://github.com/Genome-Function-Initiative-Oxford/REnformer)** — Predicts cell-type-specific chromatin accessibility from DNA sequence using deep learning and single-cell ATAC-seq data. Supports regulatory variant effect analysis. [Publication](https://doi.org/10.1109/CIBCB66090.2025.11177081).
- **[REgulamentary](https://github.com/Genome-Function-Initiative-Oxford/REgulamentary)** — Python and Snakemake pipeline for genome-wide, cell-type-specific annotation of cis-regulatory elements, including enhancers, promoters and CTCF-associated regions. Currently under revision. [Publication](https://doi.org/10.1093/bioadv/vbag079).

### Signal quality and normalisation

- **[chromatin-bigwig-qc](https://github.com/Genome-Function-Initiative-Oxford/chromatin-bigwig-qc)** — Machine-learning quality control for chromatin accessibility bigWig tracks, with scores based on biologically grounded genomic features. Preprint: [Learning quality scores for chromatin accessibility bigWig tracks using Machine Learning](https://doi.org/10.64898/2026.06.05.730303).
- **[Zone-Equalisation-Normalisation](https://github.com/Genome-Function-Initiative-Oxford/Zone-Equalisation-Normalisation)** (**ZEN-norm**) — Python package for normalising genomic signal bigWigs, reversing prior normalisation and comparing methods. [Publication](https://doi.org/10.1093/bioinformatics/btag622).

### Genomic utilities

- **[EdsTools](https://github.com/Genome-Function-Initiative-Oxford/EdsTools)** — BEDTools-style utilities for working with VCF and BED files, including retrieving the allele sequence most represented in a peak.
