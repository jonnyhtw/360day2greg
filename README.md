# 360day2greg
code to convert 360-day-calendar climate model data to Gregorian taking leap years into account

# Example papermill usage (more info here ---> https://papermill.readthedocs.io/en/latest/)
papermill ./360day2greg.ipynb ./360day2greg-daily_min_temperature-1971.ipynb -p year 1971 -r var daily_min_temperature
