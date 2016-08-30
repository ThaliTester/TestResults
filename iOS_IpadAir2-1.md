#### Test 797638305c870dd_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/0EFF7C1E-15F0-420A-9CE0-BACDFDD8700A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0EFF7C1E-15F0-420A-9CE0-BACDFDD8700A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F702C446-DE5E-4E25-82C1-E668E974EA74/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50960"
,(lldb)     command script import "/tmp/0EFF7C1E-15F0-420A-9CE0-BACDFDD8700A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:59:18.782 ThaliTest[1373:2510333] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/205A969C-4448-4FD6-8C59-252ED70FEA15/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:59:19.136 ThaliTest[1373:2510333] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:59:19.137 ThaliTest[1373:2510333] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:59:19.154 ThaliTest[1373:2510333] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:59:20.872 ThaliTest[1373:2510333] Using UIWebView
,2016-08-30 15:59:20.878 ThaliTest[1373:2510333] [CDVTimer][handleopenurl] 0.496030ms
,2016-08-30 15:59:20.886 ThaliTest[1373:2510333] [CDVTimer][intentandnavigationfilter] 7.158995ms
,2016-08-30 15:59:20.887 ThaliTest[1373:2510333] [CDVTimer][gesturehandler] 0.352025ms
,2016-08-30 15:59:20.887 ThaliTest[1373:2510333] [CDVTimer][TotalPluginStartup] 9.716034ms
,2016-08-30 15:59:27.530 ThaliTest[1373:2510333] Resetting plugins due to page load.
,2016-08-30 15:59:30.962 ThaliTest[1373:2510333] Finished load of: file:///var/mobile/Containers/Bundle/Application/F702C446-DE5E-4E25-82C1-E668E974EA74/ThaliTest.app/www/index.html
,2016-08-30 15:59:31.168 ThaliTest[1373:2510333] JXcore Cordova plugin initializing
,2016-08-30 15:59:31.169 ThaliTest[1373:2510593] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 15:59:37.330 ThaliTest[1373:2510593] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 15:59:37.330 ThaliTest[1373:2510593] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-30 15:59:37.331 ThaliTest[1373:2510593] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 15:59:37.332 ThaliTest[1373:2510593] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 15:59:37.626 ThaliTest[1373:2510593] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005070030689239502
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
