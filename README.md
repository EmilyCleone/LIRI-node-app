# LIRI-node-app

1. Clearly state the problem the app is trying to solve (i.e. what is it doing and why)
2. Give a high-level overview of how the app is organized
3. GivI, e start-to-finish instructions on how to run the app
4. Include screenshots, gifs or videos of the app functioning
5. Contain a link to a deployed version of the app
6. Clearly list the technologies used in the app
7. State your role in the app development
 
### How to use 
Use node to run this program. Use node liri.js then run one of the following comands, then add search text:

* `concert-this`
* `spotify-this-song`
* `movie-this`
* `do-what-it-says`

### When running a command follow it by desired text/search.
Example:
node liri.js movie-this Fantastic Mr. Fox

### When concert-this command is used you will be provided with:

* Name of the venue
* Venue location
* Date of the Event

### When spotify-this-song command is used you will be provided with:

* Artist(s)
* The song's name
* A preview link of the song from Spotify
* The album that the song is from
* If no song is provided then your program will default to "The Sign" by Ace of Base.

### When movie-this command is used you will be provided with:

* Title of the movie.
* Year the movie came out.
* IMDB Rating of the movie.
* Rotten Tomatoes Rating of the movie.
* Country where the movie was produced.
* Language of the movie.
* Plot of the movie.
* Actors in the movie.
* If the user doesn't type a movie in, the program will output data for the movie 'Fantastic Mr. Fox'.

### When do-what-it-says command:
A random.txt file with search for spotify-this-song "I want it that way." This will give you the spotify results of "I want it that way."

### Technologies Used
* JavaScript
* Node.js
* Spotify API
* Bands in Town API
* OMDB API
