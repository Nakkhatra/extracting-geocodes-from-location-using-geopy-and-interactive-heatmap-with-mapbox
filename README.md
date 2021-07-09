# extracting_geocodes_from_location_using_geopy

First, let's import all the required libraries and modules and install geopy to use it. We will geocode our locations using geopy.
Mounting the .csv file with locations from my google drive.
Splitting our locations by comma into separate columns, then stripping off the whitespaces and replacing the NaN values with empty string.
Sample example for how to get geocodes using geopy.
Making a function for using geopy for getting geocodes.
As we have three columns separated, if we do not get any result using all three, then we will look for results with the last two, if still we don't get anything, then we will look for results for the last column only. We are adding 'Bangladesh' at the end for searching for locations only in Bangladesh.
Dropping the rows for which we did not receive any geocode.
Exporting the .csv file to local machine.
Now I will use these geocodes to make a heatmap using mapbox since mapbox doesn't require any kind of API keys.
