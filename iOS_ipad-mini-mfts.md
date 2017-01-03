#### Test 995727499fee306_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/086C03D2-4164-4019-BD05-10F1D1E11695/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/086C03D2-4164-4019-BD05-10F1D1E11695/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/16C003A7-6F1E-4BFE-ABFC-834B3A3CD48D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55707"
,(lldb)     command script import "/tmp/086C03D2-4164-4019-BD05-10F1D1E11695/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 11:34:14.327 ThaliTest[1251:4041076] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/73E5518E-C104-4765-9E2F-9FB4265ABF35/Library/Cookies/Cookies.binarycookies
,2017-01-03 11:34:14.483 ThaliTest[1251:4041076] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 11:34:14.487 ThaliTest[1251:4041076] Multi-tasking -> Device: YES, App: YES
,2017-01-03 11:34:14.519 ThaliTest[1251:4041076] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 11:34:15.302 ThaliTest[1251:4041076] Using UIWebView
,2017-01-03 11:34:15.311 ThaliTest[1251:4041076] [CDVTimer][handleopenurl] 0.505030ms
,2017-01-03 11:34:15.319 ThaliTest[1251:4041076] [CDVTimer][intentandnavigationfilter] 7.509053ms
2017-01-03 11:34:15.320 ThaliTest[1251:4041076] [CDVTimer][gesturehandler] 0.339985ms
2017-01-03 11:34:15.320 ThaliTest[1251:4041076] [CDVTimer][TotalPluginStartup] 9.701967ms
,2017-01-03 11:34:26.071 ThaliTest[1251:4041076] Resetting plugins due to page load.
,2017-01-03 11:34:26.870 ThaliTest[1251:4041076] Finished load of: file:///var/containers/Bundle/Application/16C003A7-6F1E-4BFE-ABFC-834B3A3CD48D/ThaliTest.app/www/index.html
,2017-01-03 11:34:27.109 ThaliTest[1251:4041076] JXcore Cordova plugin initializing
,2017-01-03 11:34:27.111 ThaliTest[1251:4041278] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 10:35:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-03 10:35:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 10:35:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-01-03 10:35:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-03 10:35:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-03 10:35:43 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  34.826789021492
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
