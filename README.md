forked-daapd docker container
============

forked from https://github.com/double16/forked-daapd
adapted so that the current github version will be used (and compiled) so that spotify, mpd and lastfm support is enabled

forked-daapd is an iTunes and Roku streaming music server.

Features:
- Volume /media to mount your media
- Volume /cache for storing the forked-daapd media cache
- Volume /log for storing logs in addition to the console
- Environment variable MEDIA_SERVER_NAME to name your server, optional
- Environment variable MEDIA_SERVER_DATA to read media from somewhere other than /media, optional
- Environment variable PUID to set the user ID to faciliate use with other containers

