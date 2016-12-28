#### Test 99529739424d9f5_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/676F2208-987B-4DA0-9DBC-518052800DDE/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/676F2208-987B-4DA0-9DBC-518052800DDE/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/883067BA-AC81-493B-8987-37E2E18F0B81/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57375"
,(lldb)     command script import "/tmp/676F2208-987B-4DA0-9DBC-518052800DDE/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 11:22:28.384 ThaliTest[1060:3173880] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5DB908A7-108B-41CD-A4C0-7FAFFC4B9BBE/Library/Cookies/Cookies.binarycookies
,2016-12-28 11:22:28.525 ThaliTest[1060:3173880] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 11:22:28.529 ThaliTest[1060:3173880] Multi-tasking -> Device: YES, App: YES
,2016-12-28 11:22:28.557 ThaliTest[1060:3173880] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 11:22:29.208 ThaliTest[1060:3173880] Using UIWebView
,2016-12-28 11:22:29.215 ThaliTest[1060:3173880] [CDVTimer][handleopenurl] 0.569046ms
,2016-12-28 11:22:29.222 ThaliTest[1060:3173880] [CDVTimer][intentandnavigationfilter] 7.127941ms
2016-12-28 11:22:29.223 ThaliTest[1060:3173880] [CDVTimer][gesturehandler] 0.334978ms
2016-12-28 11:22:29.223 ThaliTest[1060:3173880] [CDVTimer][TotalPluginStartup] 9.391010ms
,2016-12-28 11:22:38.005 ThaliTest[1060:3173880] Resetting plugins due to page load.
,2016-12-28 11:22:38.688 ThaliTest[1060:3173880] Finished load of: file:///var/containers/Bundle/Application/883067BA-AC81-493B-8987-37E2E18F0B81/ThaliTest.app/www/index.html
,2016-12-28 11:22:38.925 ThaliTest[1060:3173880] JXcore Cordova plugin initializing
2016-12-28 11:22:38.927 ThaliTest[1060:3174049] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 10:23:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 10:23:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 10:23:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-28 10:23:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 10:23:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 10:23:48 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.43400001525879
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
