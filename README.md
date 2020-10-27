# HW06

![Equator](python_api_challenge/A.png)

## Part I - WeatherPy
Within my python script, I have numerous steps where I stop the code to write the dataframes to a Excel or csv file to a local directory. This was done bause of how long it was taking to run the code and getting numerous API errors stating that I was making too many calls.
Additionally, I inluded logic to check if these files already exist, to make sure I do not accidentally overwrite them and have the option of just reading them instead of regenerating the data

NOTE: I am unsure why cities were bundled in groups of 50 and never used this methodology in the notebook

Saved "PNG" pictures and files can be seen out the output folder


## Part II - VacationPy

The same error preventing methods above were also applied to this part as to avoid troubleshooting and make everything streamlined.

I also tried making numerous functions to help aleanup and automate the code.