#### Test 99261278b72b2a5_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99261278b72b2a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/4999569D-47CD-49C4-A210-48072DD3CFC0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/4999569D-47CD-49C4-A210-48072DD3CFC0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99261278b72b2a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99261278b72b2a5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1DF1F67E-E089-4658-933B-E473AFE8507C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64595"
,(lldb)     command script import "/tmp/4999569D-47CD-49C4-A210-48072DD3CFC0/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 15:07:14.875 ThaliTest[1132:3351367] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E839E257-4AB6-489C-88BF-26EDDA6E4E81/Library/Cookies/Cookies.binarycookies
,2016-12-29 15:07:15.015 ThaliTest[1132:3351367] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 15:07:15.017 ThaliTest[1132:3351367] Multi-tasking -> Device: YES, App: YES
,2016-12-29 15:07:15.045 ThaliTest[1132:3351367] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 15:07:15.833 ThaliTest[1132:3351367] Using UIWebView
,2016-12-29 15:07:15.839 ThaliTest[1132:3351367] [CDVTimer][handleopenurl] 0.496030ms
,2016-12-29 15:07:15.847 ThaliTest[1132:3351367] [CDVTimer][intentandnavigationfilter] 7.207990ms
2016-12-29 15:07:15.848 ThaliTest[1132:3351367] [CDVTimer][gesturehandler] 0.325978ms
2016-12-29 15:07:15.848 ThaliTest[1132:3351367] [CDVTimer][TotalPluginStartup] 9.413004ms
,2016-12-29 15:07:26.307 ThaliTest[1132:3351367] Resetting plugins due to page load.
,2016-12-29 15:07:27.048 ThaliTest[1132:3351367] Finished load of: file:///var/containers/Bundle/Application/1DF1F67E-E089-4658-933B-E473AFE8507C/ThaliTest.app/www/index.html
,2016-12-29 15:07:27.284 ThaliTest[1132:3351367] JXcore Cordova plugin initializing
,2016-12-29 15:07:27.285 ThaliTest[1132:3351563] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 14:08:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 14:08:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 14:08:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-29 14:08:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 14:08:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-29 14:08:37 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  33.31890600919724
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
