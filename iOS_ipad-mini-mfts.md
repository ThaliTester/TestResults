#### Test 99448283f49b3a7_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AF19FAC4-2AE3-429F-BDDE-98396A222A12/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/AF19FAC4-2AE3-429F-BDDE-98396A222A12/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7C908635-D9FC-46C7-BF68-D44C57CD769C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50795"
,(lldb)     command script import "/tmp/AF19FAC4-2AE3-429F-BDDE-98396A222A12/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 16:57:19.278 ThaliTest[1091:3213447] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0E8A3CC-009B-4F63-880C-DA5C850F14EB/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:57:19.413 ThaliTest[1091:3213447] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:57:19.416 ThaliTest[1091:3213447] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:57:19.441 ThaliTest[1091:3213447] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:57:20.089 ThaliTest[1091:3213447] Using UIWebView
,2016-12-28 16:57:20.096 ThaliTest[1091:3213447] [CDVTimer][handleopenurl] 0.459969ms
,2016-12-28 16:57:20.104 ThaliTest[1091:3213447] [CDVTimer][intentandnavigationfilter] 7.647038ms
2016-12-28 16:57:20.104 ThaliTest[1091:3213447] [CDVTimer][gesturehandler] 0.353038ms
2016-12-28 16:57:20.105 ThaliTest[1091:3213447] [CDVTimer][TotalPluginS,tartup] 9.983957ms
,2016-12-28 16:57:28.905 ThaliTest[1091:3213447] Resetting plugins due to page load.
,2016-12-28 16:57:29.600 ThaliTest[1091:3213447] Finished load of: file:///var/containers/Bundle/Application/7C908635-D9FC-46C7-BF68-D44C57CD769C/ThaliTest.app/www/index.html
,2016-12-28 16:57:29.829 ThaliTest[1091:3213447] JXcore Cordova plugin initializing
2016-12-28 16:57:29.834 ThaliTest[1091:3213623] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:58:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:58:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:58:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-28 15:58:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:58:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-28 15:58:40 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  33.69876700639725
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
