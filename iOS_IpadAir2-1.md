#### Test 79763830f89c62d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830f89c62d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4693F5D7-E45C-478A-BD5E-D3F085B70B0D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4693F5D7-E45C-478A-BD5E-D3F085B70B0D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830f89c62d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830f89c62d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C3855146-B06E-4157-9F4A-A9871EAC457B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64067"
,(lldb)     command script import "/tmp/4693F5D7-E45C-478A-BD5E-D3F085B70B0D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 14:19:32.032 ThaliTest[1269:2370272] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D58CFB90-FE1C-44FA-994F-1CBC4B98B755/Library/Cookies/Cookies.binarycookies
,2016-08-29 14:19:32.433 ThaliTest[1269:2370272] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 14:19:32.434 ThaliTest[1269:2370272] Multi-tasking -> Device: YES, App: YES
,2016-08-29 14:19:32.452 ThaliTest[1269:2370272] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 14:19:34.355 ThaliTest[1269:2370272] Using UIWebView
,2016-08-29 14:19:34.362 ThaliTest[1269:2370272] [CDVTimer][handleopenurl] 0.421047ms
,2016-08-29 14:19:34.370 ThaliTest[1269:2370272] [CDVTimer][intentandnavigationfilter] 6.754994ms
,2016-08-29 14:19:34.370 ThaliTest[1269:2370272] [CDVTimer][gesturehandler] 0.311017ms
,2016-08-29 14:19:34.371 ThaliTest[1269:2370272] [CDVTimer][TotalPluginStartup] 9.104013ms
,2016-08-29 14:19:40.782 ThaliTest[1269:2370272] Resetting plugins due to page load.
,2016-08-29 14:19:44.405 ThaliTest[1269:2370272] Finished load of: file:///var/mobile/Containers/Bundle/Application/C3855146-B06E-4157-9F4A-A9871EAC457B/ThaliTest.app/www/index.html
,2016-08-29 14:19:44.637 ThaliTest[1269:2370272] JXcore Cordova plugin initializing
,2016-08-29 14:19:44.638 ThaliTest[1269:2370532] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 14:19:50.822 ThaliTest[1269:2370532] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-29 14:19:50.823 ThaliTest[1269:2370532] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-29 14:19:50.823 ThaliTest[1269:2370532] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-29 14:19:50.825 ThaliTest[1269:2370532] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-29 14:19:51.114 ThaliTest[1269:2370532] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.005028009414672852
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
