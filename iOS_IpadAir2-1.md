#### Test 8504691131acdd6_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/8FFBCDC1-8371-4F07-BB9F-AFCAA5809DCC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/8FFBCDC1-8371-4F07-BB9F-AFCAA5809DCC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/209B0FC3-1B81-40B2-9A4C-9C9542ED4099/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64746"
,(lldb)     command script import "/tmp/8FFBCDC1-8371-4F07-BB9F-AFCAA5809DCC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 12:16:22.310 ThaliTest[2555:4669097] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/533DF917-13BE-493D-B4DA-4F6AED48279C/Library/Cookies/Cookies.binarycookies
,2016-09-16 12:16:22.733 ThaliTest[2555:4669097] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 12:16:22.735 ThaliTest[2555:4669097] Multi-tasking -> Device: YES, App: YES
,2016-09-16 12:16:22.754 ThaliTest[2555:4669097] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 12:16:24.705 ThaliTest[2555:4669097] Using UIWebView
,2016-09-16 12:16:24.715 ThaliTest[2555:4669097] [CDVTimer][handleopenurl] 0.407994ms
,2016-09-16 12:16:24.722 ThaliTest[2555:4669097] [CDVTimer][intentandnavigationfilter] 6.704986ms
,2016-09-16 12:16:24.723 ThaliTest[2555:4669097] [CDVTimer][gesturehandler] 0.326037ms
,2016-09-16 12:16:24.723 ThaliTest[2555:4669097] [CDVTimer][TotalPluginStartup] 8.974016ms
,2016-09-16 12:16:31.424 ThaliTest[2555:4669097] Resetting plugins due to page load.
,2016-09-16 12:16:34.892 ThaliTest[2555:4669097] Finished load of: file:///var/mobile/Containers/Bundle/Application/209B0FC3-1B81-40B2-9A4C-9C9542ED4099/ThaliTest.app/www/index.html
,2016-09-16 12:16:35.102 ThaliTest[2555:4669097] JXcore Cordova plugin initializing
,2016-09-16 12:16:35.102 ThaliTest[2555:4669350] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 12:16:41.287 ThaliTest[2555:4669350] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-16 12:16:41.287 ThaliTest[2555:4669350] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-16 12:16:41.288 ThaliTest[2555:4669350] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-16 12:16:41.289 ThaliTest[2555:4669350] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 12:16:41.578 ThaliTest[2555:4669350] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004974961280822754
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
