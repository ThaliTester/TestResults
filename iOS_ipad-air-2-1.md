#### Test 995727499fee306_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/32E28CF1-07A2-45B8-9F72-7BD00367A01C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/32E28CF1-07A2-45B8-9F72-7BD00367A01C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/995727499fee306/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4F58E301-6D77-43CA-AE2D-7F680BD0669C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55711"
,(lldb)     command script import "/tmp/32E28CF1-07A2-45B8-9F72-7BD00367A01C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 11:35:15.761 ThaliTest[1830:4123548] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DB881442-20E4-49F5-AF09-E60C7D6CA9B6/Library/Cookies/Cookies.binarycookies
,2017-01-03 11:35:16.125 ThaliTest[1830:4123548] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 11:35:16.126 ThaliTest[1830:4123548] Multi-tasking -> Device: YES, App: YES
,2017-01-03 11:35:16.145 ThaliTest[1830:4123548] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 11:35:18.130 ThaliTest[1830:4123548] Using UIWebView
,2017-01-03 11:35:18.140 ThaliTest[1830:4123548] [CDVTimer][handleopenurl] 0.360966ms
,2017-01-03 11:35:18.148 ThaliTest[1830:4123548] [CDVTimer][intentandnavigationfilter] 6.733000ms
,2017-01-03 11:35:18.149 ThaliTest[1830:4123548] [CDVTimer][gesturehandler] 0.449955ms
,2017-01-03 11:35:18.149 ThaliTest[1830:4123548] [CDVTimer][TotalPluginStartup] 9.185016ms
,2017-01-03 11:35:24.871 ThaliTest[1830:4123548] Resetting plugins due to page load.
,2017-01-03 11:35:28.253 ThaliTest[1830:4123548] Finished load of: file:///var/mobile/Containers/Bundle/Application/4F58E301-6D77-43CA-AE2D-7F680BD0669C/ThaliTest.app/www/index.html
,2017-01-03 11:35:28.478 ThaliTest[1830:4123548] JXcore Cordova plugin initializing
,2017-01-03 11:35:28.479 ThaliTest[1830:4123792] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 10:35:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-03 10:35:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 10:35:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-03 10:35:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-03 10:35:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-03 10:36:06 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  27.21914899349213
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered

```
