# Identifying a role for _IRF5_ in Sjögren's Syndrome using Human Genetics and Multi-Omics Data 

## 🧬 Scientific Rationale 
Sjögren's Syndrome (SS) is a complex autoimmune disease that is characterized by inflammation and tissue destruction of the salivary and lacrimal glands, though many patients also experience extraglandular symptoms including synovitis and interstitial lung disease (PMID: 36914790). The etiology of the disease is complex, with a combination of genetic and environmental factors playing a role in disease risk and pahtogenesis. Twin studies show a monozygotic twin concordance rate of ~30%, indicating a modest but important role of genetics in disease risk. Prior Genome-Wide Association Studies (GWAS) have identified several key risk loci for SS, including  _IRF5-TNPO3_, _TYK2_, and _STAT4_. Post-GWAS analyses, such as colocalization, can nominate molecular mechanisms by which these loci increase risk for SS. This goal of this project is to replicate the SS association at the _IRF5-TPNO3_ locus and perform post-GWAS analyses to identify a role of IRF5 in the genetic risk for SS.  

## Project Goals 
- Quality Control (QC) a GWAS dataset for SS and replicate associations from the dataset
- Replicate GWAS QC plots: Quantile-Quantile (QQ) plot, Manhattan Plot 
- Identify genome-wide significant variants at the _IRF5-TNPO3_ locus and curate data for post-GWAS analysis 
- Perform colocalization analysis and identify SS risk variants at the _IRF5-TNPO3_ locus  driving genotype-dependent gene expression (eQTL) and protien abundance (pQTL)

## Why is this Approach Useful for Target Identification and Drug Development? 
This approach nominates specific immune pathways that are important for autoimmmune disease pathogenesis and prioritizes relevant cell-types in these pathways. In early discovery, this information can be used to inform the development of pre-clinical platforms (in vitro/in vivo/ex vivo models) to validate potential disease targets. 

## Data Availability
- Sjögren's Syndrome GWAS data is pulled from: Taylor KE, et al. Genome-Wide Association Analysis Reveals Genetic Heterogeneity of Sjögren's Syndrome According to Ancestry. Arthritis Rheumatol. 2017 Jun;69(6):1294-1305. doi: 10.1002/art.40040.
- Genetic Coordinates for the IRF5-TNPO3 Locus is from: Kottyan LC, et al. The IRF5–TNPO3 association with systemic lupus erythematosus has two components that other autoimmune disorders variably share. Hum Mol Genet. 2015 Jan 15;24(2):582-96. doi: 10.1093/hmg/ddu455.

Raw and processed data from the publication are **not distributed** in this repository due to licensing and size restrictions.  
Users must obtain data directly from the original publication or associated repositories.

## Environment
This project uses a reproducible conda environment (see `environment.yml`):

```bash
conda env create -f environment.yml
conda activate coloc_r_env
```
## License
This project’s code is released under the MIT License (see `LICENSE`).
