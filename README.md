# Brain Network Parcellation in R
Bundle cortical brain network/parcellation that are publicly available in a convenient form to use in R

* https://www.lead-dbs.org/helpsupport/knowledge-base/atlasesresources/cortical-atlas-parcellations-mni-space/
* aging parcellation: https://github.com/hldeepblue/aging_parcellation

## 1. Collect all the brain parcellation/atlas in different formats
* use `cifti`, `gifti` pacakges
* Gordon 333 (fs_LR)
* Power 2011 (fs_LR)
* Schafer
* Yeo?
* Chan 2014
* Han 2018


## 2. Make a function that reads in gifti/cifti of data + parcellation and outputs corr-matrix
* Look into portion of R-for-brain-network repo

## 3. How about volumes?
* Use `oro.nifti`
* MNI based atlas?
* FreeSurfer native-space based segmentation

