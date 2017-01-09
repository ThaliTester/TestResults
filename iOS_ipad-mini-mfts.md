#### Test 1006908264485454_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/40C45ADE-9E08-4ED0-A8A4-512C2F3F669B/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/40C45ADE-9E08-4ED0-A8A4-512C2F3F669B/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/52DAB07C-9937-48F5-BD2C-CB2D450106A6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57297"
,(lldb)     command script import "/tmp/40C45ADE-9E08-4ED0-A8A4-512C2F3F669B/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-09 15:40:23.883 ThaliTest[1435:4888790] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0EDF5592-3C17-4736-AF54-D76808F5B7BE/Library/Cookies/Cookies.binarycookies
,2017-01-09 15:40:24.032 ThaliTest[1435:4888790] Apache Cordova native platform version 4.3.1 is starting.
2017-01-09 15:40:24.035 ThaliTest[1435:4888790] Multi-tasking -> Device: YES, App: YES
,2017-01-09 15:40:24.060 ThaliTest[1435:4888790] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-09 15:40:24.486 ThaliTest[1435:4888790] Using UIWebView
,2017-01-09 15:40:24.496 ThaliTest[1435:4888790] [CDVTimer][handleopenurl] 0.465989ms
,2017-01-09 15:40:24.504 ThaliTest[1435:4888790] [CDVTimer][intentandnavigationfilter] 7.390022ms
2017-01-09 15:40:24.505 ThaliTest[1435:4888790] [CDVTimer][gesturehandler] 0.329018ms
2017-01-09 15:40:24.505 ThaliTest[1435:4888790] [CDVTimer][TotalPluginS,tartup] 9.836018ms
,2017-01-09 15:40:30.274 ThaliTest[1435:4888790] Resetting plugins due to page load.
,2017-01-09 15:40:30.791 ThaliTest[1435:4888790] Finished load of: file:///var/containers/Bundle/Application/52DAB07C-9937-48F5-BD2C-CB2D450106A6/ThaliTest.app/www/index.html
,2017-01-09 15:40:31.073 ThaliTest[1435:4888790] JXcore Cordova plugin initializing
2017-01-09 15:40:31.075 ThaliTest[1435:4888933] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-09 14:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-09 14:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-09 14:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-09 14:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-09 14:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-09 14:41:44 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  36.07572799921036
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
