#### Test 98115565db523c3_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/ADD0E54A-51E9-4876-A625-013BAFE4312E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/ADD0E54A-51E9-4876-A625-013BAFE4312E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/AF89CE22-4FD4-4716-8B69-E5106ADDAC48/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49562"
,(lldb)     command script import "/tmp/ADD0E54A-51E9-4876-A625-013BAFE4312E/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-15 12:11:39.134 ThaliTest[589:1319232] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7066CA6E-CC65-4E39-BCE8-8E306835A69B/Library/Cookies/Cookies.binarycookies
,2016-12-15 12:11:39.274 ThaliTest[589:1319232] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 12:11:39.277 ThaliTest[589:1319232] Multi-tasking -> Device: YES, App: YES
,2016-12-15 12:11:39.305 ThaliTest[589:1319232] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 12:11:40.100 ThaliTest[589:1319232] Using UIWebView
,2016-12-15 12:11:40.111 ThaliTest[589:1319232] [CDVTimer][handleopenurl] 0.464022ms
,2016-12-15 12:11:40.119 ThaliTest[589:1319232] [CDVTimer][intentandnavigationfilter] 7.170022ms
2016-12-15 12:11:40.120 ThaliTest[589:1319232] [CDVTimer][gesturehandler] 0.362992ms
2016-12-15 12:11:40.120 ThaliTest[589:1319232] [CDVTimer][TotalPluginStar,tup] 9.414971ms
,2016-12-15 12:11:50.717 ThaliTest[589:1319232] Resetting plugins due to page load.
,2016-12-15 12:11:51.508 ThaliTest[589:1319232] Finished load of: file:///var/containers/Bundle/Application/AF89CE22-4FD4-4716-8B69-E5106ADDAC48/ThaliTest.app/www/index.html
,2016-12-15 12:11:51.747 ThaliTest[589:1319232] JXcore Cordova plugin initializing
,2016-12-15 12:11:51.749 ThaliTest[589:1319415] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 11:12:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 11:12:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 11:12:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-15 11:12:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 11:12:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-15 11:12:57 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  29.79221200942993
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
