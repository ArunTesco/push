# PushNotification using service worker


HTML5 comes with lots of new features one of the most exiting  feature among them is service worker 

##what is service worker 

A service worker is a script that is run by your browser in the background, separate from a web page, opening the door to features which don't need a web page or user interaction.

###This is a simple Application which shows how service worker is being used for Push Notification

  Here i am using Google cloud messing for push Notification (you should have GCM account appkey to run this app you can create it its free for 90 days)
  
##Installation 
  - clone the repo
  - npm install
  - just update ur "gcm_sender_id": "XXXXXX" in manifest file and Your GCM API KEY in app.js gcm.Sender('Your GCM API KEY')
  - node app.js
  - browse the site in 4000 port 

### For more info on Service worker you can click [here](http://www.html5rocks.com/en/tutorials/service-worker/introduction/)
