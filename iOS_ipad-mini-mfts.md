#### Test 9967484811caee1_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/CC9B08AC-787E-4058-A3BB-F18726BEB1D5/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/CC9B08AC-787E-4058-A3BB-F18726BEB1D5/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/87767FE7-2070-4395-A24D-3DCC4FCEE48D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50007"
,(lldb)     command script import "/tmp/CC9B08AC-787E-4058-A3BB-F18726BEB1D5/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 18:12:30.126 ThaliTest[1140:3370503] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D061BE17-71EA-4D66-B25B-87BC211C2446/Library/Cookies/Cookies.binarycookies
,2016-12-29 18:12:30.265 ThaliTest[1140:3370503] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 18:12:30.269 ThaliTest[1140:3370503] Multi-tasking -> Device: YES, App: YES
,2016-12-29 18:12:30.297 ThaliTest[1140:3370503] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 18:12:31.069 ThaliTest[1140:3370503] Using UIWebView
,2016-12-29 18:12:31.075 ThaliTest[1140:3370503] [CDVTimer][handleopenurl] 0.542998ms
,2016-12-29 18:12:31.083 ThaliTest[1140:3370503] [CDVTimer][intentandnavigationfilter] 7.216990ms
2016-12-29 18:12:31.083 ThaliTest[1140:3370503] [CDVTimer][gesturehandler] 0.326037ms
2016-12-29 18:12:31.084 ThaliTest[1140:3370503] [CDVTimer][TotalPluginStartup] 9.446979ms
,2016-12-29 18:12:41.634 ThaliTest[1140:3370503] Resetting plugins due to page load.
,2016-12-29 18:12:42.408 ThaliTest[1140:3370503] Finished load of: file:///var/containers/Bundle/Application/87767FE7-2070-4395-A24D-3DCC4FCEE48D/ThaliTest.app/www/index.html
,2016-12-29 18:12:42.643 ThaliTest[1140:3370503] JXcore Cordova plugin initializing
,2016-12-29 18:12:42.645 ThaliTest[1140:3370693] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 17:13:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 17:13:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 17:13:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-29 17:13:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 17:13:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-29 17:13:52 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.98625600337982
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
