# Youtube Better Shuffler, AKA Duke's Randomiser
An improved shuffling method for Youtube playlists

To use, simply download the html page and run in a browser, and enter the URL of your playlist. 

## About
This was put together after realising that youtube's shuffle method would often play only a small selection of videos in a large playlist. 

This html page uses the Youtube IFrames API and provides a better shuffling method than the shuffle feature in Youtube. The method used by the page is as follows:

1 - Generate random video number between 1 and the total number of videos in playlist.
2 - Check for this number in a "bucket" of previously played videos. 
3 - Play the video only if not in this bucket, otherwise start again at 1.
4 - When all playlist videos are in the bucket, empty it and add the last played video back in.

## TODO
Deleted videos - the current code should ignore deleted or unplayable videos in a playlist but this is still in testing.

## Credits
Liam Chessell 2020
