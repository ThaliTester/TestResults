#### Test 10191057309b3d0c_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10191057309b3d0c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0F90DFEA-3ABB-4851-B143-1AE7E8837442/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/0F90DFEA-3ABB-4851-B143-1AE7E8837442/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10191057309b3d0c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10191057309b3d0c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9BB1881A-842B-4394-8E71-6C67BE7EAB49/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61383"
,(lldb)     command script import "/tmp/0F90DFEA-3ABB-4851-B143-1AE7E8837442/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-18 12:36:15.093 ThaliTest[1665:5905598] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0470E170-88A6-4A98-A19B-EFD1712B0AC7/Library/Cookies/Cookies.binarycookies
,2017-01-18 12:36:15.270 ThaliTest[1665:5905598] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-18 12:36:15.273 ThaliTest[1665:5905598] Multi-tasking -> Device: YES, App: YES
,2017-01-18 12:36:15.302 ThaliTest[1665:5905598] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-18 12:36:15.830 ThaliTest[1665:5905598] Using UIWebView
,2017-01-18 12:36:15.839 ThaliTest[1665:5905598] [CDVTimer][handleopenurl] 0.456989ms
2017-01-18 12:36:15.847 ThaliTest[1665:5905598] [CDVTimer][intentandnavigationfilter] 7.071972ms
2017-01-18 12:36:15.848 ThaliTest[1665:5905598] [CDVTimer][gesturehandler] 0.303984ms
2017-01-18 12:36:15.848 ThaliTest[1665:5905598] [CDVTimer][TotalPluginStartup] 9.201944ms
,2017-01-18 12:36:22.939 ThaliTest[1665:5905598] Resetting plugins due to page load.
,2017-01-18 12:36:23.520 ThaliTest[1665:5905598] Finished load of: file:///var/containers/Bundle/Application/9BB1881A-842B-4394-8E71-6C67BE7EAB49/ThaliTest.app/www/index.html
,2017-01-18 12:36:23.797 ThaliTest[1665:5905598] JXcore Cordova plugin initializing
2017-01-18 12:36:23.799 ThaliTest[1665:5905742] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-18 11:37:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-18 11:37:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-18 11:37:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-18 11:37:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-18 11:37:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-18 11:37:34 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  29.84919100999832
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
