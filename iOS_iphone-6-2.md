#### Test 996810527fc9b76_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/996810527fc9b76/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/57E22701-BD5F-4E54-8D9A-F5D1B66F76C5/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/57E22701-BD5F-4E54-8D9A-F5D1B66F76C5/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/996810527fc9b76/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/996810527fc9b76/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/43F36483-F6C0-47E6-93F7-9F39D5F7C422/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51802"
,(lldb)     command script import "/tmp/57E22701-BD5F-4E54-8D9A-F5D1B66F76C5/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 19:18:15.427 ThaliTest[1618:2848957] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/57A23C7D-24BE-4075-BD0E-F3C28DAC24B7/Library/Cookies/Cookies.binarycookies
,2016-12-29 19:18:15.479 ThaliTest[1618:2848957] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 19:18:15.480 ThaliTest[1618:2848957] Multi-tasking -> Device: YES, App: YES
,2016-12-29 19:18:15.493 ThaliTest[1618:2848957] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 19:18:15.810 ThaliTest[1618:2848957] Using UIWebView
,2016-12-29 19:18:15.817 ThaliTest[1618:2848957] [CDVTimer][handleopenurl] 0.183046ms
,2016-12-29 19:18:15.821 ThaliTest[1618:2848957] [CDVTimer][intentandnavigationfilter] 4.444957ms
2016-12-29 19:18:15.822 ThaliTest[1618:2848957] [CDVTimer][gesturehandler] 0.168025ms
2016-12-29 19:18:15.822 ThaliTest[1618:2848957] [CDVTimer][TotalPluginStartup] 5.646944ms
,2016-12-29 19:18:21.469 ThaliTest[1618:2848957] Resetting plugins due to page load.
,2016-12-29 19:18:21.808 ThaliTest[1618:2848957] Finished load of: file:///var/containers/Bundle/Application/43F36483-F6C0-47E6-93F7-9F39D5F7C422/ThaliTest.app/www/index.html
,2016-12-29 19:18:22.152 ThaliTest[1618:2848957] JXcore Cordova plugin initializing
,2016-12-29 19:18:22.153 ThaliTest[1618:2849150] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 18:18:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 18:18:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 18:18:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-29 18:18:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 18:18:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-29 18:19:13 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  39.95577400922775
F,ailed to execute UT.
2016-12-29 18:19:13 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
```
