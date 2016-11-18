#### Test 93765317141d42a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93765317141d42a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/E04E1BEF-6B28-4EED-8BB0-FCCD6C46BBBE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E04E1BEF-6B28-4EED-8BB0-FCCD6C46BBBE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93765317141d42a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93765317141d42a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4C17114C-ED6B-456B-A33C-2C0A3247C866/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54568"
,(lldb)     command script import "/tmp/E04E1BEF-6B28-4EED-8BB0-FCCD6C46BBBE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 16:47:37.212 ThaliTest[5790:12553838] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/37125879-45CE-4C55-A10F-D16981AD17AE/Library/Cookies/Cookies.binarycookies
,2016-11-18 16:47:37.429 ThaliTest[5790:12553838] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 16:47:37.430 ThaliTest[5790:12553838] Multi-tasking -> Device: YES, App: YES
,2016-11-18 16:47:37.442 ThaliTest[5790:12553838] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 16:47:38.279 ThaliTest[5790:12553838] Using UIWebView
,2016-11-18 16:47:38.281 ThaliTest[5790:12553838] [CDVTimer][handleopenurl] 0.095010ms
,2016-11-18 16:47:38.283 ThaliTest[5790:12553838] [CDVTimer][intentandnavigationfilter] 1.848042ms
2016-11-18 16:47:38.283 ThaliTest[5790:12553838] [CDVTimer][gesturehandler] 0.086010ms
2016-11-18 16:47:38.283 ThaliTest[5790:12553838] [CDVTimer][TotalPluginStartup] 2.451003ms
,2016-11-18 16:47:41.401 ThaliTest[5790:12553838] Resetting plugins due to page load.
,2016-11-18 16:47:42.837 ThaliTest[5790:12553838] Finished load of: file:///var/mobile/Containers/Bundle/Application/4C17114C-ED6B-456B-A33C-2C0A3247C866/ThaliTest.app/www/index.html
,2016-11-18 16:47:42.978 ThaliTest[5790:12553838] JXcore Cordova plugin initializing
,2016-11-18 16:47:42.979 ThaliTest[5790:12554004] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 15:47:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 15:47:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 15:47:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 15:47:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 15:47:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-18 15:48:28 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  35.74687701463699
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
