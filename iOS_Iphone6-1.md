#### Test 82914073d0f9b46_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4980BB85-8BB7-415C-8FA5-2C0BA22B598B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4980BB85-8BB7-415C-8FA5-2C0BA22B598B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EED95605-4E9C-43E8-AEFF-CE6E333457F2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57455"
,(lldb)     command script import "/tmp/4980BB85-8BB7-415C-8FA5-2C0BA22B598B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-06 19:15:00.597 ThaliTest[1292:2184277] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F6AA7DF9-01B6-4A0D-8949-DA24179211A9/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:15:01.052 ThaliTest[1292:2184277] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:15:01.054 ThaliTest[1292:2184277] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:15:01.074 ThaliTest[1292:2184277] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:15:03.345 ThaliTest[1292:2184277] Using UIWebView
,2016-09-06 19:15:03.351 ThaliTest[1292:2184277] [CDVTimer][handleopenurl] 0.409007ms
,2016-09-06 19:15:03.359 ThaliTest[1292:2184277] [CDVTimer][intentandnavigationfilter] 7.448971ms
2016-09-06 19:15:03.360 ThaliTest[1292:2184277] [CDVTimer][gesturehandler] 0.338972ms
2016-09-06 19:15:03.361 ThaliTest[1292:2184277] [CDVTimer][TotalPluginS,tartup] 9.781003ms
,2016-09-06 19:15:10.491 ThaliTest[1292:2184277] Resetting plugins due to page load.
,2016-09-06 19:15:14.319 ThaliTest[1292:2184277] Finished load of: file:///var/mobile/Containers/Bundle/Application/EED95605-4E9C-43E8-AEFF-CE6E333457F2/ThaliTest.app/www/index.html
,2016-09-06 19:15:14.619 ThaliTest[1292:2184277] JXcore Cordova plugin initializing
,2016-09-06 19:15:14.619 ThaliTest[1292:2184535] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  38
,Number of passed tests:  38
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  11.96792203187943
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
