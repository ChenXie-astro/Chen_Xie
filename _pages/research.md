---
layout: archive
title: "My research activities"
permalink: /research/
author_profile: true
# header:
  # og_image: "research/ecdf.png"
---

Follow the links below to jump to the latest results.
* [JWST/NIRSpec observation of debris disk](#JWST/NIRSpec-observation-of-debris-disk)

<!-- * [Disk imaging with IFS using RDI-DIsNMF](#Disk-imaging-with-IFS-using-RDI-DIsNMF) -->

* [First dynamical detection of a companion driving a spiral arm](#first-dynamical-detection-of-a-companion-driving-a-spiral-arm)


* [Performance of reference-star differential imaging on SPHERE](#performance-of-reference-star-differential-imaging-on-sphere)


* [Studying stellar jet in HD 163296 with MUSE](#studying-stellar-jet-in-hd-163296-with-muse)


* [Searching for proto-planets with MUSE](#searching-for-proto-planets-with-muse)


* [Discovery of two new radio halos](#discovery-of-two-new-radio-halos)


* [First confirmation of the AGN activity among GRB host galaxies](#first-confirmation-of-the-agn-activity-among-grb-host-galaxies)


<!-- * [Custom foo description](#foo) -->



<!-- <span style="color:gary">some *blue* text</span>. -->

<span style="color:gray"><font size="6">Postdoc Research (2023-)</font></span>

# JWST/NIRSpec IFU observation of debris disks
(Ongoing project, check out my talk at the Dust Devils workshop)



<span style="color:gray"><font size="6">PhD Research (2020-2023)</font></span>

Highlights from my PhD projects:
* I thoroughly studied the performance of reference-star differential imaging (RDI) on VLT/SPHERE. On average, RDI can outperform angular differential imaging (ADI) in detecting point sources at short angular separations (<0.4"), with an average gain of ~0.8 mag at 0.15". In disk imaging, RDI can reveal more disk features and provide a more robust recovery of the disk morphology.

* The RDI reference library I built can be easily implemented into legacy or future SPHERE observations without additional costs, achieving better performance than that of ADI.

* The RDI-DIsNMF technique is optimized for the direct imaging of circumstellar disks in total intensity by minimizing self-subtraction and overfitting that has plagued previous methods. As a result, RDI-DIsNMF provides accurate photometry and morphology of the disk. 

* I provided the first dynamical detection of a companion driving a spiral arm in a protoplanetary disk


<!-- # Disk imaging with IFS using RDI-DIsNMF
(Ongoing project) -->


# First dynamical detection of a companion driving a spiral arm 
(Xie, C. et al. 2023; [A&A](https://www.aanda.org/articles/aa/pdf/2023/07/aa46305-23.pdf), [arXiv](https://arxiv.org/pdf/2306.09279.pdf), [ADS](https://ui.adsabs.harvard.edu/abs/2023A%26A...675L...1X/abstract))

I reported multi-epoch observations of the binary system HD 100453 using VLT/SPHERE. By effectively removing starlight contamination and recovering the spiral features, I measured the motion of the spirals over a span of 4 yr for dynamical motion analysis. The spiral pattern motion is consistent with the orbital motion of the eccentric companion. This direct observational evidence supports the long-standing theory on the origin of spiral features in protoplanetary disks. With the pattern motion of companion-driven spirals being independent of companion mass, it is feasible to search for hidden spiral-arm-driving planets that are beyond the detection of existing ground-based high-contrast imagers.

The RDI-DIsNMF technique enables the accurate recovery of the disk morphology and facilitates the dynamical analysis of the spiral and companion motions in HD100453. 

![HD100453](/images/research/HD100453.png)


# Reference-star differential imaging on SPHERE
(Xie, C. et al. 2022; [A&A](https://www.aanda.org/articles/aa/pdf/forth/aa43379-22.pdf), [arXiv](https://arxiv.org/pdf/2208.07915.pdf), [ADS](https://ui.adsabs.harvard.edu/abs/2022arXiv220807915X/abstract))

I characterized the performance of reference-star differential imaging (RDI) on SPHERE/IRDIS data in direct imaging of exoplanets and disks. I made use of all the archival data in H23 obtained by SPHERE/IRDIS in the past five years to build a master reference library and perform RDI. In the point-source detection, RDI can outperform ADI at small angular separations (<0.4") with a gain of ~0.8 mag over ADI at 0.15" separation for observations under median conditions. In disk imaging, RDI can reveal more disk features and provide a more robust recovery of the disk morphology. We resolve [33 disks](/images/disk_gallery/disk_all_SB_paper.png) in total intensity (19 planet-forming disks and 14 debris disks). 


# Studying stellar jet in HD 163296 with MUSE 
(Xie, C. et al. 2021; [A&A](https://www.aanda.org/articles/aa/pdf/2021/06/aa40602-21.pdf), [arXiv](https://arxiv.org/pdf/2106.01661.pdf), [ADS](https://ui.adsabs.harvard.edu/abs/2021A%26A...650L...6X/abstract))


I led the study of the stellar jet in HD 163296 with VLT/MUSE. It was the first attempt to use the MUSE narrow field mode observation to study stellar jets. I applied the modified high-resolution spectral differential imaging (HRSDI) technique that I developed in [prveious work](https://ui.adsabs.harvard.edu/abs/2020A%26A...644A.149X/abstract) to image the stellar jet. I demonstrated the capability of MUSE in imaging extended sources, such as stellar jets.

One of the science highlights is that we constrain the jet launching region to be less than 1 au in radius, thanks to the high spatial resolution of MUSE.

![stellar_jet](/images/research/SN_v_map_jet_paper.png)



 <!-- <font size="6">Marster Research (2018-2020)</font> -->
<span style="color:gray"><font size="6">Master Research (2018-2020)</font></span>

# Searching for proto-planets with MUSE
(Xie, C. et al. 2020; [A&A](https://www.aanda.org/articles/aa/pdf/2020/12/aa38242-20.pdf), [arXiv](https://arxiv.org/pdf/2011.08043.pdf), [ADS](https://ui.adsabs.harvard.edu/abs/2020A%26A...644A.149X/abstract))

I conducted a small search for proto-planets around 5 stars with VLT/MUSE. Unfortunately, we didn't find any new planet except for PDS 70 b and c. MUSE has some instrumental issues that limit the contrast that appear in cases with strong point sources. I modified the HRSDI technique to better handle the instrumental artifacts and improve the contrast. 

The HRSDI technique when applied to MUSE data allows us to reach the photon noise limit at small separations (i.e., <0.5"; see the right plane below). With the combination of high-contrast imaging and medium spectral resolution, MUSE can achieve fainter detection limits in apparent line flux than SPHERE/ZIMPOL by a factor of 5 (see, the left plane below).

![muse_paper](/images/research/muse_paper.png)



# Discovery of two new radio halos
(Xie, C. et al. 2020; [A&A](https://www.aanda.org/articles/aa/pdf/2020/04/aa36953-19.pdf), [arXiv](https://arxiv.org/pdf/2001.04725.pdf), [ADS](https://ui.adsabs.harvard.edu/abs/2020A%26A...636A...3X/abstract))

We reported the discovery of two new radio halos in the frontier fields clusters Abell S1063 and Abell 370. I processed and analyzed the radio data obtained by VLA and GMRT in 325 MHz, 1.5 GHz, and 3 GHz. Besides the discovery, I also found the radio halo in Abell S1063 has spectral steeping, which suggests the formation of the radio halo is caused by the turbulent reacceleration.

To further confirm the spectral steepening, I led the follow-up observations (~16 hours) with VLA and GMRT to increase the wavelength coverage from 0.15 to 6 GHz.

![radio_halo](/images/research/radio_halo_paper.png)




 <!-- <font size="6">Undergraduate Research</font> -->
<span style="color:gray"><font size="6">Undergraduate Research</font></span>

# First confirmation of the AGN activity among GRB host galaxies 
(Xie, C. et al. 2016; [ApJL](https://iopscience.iop.org/article/10.3847/2041-8205/824/2/L17/pdf), [arXiv](https://arxiv.org/pdf/1606.00140.pdf), [ADS](https://ui.adsabs.harvard.edu/abs/2016ApJ...824L..17X/abstract))

![GRB_hosts](/images/research/GRB_hosts.png)
 

<!-- # Foo -->





> Last updated around Augest 2022.