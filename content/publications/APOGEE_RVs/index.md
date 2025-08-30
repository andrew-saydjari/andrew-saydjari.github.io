+++

template = "post.html"
title = "Improving Radial Velocities by Marginalizing over Stars and Sky: Achieving 30 m/s RV Precision for APOGEE in the Plate Era"
date = 2025-02-25

[extra]
abstract = "The radial velocity catalog from the Apache Point Observatory Galactic Evolution Experiment (APOGEE) is unique in its simultaneously large volume and high precision as a result of its decade-long survey duration, multiplexing (600 fibers), and spectral resolution of R ∼ 22,500. However, previous data reductions of APOGEE have not fully realized the potential radial velocity (RV) precision of the instrument. Here we present an RV catalog based on a new reduction of all 2.6 million visits of APOGEE DR17 and validate it against improved estimates for the theoretical RV performance. The core ideas of the new reduction are the simultaneous modeling of all components in the spectra, rather than a separate subtraction of point estimates for the sky, and a marginalization over stellar types, rather than a grid search for an optimum. We show that this catalog, when restricted to RVs measured with the same fiber, achieves noise-limited precision down to 30 m/s and delivers well-calibrated uncertainties. We also introduce a general method for calibrating fiber-to-fiber constant RV offsets and demonstrate its importance for high RV precision work in multifiber spectrographs. After calibration, we achieve 47 m/s RV precision on the combined catalog with RVs measured with different fibers. This degradation in precision relative to measurements with only a single fiber suggests that refining line spread function models should be a focus in the Sloan Digital Sky Survey V to improve the fiber-unified RV catalog."

authors = ["Andrew K Saydjari, Douglas P Finkbeiner, + 8 others"]

links = [
    { name = "ADS", link = "https://ui.adsabs.harvard.edu/abs/2025AJ....169..167S/abstract" },
    { name = "Zenodo", link = "https://doi.org/10.5281/zenodo.13251248" },
]

publication = "ApJ"
year = 2025

image = { path = "fiberOffsets.png", style="banner", caption = "Matrix visualizing the total number of visits of the same star by different fibers, which is key to the self-calibration procedure we employ." }

+++

