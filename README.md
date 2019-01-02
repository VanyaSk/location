# location
Get the location of the post
We'll use reverse_geocoder library (https://pypi.org/project/reverse_geocoder/) which allows us to get different parametres like country, state, address, city etc. 
Out of our dataset we need to extract lists of latitudes and longitudes as coordinates. Then we match them as parametres to our function 'location'. And the final step is to add additional column to our DataFrame with the city. 
