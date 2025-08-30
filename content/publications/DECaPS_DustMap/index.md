+++

template = "post.html"
title = "A Deep, High-Angular Resolution 3D Dust Map of the Southern Galactic Plane"
date = 2025-03-25

[extra]
abstract = "We present a deep, high-angular resolution 3D dust map of the southern Galactic plane over  239∘<ℓ<6∘ and |b|<10∘ built on photometry from the DECaPS2 survey, in combination with photometry from VVV, 2MASS, and unWISE and parallaxes from Gaia DR3 where available. To construct the map, we first infer the distance, extinction, and stellar types of over 700 million stars using the brutus stellar inference framework with a set of theoretical MIST stellar models. Our resultant 3D dust map has an angular resolution of 1′, roughly an order of magnitude finer than existing 3D dust maps and comparable to the angular resolution of the Herschel 2D dust emission maps. We detect complexes at the range of distances associated with the Sagittarius-Carina and Scutum-Centaurus arms in the fourth quadrant, as well as more distant structures out to a maximum reliable distance of d ≈ 10 kpc from the Sun. The map is sensitive up to a maximum extinction of roughly AV≈12 mag. We publicly release both the stellar catalog and the 3D dust map, the latter of which can easily be queried via the Python package dustmaps. When combined with the existing Bayestar19 3D dust map of the northern sky, the DECaPS 3D dust map fills in the missing piece of the Galactic plane, enabling extinction corrections over the entire disk |b|<10∘. Our map serves as a pathfinder for the future of 3D dust mapping in the era of LSST and Roman, targeting regimes accessible with deep optical and near-infrared photometry but often inaccessible with Gaia."

authors = ["Catherine Zucker & Andrew K Saydjari & Joshua S Speagle, + 8 others"]

links = [
    { name = "ADS", link = "https://ui.adsabs.harvard.edu/abs/2025arXiv250302657Z/abstract" },
    { name = "Query", link = "https://datalab.noirlab.edu/data-explorer?showTable=decaps_dr2.stellar_inference" },
    { name = "Zenodo", link = "https://doi.org/10.5281/zenodo.14952833" },
    { name = "Code", link = "https://doi.org/10.5281/zenodo.14915000" },
]

publication = "ApJ"
year = 2025

image = { path = "SPIRE_subfield.png", style="banner", caption = "Zoom-in of 3D dust map, integrated to 7 kpc. This is a region which also has Herschel/SPIRE imaging, which we use for validation and to show comparable angular resolution." }

+++

