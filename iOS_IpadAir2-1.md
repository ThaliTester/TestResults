#### Test 8504691174f7534_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/82D0C662-F9B0-453C-AE72-06F94985D75F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/82D0C662-F9B0-453C-AE72-06F94985D75F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691174f7534/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/860F07B5-C0DC-4E53-A55C-9A5945D97075/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58592"
,(lldb)     command script import "/tmp/82D0C662-F9B0-453C-AE72-06F94985D75F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 12:00:44.760 ThaliTest[2424:4532306] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/099DC949-2E33-4E0F-816B-A7824C472E52/Library/Cookies/Cookies.binarycookies
,2016-09-15 12:00:45.176 ThaliTest[2424:4532306] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 12:00:45.178 ThaliTest[2424:4532306] Multi-tasking -> Device: YES, App: YES
,2016-09-15 12:00:45.197 ThaliTest[2424:4532306] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 12:00:47.117 ThaliTest[2424:4532306] Using UIWebView
,2016-09-15 12:00:47.124 ThaliTest[2424:4532306] [CDVTimer][handleopenurl] 0.551045ms
,2016-09-15 12:00:47.132 ThaliTest[2424:4532306] [CDVTimer][intentandnavigationfilter] 6.757975ms
,2016-09-15 12:00:47.133 ThaliTest[2424:4532306] [CDVTimer][gesturehandler] 0.331998ms
,2016-09-15 12:00:47.133 ThaliTest[2424:4532306] [CDVTimer][TotalPluginStartup] 9.199977ms
,2016-09-15 12:00:53.649 ThaliTest[2424:4532306] Resetting plugins due to page load.
,2016-09-15 12:00:56.755 ThaliTest[2424:4532306] Finished load of: file:///var/mobile/Containers/Bundle/Application/860F07B5-C0DC-4E53-A55C-9A5945D97075/ThaliTest.app/www/index.html
,2016-09-15 12:00:56.969 ThaliTest[2424:4532306] JXcore Cordova plugin initializing
,2016-09-15 12:00:56.970 ThaliTest[2424:4532563] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 12:01:03.198 ThaliTest[2424:4532563] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 12:01:03.198 ThaliTest[2424:4532563] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-15 12:01:03.199 ThaliTest[2424:4532563] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-15 12:01:03.200 ThaliTest[2424:4532563] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-15 12:01:03.489 ThaliTest[2424:4532563] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004989981651306152
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
