#### Test 85046911783e9ea_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/D9B031BF-32A7-4781-9418-8B6365256DAC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D9B031BF-32A7-4781-9418-8B6365256DAC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/03053D9B-512D-4251-B74A-C4B8E61841E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64839"
,(lldb)     command script import "/tmp/D9B031BF-32A7-4781-9418-8B6365256DAC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 18:59:10.415 ThaliTest[2695:5069942] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/40B75C66-81A4-4A09-9E2B-170EC9E6CBCF/Library/Cookies/Cookies.binarycookies
,2016-09-19 18:59:10.796 ThaliTest[2695:5069942] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 18:59:10.798 ThaliTest[2695:5069942] Multi-tasking -> Device: YES, App: YES
,2016-09-19 18:59:10.817 ThaliTest[2695:5069942] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 18:59:12.886 ThaliTest[2695:5069942] Using UIWebView
,2016-09-19 18:59:12.894 ThaliTest[2695:5069942] [CDVTimer][handleopenurl] 0.388980ms
,2016-09-19 18:59:12.901 ThaliTest[2695:5069942] [CDVTimer][intentandnavigationfilter] 6.937981ms
,2016-09-19 18:59:12.902 ThaliTest[2695:5069942] [CDVTimer][gesturehandler] 0.375032ms
,2016-09-19 18:59:12.902 ThaliTest[2695:5069942] [CDVTimer][TotalPluginStartup] 9.264946ms
,2016-09-19 18:59:20.524 ThaliTest[2695:5069942] Resetting plugins due to page load.
,2016-09-19 18:59:24.495 ThaliTest[2695:5069942] Finished load of: file:///var/mobile/Containers/Bundle/Application/03053D9B-512D-4251-B74A-C4B8E61841E9/ThaliTest.app/www/index.html
,2016-09-19 18:59:24.704 ThaliTest[2695:5069942] JXcore Cordova plugin initializing
,2016-09-19 18:59:24.705 ThaliTest[2695:5070215] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 18:59:30.852 ThaliTest[2695:5070215] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-19 18:59:30.852 ThaliTest[2695:5070215] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 18:59:30.852 ThaliTest[2695:5070215] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-19 18:59:30.854 ThaliTest[2695:5070215] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 18:59:31.143 ThaliTest[2695:5070215] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005240023136138916
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
