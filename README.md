# MaNGa Spectra Stacking
We provide the stacked spectra for a random initial sample of 25 galaxies.

The csv files provided contain the stacks of the spectra of MaNGa galaxies within an annulus region a certain distance away from the centre of the galaxy. The PlateIFU of the individual galaxies is given in the name of the file.

The first column is the wavelength, which is given in units of Angstrom. We provide masks for the sky lines, which can be found in the column named 'Masked'

The flux is given in units of: $ergÅ^{-1}s^{-1}spaxel^{-1}cm^{-2}$

Galaxies are mapped using consecutive annulus regions at different distances to the centre of the galaxy. The columns in the csv files containing information regarding the flux inside of each region are named as 'flux_radius_{}', where {} corresponds to the annulus region in question. We note that not all galaxies will have the same number of flux columns given the differences in sizes and redshifts. The inverse variance for each anulus region is also provided, named as 'ivar_radius_{}', using the same convention as flux. 

The flux is computed by adding the flux from all of the spaxels inside of that region and the inverse variance from each spaxel is combined to obtain the total ivar. 

We all wavelengths are in rest-frame and we provide a 'Redshift_file.csv' file, which contains the redshift values for the 25 galaxies. 

Any questions regarding the files provided, please contact me on: msfr1@st-andrews.ac.uk.
