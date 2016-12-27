#### Test 99374565572e946_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/EF205FE1-9533-4502-A4AC-CD656B6D339C/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/EF205FE1-9533-4502-A4AC-CD656B6D339C/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/70DEEE23-F412-405B-9C3C-03BF57850D09/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64633"
,(lldb)     command script import "/tmp/EF205FE1-9533-4502-A4AC-CD656B6D339C/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 14:14:41.390 ThaliTest[1019:3040584] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/78CB03CC-3A70-42A7-A2B2-1E84EC759B9A/Library/Cookies/Cookies.binarycookies
,2016-12-27 14:14:41.535 ThaliTest[1019:3040584] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 14:14:41.538 ThaliTest[1019:3040584] Multi-tasking -> Device: YES, App: YES
,2016-12-27 14:14:41.564 ThaliTest[1019:3040584] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 14:14:42.339 ThaliTest[1019:3040584] Using UIWebView
,2016-12-27 14:14:42.345 ThaliTest[1019:3040584] [CDVTimer][handleopenurl] 0.563979ms
,2016-12-27 14:14:42.353 ThaliTest[1019:3040584] [CDVTimer][intentandnavigationfilter] 7.166982ms
2016-12-27 14:14:42.354 ThaliTest[1019:3040584] [CDVTimer][gesturehandler] 0.328958ms
2016-12-27 14:14:42.354 ThaliTest[1019:3040584] [CDVTimer][TotalPluginS,tartup] 9.415984ms
,2016-12-27 14:14:52.723 ThaliTest[1019:3040584] Resetting plugins due to page load.
,2016-12-27 14:14:53.489 ThaliTest[1019:3040584] Finished load of: file:///var/containers/Bundle/Application/70DEEE23-F412-405B-9C3C-03BF57850D09/ThaliTest.app/www/index.html
,2016-12-27 14:14:53.717 ThaliTest[1019:3040584] JXcore Cordova plugin initializing
,2016-12-27 14:14:53.721 ThaliTest[1019:3040759] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 13:15:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 13:15:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 13:15:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-27 13:15:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 13:15:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 13:16:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.59024405479431
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
