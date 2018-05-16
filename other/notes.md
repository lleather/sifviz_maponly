potential package for reading and displaying NetCDF data?: https://github.com/Reading-eScience-Centre/ncwms

https://github.com/consbio/ncdjango
https://github.com/consbio/clover
https://github.com/mapbox/rasterio

READ AND EXPLORE NETCDF FILES - JS
https://github.com/cheminfo-js/netcdfjs

#TO do:

##Design:
- choose color scheme
    range([#FEEB97, #4FB783, #409D9B, #034561]
    [#FFF1BC, #7DC383, #6A9C78, #446E5C]
    #EEEEEE#4ECCA3#393E46#23293

- choose font family
    <link href="https://fonts.googleapis.com/css?family=Montserrat|Roboto|Rubik|Open+Sans" rel="stylesheet">

    font-family: 'Roboto', sans-serif;
    font-family: 'Montserrat', sans-serif;
    font-family: 'Rubik', sans-serif;
    font-family: 'Open Sans', sans-serif;

- choose favicon
<link rel="icon" href="img/greendiamond.ico" type="image/x-icon"/>


- raster processing: make NAs 0 when they overlap with land; retain NAs as -999 when they're over water