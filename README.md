# Cherry-blossom-2025-comp

### First step:

In order to reproduce fully (as if you just want to see final results feel free to just run "prediction_maker.qmd") you will need to create your own noaa token, which can be done at (https://www.ncdc.noaa.gov/cdo-web/token) and then place it in a text file called "noaa-token.txt" (Not in the Data folder, put it in the main folder with all the other .qmd files) 

Make sure you have a stable internet connection.

Of course make sure you have the required packages.

### Generate Variables:

Start with the quatro file "noaa-weather-data-collect" This will allow you to genreate the variables required for model building and prediction

### Model Building:

Go through all quatro files that end with "-model-builder.qmd". NOTE: due to the large amount of models training due to cross-validation and hyperparameter tuning, expect a long run time (~2 hours) for each qmd. (Note that the required parameter data is already stored within the /Data folder so if you just want to see the final product you do not need to run these qmd files).

### Predictions

Go through "prediction_maker.qmd" to generate predictions for each location as well as prediction intervals (although not required for the 2025 competition).
