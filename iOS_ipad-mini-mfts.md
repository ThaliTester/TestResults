#### Test 98710374837bb9b_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/5D9B702E-9A60-4E60-84F9-E2992805A44E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/5D9B702E-9A60-4E60-84F9-E2992805A44E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/755B00F6-D344-4EA2-9E69-4382B34B8622/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50569"
,(lldb)     command script import "/tmp/5D9B702E-9A60-4E60-84F9-E2992805A44E/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-22 18:58:48.281 ThaliTest[834:2345745] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AECCFB39-54E1-4456-BE4A-C40C68F148F4/Library/Cookies/Cookies.binarycookies
,2016-12-22 18:58:48.423 ThaliTest[834:2345745] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-22 18:58:48.425 ThaliTest[834:2345745] Multi-tasking -> Device: YES, App: YES
,2016-12-22 18:58:48.451 ThaliTest[834:2345745] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-22 18:58:49.231 ThaliTest[834:2345745] Using UIWebView
,2016-12-22 18:58:49.237 ThaliTest[834:2345745] [CDVTimer][handleopenurl] 0.479996ms
,2016-12-22 18:58:49.245 ThaliTest[834:2345745] [CDVTimer][intentandnavigationfilter] 7.211030ms
2016-12-22 18:58:49.246 ThaliTest[834:2345745] [CDVTimer][gesturehandler] 0.325024ms
2016-12-22 18:58:49.246 ThaliTest[834:2345745] [CDVTimer][TotalPluginStartup] 9.373009ms
,2016-12-22 18:58:59.834 ThaliTest[834:2345745] Resetting plugins due to page load.
,2016-12-22 18:59:00.896 ThaliTest[834:2345745] Finished load of: file:///var/containers/Bundle/Application/755B00F6-D344-4EA2-9E69-4382B34B8622/ThaliTest.app/www/index.html
,2016-12-22 18:59:01.125 ThaliTest[834:2345745] JXcore Cordova plugin initializing
,2016-12-22 18:59:01.127 ThaliTest[834:2345921] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-22 17:59:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-22 17:59:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-22 17:59:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-22 17:59:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-22 17:59:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-22 18:00:09 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  32.20452404022217
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
