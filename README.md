# Calculations pertaining to 4C 31.04

Here we collect Jupyter notebooks and other scripts pertaining to calculations of 4C 31.04

## Whats inside

Currently we have:
- *timescales.ipynb* : Jupyter notebook with calculations of jet head crossing timescale as functions of density ratio of jet to ambient medium, jet proper density parameter, and Lorentz factor


## Information on files

physconst.py
: This module just contains some physical constants in cgs units.
  Usage:
  ``` python
  import physconst as pc
  pressure = number_density * pc.kboltz * temperature
  ```
