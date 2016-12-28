#### Test 99529739424d9f5_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app
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
,(lldb) command source -s 0 '/tmp/EA5E2E69-BE27-4B2C-878D-725DAF864432/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/EA5E2E69-BE27-4B2C-878D-725DAF864432/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E92A2112-4718-4147-89A7-FD4DF160A26D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57731"
,(lldb)     command script import "/tmp/EA5E2E69-BE27-4B2C-878D-725DAF864432/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 11:23:55.319 ThaliTest[1534:3232718] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EEEBBE61-11BF-407C-A298-C60BCB87D5D2/Library/Cookies/Cookies.binarycookies
,2016-12-28 11:23:55.634 ThaliTest[1534:3232718] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 11:23:55.635 ThaliTest[1534:3232718] Multi-tasking -> Device: YES, App: YES
,2016-12-28 11:23:55.649 ThaliTest[1534:3232718] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 11:23:57.434 ThaliTest[1534:3232718] Using UIWebView
,2016-12-28 11:23:57.441 ThaliTest[1534:3232718] [CDVTimer][handleopenurl] 0.343025ms
,2016-12-28 11:23:57.448 ThaliTest[1534:3232718] [CDVTimer][intentandnavigationfilter] 6.460011ms
,2016-12-28 11:23:57.448 ThaliTest[1534:3232718] [CDVTimer][gesturehandler] 0.277996ms
,2016-12-28 11:23:57.449 ThaliTest[1534:3232718] [CDVTimer][TotalPluginStartup] 8.665979ms
,2016-12-28 11:24:04.256 ThaliTest[1534:3232718] Resetting plugins due to page load.
,2016-12-28 11:24:07.129 ThaliTest[1534:3232718] Finished load of: file:///var/mobile/Containers/Bundle/Application/E92A2112-4718-4147-89A7-FD4DF160A26D/ThaliTest.app/www/index.html
,2016-12-28 11:24:07.356 ThaliTest[1534:3232718] JXcore Cordova plugin initializing
,2016-12-28 11:24:07.357 ThaliTest[1534:3232940] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 10:24:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 10:24:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 10:24:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-28 10:24:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 10:24:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-28 10:24:43 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.45515698194504
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
