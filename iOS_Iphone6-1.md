#### Test 83070177a758936_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DF83A439-3AE0-4198-9D30-80D437441A27/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DF83A439-3AE0-4198-9D30-80D437441A27/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83070177a758936/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/921C1B7A-31F5-40E9-BDC7-C012445DFB4E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56623"
,(lldb)     command script import "/tmp/DF83A439-3AE0-4198-9D30-80D437441A27/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-12 13:48:53.864 ThaliTest[388:475121] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0E6B4F83-B581-4669-A9B8-D9F76033F2F3/Library/Cookies/Cookies.binarycookies
,2016-09-12 13:48:54.429 ThaliTest[388:475121] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-12 13:48:54.431 ThaliTest[388:475121] Multi-tasking -> Device: YES, App: YES
,2016-09-12 13:48:54.470 ThaliTest[388:475121] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-12 13:48:55.145 ThaliTest[388:475121] Using UIWebView
,2016-09-12 13:48:55.156 ThaliTest[388:475121] [CDVTimer][handleopenurl] 0.391960ms
,2016-09-12 13:48:55.164 ThaliTest[388:475121] [CDVTimer][intentandnavigationfilter] 8.213043ms
2016-09-12 13:48:55.165 ThaliTest[388:475121] [CDVTimer][gesturehandler] 0.352979ms
2016-09-12 13:48:55.166 ThaliTest[388:475121] [CDVTimer][TotalPluginStartup] 10.634005ms
,2016-09-12 13:49:00.992 ThaliTest[388:475121] Resetting plugins due to page load.
,2016-09-12 13:49:01.595 ThaliTest[388:475121] Finished load of: file:///var/containers/Bundle/Application/921C1B7A-31F5-40E9-BDC7-C012445DFB4E/ThaliTest.app/www/index.html
,2016-09-12 13:49:02.052 ThaliTest[388:475121] JXcore Cordova plugin initializing
,2016-09-12 13:49:02.053 ThaliTest[388:475326] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  16
Number of passed tests:  16
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.34498900175095
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
