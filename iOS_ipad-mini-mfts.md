#### Test 102271039a5a4541_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/04D2B427-3843-4032-AEE8-0DFD98EE07EC/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/04D2B427-3843-4032-AEE8-0DFD98EE07EC/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7B507ABD-69F2-4FBE-BE84-784B78E9889C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63955"
,(lldb)     command script import "/tmp/04D2B427-3843-4032-AEE8-0DFD98EE07EC/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 18:12:52.218 ThaliTest[1880:6808841] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/132E1D70-611D-4C0B-8CC9-D1FEB62082A2/Library/Cookies/Cookies.binarycookies
,2017-01-24 18:12:52.373 ThaliTest[1880:6808841] Apache Cordova native platform version 4.3.1 is starting.
2017-01-24 18:12:52.375 ThaliTest[1880:6808841] Multi-tasking -> Device: YES, App: YES
,2017-01-24 18:12:52.400 ThaliTest[1880:6808841] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 18:12:52.913 ThaliTest[1880:6808841] Using UIWebView
2017-01-24 18:12:52.919 ThaliTest[1880:6808841] [CDVTimer][handleopenurl] 0.451982ms
,2017-01-24 18:12:52.928 ThaliTest[1880:6808841] [CDVTimer][intentandnavigationfilter] 8.394003ms
2017-01-24 18:12:52.929 ThaliTest[1880:6808841] [CDVTimer][gesturehandler] 0.315964ms
2017-01-24 18:12:52.929 ThaliTest[1880:6808841] [CDVTimer][TotalPluginStartup] 10.484040ms
,2017-01-24 18:12:59.921 ThaliTest[1880:6808841] Resetting plugins due to page load.
,2017-01-24 18:13:00.681 ThaliTest[1880:6808841] Finished load of: file:///var/containers/Bundle/Application/7B507ABD-69F2-4FBE-BE84-784B78E9889C/ThaliTest.app/www/index.html
,2017-01-24 18:13:00.946 ThaliTest[1880:6808841] JXcore Cordova plugin initializing
2017-01-24 18:13:00.948 ThaliTest[1880:6808985] JXcore instance initializing
Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-24 17:13:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-24 17:13:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 17:13:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-24 17:13:40 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-24 17:13:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-24 17:14:14 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  32.50057303905487
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
