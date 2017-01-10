#### Test 100892963a470a85_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/6E6FABB4-9964-41D6-A3F6-6BD76CF11866/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6E6FABB4-9964-41D6-A3F6-6BD76CF11866/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/100892963a470a85/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E4217FF1-AB3A-4588-94E8-3A452D92C592/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59208"
,(lldb)     command script import "/tmp/6E6FABB4-9964-41D6-A3F6-6BD76CF11866/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-10 16:53:00.998 ThaliTest[2161:5273464] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/78285E28-8477-4321-9284-5E50D9DE86E5/Library/Cookies/Cookies.binarycookies
,2017-01-10 16:53:01.220 ThaliTest[2161:5273464] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-10 16:53:01.221 ThaliTest[2161:5273464] Multi-tasking -> Device: YES, App: YES
,2017-01-10 16:53:01.233 ThaliTest[2161:5273464] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-10 16:53:02.078 ThaliTest[2161:5273464] Using UIWebView
,2017-01-10 16:53:02.080 ThaliTest[2161:5273464] [CDVTimer][handleopenurl] 0.105977ms
,2017-01-10 16:53:02.082 ThaliTest[2161:5273464] [CDVTimer][intentandnavigationfilter] 1.791000ms
2017-01-10 16:53:02.082 ThaliTest[2161:5273464] [CDVTimer][gesturehandler] 0.079036ms
2017-01-10 16:53:02.082 ThaliTest[2161:5273464] [CDVTimer][TotalPluginStartup] 2.386987ms
,2017-01-10 16:53:05.207 ThaliTest[2161:5273464] Resetting plugins due to page load.
,2017-01-10 16:53:06.646 ThaliTest[2161:5273464] Finished load of: file:///var/mobile/Containers/Bundle/Application/E4217FF1-AB3A-4588-94E8-3A452D92C592/ThaliTest.app/www/index.html
,2017-01-10 16:53:06.784 ThaliTest[2161:5273464] JXcore Cordova plugin initializing
,2017-01-10 16:53:06.784 ThaliTest[2161:5273666] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-10 15:53:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-10 15:53:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-10 15:53:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-10 15:53:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-10 15:53:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-10 15:53:44 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  28.36099702119827
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
