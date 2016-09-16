#### Test 83627337176b608_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/A38349D2-56BD-4B4D-A8A7-ADF31C755131/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A38349D2-56BD-4B4D-A8A7-ADF31C755131/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337176b608/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8B37EBD6-136F-4CBF-BD9A-CB5F5807FB08/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55851"
,(lldb)     command script import "/tmp/A38349D2-56BD-4B4D-A8A7-ADF31C755131/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 10:01:00.663 ThaliTest[2528:4654241] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ADF90F3C-6963-4D9D-AD30-8EC117176037/Library/Cookies/Cookies.binarycookies
,2016-09-16 10:01:01.096 ThaliTest[2528:4654241] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 10:01:01.097 ThaliTest[2528:4654241] Multi-tasking -> Device: YES, App: YES
,2016-09-16 10:01:01.116 ThaliTest[2528:4654241] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 10:01:02.951 ThaliTest[2528:4654241] Using UIWebView
,2016-09-16 10:01:02.958 ThaliTest[2528:4654241] [CDVTimer][handleopenurl] 0.436008ms
,2016-09-16 10:01:02.966 ThaliTest[2528:4654241] [CDVTimer][intentandnavigationfilter] 6.622016ms
,2016-09-16 10:01:02.966 ThaliTest[2528:4654241] [CDVTimer][gesturehandler] 0.306010ms
,2016-09-16 10:01:02.967 ThaliTest[2528:4654241] [CDVTimer][TotalPluginStartup] 8.885026ms
,2016-09-16 10:01:09.630 ThaliTest[2528:4654241] Resetting plugins due to page load.
,2016-09-16 10:01:12.884 ThaliTest[2528:4654241] Finished load of: file:///var/mobile/Containers/Bundle/Application/8B37EBD6-136F-4CBF-BD9A-CB5F5807FB08/ThaliTest.app/www/index.html
,2016-09-16 10:01:13.094 ThaliTest[2528:4654241] JXcore Cordova plugin initializing
,2016-09-16 10:01:13.094 ThaliTest[2528:4654511] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 10:01:19.222 ThaliTest[2528:4654511] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 10:01:19.222 ThaliTest[2528:4654511] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-16 10:01:19.222 ThaliTest[2528:4654511] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-16 10:01:19.224 ThaliTest[2528:4654511] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 10:01:19.511 ThaliTest[2528:4654511] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005029022693634033
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
