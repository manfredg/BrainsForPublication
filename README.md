# BrainsForPublication

[![Join the chat at https://gitter.im/WhitakerLab/BrainsForPublication](https://badges.gitter.im/WhitakerLab/BrainsForPublication.svg)](https://gitter.im/WhitakerLab/BrainsForPublication?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Code and documentation for the Brains for Publication proposal for the 2016 OHBM Hackathon.

## Release information
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.596845.svg)](https://doi.org/10.5281/zenodo.596845)

The BrainsForPublication repository is backed up on Zenodo and can be cited either with the **concept DOI** - [10.5281/zenodo.596845](https://doi.org/10.5281/zenodo.596845) - or the doi associated with the specific **version** you used for your analyses (which can be found by looking on the righthand side of [project's Zenodo page](https://doi.org/10.5281/zenodo.596845). For more information about the difference between concept and version DOIs check out [this blog post](https://blogs.openaire.eu/?p=2010) from the Zenodo team.

An example specific citation would be:

> Kirstie Whitaker, Michael Notter, & Sarah Morgan. (2017, December 1). BrainsForPublication (Version v0.2.1). Zenodo. http://doi.org/10.5281/zenodo.1069156

## Some pretty pictures

Want to project your 3D statistical maps through a glass brain? Check out ***[mni_glass_brain.py](https://github.com/KirstieJane/BrainsForPublication/blob/master/docs/mni_glass_brain.md)***

<img
  src="https://raw.githubusercontent.com/KirstieJane/BrainsForPublication/master/test_data/ALL_N95_Mean_cope2_thresh_zstat1_GlassBrain_ortho.png"
  align="middle"
  width=70%/>
<BR CLEAR=ALL>

Want to see where the clusters in your 3D statistical maps are? Check out ***[show_cluster_in_volume.py](https://github.com/KirstieJane/BrainsForPublication/blob/master/docs/show_cluster_in_volume.md)***

<img
  src="https://raw.githubusercontent.com/KirstieJane/BrainsForPublication/master/test_data/cluster00.png"
  align="middle"
  width=70%/>
<BR CLEAR=ALL>

Want to make beautiful images of your freesurfer results? Check out ***[pysurfer_combined.py](https://github.com/KirstieJane/BrainsForPublication/blob/master/docs/pysurfer_plot_500parcellation_surface_values.md)***

<img
  src="https://raw.githubusercontent.com/KirstieJane/BrainsForPublication/master/test_data/PLS2_with99s_pial_classic_combined.png"
  align="middle"
  width=50%/>
<BR CLEAR=ALL>

Want to make a snazzy gif of your own brain? Check out ***[subj_anat_gif.py](https://github.com/KirstieJane/BrainsForPublication/blob/master/docs/subj_anat_gif.md)***

<img
  src="https://raw.githubusercontent.com/KirstieJane/BrainsForPublication/master/test_data/KW_high_res_sagittal.gif"
  align="middle"
  width=50%/>
<BR CLEAR=ALL>

## Online processing

If you don't want to download anything, you can actually run these scripts online. Click [![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/KirstieJane/BrainsForPublication) to get started.

## The proposal in brief

**The problem**: You bust your butt figuring out how to do all the complicated neuroimaging analyses, then you write up all the steps in your methods section (whether you do it well is a project for another day) and interpret your results in your discussion section. And then to make the figures for your manuscript you make a screen shot and copy and paste the image into powerpoint before adding some labels and saving as a high res image.

**The inequality**: So many other groups have much better images than you! They have code they use to generate 3D renders of your results, or movies though the many slices, or spinning renderings! They have the expertise probably because they have developed some of the code to do "fancy" analyses and you're not sure how you can jump in with your output from a different analysis package to make their beautiful pictures.

**The solution**: At the OHBM BrainHack unconference in Lausanne we'll work together to provide examples and documentation for how to transform your 3D nifti images into various different types of figures (and movies and gifs) so your publication will entice readers to read about your work based on the lovely images you present.

**The side effect**: By providing the tools we will ensure that graduate students and other early career researchers maintain much better standards of reproducibility and replicability when presenting their work for publication.

## Contributing to the project

If you'd like to contribute to the project please read our [guidelines](https://github.com/KirstieJane/BrainsForPublication/blob/master/CONTRIBUTING.md). Please also read through our [code of conduct](https://github.com/KirstieJane/BrainsForPublication/blob/master/CODE_OF_CONDUCT.md). We want this project to be open and supportive of anyone at any level of seniority or GitHub/coding/statistical/neuroantomical/aesthetic expertise.
