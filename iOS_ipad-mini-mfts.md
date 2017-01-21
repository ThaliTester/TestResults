#### Test 1025817085707029_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1025817085707029/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/76C75F1E-B26F-4F80-858C-0146E357FFD3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/76C75F1E-B26F-4F80-858C-0146E357FFD3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1025817085707029/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1025817085707029/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/33275E72-09B0-4508-886C-F3A711B01363/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60917"
,(lldb)     command script import "/tmp/76C75F1E-B26F-4F80-858C-0146E357FFD3/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-21 14:22:08.833 ThaliTest[1761:6349452] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/26455750-C03F-436B-AEA7-517EEA9CAD98/Library/Cookies/Cookies.binarycookies
,2017-01-21 14:22:08.987 ThaliTest[1761:6349452] Apache Cordova native platform version 4.3.1 is starting.
2017-01-21 14:22:08.989 ThaliTest[1761:6349452] Multi-tasking -> Device: YES, App: YES
,2017-01-21 14:22:09.015 ThaliTest[1761:6349452] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-21 14:22:09.430 ThaliTest[1761:6349452] Using UIWebView
,2017-01-21 14:22:09.439 ThaliTest[1761:6349452] [CDVTimer][handleopenurl] 0.633001ms
,2017-01-21 14:22:09.446 ThaliTest[1761:6349452] [CDVTimer][intentandnavigationfilter] 7.125974ms
,2017-01-21 14:22:09.447 ThaliTest[1761:6349452] [CDVTimer][gesturehandler] 0.520051ms
,2017-01-21 14:22:09.448 ThaliTest[1761:6349452] [CDVTimer][TotalPluginStartup] 9.734035ms
,2017-01-21 14:22:15.329 ThaliTest[1761:6349452] Resetting plugins due to page load.
,2017-01-21 14:22:15.850 ThaliTest[1761:6349452] Finished load of: file:///var/containers/Bundle/Application/33275E72-09B0-4508-886C-F3A711B01363/ThaliTest.app/www/index.html
,2017-01-21 14:22:16.120 ThaliTest[1761:6349452] JXcore Cordova plugin initializing
2017-01-21 14:22:16.122 ThaliTest[1761:6349597] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-21 13:22:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-21 13:22:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-21 13:22:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-21 13:22:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-21 13:22:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-21 13:23:29 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  32.5614709854126
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
