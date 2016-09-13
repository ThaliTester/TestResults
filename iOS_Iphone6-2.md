#### Test 846487404bc066c_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/62051FA4-5D39-4751-B82C-39CBCBBA799B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/62051FA4-5D39-4751-B82C-39CBCBBA799B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EF0170D4-F6A8-4862-86A7-39181C7D20DC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49389"
,(lldb)     command script import "/tmp/62051FA4-5D39-4751-B82C-39CBCBBA799B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 02:55:39.654 ThaliTest[577:625863] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/00747A79-C312-47F3-8BB3-06FB2E98E952/Library/Cookies/Cookies.binarycookies
,2016-09-13 02:55:40.070 ThaliTest[577:625863] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 02:55:40.072 ThaliTest[577:625863] Multi-tasking -> Device: YES, App: YES
,2016-09-13 02:55:40.094 ThaliTest[577:625863] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 02:55:40.687 ThaliTest[577:625863] Using UIWebView
2016-09-13 02:55:40.693 ThaliTest[577:625863] [CDVTimer][handleopenurl] 0.567019ms
,2016-09-13 02:55:40.702 ThaliTest[577:625863] [CDVTimer][intentandnavigationfilter] 8.368969ms
2016-09-13 02:55:40.703 ThaliTest[577:625863] [CDVTimer][gesturehandler] 0.391006ms
2016-09-13 02:55:40.703 ThaliTest[577:625863] [CDVTimer][TotalPluginStartup] 10.858953ms
,2016-09-13 02:55:47.869 ThaliTest[577:625863] Resetting plugins due to page load.
,2016-09-13 02:55:48.401 ThaliTest[577:625863] Finished load of: file:///var/containers/Bundle/Application/EF0170D4-F6A8-4862-86A7-39181C7D20DC/ThaliTest.app/www/index.html
,2016-09-13 02:55:48.797 ThaliTest[577:625863] JXcore Cordova plugin initializing
,2016-09-13 02:55:48.798 ThaliTest[577:626059] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 02:55:55.351 ThaliTest[577:626059] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 02:55:55.351 ThaliTest[577:626059] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 02:55:55.351 ThaliTest[577:626059,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 02:55:55.353 ThaliTest[577:626059] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-13 02:55:55.733 ThaliTest[577:626059] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00432199239730835
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
