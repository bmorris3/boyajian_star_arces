# KIC 8462852 (Boyajian's Star) spectroscopic follow up 
### APO/ARCES spectrum of Tabetha Boyajian's Star (KIC 8462852)
### [Brett Morris](mailto:bmmorris@uw.edu) and Jim Davenport

The notebook `kic8462852.ipynb` contains code for retrieving my [APO ARC 3.5 m/ARCES](http://www.apo.nmsu.edu/arc35m/Instruments/ARCES/) (R~31,500) spectrum of Boyajian's Star (KIC 8462852) at 2017-05-20 10:34 UTC. It downloads the wavelength-calibrated spectra from my webpage and caches them locally, then normalizes the continuum using the spectroscopic standard [BD +28 4211](https://www.eso.org/sci/observing/tools/standards/spectra/bd28d4211.html), and shifts the wavelengths to the star's rest frame. The telluric standard star [HR 7916](http://simbad.harvard.edu/simbad/sim-basic?Ident=HR7916&submit=SIMBAD+search) (spectral type F2Vn) is also included. 

If you make use of this spectrum in your research, please contact [Brett Morris](mailto:bmmorris@uw.edu) about attribution.

View a static version of the notebook [here](http://nbviewer.jupyter.org/github/bmorris3/boyajian_star_arces/blob/master/kic8462852.ipynb?refresh=True).

### Required packages: 
astropy, astroquery, specutils, numpy, scipy, matplotlib

