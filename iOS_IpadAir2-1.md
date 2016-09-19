#### Test 8504691185ffef1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691185ffef1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/BED82BF4-874C-4434-A199-85FC80F8C8B4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/BED82BF4-874C-4434-A199-85FC80F8C8B4/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691185ffef1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691185ffef1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2220DFC3-1F8B-4FE8-A007-12A1A7E11082/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59016"
,(lldb)     command script import "/tmp/BED82BF4-874C-4434-A199-85FC80F8C8B4/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 14:36:41.745 ThaliTest[2674:5044787] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2BF3D1A4-27C1-4239-919D-887266728660/Library/Cookies/Cookies.binarycookies
,2016-09-19 14:36:42.196 ThaliTest[2674:5044787] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 14:36:42.198 ThaliTest[2674:5044787] Multi-tasking -> Device: YES, App: YES
,2016-09-19 14:36:42.217 ThaliTest[2674:5044787] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 14:36:44.416 ThaliTest[2674:5044787] Using UIWebView
,2016-09-19 14:36:44.425 ThaliTest[2674:5044787] [CDVTimer][handleopenurl] 0.395000ms
,2016-09-19 14:36:44.433 ThaliTest[2674:5044787] [CDVTimer][intentandnavigationfilter] 6.716967ms
,2016-09-19 14:36:44.433 ThaliTest[2674:5044787] [CDVTimer][gesturehandler] 0.306010ms
,2016-09-19 14:36:44.434 ThaliTest[2674:5044787] [CDVTimer][TotalPluginStartup] 8.932948ms
,2016-09-19 14:36:51.988 ThaliTest[2674:5044787] Resetting plugins due to page load.
,2016-09-19 14:36:56.320 ThaliTest[2674:5044787] Finished load of: file:///var/mobile/Containers/Bundle/Application/2220DFC3-1F8B-4FE8-A007-12A1A7E11082/ThaliTest.app/www/index.html
,2016-09-19 14:36:56.524 ThaliTest[2674:5044787] JXcore Cordova plugin initializing
2016-09-19 14:36:56.525 ThaliTest[2674:5045109] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 14:37:02.751 ThaliTest[2674:5045109] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-19 14:37:02.752 ThaliTest[2674:5045109] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 14:37:02.752 ThaliTest[2674:5045109] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-19 14:37:02.753 ThaliTest[2674:5045109] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 14:37:03.045 ThaliTest[2674:5045109] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.0050240159034729
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
