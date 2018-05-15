# LIRI Bot

LIRI Bot is a Langugae Interpretation and Recognition Interface, similar to iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface. LIRI is be a command line node app that takes in parameters and returns data corresponding to one of the four commands.


## Commands

* `my-tweets`
* `spotify-this-song`
* `movie-this`
* `do-what-it-says`

## What Each Command Does

#### `node liri.js my-tweets`

Twitter NPM Package - https://www.npmjs.com/package/twitter

Displays my last 20 tweets in the terminal/bash window and logs the output in `log.txt`.


#### `node-liri.js spotify-this-song <song name>`

Spotify NPM Package - https://www.npmjs.com/package/spotify

Displays the following information about the song entered in the terminal/bash window and logs the output in `log.txt`.

  * Artist(s)
  * Song's name
  * Preview link from spotify

#### `node liri.js movie-this <movie name>`

Request NPM Package - https://www.npmjs.com/package/request > [OMDB API](http://www.omdbapi.com)

Displays the following information about the movie entered in the terminal/bash window and logs the output in `log.txt`.

  * Title of the movie
  * Year movie was released
  * IMDB rating 
  * Rotten Tomatoes rating
  * Country where movie was produced
  * Langugage of the movie
  * Movie plot
  * Cast

#### `node liri.js do-what-it-says`

FS NPM Package - https://nodejs.org/api/fs.html

Using the `fs` node package, LIRI will take the text inside random.txt and then use it to call one of LIRI's four commands. The output will be displayed in the terminal/bash window and logged in `log.txt`.

## Examples
![Alt text](images/tweets.jpg 'Tweets')
![Alt text](images/spotify.jpg 'Spotify')
![Alt text](images/movie.jpg 'Movie')
![Alt text](images/read.jpg 'Read')
