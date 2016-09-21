#### Test 85960304e9d96a8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E69E11B9-0192-4DE6-9858-B7699A4CC02D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E69E11B9-0192-4DE6-9858-B7699A4CC02D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304e9d96a8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4E7AEAFC-8301-451B-B6CD-E62ACE217428/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55142"
,(lldb)     command script import "/tmp/E69E11B9-0192-4DE6-9858-B7699A4CC02D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 13:04:44.698 ThaliTest[2844:5296689] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D3ECFA7A-1CAA-44C0-A102-F4EF281C6A64/Library/Cookies/Cookies.binarycookies
,2016-09-21 13:04:45.228 ThaliTest[2844:5296689] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 13:04:45.230 ThaliTest[2844:5296689] Multi-tasking -> Device: YES, App: YES
,2016-09-21 13:04:45.246 ThaliTest[2844:5296689] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 13:04:47.594 ThaliTest[2844:5296689] Using UIWebView
,2016-09-21 13:04:47.601 ThaliTest[2844:5296689] [CDVTimer][handleopenurl] 0.427008ms
,2016-09-21 13:04:47.609 ThaliTest[2844:5296689] [CDVTimer][intentandnavigationfilter] 7.183969ms
,2016-09-21 13:04:47.610 ThaliTest[2844:5296689] [CDVTimer][gesturehandler] 0.328004ms
,2016-09-21 13:04:47.610 ThaliTest[2844:5296689] [CDVTimer][TotalPluginStartup] 9.676993ms
,2016-09-21 13:04:55.003 ThaliTest[2844:5296689] Resetting plugins due to page load.
,2016-09-21 13:04:59.124 ThaliTest[2844:5296689] Finished load of: file:///var/mobile/Containers/Bundle/Application/4E7AEAFC-8301-451B-B6CD-E62ACE217428/ThaliTest.app/www/index.html
,2016-09-21 13:04:59.329 ThaliTest[2844:5296689] JXcore Cordova plugin initializing
,2016-09-21 13:04:59.330 ThaliTest[2844:5296991] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 13:05:05.470 ThaliTest[2844:5296991] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 13:05:05.470 ThaliTest[2844:5296991] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 13:05:05.470 ThaliTest[2844:5296991] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 13:05:05.472 ThaliTest[2844:5296991] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 13:05:05.747 ThaliTest[2844:5296991] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005066037178039551
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
