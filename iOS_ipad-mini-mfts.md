#### Test 953210620aa0610_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/063CC157-9766-458F-9871-7FEB80A42912/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/063CC157-9766-458F-9871-7FEB80A42912/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/72D7C424-0F79-4600-AA9F-6F13EB3AA509/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54843"
,(lldb)     command script import "/tmp/063CC157-9766-458F-9871-7FEB80A42912/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 16:46:31.272 ThaliTest[313:192166] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/29D41642-01F1-472B-887E-11D81A399725/Library/Cookies/Cookies.binarycookies
,2016-12-07 16:46:31.404 ThaliTest[313:192166] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 16:46:31.407 ThaliTest[313:192166] Multi-tasking -> Device: YES, App: YES
,2016-12-07 16:46:31.436 ThaliTest[313:192166] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 16:46:32.100 ThaliTest[313:192166] Using UIWebView
,2016-12-07 16:46:32.109 ThaliTest[313:192166] [CDVTimer][handleopenurl] 0.383019ms
,2016-12-07 16:46:32.117 ThaliTest[313:192166] [CDVTimer][intentandnavigationfilter] 7.402956ms
2016-12-07 16:46:32.118 ThaliTest[313:192166] [CDVTimer][gesturehandler] 0.344038ms
2016-12-07 16:46:32.118 ThaliTest[313:192166] [CDVTimer][TotalPluginStartup] 9.582043ms
,2016-12-07 16:46:42.512 ThaliTest[313:192166] Resetting plugins due to page load.
,2016-12-07 16:46:43.297 ThaliTest[313:192166] Finished load of: file:///var/containers/Bundle/Application/72D7C424-0F79-4600-AA9F-6F13EB3AA509/ThaliTest.app/www/index.html
,2016-12-07 16:46:43.528 ThaliTest[313:192166] JXcore Cordova plugin initializing
,2016-12-07 16:46:43.530 ThaliTest[313:192335] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 15:47:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 15:47:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 15:47:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-07 15:47:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 15:47:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 15:47:53 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  34.41760498285294
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
