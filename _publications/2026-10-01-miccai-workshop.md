---
title: "Cross-Modal MRI Ovary Segmentation in Endometriosis Using Unpaired TVUS Prototype Priors"
collection: publications
category: conferences
permalink: /publications/cross-modal-ovary/
excerpt: 'Unpaired TVUS data can be used to improve the ovary segmentation in MRI images.'
date: 2026-10-01
venue: 'CAPI-WOMEN Workshop@MICCAI 2026, Oct 1'
paperurl: 'https://papers.miccai.org/miccai-2026-sat/CAPI_WOMEN_009.html'
citation: 'Kang, X., Felsner, L., Perrin, D., Liu, D., Arjomandi, J., Mathis-Ullrich, F., ... & Breininger, K. (2026). Cross-Modal MRI Ovary Segmentation in Endometriosis Using Unpaired TVUS Prototype Priors. arXiv preprint arXiv:2608.18515.'
pdf: /files/cross-modal-ovary.pdf
redirect_to: /files/cross-modal-ovary.pdf
---
Transvaginal ultrasound (TVUS) and magnetic resonance imaging (MRI) provide complementary information for endometriosis image analysis, yet existing studies mainly focus on single-modality analysis or disease classification, leaving cross-modal ovarian segmentation largely unexplored. In this work, to tackle the increased difficulty of ovary segmentation in MRI due to ovaries’ small target size and ambiguous boundaries with surrounding pelvic structures, we propose a dual branch framework for ovary segmentation across TVUS and MRI. More specifically, by adapting MedSAM3 with TVUS-derived prototype bank, we aim to align anatomically consistent feature representations across both modalities. Extensive experiments are conducted on endometriosisrelated TVUS and MRI datasets. We observe quantitative and qualitative improvements of over 5 percentage points for the proposed dualbranch approach compared with multiple state-of-the-art methods. Furthermore, our ablation study shows the contribution of individual components such as the prototype bank and the importance of warm-up pretraining in the source TVUS domain. 