# Last Collage

A last.fm album collage generator. It uses the last.fm api along with jQuery to create a collage of the album covers of a user's most listened to album. Collages can be anywhere from a 2x2 to a 7x7. The time range can go from one week to the entire lifetime of the account.

The collage will display the album cover art, the artist name, the album name and the playcount(how many listens). 

# Collage Example

![alt text](https://i.imgur.com/1c6jpvO.png "5x5 Collage Example")

# Site Example

![alt text](https://i.imgur.com/MDhU4b7.png "Site Example")

# Site With Collage

You will notice that the collage is left aligned. That is to ensure that dom-to-image doesn't add a bunch of white space into the image. 

![alt text](https://i.imgur.com/gi1es1k.jpg "Site Example")


Sadly the site doesn't work on any of the mobile devices I have tested due to how dom-to-image works from what I can tell. If you happen to know how to get it to work feel free to send me a pull request.