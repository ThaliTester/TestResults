#### Test 981169263321dad_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/981169263321dad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/02B00687-7B06-4669-90D3-C7495B62D76A/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/02B00687-7B06-4669-90D3-C7495B62D76A/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/981169263321dad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/981169263321dad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B4D749DF-7142-43BE-88EC-E4BA20F15CBC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61711"
,(lldb)     command script import "/tmp/02B00687-7B06-4669-90D3-C7495B62D76A/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-15 11:13:26.156 ThaliTest[578:1311256] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/61A69AEB-8905-4DDD-865E-5BFCF1E679C3/Library/Cookies/Cookies.binarycookies
,2016-12-15 11:13:26.323 ThaliTest[578:1311256] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 11:13:26.326 ThaliTest[578:1311256] Multi-tasking -> Device: YES, App: YES
,2016-12-15 11:13:26.351 ThaliTest[578:1311256] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 11:13:27.018 ThaliTest[578:1311256] Using UIWebView
,2016-12-15 11:13:27.027 ThaliTest[578:1311256] [CDVTimer][handleopenurl] 0.445008ms
,2016-12-15 11:13:27.034 ThaliTest[578:1311256] [CDVTimer][intentandnavigationfilter] 7.103980ms
2016-12-15 11:13:27.035 ThaliTest[578:1311256] [CDVTimer][gesturehandler] 0.326991ms
2016-12-15 11:13:27.035 ThaliTest[578:1311256] [CDVTimer][TotalPluginStartup] 9.276986ms
,2016-12-15 11:13:35.855 ThaliTest[578:1311256] Resetting plugins due to page load.
,2016-12-15 11:13:36.532 ThaliTest[578:1311256] Finished load of: file:///var/containers/Bundle/Application/B4D749DF-7142-43BE-88EC-E4BA20F15CBC/ThaliTest.app/www/index.html
,2016-12-15 11:13:36.773 ThaliTest[578:1311256] JXcore Cordova plugin initializing
2016-12-15 11:13:36.776 ThaliTest[578:1311432] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 10:14:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 10:14:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 10:14:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-15 10:14:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 10:14:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-15 10:14:43 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  30.6769460439682
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
