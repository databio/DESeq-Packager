# DESeq-Packager
From Aaron Gu

```R
DESeq_Packager(pepr, data_source, gene_names, gene_counts)
```

DESeq-Packager takes in an RNA-seq project in [PEP format](https://pepkit.github.io/docs/pepr/) and combines the data for each sample into a DESeq countDataSet structure. Best used with output from the [rnapipe](https://github.com/databio/rnapipe) pipeline.

### Required Packages

- pepr
- data.table

## Quick Start

The test_pckgr.html file contains the instructions on how to use the DESeq-Packager function with a sample data set. In a few seconds, DESeq-Packager will produce a countDataSet ready for subsequent DESeq analysis.
