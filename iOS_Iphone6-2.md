#### Test 85046911bd0d025_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F2FCB991-C00D-4B58-ACB0-1BBBA0D0C44C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F2FCB991-C00D-4B58-ACB0-1BBBA0D0C44C/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911bd0d025/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6F803CB5-5916-444D-A56B-5CF69846022A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54972"
,(lldb)     command script import "/tmp/F2FCB991-C00D-4B58-ACB0-1BBBA0D0C44C/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 04:37:46.052 ThaliTest[1107:1424230] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7B136BFE-0450-41E7-AE49-2F8E1CE5282C/Library/Cookies/Cookies.binarycookies
,2016-09-20 04:37:46.390 ThaliTest[1107:1424230] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 04:37:46.392 ThaliTest[1107:1424230] Multi-tasking -> Device: YES, App: YES
,2016-09-20 04:37:46.417 ThaliTest[1107:1424230] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 04:37:46.932 ThaliTest[1107:1424230] Using UIWebView
,2016-09-20 04:37:46.942 ThaliTest[1107:1424230] [CDVTimer][handleopenurl] 0.378966ms
,2016-09-20 04:37:46.949 ThaliTest[1107:1424230] [CDVTimer][intentandnavigationfilter] 7.148027ms
2016-09-20 04:37:46.950 ThaliTest[1107:1424230] [CDVTimer][gesturehandler] 0.340998ms
2016-09-20 04:37:46.950 ThaliTest[1107:1424230] [CDVTimer][TotalPluginS,tartup] 9.476006ms
,2016-09-20 04:37:52.275 ThaliTest[1107:1424230] Resetting plugins due to page load.
,2016-09-20 04:37:52.697 ThaliTest[1107:1424230] Finished load of: file:///var/containers/Bundle/Application/6F803CB5-5916-444D-A56B-5CF69846022A/ThaliTest.app/www/index.html
,2016-09-20 04:37:53.097 ThaliTest[1107:1424230] JXcore Cordova plugin initializing
,2016-09-20 04:37:53.099 ThaliTest[1107:1424549] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 04:37:59.737 ThaliTest[1107:1424549] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 04:37:59.737 ThaliTest[1107:1424549] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 04:37:59.737 ThaliTest[1107:1,424549] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 04:37:59.740 ThaliTest[1107:1424549] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 04:38:00.144 ThaliTest[1107:1424549] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003910958766937256
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
