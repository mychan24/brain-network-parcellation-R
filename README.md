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
* Han 2018 - 5 age groups


## 2. Make a function that reads in gifti/cifti of data + parcellation and outputs corr-matrix
* Look into portion of R-for-brain-network repo
	+ `cii2mat.R`, `gii2mat.R`
	+ Use the above function within a wrapper to use the default atlases? 


## 3. How about volumes?
* Use `oro.nifti` or `Rnifti`
* MNI based atlas?
		+ Power 2011 coordinates are in MNI, create sepheres in 333?
		+ Han 2018 has NIFTI files for 5 age groups
* FreeSurfer native-space based segmentation
		+ The function has to take in a segmentation files in mgz format? 

