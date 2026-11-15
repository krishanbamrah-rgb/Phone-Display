PHONE DISPLAY (online version)
Files: index.html, config.json, images/

Images: 1 Come on in, 2 Reduce interruptions, 3 Do Not Disturb, 4 Gaming, 5 Sleeping, 6 Working

To change what the phone shows, edit config.json:
  "mode": "single"  -> shows the image named in "image"
  "mode": "cycle"   -> rotates through every image in "images", every "interval" seconds (min 3)
If you replace an image but keep its file name, add 1 to "version" so the phone reloads it.
The phone checks for changes about every 20 seconds, but the host can take 1-2 minutes to publish an edit.
