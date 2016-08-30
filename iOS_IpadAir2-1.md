#### Test 8326112021d0a60_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7467EB09-0B11-4E1C-818E-261AFF6B1200/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7467EB09-0B11-4E1C-818E-261AFF6B1200/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2ECAB4E3-09B2-404E-8695-EED4FEC7DB9D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61146"
,(lldb)     command script import "/tmp/7467EB09-0B11-4E1C-818E-261AFF6B1200/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 14:55:11.040 ThaliTest[1348:2501656] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8DC01882-892A-4EEA-A5A4-CA30AC010FAC/Library/Cookies/Cookies.binarycookies
,2016-08-30 14:55:11.430 ThaliTest[1348:2501656] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 14:55:11.431 ThaliTest[1348:2501656] Multi-tasking -> Device: YES, App: YES
,2016-08-30 14:55:11.450 ThaliTest[1348:2501656] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 14:55:13.315 ThaliTest[1348:2501656] Using UIWebView
,2016-08-30 14:55:13.325 ThaliTest[1348:2501656] [CDVTimer][handleopenurl] 0.490010ms
,2016-08-30 14:55:13.332 ThaliTest[1348:2501656] [CDVTimer][intentandnavigationfilter] 6.551981ms
,2016-08-30 14:55:13.333 ThaliTest[1348:2501656] [CDVTimer][gesturehandler] 0.303984ms
,2016-08-30 14:55:13.333 ThaliTest[1348:2501656] [CDVTimer][TotalPluginStartup] 8.996010ms
,2016-08-30 14:55:19.966 ThaliTest[1348:2501656] Resetting plugins due to page load.
,2016-08-30 14:55:23.484 ThaliTest[1348:2501656] Finished load of: file:///var/mobile/Containers/Bundle/Application/2ECAB4E3-09B2-404E-8695-EED4FEC7DB9D/ThaliTest.app/www/index.html
,2016-08-30 14:55:23.746 ThaliTest[1348:2501656] JXcore Cordova plugin initializing
,2016-08-30 14:55:23.748 ThaliTest[1348:2501906] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 14:55:29.915 ThaliTest[1348:2501906] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-30 14:55:29.916 ThaliTest[1348:2501906] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 14:55:29.916 ThaliTest[1348:2501906] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 14:55:29.917 ThaliTest[1348:2501906] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 14:55:30.211 ThaliTest[1348:2501906] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004478931427001953
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
