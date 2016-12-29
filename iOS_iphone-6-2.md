#### Test 992473934db55e8_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9E3F8CCA-00F1-4420-934F-104D95D053CE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/9E3F8CCA-00F1-4420-934F-104D95D053CE/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F3EC190B-BD1C-4A48-959E-D75F9F023EA2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61469"
,(lldb)     command script import "/tmp/9E3F8CCA-00F1-4420-934F-104D95D053CE/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 14:07:06.528 ThaliTest[1576:2815077] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/80AE8AE5-FA36-4CED-989E-7B411B91C296/Library/Cookies/Cookies.binarycookies
,2016-12-29 14:07:06.571 ThaliTest[1576:2815077] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 14:07:06.572 ThaliTest[1576:2815077] Multi-tasking -> Device: YES, App: YES
,2016-12-29 14:07:06.585 ThaliTest[1576:2815077] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 14:07:06.900 ThaliTest[1576:2815077] Using UIWebView
2016-12-29 14:07:06.904 ThaliTest[1576:2815077] [CDVTimer][handleopenurl] 0.172019ms
,2016-12-29 14:07:06.909 ThaliTest[1576:2815077] [CDVTimer][intentandnavigationfilter] 4.823983ms
2016-12-29 14:07:06.909 ThaliTest[1576:2815077] [CDVTimer][gesturehandler] 0.147998ms
2016-12-29 14:07:06.909 ThaliTest[1576:2815077] [CDVTimer][TotalPluginStartup] 5.911052ms
,2016-12-29 14:07:12.965 ThaliTest[1576:2815077] Resetting plugins due to page load.
,2016-12-29 14:07:13.276 ThaliTest[1576:2815077] Finished load of: file:///var/containers/Bundle/Application/F3EC190B-BD1C-4A48-959E-D75F9F023EA2/ThaliTest.app/www/index.html
,2016-12-29 14:07:13.636 ThaliTest[1576:2815077] JXcore Cordova plugin initializing
,2016-12-29 14:07:13.637 ThaliTest[1576:2815248] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 13:07:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 13:07:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 13:07:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-29 13:07:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 13:07:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-29 13:07:49 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.30000901222229
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
