#### Test 9732732894937d3_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/4FD08253-2293-4B14-B623-4AACD1D690A0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/4FD08253-2293-4B14-B623-4AACD1D690A0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1620AB8E-1F84-4AAF-8E9E-72A3B04C706A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61907"
,(lldb)     command script import "/tmp/4FD08253-2293-4B14-B623-4AACD1D690A0/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-09 16:50:46.925 ThaliTest[450:355667] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/11E75216-3DF3-4960-9025-E60FC61B7403/Library/Cookies/Cookies.binarycookies
,2016-12-09 16:50:46.967 ThaliTest[450:355667] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-09 16:50:46.968 ThaliTest[450:355667] Multi-tasking -> Device: YES, App: YES
,2016-12-09 16:50:46.981 ThaliTest[450:355667] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-09 16:50:47.303 ThaliTest[450:355667] Using UIWebView
2016-12-09 16:50:47.307 ThaliTest[450:355667] [CDVTimer][handleopenurl] 0.142992ms
,2016-12-09 16:50:47.311 ThaliTest[450:355667] [CDVTimer][intentandnavigationfilter] 4.501998ms
2016-12-09 16:50:47.312 ThaliTest[450:355667] [CDVTimer][gesturehandler] 0.149012ms
2016-12-09 16:50:47.312 ThaliTest[450:355667] [CDVTimer][TotalPluginStartup] 5.551994ms
,2016-12-09 16:50:53.575 ThaliTest[450:355667] Resetting plugins due to page load.
,2016-12-09 16:50:54.024 ThaliTest[450:355667] Finished load of: file:///var/containers/Bundle/Application/1620AB8E-1F84-4AAF-8E9E-72A3B04C706A/ThaliTest.app/www/index.html
,2016-12-09 16:50:54.368 ThaliTest[450:355667] JXcore Cordova plugin initializing
2016-12-09 16:50:54.369 ThaliTest[450:355848] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-09 15:51:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-09 15:51:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-09 15:51:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-09 15:51:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-09 15:51:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-09 15:51:31 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.43637299537659
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
