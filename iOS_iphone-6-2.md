#### Test 9967484811caee1_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7002D4D8-DBE6-45B5-ADF9-DF486EE6E127/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/7002D4D8-DBE6-45B5-ADF9-DF486EE6E127/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2C874015-18BD-46F4-A72F-1E167B57BA70/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50011"
,(lldb)     command script import "/tmp/7002D4D8-DBE6-45B5-ADF9-DF486EE6E127/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 18:13:41.597 ThaliTest[1608:2841553] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/727127D4-76D7-4D00-AAB3-358516EE00A6/Library/Cookies/Cookies.binarycookies
,2016-12-29 18:13:41.638 ThaliTest[1608:2841553] Apache Cordova native platform version 4.3.1 is starting.
2016-12-29 18:13:41.639 ThaliTest[1608:2841553] Multi-tasking -> Device: YES, App: YES
,2016-12-29 18:13:41.653 ThaliTest[1608:2841553] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 18:13:41.967 ThaliTest[1608:2841553] Using UIWebView
,2016-12-29 18:13:41.970 ThaliTest[1608:2841553] [CDVTimer][handleopenurl] 0.182986ms
,2016-12-29 18:13:41.975 ThaliTest[1608:2841553] [CDVTimer][intentandnavigationfilter] 4.463017ms
2016-12-29 18:13:41.975 ThaliTest[1608:2841553] [CDVTimer][gesturehandler] 0.147998ms
2016-12-29 18:13:41.976 ThaliTest[1608:2841553] [CDVTimer][TotalPluginS,tartup] 5.620003ms
,2016-12-29 18:13:47.586 ThaliTest[1608:2841553] Resetting plugins due to page load.
,2016-12-29 18:13:47.918 ThaliTest[1608:2841553] Finished load of: file:///var/containers/Bundle/Application/2C874015-18BD-46F4-A72F-1E167B57BA70/ThaliTest.app/www/index.html
,2016-12-29 18:13:48.254 ThaliTest[1608:2841553] JXcore Cordova plugin initializing
,2016-12-29 18:13:48.255 ThaliTest[1608:2841751] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 17:13:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 17:13:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 17:13:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-29 17:13:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 17:13:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-29 17:14:24 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.09679400920868
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
