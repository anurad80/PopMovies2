# Movie Corner

**[IMPORTANT: for the Application to work, Please enter the APIkey in the gradle file in the app folder in the place of 
the string '&lt;api_key&gt;'. Add api key within double quotes.]**

Searching for Movies? This Android app makes it easy to discover, search movies and mark them to your favorites.  Also make your device lively with added features like notifications for movies releasing this week, widget for box office top ten, setting favorite movie poster as wallpaper
This Application opens a grid arrangement of the movieposters according to the selected sort-order (from Settings menu).
The order can be most-popular or highest-rated or favorites. When a poster is clicked the details of the coresponding movie is displayed. Each movies shows original title, movie poster, plot synopsis, user rating, release date, trailers and user reviews. 
It is compatible with all devices running on Ice Cream Sandwich and higher (API Level 15).

This app fetches data from themoviedb API, but is not endorsed or certified by TMDb. Favorited movies will be saved to the database (implemented using content provider), and will be viewable offline. However, As internet connectivity is required to establish connection to the movie database, the most popular and highest rated movies will not load without internet.
Features:
- Movies search based on Popularity or Rating
- Add/remove movie as favorite
- Optimized app experience for tablet
*  widget for topten box office hits to Home screen
*  Notifications for movies to be released this week for a chosen favorite genre
*  Set favorite movie poster as device wallpaper (using MUZEI FOR WALLPAPER app)
- Watch trailer on Youtube
- Share trailers with friends
- View user reviews
- Image descriptions for accessibility readers
- RTL support

Implements: _SyncAdapter; AsyncHandler; NavigationManager; Tablayout; Searchwidget; widgetProvider; NotificationManager; SQLite database with custom Content Provider; CursorLoader; Preference Manager; Share Action Provider; FragmentManager; Intent; Shared Preferences; Activity lifecycle; HTTP requests, web APIs; Android Permissions; App navigation with Explicit Intents; GridView; ListView; Accessibility; Butterknife; Progress Wheel; Picasso ; Parcelable; Stetho._
This app was submitted as a project for Android Developer Nanodegree program on Udacity.

####How to Run the Application: 
This app can be run on Android Studio. 

1. Download the .zip file from the github. 
2. Extract the .zip file’s contents to a convenient location on your hard disk. 
3. In the Android Studio, click on File->New->Import Project and select the unzipped project folder. 

Now all of the project files will be displayed in the project structure. Press the ‘Run’ button and choose the 
running device to run the application.
NOTE: Click on a empty space on homescreen , select widget and choose MovieCorner to place a widget for 'boxoffice top ten' on your homescreen
