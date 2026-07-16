# Lab GitHub Space

Our space to share resources useful for everyone in the CDPR team.
You will find all code (projects related, and tools) here: [ICM-Frontlab-CDPR repositories](https://github.com/orgs/ICM-Frontlab-CDPR/repositories).

Please note:
- The official versioning tool at ICM is GitLab. GitHub is used here temporarily, as more people are currently familiar with it.
- This is a technical documentation: common conceptual knowledge should be stored elsewhere (coregistration - mri sequences - time series ...).
- Before to go further here, be sure to have visited [ICM FrontLab CDPR Introduction](https://icm-frontlab-cdpr.github.io/) (for a general presentation & important conceptual knowledge in the team).

## 🚀 Getting Started

- For newcomers, not yet familiar with versioning using Git and GitHub, please have a look at the [git-it](https://github.com/jlord/git-it-electron) repository — a wonderful tutorial to get started. Do not hesitate to ask for help!
- Ask for access to the specific repository you will be involved in for your project.
- Visit the [Minimal Use](minimal_use.md) guide.

## 🔬 ICM-Internal Technical Resources

### Teams
- [Bacci Lab](https://github.com/Bacci-Lab) — ICM research team.
- *add les autres équipes qui font des choses proches de nous au sein de l'ICM.*

### ICM-DSI and acquisitions plateformes
- [ICM-wiki](https://dokuwiki.icm-institute.org/) — internal documentation (really important for cluster use!).
- [HPC OnDemand](https://wiki.icm-institute.org/books/hpc-high-performance-computing/page/hpcod-hpc-ondemand) — web access to the HPC compute cluster.

## 🌐 External Technical Resources

### 🧠 Global Neurosciences

#### General Data
- [BIDS](https://bids.neuroimaging.io/index.html) — standard for organizing neuroimaging data.
- [opensource datasets](https://openneuro.org/) — open repository of shared neuroimaging datasets.
- [neuropsis NIfTI viewer](https://www.neuropsis.org/nifti_viewer.html) — browser-based NIfTI viewer.
- [ASReview](https://asreview.nl/) — AI-assisted screening for systematic reviews.

#### EEG Processing
- [EEG-101 - EEG standardization community](https://github.com/eeg101-costaction) — EEG standardization community.
- [MNE-tools for MEG and EEG](https://github.com/mne-tools/mne-python) — MEG/EEG analysis in Python.

#### MRI Processing
- [Nipy community for MRI](https://github.com/nipy) — Python community for MRI/neuroimaging.
- MNI tools: [ANTs](https://github.com/ANTsX/ANTs) — registration & normalization to standard space.
- General segmentation: [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/) — cortical surface reconstruction & parcellation; [SPM](https://www.fil.ion.ucl.ac.uk/spm/) — MRI/fMRI segmentation & statistics.

#### Classic Analysis
- [numpy](https://numpy.org/), [pandas](https://pandas.pydata.org/), etc. — array & dataframe computing.
- UX software such as [brainlife](https://brainlife.io/) — cloud platform for neuroimaging pipelines.

#### Machine Learning Analysis
- [scikit-learn](https://scikit-learn.org/) — classical machine learning.
- [torch](https://pytorch.org/) or [tensorflow](https://www.tensorflow.org/) — deep learning frameworks.
- *neuralset from Meta: first release soon for decoding methods :)*

#### Vizulisations
- [Quarto](https://quarto.org/) — reproducible scientific documents & reports.

### 🔧 Lab Specific
*add le lien vers les pipelines du labo et aussi les outils hors labo.*

We are dealing with very particular data and consequently, we use particular methods:

#### Data specificities: stroke and neurodegeneration particular tools and data
- Stroke dataset [ATLAS](https://atlas.grand-challenge.org/Data/) — public stroke lesion dataset. See also [ICPSR](https://www.icpsr.umich.edu/sites/icpsr/find-data).
- VAEs-assisted lesion-mask reconstruction with [REFLECT](https://github.com/farzad-bz/REFLECT) — [Medical-VAE weights](https://huggingface.co/farzadbz/Medical-VAE).
- [SynthStroke_CDPR](https://github.com/ICM-Frontlab-CDPR/SynthStroke_CDPR) — our lab repository.
- *Linda (see Leonore).*

#### Methods specificites: tES-related (TMS, tACS)
- [SimNIBS](https://github.com/simnibs/simnibs) — tES/TMS field simulation (and ROAST...).
- [BCBToolKit](https://github.com/chrisfoulon/BCBToolKit) — disconnectome & tractography toolkit. *add Vincent pipeline from Monica.*
- [Brainsight Neuronavigation](https://www.rogue-research.com/) — TMS neuronavigation system (Rogue Research).
- 3D neuronavigation: [headmodel_individualization](https://github.com/harmening/headmodel_individualization) — individual head-model building.

#### Methods specificites: closed-loop and BCI
- [OpenViBE](https://openvibe.inria.fr/) — real-time BCI acquisition & processing platform (documentation on site).
- [OpenBCI](https://github.com/OpenBCI) — open-source EEG / biosensing hardware and code.
- *doc Guilaume to add.*

---

PS: Also, never forget that in 99.99% the piece of code we need is already available publicly, we just have to find it.
Please feel free to update the ressources!
