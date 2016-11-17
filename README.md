# Movies app

_** Modified from react-native repo to utilize tMDb api for movies since rottentomatoes api is not widely accessible_

The Movies app is a demonstration of basic concepts, such as fetching data, rendering a list of data including images, and navigating between different screens.

<table>
  <tr>
    <td align="center"><img src="https://github.com/realdubb/react-native-tmdb-movies/blob/master/screenshots/HomeScreen.png" width="250"/><br/>Main Screen</td>
    <td align="center"><img src="https://github.com/realdubb/react-native-tmdb-movies/blob/master/screenshots/MovieDetail.png" width="250"/><br/>Detail view</td>
  </tr>
   <tr>
    <td align="center"><img src="https://github.com/realdubb/react-native-tmdb-movies/blob/master/screenshots/SearchingDisplay.png" width="250"/><br/>Searching</td>
    <td align="center"></td>
  </tr>
  
</table>


## How to build and run it yourself

You need to have your machine setup for [React Native Development](https://facebook.github.io/react-native/docs/getting-started.html) and API key from [TMDB The Movie Database](https://www.themoviedb.org/faq/api?language=en)


Complete the following steps to build and run the app:

1. Clone this repository:

  ~~~
  $ git clone https://github.com/realdubb/rnMovies.git
  ~~~

2. Enter the `rnMovies` directory:

  ~~~
  $ cd rnMovies
  ~~~

3. Install dependencies:

  ~~~
  $ npm install
  ~~~


4. Build and run for iOS

  ~~~
  $ react-native run-ios
  ~~~

5. Build and run for Android
  
  ~~~
  $ react-native run-android
  ~~~


#### Tested with:

ox mavericks

react-native-cli: 1.0.0
react-native: 0.37.0

node v6.2.1
npm 3.10.8

ios 10.1 & xcode 8
