# Proptool_Extension
Mustafa Alfaouri Master's Project: PropTool Extension

This is an extension made to simulate an average user propaganda score for a group of users that are viewing the same page as you. This is done using a CSV API called retool.

The APIs used in this project are the two instances of the retool api, one for the average propaganda score, and one for the political ideology of the state you live in. The other APIs are the Google Maps api and the geocoding api.

PLEASE NOTE:

You MUST generate your own API key for the google apis. This is done by making a google cloud account. you are given a free trial and they give you credit to use as well.

Some steps to help: 

-Go to cloud.google.com

-Create an account and a project

-Refer to this link to create an api key: https://developers.google.com/maps/documentation/javascript/get-api-key

One that is done, paste that API key into its indicated located within the google api fetch call in the code.

MAKE SURE TO ADD THE API KEY TO calcprop.js AND THE INLINE SCRIPT IN ptpopup.html

Retool CSV API:

The retool CSV API is open source and allows unlimited calls. If the API is not called for about 30 days, it is deleted. My datasets are included so you can just go to the website reupload the CSVs (or even just upload your own for your own use) and create new ones by following the prompts.

Just keep in mind you will have to change the URLs in each retool API call once you create the new ones.

Here is the link to retool:

https://retool.com/utilities/generate-api-from-csv

