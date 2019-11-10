# COSPv1

COSP is the Cloud Feedback Model Intercomparison Project (CFMIP) Observation Simulator Package.

This is a fork of [CFMIP/COSPv1](https://github.com/CFMIP/COSPv1) with for
use with the Automatic Lidar and Ceilometer Framework [ALCF](https://alcf-lidar.github.io).
It includes support for a surface lidar and additional lidar wavelengths: 532 nm, 910 nm and 1064 nm.

Known issues:

- Mie scattering from ice is treated as the same as Mie scattering from liquid.
- No precipitation or aerosol simulation (not present in COSPv1).

Additional COSP configuration options:

- `surface_lidar` – Surface lidar switch (1 – surface, 0 – spaceborne)
- `lidar_wavelength` – Lidar wavelength (nm)

See the original [README](README.txt) for more information.
