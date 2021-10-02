# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [ x ] (5pts) User can tap a cell to see more details about a particular movie.
- [ x ] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthrough GIF

<img src="https://i.imgur.com/FcWJLNh.gif" width=250><br>

### Notes
Only problem I faced was the extension side for the posters in the collection view. The similar method from API was a little weird too. 


## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [ x ] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [ x ] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [ x ] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthrough GIF

<img src="https://i.imgur.com/PVj8uJ6.gif" width=250><br>

### Notes
Had some trouble making the MovieViewController, did not do a cocoa touch class at first. Poster URL was not working at first until changed from "http" to "https"

