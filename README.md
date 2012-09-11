eclipse-android-cordova-facebook
================================

Eclipse project of a skeleton web app for Android with native Facebook Connect integration thanks to Phonegap/Cordova and plugins. 

Ready to run with Hackbook example and all the latest Cordova fixes at time of commit.

* http://phonegap.com/
* https://github.com/davejohnson/phonegap-plugin-facebook-connect

Reusing this template
---------------------
* Install Android SDK and ADT Eclipse plugin (see .2 http://docs.phonegap.com/en/2.0.0/guide_getting-started_android_index.md.html )
* Import then rename the project in Eclipse
* Right-click on project/Android Tools/Rename Application Package (make sure the project is automatically rebuilt)
* Change app name and activity name in /res/values/string.xml and all the versions of ic_launcher.pg in res/drawable-*
* Set your Facebook App ID at the bottom /assets/www/index.html
* Generate your hash key and save it in your Facebook App settings (see https://developers.facebook.com/docs/mobile/android/build/#sig)