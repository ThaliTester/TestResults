#### Test 99448283c38bc5f_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/97BA3EF1-7324-4C32-92C7-DB4CB0CD0331/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/97BA3EF1-7324-4C32-92C7-DB4CB0CD0331/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8B50ECBC-1C3F-4166-99E1-FF4533665D87/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52268"
,(lldb)     command script import "/tmp/97BA3EF1-7324-4C32-92C7-DB4CB0CD0331/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 15:51:37.884 ThaliTest[1484:3108962] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/081D579F-B464-4F99-B529-DB5C4D065AC2/Library/Cookies/Cookies.binarycookies
,2016-12-27 15:51:38.265 ThaliTest[1484:3108962] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 15:51:38.267 ThaliTest[1484:3108962] Multi-tasking -> Device: YES, App: YES
,2016-12-27 15:51:38.288 ThaliTest[1484:3108962] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 15:51:40.227 ThaliTest[1484:3108962] Using UIWebView
,2016-12-27 15:51:40.234 ThaliTest[1484:3108962] [CDVTimer][handleopenurl] 0.388026ms
,2016-12-27 15:51:40.242 ThaliTest[1484:3108962] [CDVTimer][intentandnavigationfilter] 7.135987ms
,2016-12-27 15:51:40.243 ThaliTest[1484:3108962] [CDVTimer][gesturehandler] 0.326991ms
,2016-12-27 15:51:40.243 ThaliTest[1484:3108962] [CDVTimer][TotalPluginStartup] 9.528995ms
,2016-12-27 15:51:46.643 ThaliTest[1484:3108962] Resetting plugins due to page load.
,2016-12-27 15:51:49.675 ThaliTest[1484:3108962] Finished load of: file:///var/mobile/Containers/Bundle/Application/8B50ECBC-1C3F-4166-99E1-FF4533665D87/ThaliTest.app/www/index.html
,2016-12-27 15:51:49.955 ThaliTest[1484:3108962] JXcore Cordova plugin initializing
,2016-12-27 15:51:49.956 ThaliTest[1484:3109201] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 14:51:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 5 seconds, with unfulfilled expectations: "Mock client can't connect to listener port". in file: Optional("<unknown>"), line: 0
,2016-12-27 14:52:32 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  32.31278896331787
,Failed to execute UT.
,2016-12-27 14:52:32 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
