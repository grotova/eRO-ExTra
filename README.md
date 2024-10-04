# Data description

In the [**`optical_spectra/`**](optical_spectra/) directory, you will find subdirectories for eRO-ExTra sources with optical follow-up observations.

### Each source directory contains two key files:

- A FITS file with the optical spectra, which contains: wavelength [A], flux [erg/cm2/s/A] (not dereddened)
- A plot that provides a quick visualization of the spectra in the rest-frame.

### The FITS file headers contain essential information about the observations, including:

- source name: 'SOURCE' 
- observation date: 'DATE-OBS'
- telescope: 'HIERARCH TELESCOPE'
- instrument: 'HIERARCH INSTRUMENT'
- exposure time [s]: 'EXPOSURE'
- Observer's name: 'OBSERVER'
- 'RA'        = '89.2050'
- 'DEC'       = '-21.3207'
- 'REDSHIFT'  

Special Note for WiFeS data:
For sources observed with the WiFeS instrument, the blue and red parts of the spectra are provided in separate FITS files.

For any questions, requests, or issues, feel free to contact me by email (grotova@mpe.mpg.de) or via GitHub.
