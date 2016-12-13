#### Test 977271034c6c8cc_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/1F18D6F3-59F8-4D5B-92C3-34E9F003B272/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/1F18D6F3-59F8-4D5B-92C3-34E9F003B272/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/844958C5-8B03-420B-BCB7-CD9C77C7565F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52719"
,(lldb)     command script import "/tmp/1F18D6F3-59F8-4D5B-92C3-34E9F003B272/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 12:18:21.442 ThaliTest[494:1032625] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1EDAD864-166F-4E13-B2EA-B351CFAEC036/Library/Cookies/Cookies.binarycookies
,2016-12-13 12:18:21.595 ThaliTest[494:1032625] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 12:18:21.597 ThaliTest[494:1032625] Multi-tasking -> Device: YES, App: YES
,2016-12-13 12:18:21.623 ThaliTest[494:1032625] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 12:18:22.401 ThaliTest[494:1032625] Using UIWebView
,2016-12-13 12:18:22.407 ThaliTest[494:1032625] [CDVTimer][handleopenurl] 0.506997ms
,2016-12-13 12:18:22.415 ThaliTest[494:1032625] [CDVTimer][intentandnavigationfilter] 7.237971ms
2016-12-13 12:18:22.416 ThaliTest[494:1032625] [CDVTimer][gesturehandler] 0.326037ms
2016-12-13 12:18:22.416 ThaliTest[494:1032625] [CDVTimer][TotalPluginStartup] 9.427965ms
,2016-12-13 12:18:32.691 ThaliTest[494:1032625] Resetting plugins due to page load.
,2016-12-13 12:18:33.466 ThaliTest[494:1032625] Finished load of: file:///var/containers/Bundle/Application/844958C5-8B03-420B-BCB7-CD9C77C7565F/ThaliTest.app/www/index.html
,2016-12-13 12:18:33.708 ThaliTest[494:1032625] JXcore Cordova plugin initializing
,2016-12-13 12:18:33.710 ThaliTest[494:1032831] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 11:19:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 11:19:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 11:19:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-13 11:19:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 11:19:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 11:19:42 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.23776799440384
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
