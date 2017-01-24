#### Test 1027067423e9264e_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1027067423e9264e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D5B9AC77-E553-4BA3-B3C2-4FCD4D433CCD/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/D5B9AC77-E553-4BA3-B3C2-4FCD4D433CCD/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1027067423e9264e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1027067423e9264e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6D91B121-3F78-44E8-AB61-073CF75F4C69/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54946"
,(lldb)     command script import "/tmp/D5B9AC77-E553-4BA3-B3C2-4FCD4D433CCD/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 08:01:27.769 ThaliTest[1845:6741657] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2F5F1660-7951-487D-9C3C-680A3B25C89B/Library/Cookies/Cookies.binarycookies
,2017-01-24 08:01:27.917 ThaliTest[1845:6741657] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 08:01:27.919 ThaliTest[1845:6741657] Multi-tasking -> Device: YES, App: YES
,2017-01-24 08:01:27.943 ThaliTest[1845:6741657] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 08:01:28.432 ThaliTest[1845:6741657] Using UIWebView
,2017-01-24 08:01:28.438 ThaliTest[1845:6741657] [CDVTimer][handleopenurl] 0.473976ms
2017-01-24 08:01:28.445 ThaliTest[1845:6741657] [CDVTimer][intentandnavigationfilter] 6.929994ms
2017-01-24 08:01:28.446 ThaliTest[1845:6741657] [CDVTimer][gesturehandle,r] 0.295997ms
2017-01-24 08:01:28.446 ThaliTest[1845:6741657] [CDVTimer][TotalPluginStartup] 8.958995ms
,2017-01-24 08:01:35.284 ThaliTest[1845:6741657] Resetting plugins due to page load.
,2017-01-24 08:01:35.852 ThaliTest[1845:6741657] Finished load of: file:///var/containers/Bundle/Application/6D91B121-3F78-44E8-AB61-073CF75F4C69/ThaliTest.app/www/index.html
,2017-01-24 08:01:36.107 ThaliTest[1845:6741657] JXcore Cordova plugin initializing
,2017-01-24 08:01:36.109 ThaliTest[1845:6741806] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 07:02:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-24 07:02:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 07:02:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-24 07:02:14 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-24 07:02:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-24 07:03:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  49.35399800539017
F,ailed to execute UT.
2017-01-24 07:03:05 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
```
