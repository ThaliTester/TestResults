#### Test 96293062c9b8e19_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/3F7026BE-8BBF-4D49-9B89-E8D05D39B6C3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/3F7026BE-8BBF-4D49-9B89-E8D05D39B6C3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96293062c9b8e19/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/ECBDD9A4-179F-41A4-A154-79F06991F119/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55662"
,(lldb)     command script import "/tmp/3F7026BE-8BBF-4D49-9B89-E8D05D39B6C3/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 17:11:42.428 ThaliTest[318:195822] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B56E8E79-1604-41BC-BCF3-F2CF1A5E23D1/Library/Cookies/Cookies.binarycookies
,2016-12-07 17:11:42.570 ThaliTest[318:195822] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 17:11:42.573 ThaliTest[318:195822] Multi-tasking -> Device: YES, App: YES
,2016-12-07 17:11:42.601 ThaliTest[318:195822] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 17:11:43.388 ThaliTest[318:195822] Using UIWebView
,2016-12-07 17:11:43.394 ThaliTest[318:195822] [CDVTimer][handleopenurl] 0.384033ms
,2016-12-07 17:11:43.402 ThaliTest[318:195822] [CDVTimer][intentandnavigationfilter] 7.400036ms
2016-12-07 17:11:43.403 ThaliTest[318:195822] [CDVTimer][gesturehandler] 0.328004ms
2016-12-07 17:11:43.403 ThaliTest[318:195822] [CDVTimer][TotalPluginStartup] 9.467959ms
,2016-12-07 17:11:54.054 ThaliTest[318:195822] Resetting plugins due to page load.
,2016-12-07 17:11:54.833 ThaliTest[318:195822] Finished load of: file:///var/containers/Bundle/Application/ECBDD9A4-179F-41A4-A154-79F06991F119/ThaliTest.app/www/index.html
,2016-12-07 17:11:55.064 ThaliTest[318:195822] JXcore Cordova plugin initializing
,2016-12-07 17:11:55.065 ThaliTest[318:195992] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 16:12:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 16:12:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 16:12:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-07 16:12:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 16:12:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 16:13:05 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  34.92658299207687
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
