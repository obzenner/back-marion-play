**Tutorial videos:** 
https://drive.google.com/a/kinja.com/?tab=mo#folders/0B_CBiuTeE4dyNXJNMGFJODd5WG8
##Tech info to watch videos in Google Hangouts with sound
To watch the video on the screen with sound on Google Hangouts so everyone in the call can hear the sound, you should:
- Download https://code.google.com/p/soundflower/downloads/detail?name=Soundflower-1.6.6b.dmg&can=2&q=
- Install it and restart computer
- Set Soundflower (2ch) app in MAC OS top bar (where the WIFI is) to Built-In Output
- Set Google Hangouts Settings: Microphone should be set to Soundflower (2ch). The speakers should be set to Built-in Output
- Set MAC Audio preferences: Output should be set to Soundflower (2ch) and use Quick Time to watch the videos. VLC is buggy.

##The stack

**Front-end:**
- Backbone + Marionette http://marionettejs.com/
- Require.js for AMD http://requirejs.org/

**Back-end:**
- Play Framework https://www.playframework.com/

##Progress

#Day 1 - 13 Feb 2015
- We have set up Google Hangouts to work with sound when watching videos.
- We have agreed to be open-minded about how we will create API endpoints for the app depending on how the tutorial goes. The available options are http://deployd.com/ and a Play app. It would be great to see an implementation of 1 or 2 API endpoints using Scala with commentary.

**Next time:** Watch and implement as much as we can and note the merits and demerits of the approach used in this course. 


#Day 2 - 20 Feb 2015
- We have watched Episode 4 where the focus was mainly on the app structure and how to avoid spaghetti code when writing Marionette apps.

The main take-away is this:

**DON'T DO**

See diagram at 44:25

**DO**
![image App structure]
(https://lh5.googleusercontent.com/2kXx2R4kT6Wsy3cRoc5MbyHRfNCTLFvZMshOW1STTyHKTmRS6dDU40iq1NE-nmPLxkLEE53RemM=w2498-h1150)
See diagram at 43:58

#Day 3 - 6 March 2015
- Episode 5 covers the way to structure the app, shows how to use abstract models and collections and how to use your own template engine with Marionette. All the marionette and other lib overrides are stored in a `config` folder within `javascripts`

App structure as of this moment looks like this:
![image app structure]
(https://lh3.googleusercontent.com/oAX21P9kVJ6CeEdlwwVZX1mVloW3QS-VWrmdRYfnYvYc3QvuMuJGaN2ti0mwmOtyTZRg_5sZVJc=w2498-h1150)
