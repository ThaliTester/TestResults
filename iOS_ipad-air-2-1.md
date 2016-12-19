#### Test 983548825638cdd_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/094A41CC-3708-4FFD-A249-A8713E08A6CE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/094A41CC-3708-4FFD-A249-A8713E08A6CE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D8150B45-87D4-4212-9B78-40A088FBBAFF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57979"
,(lldb)     command script import "/tmp/094A41CC-3708-4FFD-A249-A8713E08A6CE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 14:11:59.053 ThaliTest[1023:1941676] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88A467DE-C29B-4110-8E17-B526BA8A718C/Library/Cookies/Cookies.binarycookies
,2016-12-19 14:11:59.427 ThaliTest[1023:1941676] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 14:11:59.429 ThaliTest[1023:1941676] Multi-tasking -> Device: YES, App: YES
,2016-12-19 14:11:59.447 ThaliTest[1023:1941676] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 14:12:01.338 ThaliTest[1023:1941676] Using UIWebView
,2016-12-19 14:12:01.346 ThaliTest[1023:1941676] [CDVTimer][handleopenurl] 0.395954ms
,2016-12-19 14:12:01.353 ThaliTest[1023:1941676] [CDVTimer][intentandnavigationfilter] 6.435990ms
,2016-12-19 14:12:01.353 ThaliTest[1023:1941676] [CDVTimer][gesturehandler] 0.280976ms
,2016-12-19 14:12:01.354 ThaliTest[1023:1941676] [CDVTimer][TotalPluginStartup] 8.672059ms
,2016-12-19 14:12:07.761 ThaliTest[1023:1941676] Resetting plugins due to page load.
,2016-12-19 14:12:10.821 ThaliTest[1023:1941676] Finished load of: file:///var/mobile/Containers/Bundle/Application/D8150B45-87D4-4212-9B78-40A088FBBAFF/ThaliTest.app/www/index.html
,2016-12-19 14:12:11.033 ThaliTest[1023:1941676] JXcore Cordova plugin initializing
,2016-12-19 14:12:11.034 ThaliTest[1023:1941905] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 13:12:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-19 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-19 13:12:46 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.26654303073883
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
