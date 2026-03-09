
### Using Machine to Estimatie Galaxy Distances from Multi-Wavelength Data ###

Next-generation radio surveys with the *Square Kilometre Array*, the world's largest scientficic instrument, will detect millions of galaxies which host supermassive black holes. Extracting cosmological information from these surveys requires estimating the distance (redshift) of each galaxy, but traditional optical spectroscopy cannot scale to datasets of this size.

This project explores data-driven approaches to redshift estimation using multi-wavelength photometry and spectral energy distributions (SEDs).

**Key ideas**

-  Combine radio detections with optical, UV and near-infrared photometry

-  Use machine-learning approaches to infer galaxy distances when spectroscopy is unavailable

-  Scale to millions of objects expected from upcoming Square Kilometre Array surveys

**Why this matters**

Optical spectroscopy is expensive and biased toward brighter galaxies. Photometric measurements can be obtained much deeper and for far larger samples, enabling distance estimates for galaxies that would otherwise remain unusable for cosmological studies. <br>

Knowing the distances of such a large population of galaxies, will allow us to probe back billion of years, close to the birth of the Universe, and can yield the density of baryonic (normal) matter thus constraining dark matter and energy models. 

![](https://raw.githubusercontent.com/steviecurran/quasar-distances/refs/heads/main/desiQSO_x_sdssQSO_trun.csv_desiQSO_x_sdssQSO_trun_kNN.png)

**Approach**

The pipeline combines photometric measurements across multiple wavelengths to estimate redshift using machine-learning models.

Techniques explored include:

- k-Nearest neighbours
- Decision trees
- Random forests
- Neural networks
- Feature engineering from spectral energy distributions (SEDs)

These models are trained on galaxies with known spectroscopic redshifts and then applied to much larger photometric samples.

See also *[NASA ADS](https://ui.adsabs.harvard.edu/abs/2021MNRAS.503.2639C/abstract)*,
