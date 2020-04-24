External Data Sources
Gabriel Odom
2020-03-27


======  OVARIAN CANCER  ======

NAME: PNNL Ovarian Cancer Protein Expression
FILE NAME: "Human_TCGA_OV_PNNL_Proteome_Velos_QExact_01_28_2016_PNNL_Gene_CDAP_iTRAQ_UnsharedLogRatio_r2.cct"
DESCRIPTION: Proteome data for tumor samples log-ratio normalized (Gene-level)
SOURCE: http://linkedomics.org/data_download/TCGA-OV/

NAME: PNNL Ovarian Cancer Gene Expression (UNUSED!)
FILE NAME: "Human__TCGA_OV__UNC__RNAseq__HiSeq_RNA__01_28_2016__BI__Gene__Firehose_RSEM_log2.cct"
DESCRIPTION: RNAseq data normalized counts (Illumina HiSeq platform, Gene-level, RPKM)
SOURCE: http://linkedomics.org/data_download/TCGA-OV/

NAME: Ovarian Cancer Clinical Response
FILE NAME: "Human__TCGA_OV__MS__Clinical__Clinical__01_28_2016__BI__Clinical__Firehose.tsi"
DESCRIPTION: Clinical annotation
SOURCE: http://linkedomics.org/data_download/TCGA-OV/

NAME: gene expression RNAseq IlluminaHiSeq pancan normalized 
FILE NAME: "HiSeqV2_PANCAN"
DESCRIPTION: TCGA ovarian serous cystadenocarcinoma (OV) gene expression by RNAseq, mean-normalized (per gene) across all TCGA cohorts. Values in this dataset are generated at UCSC by combining "gene expression RNAseq" values of all TCGA cohorts, values are then mean-centered per gene, then extracting the converted data only belongs to the this cohort.For comparing data within this cohort, we recommend to use the "gene expression RNAseq" dataset. For questions regarding the gene expression of this particular cohort in relation to other types tumors, you can use the pancan normalized version of the "gene expression RNAseq" data. For comparing with data outside TCGA, we recommend using the percentile version if the non-TCGA data is normalized by percentile ranking. For more information, please see our Data FAQ: here.
SOURCE: https://xenabrowser.net/datapages/?cohort=TCGA%20Ovarian%20Cancer%20(OV)&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443



======  KIDNEY CANCER  ======

NAME: gene expression RNAseq IlluminaHiSeq 
FILE NAME: "HiSeqV2"
DESCRIPTION: The gene expression profile was measured experimentally using the Illumina HiSeq 2000 RNA Sequencing platform by the University of North Carolina TCGA genome characterization center. Level 3 data was downloaded from TCGA data coordination center. This dataset shows the gene-level transcription estimates, as in log2(x+1) transformed RSEM normalized count. Genes are mapped onto the human genome coordinates using UCSC Xena HUGO probeMap (see ID/Gene mapping link below for details). Reference to method description from University of North Carolina TCGA genome characterization center: DCC descriptionIn order to more easily view the differential expression between samples, we set the default view to center each gene or exon to zero by independently subtracting the mean of each gene or exon on the fly. Users can view the original non-normalized values by adjusting visualization settings.
SOURCE: https://xenabrowser.net/datapages/?cohort=TCGA%20Kidney%20Papillary%20Cell%20Carcinoma%20(KIRP)&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443

NAME: phenotype Phenotypes
FILE NAME: "KIRP_clinicalMatrix"
DESCRIPTION: 
SOURCE: https://xenabrowser.net/datapages/?cohort=TCGA%20Kidney%20Papillary%20Cell%20Carcinoma%20(KIRP)&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443



======  Colon Cancer  ======

NAME: Colon Cancer Clinical Response
FILE NAME: "Human__TCGA_COADREAD__MS__Clinical__Clinical__01_28_2016__BI__Clinical__Firehose.tsi"
DESCRIPTION: Clinical annotation
SOURCE: http://linkedomics.org/data_download/TCGA-COADREAD/

NAME: Colon Cancer Protein Expression
FILE NAME: "Human__TCGA_COADREAD__VU__Proteome__Velos__01_28_2016__VU__Gene__CDAP_UnsharedPrecursorArea_r2.cct"
DESCRIPTION: Proteome data for tumor samples log-ratio normalized (Gene-level)
SOURCE: http://linkedomics.org/data_download/TCGA-COADREAD/

NAME: Colon Cancer Gene Expression 
FILE NAME: "Human__TCGA_COADREAD__UNC__RNAseq__GA_RNA__01_28_2016__BI__Gene__Firehose_RSEM_log2.cct"
DESCRIPTION: RNAseq data normalized counts (Illumina GenomeAnalyzer platform, Gene-level, RPKM)
SOURCE: http://linkedomics.org/data_download/TCGA-COADREAD/
