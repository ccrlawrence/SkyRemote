SkyRemote
=========

Based on lgladdy's SkyRemote. This makes use of Picasso's ability to display photos.

Rights respected for Miranda on Google Code http://code.google.com/p/miranda-upnp/ and licensed under GPLv3.


How does it work?
------------------------------------------------

As well as advertising some DLNA endpoints, there is also a hidden function on port 49153 to display a photo on Picasso, in front of the playing video. This version alters the photo to display properly, serves in on a random port and then requests Picasso to display it via a GET request.

To run the script, you'll need python installed. You already have this if you're on a mac, and probably on linux too. Then you can run:

    python skyRemote.py

The commands in relation to showing pitcures are:
```
    python skyRemote.py
    showpic show photo.jpg
    showpic show /Users/Name/Documents/photo.png
    showpic hide
```

Please let me know if you like it.
