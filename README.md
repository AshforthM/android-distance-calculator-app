# Android Distance Calculator Application - Java
This application calculates the distance between two locations using the Google Maps API. You can find your own location, search locations by name, draw lines between two locations and check the distance in kilometres. I used the Haversine formula to calculate the direct distance, and if you want to see the distance via car, bike, etc. I have included a button to launch the Google Maps app using the locations you've chosen.

* [Shortcut to Java Code](https://github.com/AshforthM/android-distance-calculator-app/blob/main/app/src/main/java/ca/nait/mashforth/distanceapp/MapsActivity.java)
* [Shortcut to XML](https://github.com/AshforthM/android-distance-calculator-app/blob/main/app/src/main/res/layout/activity_maps.xml)

![Image of user interface at load](https://github.com/AshforthM/android-distance-calculator-app/blob/main/images/user-interface-on-load.jpg)

## Running the app
You will need a Google Maps API key. If you don't have one, [click here to get started.](https://developers.google.com/maps/documentation/android/start#get-key)

Copy your new API key into the google_maps_api.xml string "google_maps_key". The maps fragment should now load when you launch the app.

Enter a location and hit enter, or click the my-location symbol to pin your location. Enter a second location, hit enter to pin it, and click the _FIND DISTANCE_ button to draw a polyline between the two points and display the distance in kilometres in a toast message. Clicking the polyline displays the distance again. You can clear pins and polylines by clicking the clear-locations symbol.

You can check the distance via roads and more using the Google Maps application itself. Once you've entered two locations, you can click the _USE GOOGLE_ button to launch the app directions feature with your chosen locations. You will be prompted to install Google Maps if you do not have it installed already.

![Image of user interface at find location](https://github.com/AshforthM/android-distance-calculator-app/blob/main/images/user-interface-on-find.jpg)

## Notes
* Strings are intentionally hard-coded for demonstration purposes
* Coded using API 16: android 4.1 (Jelly Bean)


## Additional Resources
* [Google Documentation - Maps SDK for Android Quickstart](https://developers.google.com/maps/documentation/android-sdk/start)
* [Android Documentation - Add Maps Guide](https://developer.android.com/training/maps)