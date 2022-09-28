# 360day2greg
code to convert 360-day-calendar climate model data to Gregorian taking leap years into account

# Example papermill usage (more info here ---> https://papermill.readthedocs.io/en/latest/)
papermill ./360day2greg.ipynb ./360day2greg-air_temperature-1971.ipynb -p year 1971 -r var air_temperature

# DOI
[![DOI](https://zenodo.org/badge/541836316.svg)](https://zenodo.org/badge/latestdoi/541836316)


# Data to use to verify it's working (i.e. the filename as included in the Jupyter notebook). I'll work out how to properly cite the data later using the right DOI number etc. For now the filename alone should suffice to find it on the ESGF.

tasmin_day_UKESM1-0-LL_histSST-1950HC_r1i1p1f2_gn_19500101-20141230.nc
