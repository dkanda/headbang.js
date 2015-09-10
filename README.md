# headbang.js
Play a song based off the bpm of your headbang

## How it works
Uses tracking.js (trackingjs.com) to monitor your face's y coordinate. 
Detect the bpm over the span of 5 seconds
Use that bpm to find songs with that bpm with echonest api
Use the song artist and title to play the song with youtube api