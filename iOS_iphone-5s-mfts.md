#### Test 98710374837bb9b_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/465810F2-BAD4-4EC8-AB9A-AA182197AE1B/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/465810F2-BAD4-4EC8-AB9A-AA182197AE1B/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98710374837bb9b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5D0B3667-3FE9-442A-82A5-3E1406A6EB11/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50575"
,(lldb)     command script import "/tmp/465810F2-BAD4-4EC8-AB9A-AA182197AE1B/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-22 18:59:43.551 ThaliTest[1041:1891002] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9CB14734-F1CE-47CD-A688-CB226D5556ED/Library/Cookies/Cookies.binarycookies
,2016-12-22 18:59:43.642 ThaliTest[1041:1891002] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-22 18:59:43.644 ThaliTest[1041:1891002] Multi-tasking -> Device: YES, App: YES
,2016-12-22 18:59:43.664 ThaliTest[1041:1891002] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-22 18:59:44.138 ThaliTest[1041:1891002] Using UIWebView
,2016-12-22 18:59:44.150 ThaliTest[1041:1891002] [CDVTimer][handleopenurl] 0.399947ms
,2016-12-22 18:59:44.162 ThaliTest[1041:1891002] [CDVTimer][intentandnavigationfilter] 10.434031ms
2016-12-22 18:59:44.163 ThaliTest[1041:1891002] [CDVTimer][gesturehandler] 0.353992ms
2016-12-22 18:59:44.163 ThaliTest[1041:1891002] [CDVTimer][TotalPlugin,Startup] 13.172984ms
,2016-12-22 18:59:50.404 ThaliTest[1041:1891002] Resetting plugins due to page load.
,2016-12-22 18:59:50.900 ThaliTest[1041:1891002] Finished load of: file:///var/containers/Bundle/Application/5D0B3667-3FE9-442A-82A5-3E1406A6EB11/ThaliTest.app/www/index.html
,2016-12-22 18:59:51.356 ThaliTest[1041:1891002] JXcore Cordova plugin initializing
,2016-12-22 18:59:51.357 ThaliTest[1041:1891175] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-22 18:00:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-22 18:00:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-22 18:00:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-22 18:00:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-22 18:00:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-22 18:00:31 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  27.22289502620697
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
