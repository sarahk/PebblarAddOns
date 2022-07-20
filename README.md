# PebblarAddOns

Extract lat/lng from Pebblar's main feed as a csv dump in console

This script will add a download button to the list of buttons at the top of the map. 

Click "download"

Open the browsers console - google for info on how to do that in your browser of choice

Copy the csv dump

Make a copy of the google sheet here: https://www.labnol.org/google-maps-sheets-200817

Add a new sheet

Paste the csv contents into the new sheet

Split the text into columns

Add these forumulas:

* column L, all rows:      =GOOGLEMAPS_REVERSEGEOCODE(D1,E1)
* column M, row 2 to the bottom:     =GOOGLEMAPS_DISTANCE(L1, L2)

Sigma Icon: https://www.flaticon.com/free-icons/total Total icons created by Mayor Icons - Flaticon
