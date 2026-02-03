---
layout: dataset
title: Structural and Functional MRI
modality:
  - neurobiomarkers
keywords:
  - MRI
site:
  - Krakow
  - Aarhus
  - Brno
contact:
  - Michal Wierzchoń
participants: 303 (291 reconstructed with FreeSurfer)
summary: Multi-sequence MRI acquisition including resting-state fMRI, Multiparameter Mapping (MPM), and diffusion-weighted imaging (DWI) for comprehensive structural and functional brain characterization. Each sequence enables specific analyses yielding detailed information about connectivity and structure of the brain.
---

{% include JB/setup %}

#### Detailed description:

**Resting-state fMRI**

The resting-state data allow us to assess the functional connectivity of the brain based on a statistical correlation between patterns of activation in different regions of the brain, both on micro- and macro-scale (exemplary analysis: local homogeneity, seed-to-seed connectivity, network metrics).

Acquisition parameters:
- TR = 0.801ms
- 18 minutes of acquisition
- Eyes-open with fixation point
- High quality data resulting in reliable assessment of functional connectivity

Preprocessing:
- Pre-processed with fMRIPrep pipeline (Esteban et al., 2019)
- Denoised following the approach described in Finn et al. (2015)

**Diffusion-Weighted Imaging (DWI)**

The DWI sequence permits analysis of the anatomical connectivity of the brain by tracing axonal fibres inside the white matter (Basser, Mattiello, & LeBihan, 1994). The parameters were adjusted in a way allowing for tensor-based (DTI) and kurtosis-based (DKI) models; modalities which inform us about the tissues' microcellular properties and axonal density (Jensen, Helpern, Ramani, Lu, & Kaczynski, 2005).

Preprocessing:
- Denoised (MPPCA; Manjon et al., 2013 and Gibbs de-ringing; Kellner, Dhital, Kiselev, & Reisert)
- Distortion correction (TopUp; Andersson, Skare, & Ashburner, 2003)
- Motion correction (Eddy; Andersson & Sotiropoulos, 2016)
- Processed with FSL (Jenkinson et al., 2012) and DIPY (Garyfallidis et al., 2014) toolboxes
- MRtrix3 (Tournier et al., 2019) used to fit diffusion tensors and derive metrics such as fractional anisotropy, axial and radial diffusivity, and apparent diffusion coefficient

**Multiparameter Mapping (MPM)**

MPM is a novel technique of quantitative MRI providing rich information about the structural organisation and histological profile of the brain (Weiskopf, Edwards, Helms, Mohammadi, & Kirilina, 2021). This approach offers a variety of analysis methods, like standard voxel-based morphometry, cortical and subcortical volume, thickness, and curvature as well as non-invasive in vivo histology (iron content, myelination).

Importantly, this sequence allows for inter-scanner comparison (Weiskopf et al., 2013) which is crucial in terms of the data collected in cooperation with other centres within CA18106 and SkuldNet consortium.

MPM processing:
- Maps constructed using the hMRI toolbox (Tabelow et al., 2019)
- Synthetic T1-weighted images created using effective proton density (PD*) and longitudinal relaxation rate (R1) maps
- Cortical reconstruction using FreeSurfer (Fischl, 2012)

#### Quality Control

From the 303 scanning sessions performed, 291 subjects were reconstructed with FreeSurfer (Fischl, 2012):
- 28% were inspected by three separate trained operators to identify segmentation issues
- Remaining 72% checked by two operators
- All issues were fixed in line with software manual
- Three reconstructions failed the QA
- Two were flagged as potentially unusable due to significant structural pathology within the brain area

All data were quality controlled from the acquisition and at the end of each pre-processing step. The data conforms to BIDS (Brain Imaging Data Structure) standard (Pernet, Appelhoff, Gorgolewski et al., 2019) and has been anonymised for the purpose of open dissemination and reusability.

#### Related publications