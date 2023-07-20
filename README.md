# r-place-autoplace



# How to setup a bot (only macOS and Linux)
(windows soon)

1. Go to https://www.reddit.com/r/place/?screenmode=fullscreen
2. Open the network console
3. place a pixel
4. 2 query requests should have been sent. Pick the one that contains the request json setPixel.
5. now right click that request and hover on copy value and then click copy as cURL address.
6. now open a console and type ``while true ; do```
7. after the do put a space and then paste your clipboard
8. at the end put ```; sleep 300 ; done```
9. now press enter and every 5 minutes the pixel selected in 3. will be set to the same color and at the same position.
