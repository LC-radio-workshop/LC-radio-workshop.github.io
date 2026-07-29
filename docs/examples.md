# Overview of Shared Notebooks

Here you can find a brief overview of all worked example notebooks shared via our [GitHub Org](https://github.com/LC-radio-workshop/example_notebooks). <br>
Notebooks specific to software tools, data formats, data providers, or instruments are available. Many of them demonstrate how to combine multi-instrument data.

Most of these notebooks have been prepared during the workshop, but we welcome any new contributions you might think are useful and want to share with the community. If this is the case, please submit a pull request on GitHub.

## Software-specific notebooks

- **LofarSciQLop.ipynb**: Plot radio spectra (from I-LOFAR, Solar Orbiter, PSP, STEREO, and WIND) using SciQLop.
- **pyspedas_radio_workshop_example.ipynb**: Demonstration of plotting radio spectra with PySPEDAS (using data from PSP, Solar Orbiter, STEREO, and WIND).
- **Maser_general_tutorial.ipynb**: Introduction to the maser-data package (which is part of maser4py).
- **multi_instrument_plot_ilofar_rfs_radiospectra.ipynb**: Plot radio spectra (from PSP and I-LOFAR) using the radiospectra package.

## Data-format-specific notebooks

- **example_cdf_readers.ipynb**: How to read, print, and extract data from CDF files.
- **open_FITS_example.ipynb**: How to read, print, and extract data from FITS files.

## Provider-specific notebooks

- **CDAWeb_browsing_example.ipynb**: Exploring CDAWeb with SunPy Fido

## Instrument-specific notebooks

### Parker Solar Probe (PSP)

- **FIELDS combined dynamic spectrum.ipynb**: Combine and plot Level 3 HFR and LFR data from PSP/FIELDS using pycdf. Data format: CDF.
- **FIELDS dynamic spectrum LFR (PSD).ipynb**: Plot Level 3 data from PSP/FIELDS/LFR using pycdf. Data format: CDF.
- **plot_psp.ipynb**: Plot and combine Level 2 LFR and HFR data from PSP/FIELDS, loading the data using either pycdf or pyspedas. Data format: CDF.
- **psp_analysis.ipynb**: Combine and plot Level 3 HFR and LFR data from PSP/FIELDS, downloaded using SunPy Fido and read using cdflib. Data format: CDF.

### Solar Orbiter (SolO)

- **RPW_L3_combined_spectrogram.ipynb**: Combine and plot Level 3 HFR and TNR data from Solar Orbiter/RPW using spacepy pycdf. Data format: CDF.
- **RPW_download_and_plot_L2_spectrogram_(with_maser).ipynb**: Download Level 2 data from Solar Orbiter/RPW (using SunPy Fido) and plot it after filtering noisy frequency channels.
- **RPW_hfr-tnr_combined_spectrogram.ipynb**: Download Level 2 HFR and TNR data from Solar Orbiter/RPW (using SunPy Fido) and plot the combined spectrum (after filtering the noisy channels).

### STEREO

- **STEREO.ipynb**: Download Level 3 HFR and LFR data from STEREO using SunPy Fido, and plot the combine spectrum using maser4py. Data format: CDF.
- **plot_swaves.ipynb**: Plot Level 2 data from STEREO/SWAVES, loading it using pycdf, pyspedas, or fetch_STAswaves (which can also download the data). Data format: CDF.

### WIND

- **plot_wind.ipynb**: Download, combine and plot Level 2 TNR, RAD1, and RAD2 data from WIND/WAVES using pycdf or pyspedas. Data format: CDF.

### RSTN - Learmonth

- **plot_rsnt_learmonth_data.ipynb**: Read and plot spectra from RSTN-Learmonth using radiospectra.spectrogram. Data format: SRS.

### LOFAR

- **plot_lofar.ipynb**: Read and plot (processed) data from core or international LOFAR stations. Data format: FITS.

### I-LOFAR

- **plot_ilofar.ipynb**: Read and plot data from the Irish LOFAR station. Data format: FIL.

### Nançay Decameter Array (NDA)

- **nda_plt_I_V.ipynb**: Read and plot spectral data (STOKES I and V) from NDA. Data format: FITS.
- **plot_nda.ipynb**: Read and plot spectral data from NDA. Data format: FITS.
- **test_calibration_NDA.py**: A calibration function for NDA data.

### ORFEES

- **plot_orfees.ipynb**: Plot data from ORFEES. Data format: FTS.

### OVRO-LWA

- **plot_ovsa.ipynb**: Plot OVRO-LWA / EOVSA data. Data format: FITS.

### NenuFAR

- **plot_nenufar.ipynb**: Plot data from NenuFAR. Data format: PK1.
