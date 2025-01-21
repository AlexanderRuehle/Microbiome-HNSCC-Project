# Microbiome-HNSCC-Project
Repository of salivary microbiome data within the Microbiome HNSCC Project.

Amplicons were prepared and sequenced using Eurofins Genomics (Constance, Germany) INVIEW Microbiome Profiling product. This included amplification with an 16S V3-V4 primer for bacterial profiling (fwd: TACGGGAGGCAGCAG and rev: CCAGGGTATCTAATCC, multiplexing using unique dual indices and sequencing on Illumina MiSeq (PE300 mode). For each amplicon, at least 60,000 reads per amplicon were performed. Bioinformatics and statistics analyses were performed using R ≥v4.1.0. The fastq files were processed using the DADA2 pipeline v1.20.0. The reads were mapped to the Silva reference database v138.1, which was formatted previously to be compatible with DADA2.

Differential abundance analysis regarding the occurrence of a locoregional recurrence within the first 60 months after (chemo)radiation was performed using both the SIAMCAT and the ALDEx2 tool. This analysis was performed for the SALIVA trial and for the combined cohort of the SALIVA and ZissTrans trials.

Contact details: Alexander Rühle, MD, MHBA; alexander.ruehle@uniklinik-freiburg.de
