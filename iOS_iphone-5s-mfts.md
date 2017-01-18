#### Test 1019105739e32531_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/83E6FF4B-EFBC-4303-B7A5-CBB31550E650/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/83E6FF4B-EFBC-4303-B7A5-CBB31550E650/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/97437E72-E209-4060-8044-AEFDD152FC7B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63285"
,(lldb)     command script import "/tmp/83E6FF4B-EFBC-4303-B7A5-CBB31550E650/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-18 14:01:20.546 ThaliTest[416:713578] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C4B7EF8A-2F8B-41E8-A0A7-BC902A3D0B2E/Library/Cookies/Cookies.binarycookies
,2017-01-18 14:01:20.642 ThaliTest[416:713578] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-18 14:01:20.644 ThaliTest[416:713578] Multi-tasking -> Device: YES, App: YES
,2017-01-18 14:01:20.667 ThaliTest[416:713578] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-18 14:01:21.158 ThaliTest[416:713578] Using UIWebView
,2017-01-18 14:01:21.166 ThaliTest[416:713578] [CDVTimer][handleopenurl] 0.398993ms
,2017-01-18 14:01:21.177 ThaliTest[416:713578] [CDVTimer][intentandnavigationfilter] 9.984016ms
2017-01-18 14:01:21.178 ThaliTest[416:713578] [CDVTimer][gesturehandler] 0.355005ms
2017-01-18 14:01:21.178 ThaliTest[416:713578] [CDVTimer][TotalPluginStartup,] 12.664974ms
,2017-01-18 14:01:28.575 ThaliTest[416:713578] Resetting plugins due to page load.
,2017-01-18 14:01:28.991 ThaliTest[416:713578] Finished load of: file:///var/containers/Bundle/Application/97437E72-E209-4060-8044-AEFDD152FC7B/ThaliTest.app/www/index.html
,2017-01-18 14:01:29.393 ThaliTest[416:713578] JXcore Cordova plugin initializing
,2017-01-18 14:01:29.394 ThaliTest[416:713788] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-18 13:01:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-18 13:01:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-18 13:01:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2017-01-18 13:01:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-18 13:01:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-18 13:02:08 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.28209203481674
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
