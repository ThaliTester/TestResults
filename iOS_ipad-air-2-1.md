#### Test 99530606d5b5815_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B79479E3-C3FC-4C7C-9AD4-922008653837/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B79479E3-C3FC-4C7C-9AD4-922008653837/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/894EE394-CB78-48F5-8D4D-7CF4D53553E1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49365"
,(lldb)     command script import "/tmp/B79479E3-C3FC-4C7C-9AD4-922008653837/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-12-28 16:33:42.933 ThaliTest[1565:3268018] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E1AD70D-D6AF-485D-BF8B-57FBFA4E2289/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:33:43.289 ThaliTest[1565:3268018] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:33:43.291 ThaliTest[1565:3268018] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:33:43.313 ThaliTest[1565:3268018] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:33:45.317 ThaliTest[1565:3268018] Using UIWebView
,2016-12-28 16:33:45.324 ThaliTest[1565:3268018] [CDVTimer][handleopenurl] 0.359952ms
,2016-12-28 16:33:45.331 ThaliTest[1565:3268018] [CDVTimer][intentandnavigationfilter] 6.866992ms
,2016-12-28 16:33:45.332 ThaliTest[1565:3268018] [CDVTimer][gesturehandler] 0.312984ms
2016-12-28 16:33:45.333 ThaliTest[1565:3268018] [CDVTimer][TotalPluginStartup] 9.118021ms
,2016-12-28 16:33:51.835 ThaliTest[1565:3268018] Resetting plugins due to page load.
,2016-12-28 16:33:55.175 ThaliTest[1565:3268018] Finished load of: file:///var/mobile/Containers/Bundle/Application/894EE394-CB78-48F5-8D4D-7CF4D53553E1/ThaliTest.app/www/index.html
,2016-12-28 16:33:55.390 ThaliTest[1565:3268018] JXcore Cordova plugin initializing
,2016-12-28 16:33:55.391 ThaliTest[1565:3268264] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:34:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:34:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:34:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-28 15:34:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:34:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-28 15:34:32 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  27.09567201137543
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
