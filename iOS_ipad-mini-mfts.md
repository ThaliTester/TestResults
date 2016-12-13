#### Test 9772710378c4b3e_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/1D6370E7-E65E-46E0-A50B-2EAF30F5B6E3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/1D6370E7-E65E-46E0-A50B-2EAF30F5B6E3/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4130AAF4-D3E3-4353-878E-5976248B29AF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54412"
,(lldb)     command script import "/tmp/1D6370E7-E65E-46E0-A50B-2EAF30F5B6E3/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 13:33:13.540 ThaliTest[504:1041648] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C0EB6BEA-57D5-4283-BFAD-01771443814E/Library/Cookies/Cookies.binarycookies
,2016-12-13 13:33:13.706 ThaliTest[504:1041648] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 13:33:13.708 ThaliTest[504:1041648] Multi-tasking -> Device: YES, App: YES
,2016-12-13 13:33:13.736 ThaliTest[504:1041648] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 13:33:14.532 ThaliTest[504:1041648] Using UIWebView
,2016-12-13 13:33:14.538 ThaliTest[504:1041648] [CDVTimer][handleopenurl] 0.374019ms
,2016-12-13 13:33:14.545 ThaliTest[504:1041648] [CDVTimer][intentandnavigationfilter] 7.209957ms
2016-12-13 13:33:14.546 ThaliTest[504:1041648] [CDVTimer][gesturehandler] 0.337005ms
2016-12-13 13:33:14.546 ThaliTest[504:1041648] [CDVTimer][TotalPluginStartup] 9.289980ms
,2016-12-13 13:33:25.209 ThaliTest[504:1041648] Resetting plugins due to page load.
,2016-12-13 13:33:26.005 ThaliTest[504:1041648] Finished load of: file:///var/containers/Bundle/Application/4130AAF4-D3E3-4353-878E-5976248B29AF/ThaliTest.app/www/index.html
,2016-12-13 13:33:26.248 ThaliTest[504:1041648] JXcore Cordova plugin initializing
,2016-12-13 13:33:26.251 ThaliTest[504:1041814] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 12:34:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 12:34:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 12:34:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-13 12:34:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 12:34:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 12:34:31 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  28.21237301826477
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
