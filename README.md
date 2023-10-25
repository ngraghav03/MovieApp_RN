# MovieApp_React_Native

This is a Movie App which displays information about movies like Trending Movies, Top Rated Movies, etc.
It also has search functionality to search for movies.

1. Navigatable Pages:

1) Home Screen:
  This screen has various trending movies as a carousel, then it has a scrollable movie list section for upcoming movies and top rated movies.

2) Movie Screen:
  When we click on a movie poster, it takes us to the corresponding movie screen.
  In this screen, we have information about the movie, like status (upcoming, shooting in progress), release date, genres and synopsis.
  It also has a scrollable cast list, where the cast and crew of the movies are displayed.
  Moreover, it has a scrollable movie list containing similar movies to the selected movie.

4) Person Screen:
  When we click on a person image, it takes us to the corresponding person screen.
  In this screen, we have information about the person like their birthday, age, their life history, etc.
  It also has a scrollable movie list, where the various movies that the person has worked in are displayed

5) Search Screen:
   This search screen displays the movie posters along with the movie names got by the search results of the input in search bar.
   When no results are fetched for the search input, an image is displayed to indicate no search results.

2. API Call Implementation:
  
   We are using the TMDB database to access all information and data about various movies.
   We generate an API key for the database to use their APIs.

   We are using the follwing APIs for our project:
   i) Trending Movies
   ii) Top Rated Movies
   iii) Upcoming Movies
   iv) Search Movies
   v) Movie Details API
   vi) Movie Credits API
   vii) Similar Movies API
   viii) Person Details API
   ix) Person Movies API

3. Design Inspirations:
   Letterboxd: https://letterboxd.com/
   JustWatch: https://www.justwatch.com/

4. How to run the project:

   i) Download the project from the Github repository.
   ii) Download/Install the necessary plugins like react-native-carousel, etc.
   iii) Our Splash screen/starting screen is set HomeScreen.js
   iv) This data is entered in AppEntry.js
   v) Download Expo Go app in iOS or Android device.
   vi) Open cmd and set directory to our project folder.
   vii) Then type "npx expo start"
   viii) We will get a QR Code in our cmd.
   ix) Scan this QR code in camera app in iOS or Expo Go app in Android.
   x) When finished with the project, press Ctrl + C to stop the server.

6. File Structure:

   1) api folder: This folder contains the file which has all api related URLs.
   2) assets folder: This folder contains all assets like images required for the project.
   3) components folder: This folder contains JS files needed to implement components like scrollable movie list, carousel, etc.
   4) constants folder: This folder is used to store constant values like API key for TMDB database.
   5) navigation folder: This folder contains navigation.js which has the details of all pages that we can navigate to.
   6) screens folder: This folder contains JS files needed to render different screens like Person Screen, Movie Screen, Home Screen, etc.
   7) theme folder: This folder is used to store files which are used for styling (stylesheets)
