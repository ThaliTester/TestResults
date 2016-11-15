#### Test 93765317fadb314_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/9B28F862-E54B-4DD7-8CA2-F4705564CE31/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/9B28F862-E54B-4DD7-8CA2-F4705564CE31/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93765317fadb314/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/ED8A35B7-D0B4-493D-9853-8000077762A8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57422"
,(lldb)     command script import "/tmp/9B28F862-E54B-4DD7-8CA2-F4705564CE31/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 06:52:06.906 ThaliTest[3491:7939914] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9029E2F1-2665-44A7-920D-A9D754F23C3F/Library/Cookies/Cookies.binarycookies
,2016-11-15 06:52:06.947 ThaliTest[3491:7939914] Apache Cordova native platform version 4.2.1 is starting.
2016-11-15 06:52:06.948 ThaliTest[3491:7939914] Multi-tasking -> Device: YES, App: YES
,2016-11-15 06:52:06.958 ThaliTest[3491:7939914] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 06:52:07.282 ThaliTest[3491:7939914] Using UIWebView
,2016-11-15 06:52:07.286 ThaliTest[3491:7939914] [CDVTimer][handleopenurl] 0.261962ms
,2016-11-15 06:52:07.290 ThaliTest[3491:7939914] [CDVTimer][intentandnavigationfilter] 3.624976ms
2016-11-15 06:52:07.290 ThaliTest[3491:7939914] [CDVTimer][gesturehandler] 0.150025ms
2016-11-15 06:52:07.290 ThaliTest[3491:7939914] [CDVTimer][TotalPluginStartup] 4.867971ms
,2016-11-15 06:52:13.657 ThaliTest[3491:7939914] Resetting plugins due to page load.
,2016-11-15 06:52:14.329 ThaliTest[3491:7939914] Finished load of: file:///var/containers/Bundle/Application/ED8A35B7-D0B4-493D-9853-8000077762A8/ThaliTest.app/www/index.html
,2016-11-15 06:52:14.739 ThaliTest[3491:7939914] JXcore Cordova plugin initializing
2016-11-15 06:52:14.740 ThaliTest[3491:7940084] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 14:52:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 14:52:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-15 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-15 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,2016-11-15 14:53:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  40.12191897630692
F,ailed to execute UT.
2016-11-15 14:53:05 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
```
