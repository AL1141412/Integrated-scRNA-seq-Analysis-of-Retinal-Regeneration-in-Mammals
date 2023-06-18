# Integrated-scRNA-seq-Analysis-of-Retinal-Regeneration-in-Mammals
**Files**: <br> Quality Control, Normalization, Downstream Analysis.ipynb: Performs quality control, normalization, differential expression analysis. <br> Scanorama and UMAP plotting: Integrates the datasets with Scanorama (Hie et al., 2019) and plots UMAPs of pathway genes.
<br><br>
**Python Packages & Versions:** <br>
anndata: 0.7.6 <br>
anndata2ri: 1.0.1 <br>
gprofiler: 1.0.0 <br>
matplotlib: 3.2.2 <br>
numpy: 1.19.1 <br>
pandas: **0.25.3** <br>
rpy2: 3.2.1 <br>
scanorama: 1.7.1 <br>
scanpy: 1.8.1 <br>
scipy: 1.5.0 <br>
seaborn: 0.11.1 <br>
<br><br>
**R Packages & Versions** <br>
MAST: 1.24.1 <br>
...
<br><br>
**Abstract**: <br>  &emsp;  Neurodegenerative retinal diseases cause irreversible cell damage and loss in the retina, eventually leading to blindness since mammalian retinas cannot regenerate. In contrast, zebrafish retinas regenerate after damage with Muller glial cells (MGs) through MG reprogramming, proliferation, and neurogenesis. Neurogenic transcription factors, signal transduction pathways, and chromatin modifiers play critical roles in retinal regeneration in zebrafish. <br>  <br>  &emsp;  Recent studies stimulated retinal regeneration in mouse MGs using regeneration-associated players, e.g., neurogenic transcription factor Ascl1, NMDA, Hdac inhibitor TSA, STAT inhibitor (ANTSi treatment), or YAP5SA, resulting in various degrees of cell proliferation and neurogenesis. Additionally, single-cell RNA sequencing datasets of reprogramming MGs were generated and analyzed in each study. Despite these advances, a meta-analysis of these datasets has not been reported, which is a knowledge gap that could hinder the identification of an effective strategy for retinal regeneration in mammals. <br>  <br>  &emsp;  Here, I independently performed a meta-analysis of four single-cell RNA sequencing raw datasets through data integration. I assessed the expression of the gene markers for cell proliferation and differentiation in the integrated dataset and identified differentially expressed genes (DEGs) in YAP5SA+ MGs, ANTSi MGs, and ANTSi neurons compared to control NMDA MGs. My study generated novel findings: a) YAP5SA+ MGs and ANTSi MGs reprogrammed from control NMDA MGs distinctly; b) ANTSi treatment is more effective for retinal regeneration; c) novel DEGs in these reprogramming MGs were identified; d) NFI genes and Ezh2 were still expressed in ANTSi MGs and YAP5SA+ MGs, likely affecting proper neurogenesis. My study also confirmed previous reports: a) YAP5SA+ MGs proliferated but did not generate neurons; b) ANTSi MGs proliferated and generated neurons but did not go through proper progenitor stages. Taken together, my findings provide further insight into the mechanisms underlying MG reprogramming in mice, moving us a step closer to retinal regeneration in mammals.
