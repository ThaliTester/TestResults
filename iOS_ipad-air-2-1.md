#### Test 1025817085707029_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1025817085707029/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E807B6B9-5271-4AE0-A7D4-7E97544356A6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E807B6B9-5271-4AE0-A7D4-7E97544356A6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1025817085707029/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1025817085707029/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E98B7CEB-1EC0-412F-9568-8224B6F1318A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60919"
,(lldb)     command script import "/tmp/E807B6B9-5271-4AE0-A7D4-7E97544356A6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-21 14:22:19.430 ThaliTest[2578:6626386] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/88780685-0826-4D55-817B-646EA90B70A1/Library/Cookies/Cookies.binarycookies
,2017-01-21 14:22:19.666 ThaliTest[2578:6626386] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-21 14:22:19.667 ThaliTest[2578:6626386] Multi-tasking -> Device: YES, App: YES
,2017-01-21 14:22:19.679 ThaliTest[2578:6626386] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-21 14:22:20.583 ThaliTest[2578:6626386] Using UIWebView
,2017-01-21 14:22:20.585 ThaliTest[2578:6626386] [CDVTimer][handleopenurl] 0.090003ms
,2017-01-21 14:22:20.587 ThaliTest[2578:6626386] [CDVTimer][intentandnavigationfilter] 1.793027ms
2017-01-21 14:22:20.587 ThaliTest[2578:6626386] [CDVTimer][gesturehandler] 0.075996ms
2017-01-21 14:22:20.587 ThaliTest[2578:6626386] [CDVTimer][TotalPluginStartup] 2.378047ms
,2017-01-21 14:22:23.918 ThaliTest[2578:6626386] Resetting plugins due to page load.
,2017-01-21 14:22:25.448 ThaliTest[2578:6626386] Finished load of: file:///var/mobile/Containers/Bundle/Application/E98B7CEB-1EC0-412F-9568-8224B6F1318A/ThaliTest.app/www/index.html
,2017-01-21 14:22:25.586 ThaliTest[2578:6626386] JXcore Cordova plugin initializing
,2017-01-21 14:22:25.586 ThaliTest[2578:6626595] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-21 13:22:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-21 13:22:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-21 13:22:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-21 13:22:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-21 13:22:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-21 13:23:01 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.15219503641129
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
