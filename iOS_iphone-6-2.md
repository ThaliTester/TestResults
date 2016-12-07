#### Test 953210620aa0610_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/F68AFFAD-B87B-4464-A02B-57F866176949/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F68AFFAD-B87B-4464-A02B-57F866176949/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/953210620aa0610/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9E147DDE-79DF-4AC9-9E2C-6351AE278136/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54849"
,(lldb)     command script import "/tmp/F68AFFAD-B87B-4464-A02B-57F866176949/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 16:47:16.714 ThaliTest[340:138566] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5E0CD48D-2A76-4E7C-9EEA-D7CD80BE3749/Library/Cookies/Cookies.binarycookies
,2016-12-07 16:47:16.755 ThaliTest[340:138566] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 16:47:16.756 ThaliTest[340:138566] Multi-tasking -> Device: YES, App: YES
,2016-12-07 16:47:16.769 ThaliTest[340:138566] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 16:47:17.100 ThaliTest[340:138566] Using UIWebView
,2016-12-07 16:47:17.105 ThaliTest[340:138566] [CDVTimer][handleopenurl] 0.257969ms
,2016-12-07 16:47:17.109 ThaliTest[340:138566] [CDVTimer][intentandnavigationfilter] 4.668951ms
2016-12-07 16:47:17.110 ThaliTest[340:138566] [CDVTimer][gesturehandler] 0.152946ms
2016-12-07 16:47:17.110 ThaliTest[340:138566] [CDVTimer][TotalPluginStartup,] 5.908966ms
,2016-12-07 16:47:22.629 ThaliTest[340:138566] Resetting plugins due to page load.
,2016-12-07 16:47:23.152 ThaliTest[340:138566] Finished load of: file:///var/containers/Bundle/Application/9E147DDE-79DF-4AC9-9E2C-6351AE278136/ThaliTest.app/www/index.html
,2016-12-07 16:47:23.555 ThaliTest[340:138566] JXcore Cordova plugin initializing
2016-12-07 16:47:23.556 ThaliTest[340:138739] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 15:47:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 15:47:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 15:47:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 15:47:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 15:47:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 15:47:59 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.77551501989365
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
