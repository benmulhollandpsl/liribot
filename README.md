# liribot
LIRI is a command line node app that takes in parameters and gives back data
Languae Interpretation and Recognition Interface.  Looking for concert date information, when a movie came out, or just information about a favorite song all in one quick interface without other distractions helps narrow in on the information the user is trying to get.

The four commands with specific paramters return information requested.  These results are saved to log.txt




# Technologies Used 
Javascript; NodeJS; Node packages: request, moment, dotenv
APIs used: Bands in Town, OMDB, Spotify
Git, GitHub.

### Steps

1. LIRI will search Spotify for songs, Bands in Town for concerts, and OMDB for movies.

2. Open your terminal and navigate to the folder containing the liri.js file

3. type: npm i
  a) this is in case you already have not.

4. liri.js can take in one of the following commands:

   * `concert-this`

   * `spotify-this-song`

   * `movie-this`

   * `do-what-it-says`


5.  examples:
type: node liri.js spotify-this-song ______
  
            a) the blank is the title of the song you are searching.  
            capitalization and spaces won't change the results.
  
            b) this will return a result from the spotify 
  
            c) if no song is selected we'll go to our default song.

type: node liri.js movie-this ______
          
            a) If you type Matrix (for exaple) for the blank 
            it will return information on the Matrix from the OMDB database
   


## Video Guide
  <https://drive.google.com/file/d/1SNlTVp2fgRw8t6KvlcHnHZ1wuSwJzLf6/view>
<br>
recorded using screencastify extension for google chrome on 4/3/2020




### Link to deployed project and github repository

<https://benmulhollandpsl.github.io/liribot/>

https://github.com/benmulhollandpsl/liribot






future updates would be to clean up the overall return of the results.  Feedback is welcome, and appreciated.






