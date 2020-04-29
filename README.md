# NLP Analysis of Discourse in Scientific Publications

Related Work :

**1. Analysis derived from Pubmed 200k RCT: A large-ish corpus derived from structured abstracts in clinical literature. Current state of the art.**

* Dernoncourt and Lee (2017) PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts
    * ArXiv: https://arxiv.org/abs/1710.06071
    * Github: https://github.com/Franck-Dernoncourt/pubmed-rct
* Achakulvisut et al (2019) Claim Extraction in Biomedical Publications using Deep Discourse Model and Transfer Learning
    * ArXiv: https://arxiv.org/abs/1907.00962
    * Github: https://github.com/titipata/detecting-scientific-claim

**2. Prior work from Gully + collaborators looking at clause based sequential classification of fulltext data in molecular interaction literature.**

* Dasigi et al (2017) Experiment Segmentation in Scientific Discourse as Clause-level Structured Prediction using Recurrent Neural Networks
    * ArXiv: https://arxiv.org/abs/1702.05398
    * Github: https://github.com/edvisees/sciDT
    * LSTM with attention that classifies clauses in full text paragraphs based on manually annotated data. 
* Burns et al (2017) Extracting Evidence Fragments for Distant Supervision of Molecular Interactions
    * PDF: http://ceur-ws.org/Vol-1931/paper-02.pdf 
    * Slides: http://ceur-ws.org/Vol-1931/paper-02.pdf 
    * All Data: https://doi.org/10.6084/m9.figshare.5007992.v1
    * Training / Testing Data: https://ndownloader.figshare.com/files/8437817
    * Raw Full-Text NXML files: https://ndownloader.figshare.com/files/8437805
* Burns et al (2018) Cycles of Scientific Investigation in Discourse
    * https://www.cs.cmu.edu/~hovy/papers/16Biocreative-CoSID.pdf
* Xiangci Li et  al 2019 Discourse Tagging for Scientific Evidence Extraction 
    * _incremental improvements on Dasigi et al 2017_ 
    * ArXiv: https://arxiv.org/abs/1909.04758  
    * Github: https://github.com/jacklxc/ScientificDiscourseTagging
