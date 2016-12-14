#### Test 9799024461e9bd5_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9799024461e9bd5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/CA1D31E7-D263-4E96-95AD-7405DA3FB70B/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/CA1D31E7-D263-4E96-95AD-7405DA3FB70B/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9799024461e9bd5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9799024461e9bd5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FF5A633C-188A-4474-A544-76CD9780ABB4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59977"
,(lldb)     command script import "/tmp/CA1D31E7-D263-4E96-95AD-7405DA3FB70B/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 18:10:24.804 ThaliTest[561:1212258] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CDBD4347-8CAC-418D-A667-5BDEF47B3B34/Library/Cookies/Cookies.binarycookies
,2016-12-14 18:10:24.947 ThaliTest[561:1212258] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 18:10:24.949 ThaliTest[561:1212258] Multi-tasking -> Device: YES, App: YES
,2016-12-14 18:10:24.975 ThaliTest[561:1212258] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 18:10:25.761 ThaliTest[561:1212258] Using UIWebView
,2016-12-14 18:10:25.770 ThaliTest[561:1212258] [CDVTimer][handleopenurl] 0.371993ms
,2016-12-14 18:10:25.777 ThaliTest[561:1212258] [CDVTimer][intentandnavigationfilter] 7.166982ms
2016-12-14 18:10:25.778 ThaliTest[561:1212258] [CDVTimer][gesturehandler] 0.325978ms
2016-12-14 18:10:25.778 ThaliTest[561:1212258] [CDVTimer][TotalPluginStartup] 9.223044ms
,2016-12-14 18:10:36.272 ThaliTest[561:1212258] Resetting plugins due to page load.
,2016-12-14 18:10:37.061 ThaliTest[561:1212258] Finished load of: file:///var/containers/Bundle/Application/FF5A633C-188A-4474-A544-76CD9780ABB4/ThaliTest.app/www/index.html
,2016-12-14 18:10:37.297 ThaliTest[561:1212258] JXcore Cordova plugin initializing
2016-12-14 18:10:37.299 ThaliTest[561:1212445] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-14 17:11:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-14 17:11:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-14 17:11:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-14 17:11:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-14 17:11:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,2016-12-14 17:11:57 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  45.04606395959854
,Failed to execute UT.
,2016-12-14 17:11:57 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
