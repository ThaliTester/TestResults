#### Test 8359176442466a2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8359176442466a2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C821DFE2-B635-4607-8E1D-624343B23825/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C821DFE2-B635-4607-8E1D-624343B23825/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8359176442466a2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8359176442466a2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1028B620-7255-48F0-9B97-A4C25B73364B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60805"
,(lldb)     command script import "/tmp/C821DFE2-B635-4607-8E1D-624343B23825/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-01 11:13:50.828 ThaliTest[1529:2739199] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5B999171-4E5A-4FEA-9850-027F725E3FBD/Library/Cookies/Cookies.binarycookies
,2016-09-01 11:13:51.269 ThaliTest[1529:2739199] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-01 11:13:51.270 ThaliTest[1529:2739199] Multi-tasking -> Device: YES, App: YES
,2016-09-01 11:13:51.288 ThaliTest[1529:2739199] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-01 11:13:53.130 ThaliTest[1529:2739199] Using UIWebView
,2016-09-01 11:13:53.140 ThaliTest[1529:2739199] [CDVTimer][handleopenurl] 0.393033ms
,2016-09-01 11:13:53.147 ThaliTest[1529:2739199] [CDVTimer][intentandnavigationfilter] 6.668985ms
,2016-09-01 11:13:53.148 ThaliTest[1529:2739199] [CDVTimer][gesturehandler] 0.312984ms
,2016-09-01 11:13:53.148 ThaliTest[1529:2739199] [CDVTimer][TotalPluginStartup] 9.122014ms
,2016-09-01 11:13:59.548 ThaliTest[1529:2739199] Resetting plugins due to page load.
,2016-09-01 11:14:03.149 ThaliTest[1529:2739199] Finished load of: file:///var/mobile/Containers/Bundle/Application/1028B620-7255-48F0-9B97-A4C25B73364B/ThaliTest.app/www/index.html
,2016-09-01 11:14:03.291 ThaliTest[1529:2739199] JXcore Cordova plugin initializing
2016-09-01 11:14:03.292 ThaliTest[1529:2739429] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-01 11:14:09.357 ThaliTest[1529:2739429] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-01 11:14:09.357 ThaliTest[1529:2739429] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-01 11:14:09.358 ThaliTest[1529:2739429] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-01 11:14:09.359 ThaliTest[1529:2739429] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-01 11:14:09.646 ThaliTest[1529:2739429] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.005131006240844727
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
