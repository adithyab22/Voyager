# Voyager: App that helps navigate indoors
Demo app that lets you navigate indoors in CMU Heinz college by giving you real-time indoor positioning.
To run the app, install the Basic-release.apk file under Voyager/Basic-release.apk on your android phone.

Function:
This is a sample application to demonstrate the concept of indoor positioning using indooratlas SDK.
Source: http://docs.indooratlas.com/android/

This app currently has 2 activities:
1. view the floor map
2. track and locate position real-time

Summarized documentation:

ListScreen:
Has code to display the list of options to user plus to obtain the floor id and navigation details using IALocationManager.

BlueDotView:
Re-sizes the marker to help determine your exact location.

ImageViewActivity:
Obtains the floor map uploaded on indooratlas website.

HomeScreenActivity:
Displays the Home screen Voyager logo for 3 seconds before getting to see the app functionality.

MapsOverlayActivity:
Sets the path by overlaying marker over the floor map by tracking position of user. Updates navigation details.
