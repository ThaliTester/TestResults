#### Test 846487404bc066c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7B5F04CA-C6BF-4D7B-8E88-57C53122A08B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7B5F04CA-C6BF-4D7B-8E88-57C53122A08B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/846487404bc066c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7093FA24-B218-44E0-AC97-01A69A305A28/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49383"
,(lldb)     command script import "/tmp/7B5F04CA-C6BF-4D7B-8E88-57C53122A08B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 11:55:18.400 ThaliTest[2191:4264667] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C7BEC28E-FA65-49D1-99BB-A70CFA8B19E0/Library/Cookies/Cookies.binarycookies
,2016-09-13 11:55:18.650 ThaliTest[2191:4264667] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 11:55:18.651 ThaliTest[2191:4264667] Multi-tasking -> Device: YES, App: YES
,2016-09-13 11:55:18.664 ThaliTest[2191:4264667] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 11:55:19.481 ThaliTest[2191:4264667] Using UIWebView
,2016-09-13 11:55:19.483 ThaliTest[2191:4264667] [CDVTimer][handleopenurl] 0.115037ms
,2016-09-13 11:55:19.485 ThaliTest[2191:4264667] [CDVTimer][intentandnavigationfilter] 1.885951ms
2016-09-13 11:55:19.485 ThaliTest[2191:4264667] [CDVTimer][gesturehandler] 0.101984ms
2016-09-13 11:55:19.486 ThaliTest[2191:4264667] [CDVTimer][TotalPluginS,tartup] 2.591968ms
,2016-09-13 11:55:22.554 ThaliTest[2191:4264667] Resetting plugins due to page load.
,2016-09-13 11:55:24.007 ThaliTest[2191:4264667] Finished load of: file:///var/mobile/Containers/Bundle/Application/7093FA24-B218-44E0-AC97-01A69A305A28/ThaliTest.app/www/index.html
,2016-09-13 11:55:24.142 ThaliTest[2191:4264667] JXcore Cordova plugin initializing
,2016-09-13 11:55:24.143 ThaliTest[2191:4264845] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 11:55:30.009 ThaliTest[2191:4264845] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-13 11:55:30.009 ThaliTest[2191:4264845] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 11:55:30.010 ThaliTest[2191:4264845] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 11:55:30.011 ThaliTest[2191:4264845] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-13 11:55:30.291 ThaliTest[2191:4264845] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004562973976135254
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
