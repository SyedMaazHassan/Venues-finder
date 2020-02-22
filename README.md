# Venues-finder
Venues finder according to the user’s price and guests range. App is intelligent enough to give all the necessary information about halls (only KARACHI - PAKISTAN's data is available right now) which fits on user's price range and guests quantity

INTRODUCTION:

“Wedding Venues Finder” is an essential app that becomes handy
when you want to see the information by sitting at your home. This
is app is capable finding suitable venues for you by considering
following details you provided:
 Nearest to the location that user provides
 Around the price range that user provides
 According to the given number of guests.

By having all these details you provide, it will find best choices for
you.

MAIN ACTIVITIES USED

Following activated have been used in our app,
Splash Screen: For the app startup.
Main Activity: Contains welcoming screen
User form: Contains the edittext boxes to get user input for initial information
(i.e location, price range and guest capacity)
User_Input_data: Catches the inputted information of the user from
user_form activity.
Details: After a particular venue is selected, the details of venue are shown in
this activity with the following options
 View
 Track
 Navigate
Adapter for Recycler View: Our venues list are implemented with recycler
view. This adapter sets the list of venues in recyclic cardview.

DEPENDENCIES:

Google Play services 17.0.0
Google Places 1.0.0
Sqlliteassethelper 2.0.1
Recyclerview 1.1.0
CardView 1.0.0
Google AndroidMaps 0.5
Android map utils 0.5
Ms Excel and Python was used to initially populate our database file
with the real wedding venues’ data.

APIs USED:

1-Google Places API:

The Places API is a service that returns information about places using HTTP
requests. Places are defined within this API as establishments, geographic
locations, or prominent points of interest.
The following place requests are available:

 Place Search returns a list of places based on a user&#39;s location or search
string.
 Place Details returns more detailed information about a specific place,
including user reviews.
 Place Autocomplete automatically fills in the name and/or address of a
place as user’s type.
 Query Autocomplete provides a query prediction service for text-based
geographic searches, returning suggested queries as user’s type.

2-Location Service and Maps SDK:

With the Maps SDK for Android, you can add maps based on Google Maps data
to your application. The API automatically handles access to Google Maps
servers, data downloading, map display, and response to map gestures. You
can also use API calls to add markers, polygons, and overlays to a basic map,
and to change the user&#39;s view of a particular map area. These objects provide
additional information for map locations, and allow user interaction with the
map. The API allows you to add these graphics to a map:

Sqlite Assest helper:

An Android helper class to manage database creation and version
management using an application&#39;s raw asset files.
This class provides developers with a simple way to ship their Android app with
an existing SQLite database (which may be pre-populated with data) and to
manage its initial creation and any upgrades required with subsequent version
releases.

PROJECT DEVELOPERS => SYED MAAZ HASSAN & MUSAB BIN JAVED
