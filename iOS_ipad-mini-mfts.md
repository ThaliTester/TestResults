#### Test 99374565da5d395_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99374565da5d395/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AAB6CCDE-C453-472F-82FA-F3567BAFD814/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/AAB6CCDE-C453-472F-82FA-F3567BAFD814/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99374565da5d395/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99374565da5d395/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C666607F-409D-4A7C-BD21-7CA77BEBF6C7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52950"
,(lldb)     command script import "/tmp/AAB6CCDE-C453-472F-82FA-F3567BAFD814/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 17:50:35.082 ThaliTest[972:2913008] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/62E9B57B-6FB2-4025-8DD6-467F04131067/Library/Cookies/Cookies.binarycookies
,2016-12-26 17:50:35.233 ThaliTest[972:2913008] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 17:50:35.236 ThaliTest[972:2913008] Multi-tasking -> Device: YES, App: YES
,2016-12-26 17:50:35.260 ThaliTest[972:2913008] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 17:50:36.060 ThaliTest[972:2913008] Using UIWebView
,2016-12-26 17:50:36.066 ThaliTest[972:2913008] [CDVTimer][handleopenurl] 0.443995ms
,2016-12-26 17:50:36.074 ThaliTest[972:2913008] [CDVTimer][intentandnavigationfilter] 7.706046ms
2016-12-26 17:50:36.075 ThaliTest[972:2913008] [CDVTimer][gesturehandler] 0.329018ms
2016-12-26 17:50:36.075 ThaliTest[972:2913008] [CDVTimer][TotalPluginStartup] 9.858966ms
,2016-12-26 17:50:46.724 ThaliTest[972:2913008] Resetting plugins due to page load.
,2016-12-26 17:50:47.497 ThaliTest[972:2913008] Finished load of: file:///var/containers/Bundle/Application/C666607F-409D-4A7C-BD21-7CA77BEBF6C7/ThaliTest.app/www/index.html
,2016-12-26 17:50:47.726 ThaliTest[972:2913008] JXcore Cordova plugin initializing
,2016-12-26 17:50:47.728 ThaliTest[972:2913188] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 16:51:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 16:51:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 16:51:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-26 16:51:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 16:51:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 16:52:12 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  48.44658696651459
,Failed to execute UT.
,2016-12-26 16:52:12 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
