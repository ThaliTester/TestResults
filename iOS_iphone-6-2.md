#### Test 98312760b2c4df9_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/58E36307-ABEF-4A25-9E9A-235B11F3B66B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/58E36307-ABEF-4A25-9E9A-235B11F3B66B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1F48417A-DB99-46EF-997C-EB803429463E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61610"
,(lldb)     command script import "/tmp/58E36307-ABEF-4A25-9E9A-235B11F3B66B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 15:13:22.733 ThaliTest[979:1522400] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/41B7F58F-1F29-4034-A791-AEFA9FE709EA/Library/Cookies/Cookies.binarycookies
,2016-12-19 15:13:22.833 ThaliTest[979:1522400] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 15:13:22.836 ThaliTest[979:1522400] Multi-tasking -> Device: YES, App: YES
,2016-12-19 15:13:22.857 ThaliTest[979:1522400] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 15:13:23.358 ThaliTest[979:1522400] Using UIWebView
,2016-12-19 15:13:23.365 ThaliTest[979:1522400] [CDVTimer][handleopenurl] 0.467956ms
,2016-12-19 15:13:23.374 ThaliTest[979:1522400] [CDVTimer][intentandnavigationfilter] 8.377016ms
2016-12-19 15:13:23.374 ThaliTest[979:1522400] [CDVTimer][gesturehandler] 0.310004ms
2016-12-19 15:13:23.375 ThaliTest[979:1522400] [CDVTimer][TotalPluginStar,tup] 10.829985ms
,2016-12-19 15:13:29.301 ThaliTest[979:1522400] Resetting plugins due to page load.
,2016-12-19 15:13:29.734 ThaliTest[979:1522400] Finished load of: file:///var/containers/Bundle/Application/1F48417A-DB99-46EF-997C-EB803429463E/ThaliTest.app/www/index.html
,2016-12-19 15:13:30.076 ThaliTest[979:1522400] JXcore Cordova plugin initializing
,2016-12-19 15:13:30.077 ThaliTest[979:1522565] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 14:13:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 14:13:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 14:13:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-19 14:13:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 14:13:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-19 14:14:05 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.89618498086929
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
