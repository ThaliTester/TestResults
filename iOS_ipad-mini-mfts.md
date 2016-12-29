#### Test 9965213169fe96d_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/95314C29-E2C6-42CD-BB23-AF4DE45B150E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/95314C29-E2C6-42CD-BB23-AF4DE45B150E/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FCD8CA00-FF9C-4EF8-80D7-9ACC1AD94B54/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62910"
,(lldb)     command script import "/tmp/95314C29-E2C6-42CD-BB23-AF4DE45B150E/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 14:36:36.694 ThaliTest[1127:3347241] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D0785EC2-59BE-4628-B522-09AFFBAB6748/Library/Cookies/Cookies.binarycookies
,2016-12-29 14:36:36.838 ThaliTest[1127:3347241] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 14:36:36.840 ThaliTest[1127:3347241] Multi-tasking -> Device: YES, App: YES
,2016-12-29 14:36:36.863 ThaliTest[1127:3347241] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 14:36:37.495 ThaliTest[1127:3347241] Using UIWebView
,2016-12-29 14:36:37.502 ThaliTest[1127:3347241] [CDVTimer][handleopenurl] 0.506997ms
,2016-12-29 14:36:37.509 ThaliTest[1127:3347241] [CDVTimer][intentandnavigationfilter] 7.331014ms
2016-12-29 14:36:37.510 ThaliTest[1127:3347241] [CDVTimer][gesturehandler] 0.329971ms
2016-12-29 14:36:37.511 ThaliTest[1127:3347241] [CDVTimer][TotalPluginStartup] 9.555995ms
,2016-12-29 14:36:46.321 ThaliTest[1127:3347241] Resetting plugins due to page load.
,2016-12-29 14:36:46.996 ThaliTest[1127:3347241] Finished load of: file:///var/containers/Bundle/Application/FCD8CA00-FF9C-4EF8-80D7-9ACC1AD94B54/ThaliTest.app/www/index.html
,2016-12-29 14:36:47.235 ThaliTest[1127:3347241] JXcore Cordova plugin initializing
,2016-12-29 14:36:47.236 ThaliTest[1127:3347414] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 13:37:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 13:37:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-29 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 13:37:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-29 13:37:58 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  34.22608000040054
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
