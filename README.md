# HUD
Housing and Urban Development Crosswalk API functions for R
<br>

Requires API key <br>
https://www.huduser.gov/hudapi/public/register?comingfrom=1
<br>
HUD API documentation<br>
https://www.huduser.gov/portal/dataset/api.html
<br><br>
To use functions <br>
store API key in data frame <br>
<b> HUDKey<-data.frame(key=[insert key here]) </b>

<b>HUD_tract2zip() </b> -pass the FIPS code for the tract to the function. Results are resturned as a data frame. <br>
<b>HUD_zip2tract() </b> -pass a 5 digit zip code to the function. Results are returned as a data frame.
