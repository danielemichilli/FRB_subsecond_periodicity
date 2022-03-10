# FRB_subsecond_periodicity

Software used in preparing the paper by the CHIME/FRB Coll. "Sub-second periodicity in a fast radio burst".

- `65777546_profile_model.ipynb` was used to model the signal from FRB 20191221A after correcting for dispersion, as explained in the paper. Assuming 9 peaks forming the FRB, it estimates the amplitude, width and position (or times of arrival, ToAs) for each peak, plus a global scattering timescale.
- `Timing_analysis.ipynb` uses the FRB profiles and ToAs to calculate a periodicity.
- `Plots.ipynb` is used to produce the plots visible in the paper.
- `plots` contains the output plots included in the publication.
- `data` contains archives with numpy arrays used in the notebooks.
