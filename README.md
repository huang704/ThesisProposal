## Ph.D. Thesis Proposal for Ting Huang

**Email:** huang.tin@northeastern

**Advisor:** [Olga Vitek](https://www.khoury.northeastern.edu/people/olga-vitek/)  

**Thesis Committee:** 
- Olga Vitek (Advisor, Northeastern University): [https://www.khoury.northeastern.edu/people/olga-vitek/](https://www.khoury.northeastern.edu/people/olga-vitek/)
- Predrag Radivojac (Internal committee member, Northeastern University):[https://www.ccs.neu.edu/home/radivojac/](https://www.ccs.neu.edu/home/radivojac/)
- Kylie Bemis (Internal committee member, Northeastern University):[https://kuwisdelu.github.io/](https://kuwisdelu.github.io/)
- Nuno Bandeira (External committee member, University of California, San Diego):[https://cseweb.ucsd.edu/~nbandeir/](https://cseweb.ucsd.edu/~nbandeir/)

**Thesis proposal:** 
- [Proposal](proposal.pdf)
- Abstract: Tandem mass tag (TMT)  is a multiplexing technology widely-used in proteomic research. It enables relative quantification of proteins from multiple biological samples in a single mass spectrometry run with high efficiency and high throughput. However, experiments often require more biological replicates or conditions than can be accommodated by a single run, and involve multiple TMT mixtures and multiple runs. Such larger-scale experiments combine sources of biological and technical variation in patterns that are complex, unique to TMT-based workflows, and challenging for the downstream statistical analysis. These patterns cannot be adequately characterized by statistical methods designed for other technologies, such as label-free proteomics or transcriptomics. Therefore, there is a need for flexible statistical tools, which reflect diverse and complex designs of large-scale TMT experiments, and have good statistical performance.

We first develop a general statistical approach for relative protein quantification in mass spectrometry-based experiments with TMT labeling and group comparison design. It is applicable to experiments with multiple conditions, multiple biological replicate runs, multiple technical replicate runs, and unbalanced designs. It is based on a flexible family of linear mixed-effects models that handle complex patterns of technical artifacts and missing values. The approach is implemented in {\it MSstatsTMT}, a freely available open-source R/Bioconductor package compatible with data processing tools such as Proteome Discoverer, MaxQuant, OpenMS and SpectroMine. We propose to extend the existing approach for group comparison design to more complex designs. In particular, we are interested in the repeated measures designs where protein abundance in a same subject is repeatedly measured for each condition in the TMT experiment. 

**A Statement from the Advisor:**  

