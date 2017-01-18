#### Test 1019105739e32531_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/338DABB5-6FEE-4B56-B0A6-1B6C32C5EAD0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/338DABB5-6FEE-4B56-B0A6-1B6C32C5EAD0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1019105739e32531/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C079B0CC-5B7D-4963-A8FD-4D963208DC81/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63279"
,(lldb)     command script import "/tmp/338DABB5-6FEE-4B56-B0A6-1B6C32C5EAD0/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-18 14:00:33.864 ThaliTest[1674:5916266] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/520448A4-9A39-419E-991D-F4D20B9D9A0D/Library/Cookies/Cookies.binarycookies
,2017-01-18 14:00:34.014 ThaliTest[1674:5916266] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-18 14:00:34.017 ThaliTest[1674:5916266] Multi-tasking -> Device: YES, App: YES
,2017-01-18 14:00:34.041 ThaliTest[1674:5916266] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-18 14:00:34.456 ThaliTest[1674:5916266] Using UIWebView
2017-01-18 14:00:34.462 ThaliTest[1674:5916266] [CDVTimer][handleopenurl] 0.434995ms
2017-01-18 14:00:34.470 ThaliTest[1674:5916266] [CDVTimer][intentandnavigationfilter] 7.310987ms
2017-01,-18 14:00:34.470 ThaliTest[1674:5916266] [CDVTimer][gesturehandler] 0.324011ms
2017-01-18 14:00:34.471 ThaliTest[1674:5916266] [CDVTimer][TotalPluginStartup] 9.338021ms
,2017-01-18 14:00:40.197 ThaliTest[1674:5916266] Resetting plugins due to page load.
,2017-01-18 14:00:40.705 ThaliTest[1674:5916266] Finished load of: file:///var/containers/Bundle/Application/C079B0CC-5B7D-4963-A8FD-4D963208DC81/ThaliTest.app/www/index.html
,2017-01-18 14:00:40.969 ThaliTest[1674:5916266] JXcore Cordova plugin initializing
2017-01-18 14:00:40.971 ThaliTest[1674:5916404] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-18 13:01:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-18 13:01:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-18 13:01:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-18 13:01:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-18 13:01:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-18 13:01:53 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  31.28176200389862
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
