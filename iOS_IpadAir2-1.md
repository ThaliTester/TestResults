#### Test 850469116a90ff6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/65390BD6-AA82-43C4-847E-C2EE2E5D689E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/65390BD6-AA82-43C4-847E-C2EE2E5D689E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116a90ff6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/31E538A6-7295-4DB3-BFB8-7B40C8366B84/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50048"
,(lldb)     command script import "/tmp/65390BD6-AA82-43C4-847E-C2EE2E5D689E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 07:34:10.426 ThaliTest[2723:5136103] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7513C66E-7243-4AC4-BB2F-0BAE9651D350/Library/Cookies/Cookies.binarycookies
,2016-09-20 07:34:10.769 ThaliTest[2723:5136103] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-20 07:34:10.770 ThaliTest[2723:5136103] Multi-tasking -> Device: YES, App: YES
,2016-09-20 07:34:10.785 ThaliTest[2723:5136103] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 07:34:12.605 ThaliTest[2723:5136103] Using UIWebView
,2016-09-20 07:34:12.612 ThaliTest[2723:5136103] [CDVTimer][handleopenurl] 0.371993ms
,2016-09-20 07:34:12.620 ThaliTest[2723:5136103] [CDVTimer][intentandnavigationfilter] 7.030010ms
,2016-09-20 07:34:12.621 ThaliTest[2723:5136103] [CDVTimer][gesturehandler] 0.343025ms
2016-09-20 07:34:12.621 ThaliTest[2723:5136103] [CDVTimer][TotalPluginStartup] 9.808004ms
,2016-09-20 07:34:19.513 ThaliTest[2723:5136103] Resetting plugins due to page load.
,2016-09-20 07:34:23.448 ThaliTest[2723:5136103] Finished load of: file:///var/mobile/Containers/Bundle/Application/31E538A6-7295-4DB3-BFB8-7B40C8366B84/ThaliTest.app/www/index.html
,2016-09-20 07:34:23.653 ThaliTest[2723:5136103] JXcore Cordova plugin initializing
,2016-09-20 07:34:23.654 ThaliTest[2723:5136379] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-09-20 07:34:29.839 ThaliTest[2723:5136379] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 07:34:29.839 ThaliTest[2723:5136379] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-20 07:34:29.840 ThaliTest[2723:5136379] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-20 07:34:29.841 ThaliTest[2723:5136379] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 07:34:30.129 ThaliTest[2723:5136379] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005003988742828369
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
