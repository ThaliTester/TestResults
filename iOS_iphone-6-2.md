#### Test 10045281117fe266_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10045281117fe266/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B8110C3A-022D-4F0A-B2D9-77DBDC41BCBB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/B8110C3A-022D-4F0A-B2D9-77DBDC41BCBB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10045281117fe266/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10045281117fe266/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/521C5C99-C871-4A18-AFAE-4BF025FF7B34/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64719"
,(lldb)     command script import "/tmp/B8110C3A-022D-4F0A-B2D9-77DBDC41BCBB/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-06 14:02:42.044 ThaliTest[1879:3883970] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E7AB20E-85B7-4B9C-8CC3-BD4C8192FCFE/Library/Cookies/Cookies.binarycookies
,2017-01-06 14:02:42.084 ThaliTest[1879:3883970] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-06 14:02:42.085 ThaliTest[1879:3883970] Multi-tasking -> Device: YES, App: YES
,2017-01-06 14:02:42.098 ThaliTest[1879:3883970] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-06 14:02:42.367 ThaliTest[1879:3883970] Using UIWebView
,2017-01-06 14:02:42.370 ThaliTest[1879:3883970] [CDVTimer][handleopenurl] 0.105023ms
,2017-01-06 14:02:42.373 ThaliTest[1879:3883970] [CDVTimer][intentandnavigationfilter] 2.996981ms
2017-01-06 14:02:42.374 ThaliTest[1879:3883970] [CDVTimer][gesturehandler] 0.099957ms
2017-01-06 14:02:42.374 ThaliTest[1879:3883970] [CDVTimer][TotalPluginStartup] 3.755987ms
,2017-01-06 14:02:45.723 ThaliTest[1879:3883970] Resetting plugins due to page load.
,2017-01-06 14:02:45.979 ThaliTest[1879:3883970] Finished load of: file:///var/containers/Bundle/Application/521C5C99-C871-4A18-AFAE-4BF025FF7B34/ThaliTest.app/www/index.html
,2017-01-06 14:02:46.305 ThaliTest[1879:3883970] JXcore Cordova plugin initializing
2017-01-06 14:02:46.306 ThaliTest[1879:3884143] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-06 13:02:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-06 13:02:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-06 13:02:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2017-01-06 13:02:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-06 13:02:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "found peer from another AppContext". in file: Optional("<unknown>"), line: 0
,2017-01-06 13:03:32 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  35.00555700063705
,Failed to execute UT.
,2017-01-06 13:03:32 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
