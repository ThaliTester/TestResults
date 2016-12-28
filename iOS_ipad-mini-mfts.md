#### Test 9953060646c88db_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/429070B1-D9BB-46D0-9212-60C3187CAF5B/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/429070B1-D9BB-46D0-9212-60C3187CAF5B/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/995DFF0D-EB0E-4E30-8F96-907359483F9D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59060"
,(lldb)     command script import "/tmp/429070B1-D9BB-46D0-9212-60C3187CAF5B/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 11:51:06.321 ThaliTest[1065:3177848] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D43B5AD0-74D3-4EE7-9852-9F4369BEC581/Library/Cookies/Cookies.binarycookies
,2016-12-28 11:51:06.451 ThaliTest[1065:3177848] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 11:51:06.453 ThaliTest[1065:3177848] Multi-tasking -> Device: YES, App: YES
,2016-12-28 11:51:06.479 ThaliTest[1065:3177848] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 11:51:07.267 ThaliTest[1065:3177848] Using UIWebView
,2016-12-28 11:51:07.273 ThaliTest[1065:3177848] [CDVTimer][handleopenurl] 0.598013ms
,2016-12-28 11:51:07.281 ThaliTest[1065:3177848] [CDVTimer][intentandnavigationfilter] 7.128000ms
2016-12-28 11:51:07.281 ThaliTest[1065:3177848] [CDVTimer][gesturehandler] 0.334024ms
2016-12-28 11:51:07.282 ThaliTest[1065:3177848] [CDVTimer][TotalPluginStartup] 9.452999ms
,2016-12-28 11:51:17.703 ThaliTest[1065:3177848] Resetting plugins due to page load.
,2016-12-28 11:51:18.491 ThaliTest[1065:3177848] Finished load of: file:///var/containers/Bundle/Application/995DFF0D-EB0E-4E30-8F96-907359483F9D/ThaliTest.app/www/index.html
,2016-12-28 11:51:18.728 ThaliTest[1065:3177848] JXcore Cordova plugin initializing
,2016-12-28 11:51:18.730 ThaliTest[1065:3178040] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 10:51:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 10:51:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 10:51:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-28 10:51:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 10:51:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 10:52:28 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  33.32085400819778
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
