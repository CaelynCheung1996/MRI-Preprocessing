# MRI-Preprocessing
--------------------------
## MR images preprocessing pipeline
- Inhomogeneity Correction
- Brain Extraction (Skull Stripping)
- Co-registration
- Tissue class segmentation
- Intensity Normalization

## Here are some useful tools to preprocess MR image data
------------------------------------------------------------
### Inhomogeneity Correction
- [N3](http://www.bic.mni.mcgill.ca/software/N3/)
- [N4](http://www.insight-journal.org/browse/publication/640) newer and presumably better, but in some cases N3 seems to work better. I think both tools are implemented as part of the ANTs suite of tools 
  
### Intensity Normalization
- [ITK NormalizeImageFilter](https://itk.org/Doxygen/html/classitk_1_1NormalizeImageFilter.html)

### Skull Stripping
- [BET](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/BET/UserGuide) this is part of the FSL suite that is quite straightforward to install in ubuntu. It is widely used tool, but there are a lot parameters to tune and sometimes it just fails for some reasons
- [Robex](https://www.nitrc.org/projects/robex)
- [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/fswiki/skullstrip)
- [Multi-atlas skull stripping (MASS)](https://www.nitrc.org/projects/cbica_mass) 
  related paper:https://www.sciencedirect.com/science/article/pii/S1076633213004182
- [AFNI](https://afni.nimh.nih.gov/download)

### Affine Registration
- [ANTS](http://stnava.github.io/ANTs/)
- [Fsl](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FLIRT) FLIRT 
- [FreeSurfer](https://surfer.nmr.mgh.harvard.edu/fswiki/FreeSurferCommandsRegistration)


## Some useful image viewer
- [Slicer](https://www.slicer.org/) comes with a lot of useful packages to process images, including most of those mentione above. 
- [ImageJ](https://imagej.nih.gov/ij/)
- [FslView](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslView)




  
