# Non-Emergency Medical Services Locator 

A mobile app to locate the Non-Emergency medical services nearest you. Names, location and phone number will be provided. 

Just type in your location and we'll take care of the rest. 
Made in HTML5 + PhoneGap

The entire app is contained in www/index.html (all the HTML & JS is in there), but the project will also work fine on your iOS mobile device using Cordova / PhoneGap. Just clone the repo, double-click the xcodeproj and build.

If you want to import the dataset (stores.json, at the root of this repo) into your own Usergrid / Apigee App Services account, you can do so by posting the file directly to the API. For example, with curl:

    curl -X POST -d '@stores.json' https://api.usergrid.com/<YOUR ORGANIZATION>/<YOUR APP>/<YOUR COLLECTION>


