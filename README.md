# cab_rider

This is a RideSharingApp for Android devices, developed in Flutter and the database is created in Firebase.

Can be run on both android and iOS devices, due to Flutter language, which give my the opportunity to run on two platform without having to make a major changes in my code. App is divided into two parts: rider part and driver part. 

From rider side: 
  - User can order a car;
  - See the nearby cars available on the map;
  - See the overall route;
  - See the auto-generated price for the trip;
  - Time until the driver arrive to the indicated location;
  - Can call the driver after he pick it up the trip;

This RideSharingApp has: 
  - Advanced state management concepts with the provider package;
  - User can initiate a phone call directly from app;
  - Create, Remove, Update, Delete records in Firebase Database;
  - Can find place adress with location coordinates using Google Geocoding API;
  - User firendly interfaces for both android and iOS;
  - Creating the Push Notification messages only with Firebase (FCM - can send HttpWebRequest from a single device);
  - Google Places API which gave me the possibility to obtain informations, with which I can make predictions about a given location using some search interogations;
  - Directions API which gave me directions between multiple locations;
  - A algorith for calculating the total ride price based on: base fare, distance fare and time fare;

The app using following dart libraries:
  - Firebase_core - enable connection to multiple Firebase apps;
  - Firebase_auth - enable the authentification within app and database;
  - Firebase_database - enable database comuncation with app;
  - Connectivty - allows Flutter apps to discover network connectivty;
  - Google_maps - use Google Maps JavaScript API;
  - Outline_material_icons - for design icons;
  - Geolocator - plugin which provides easy access to platform specific location services;
  - Http - high-level functions and classes;
  - Flutter_polyline_points - decodes encoded google polyline string intro list of geo-coordinates suitable for showing route/polyline on maps;
  - Animated_text_kit - for user eye catching design;
  - Flutter_GeoFire - it is an open-source library that gives you the chance to store and query keys, based on your location. The biggest advantage is to query the keys without     giving a specific geographical area, all in real time;
  - Firebase_messaging - Flutter app can recive and process push notifications as well data messages on Android and IOS;
  - Toast - for not showing the messages only on console;
  - Intl - provide internationalization and localization facilities;


Full documentation here (Romanian language):

[Aplicatie RideSharing.pdf](https://github.com/robert1564/RideSharingApp/files/7220446/Aplicatie.RideSharing.pdf)
