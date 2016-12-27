#### Test 99435972548f19d_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99435972548f19d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B7759A9F-D3D7-4D03-98AC-B24C36146D5E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B7759A9F-D3D7-4D03-98AC-B24C36146D5E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99435972548f19d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99435972548f19d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C87F9576-5C2D-4019-AFB3-79B93453D450/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63306"
,(lldb)     command script import "/tmp/B7759A9F-D3D7-4D03-98AC-B24C36146D5E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 13:49:37.576 ThaliTest[1456:3092370] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8FBEA9A8-81B9-400A-9EA3-24B8808EB088/Library/Cookies/Cookies.binarycookies
,2016-12-27 13:49:37.967 ThaliTest[1456:3092370] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 13:49:37.969 ThaliTest[1456:3092370] Multi-tasking -> Device: YES, App: YES
,2016-12-27 13:49:37.991 ThaliTest[1456:3092370] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 13:49:40.056 ThaliTest[1456:3092370] Using UIWebView
,2016-12-27 13:49:40.065 ThaliTest[1456:3092370] [CDVTimer][handleopenurl] 0.337005ms
,2016-12-27 13:49:40.072 ThaliTest[1456:3092370] [CDVTimer][intentandnavigationfilter] 6.482005ms
,2016-12-27 13:49:40.073 ThaliTest[1456:3092370] [CDVTimer][gesturehandler] 0.299037ms
,2016-12-27 13:49:40.073 ThaliTest[1456:3092370] [CDVTimer][TotalPluginStartup] 8.845985ms
,2016-12-27 13:49:46.351 ThaliTest[1456:3092370] Resetting plugins due to page load.
,2016-12-27 13:49:49.441 ThaliTest[1456:3092370] Finished load of: file:///var/mobile/Containers/Bundle/Application/C87F9576-5C2D-4019-AFB3-79B93453D450/ThaliTest.app/www/index.html
,2016-12-27 13:49:49.654 ThaliTest[1456:3092370] JXcore Cordova plugin initializing
,2016-12-27 13:49:49.654 ThaliTest[1456:3092596] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 12:49:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 12:49:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 12:49:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-27 12:49:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 12:49:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 12:50:25 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.22369796037674
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
