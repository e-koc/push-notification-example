# push-notification-example
adb shell am broadcast -a com.google.android.c2dm.intent.RECEIVE -n net.emrekoc.pushnotificationexample/net.emrekoc.pushnotificationexample.gcm.MyGcmReceiver --es "message" "Hi !!"
