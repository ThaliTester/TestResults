#### Test 103941844b3b02b3_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103941844b3b02b3/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8ECB765C-FE9E-4487-9DD9-EAD39F4560C2/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/8ECB765C-FE9E-4487-9DD9-EAD39F4560C2/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103941844b3b02b3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103941844b3b02b3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/37B38DE1-2A9A-476F-B553-E1A533041185/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57374"
,(lldb)     command script import "/tmp/8ECB765C-FE9E-4487-9DD9-EAD39F4560C2/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-31 15:38:05.497 ThaliTest[2101:7858813] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CC68743C-2075-41F3-AEA8-01688DD29ED9/Library/Cookies/Cookies.binarycookies
,2017-01-31 15:38:05.648 ThaliTest[2101:7858813] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-31 15:38:05.650 ThaliTest[2101:7858813] Multi-tasking -> Device: YES, App: YES
,2017-01-31 15:38:05.677 ThaliTest[2101:7858813] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-31 15:38:06.457 ThaliTest[2101:7858813] Using UIWebView
,2017-01-31 15:38:06.464 ThaliTest[2101:7858813] [CDVTimer][handleopenurl] 0.630975ms
,2017-01-31 15:38:06.472 ThaliTest[2101:7858813] [CDVTimer][intentandnavigationfilter] 7.483959ms
2017-01-31 15:38:06.473 ThaliTest[2101:7858813] [CDVTimer][gesturehandler] 0.331998ms
2017-01-31 15:38:06.473 ThaliTest[2101:7858813] [CDVTimer][TotalPluginStartup] 9.792984ms
,2017-01-31 15:38:17.060 ThaliTest[2101:7858813] Resetting plugins due to page load.
,2017-01-31 15:38:17.863 ThaliTest[2101:7858813] Finished load of: file:///var/containers/Bundle/Application/37B38DE1-2A9A-476F-B553-E1A533041185/ThaliTest.app/www/index.html
,2017-01-31 15:38:18.113 ThaliTest[2101:7858813] JXcore Cordova plugin initializing
,2017-01-31 15:38:18.116 ThaliTest[2101:7858991] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-31 14:38:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-31 14:38:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-31 14:38:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-31 14:38:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-31 14:38:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-31 14:39:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  34.03596198558807
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
