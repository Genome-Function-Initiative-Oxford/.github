# Genome Function Initiative Oxford

The Genome Function Initiative Oxford brings together projects supported by the Wellcome Discovery Award. It is a collaboration between the [Hughes Group](https://www.rdm.ox.ac.uk/about/our-divisions/nuffield-division-of-clinical-laboratory-sciences/nuffield-division-of-clinical-laboratory-sciences-research/hughes-group) and the [Davies Group](https://www.imm.ox.ac.uk/research/research-groups/davies-group-genome-function-and-advanced-cellular-therapy-development) at the [MRC Weatherall Institute of Molecular Medicine (MRC WIMM)](https://www.imm.ox.ac.uk/), University of Oxford.

## Public repositories

- [ALTSPLICE](https://github.com/Genome-Function-Initiative-Oxford/ALTSPLICE) contains neural network models for predicting alternative splicing.
- [CREST-GV](https://github.com/Genome-Function-Initiative-Oxford/CREST-GV) ranks cell types for sets of genetic variants by measuring their enrichment in open chromatin profiles. It includes a collection of cell-type peak data and can also use appropriately formatted in-house data.
- [chromatin-bigwig-qc](https://github.com/Genome-Function-Initiative-Oxford/chromatin-bigwig-qc) provides machine-learning-based quality control for chromatin accessibility bigWig tracks. It scores tracks using biologically grounded genomic features.
- [EdsTools](https://github.com/Genome-Function-Initiative-Oxford/EdsTools) provides BEDTools-style utilities for combining VCF variants with genomic regions and reference sequence, including retrieving the allele sequence most represented in a peak.
- [MCCGeneSkew](https://github.com/Genome-Function-Initiative-Oxford/MCCGeneSkew) contains an analysis pipeline for detecting allele-specific skew in POINT-seq data, using phased variants to assess allelic signal in genes linked to Micro-Capture-C regions.
- [REnformer](https://github.com/Genome-Function-Initiative-Oxford/REnformer) is a deep-learning model that predicts cell-type-specific chromatin accessibility from DNA sequence. It uses transfer learning with single-cell ATAC-seq data and supports regulatory variant effect analysis.
- [REgulamentary](https://github.com/Genome-Function-Initiative-Oxford/REgulamentary) is a Python and Snakemake pipeline for genome-wide, cell-type-specific annotation of cis-regulatory elements, including enhancers, promoters and CTCF-associated regions. It is currently under revision.
- [scATAC-Pseudobulk-Pipeline](https://github.com/Genome-Function-Initiative-Oxford/scATAC-Pseudobulk-Pipeline) is a Snakemake workflow that splits single-cell ATAC-seq BAM files into pseudobulk replicates and generates indexes, bigWigs and peak calls.
- [UpStreamPipeline](https://github.com/Genome-Function-Initiative-Oxford/UpStreamPipeline) provides Snakemake workflows that turn raw sequencing data, usually FASTQ files, into formats researchers can interpret, such as bigWig files. The pipelines support reproducible analysis by wet-lab scientists without requiring prior bioinformatics experience. Available workflows include:
  - **CATCH-UP** is a high-throughput pipeline for bulk ATAC-seq and ChIP-seq data ([publication](https://doi.org/10.3791/65633), published 22 September 2023).
  - **Calibrated ChIP-seq** supports comparisons across experimental and biological conditions using rigorous normalisation.
  - **tCaptureC** analyses Capture-C and Tiled Capture-C data.
  - **Bulk RNA-seq** analyses bulk RNA-seq data using STAR.
- [Zone-Equalisation-Normalisation](https://github.com/Genome-Function-Initiative-Oxford/Zone-Equalisation-Normalisation) (ZEN-norm) is a Python package for normalising genomic signal bigWigs, reversing prior normalisation, and comparing normalisation methods.
