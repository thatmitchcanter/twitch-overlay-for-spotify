# Spotify Overlay for Twitch

This is a dead-simple Twitch Overlay that uses [last.fm](https://last.fm) to scrobble the track titles and display them in a minimalistic way. The entire script is 6k with only 118 lines (the majority of them being comments and styles).

## Setting Up The Overlay

0. For this you will need:
- a last.fm account (sign up for one [here](https://www.last.fm/join))
- an API key from last.fm. Get your API key (once you've signed up for an account) [here](https://www.last.fm/api/account/create)
- the connection between Spotify and last.fm. You'll need to visit your [last.fm settings page](https://www.last.fm/settings/applications) and connect your Spotify account there.

1. Download the script and install it on a web server or your local hard drive - either should work.
2. Open index.html and edit the 'api', 'username', and 'time' variables - those will need to be filled in to your specific needs (the time variable is how often the script checks for a song change - I usually keep it at 2 seconds, but if you want to adjust it, feel free).
3. In OBS, add a new 'browser' source. Check the box that says 'Local File' if you are hosting the file on your machine. Enter the file location in the 'URL' box, and set the Width to 195, Height to 225. Feel free to tweak this as necessary.
4. Open Spotify and start playing. Everything should begin displaying on the first song change.

## To-Do

- Horizontal + Vertical Widget Views
- ???