# LIRI-Bot

1. Clearly state the problem the app is trying to solve (i.e. what is it doing and why)

This application allows the user to make requests for information about concerts, songs, and movies all within the command line. It utilizes the Bands in Town, Spotify, and OMDB API's along with multiple node modules to make such requests possible all from inside the command line. Directions on how to use it are below.

2. Give a high-level overview of how the app is organized: 

1) concert-this (musical artist)

    Returns upcoming shows from the inputted artist to the console.

2) spotify-this-song (song name)

    Returns album information from the inputted song, and a preview snippet URL, to the console.

3) movie-this (movie title)

    Returns production details from the inputted movie, along with the plot and cast, to the console.

4) do-what-it-says

    Reads the text in the <em>random.txt</em> file and runs the appropriate function to return information to the console.

3. Include screenshots, gifs or videos of the app functioning

NA - Could Not Get the Project to work fully 

4. Contain a link to a deployed version of the app

https://github.com/MichelleDT/Liri-App

5. Clearly list the technologies used in the app

This project makes use of:
* [Axios](https://www.npmjs.com/package/axios) - Make HTTP requests
* [Moment](https://www.npmjs.com/package/moment) - Format times
* [DotEnv](https://www.npmjs.com/package/dotenv) - Hide API keys
* [Node-Spotify-API](https://www.npmjs.com/package/node-spotify-api) - Retrieve song information 
* [OMDB API](http://www.omdbapi.com) - Retrieve movie information
* [Bands In Town API](http://www.artists.bandsintown.com/bandsintown-api) - Retrieve show information



