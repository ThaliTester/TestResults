#### Test 99530606d5b5815_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/307CBD9C-F1DB-407D-AD87-2579BE35F17F/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/307CBD9C-F1DB-407D-AD87-2579BE35F17F/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FBAB36CB-2334-45E7-B0A7-412FF9817024/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65510"
,(lldb)     command script import "/tmp/307CBD9C-F1DB-407D-AD87-2579BE35F17F/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-12-28 16:32:33.380 ThaliTest[1085:3209911] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EBB7FAF6-48EB-49AD-A4D4-E9BC3A8A3CDF/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:32:33.530 ThaliTest[1085:3209911] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:32:33.533 ThaliTest[1085:3209911] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:32:33.566 ThaliTest[1085:3209911] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:32:34.236 ThaliTest[1085:3209911] Using UIWebView
,2016-12-28 16:32:34.244 ThaliTest[1085:3209911] [CDVTimer][handleopenurl] 0.459015ms
,2016-12-28 16:32:34.252 ThaliTest[1085:3209911] [CDVTimer][intentandnavigationfilter] 7.389009ms
2016-12-28 16:32:34.253 ThaliTest[1085:3209911] [CDVTimer][gesturehandler] 0.344992ms
2016-12-28 16:32:34.253 ThaliTest[1085:3209911] [CDVTimer][TotalPluginStartup] 9.595037ms
,2016-12-28 16:32:43.429 ThaliTest[1085:3209911] Resetting plugins due to page load.
,2016-12-28 16:32:44.165 ThaliTest[1085:3209911] Finished load of: file:///var/containers/Bundle/Application/FBAB36CB-2334-45E7-B0A7-412FF9817024/ThaliTest.app/www/index.html
,2016-12-28 16:32:44.418 ThaliTest[1085:3209911] JXcore Cordova plugin initializing
,2016-12-28 16:32:44.421 ThaliTest[1085:3210085] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:33:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:33:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:33:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-28 15:33:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:33:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 15:33:56 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  34.79763603210449
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
