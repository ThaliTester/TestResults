#### Test 83261120b3e784a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/DB48D55A-9E98-48F9-88B1-22FC5BEC99CC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DB48D55A-9E98-48F9-88B1-22FC5BEC99CC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/4465372A-1E92-4AD1-AC8B-6F3AA950B4E8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60260"
,(lldb)     command script import "/tmp/DB48D55A-9E98-48F9-88B1-22FC5BEC99CC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-31 12:06:25.853 ThaliTest[1442:2615166] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/64CA0A1E-BEC8-497B-A3D3-CBA728CF5A7E/Library/Cookies/Cookies.binarycookies
,2016-08-31 12:06:26.266 ThaliTest[1442:2615166] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 12:06:26.268 ThaliTest[1442:2615166] Multi-tasking -> Device: YES, App: YES
,2016-08-31 12:06:26.287 ThaliTest[1442:2615166] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 12:06:28.402 ThaliTest[1442:2615166] Using UIWebView
,2016-08-31 12:06:28.408 ThaliTest[1442:2615166] [CDVTimer][handleopenurl] 0.437975ms
,2016-08-31 12:06:28.415 ThaliTest[1442:2615166] [CDVTimer][intentandnavigationfilter] 6.600022ms
,2016-08-31 12:06:28.416 ThaliTest[1442:2615166] [CDVTimer][gesturehandler] 0.337005ms
,2016-08-31 12:06:28.416 ThaliTest[1442:2615166] [CDVTimer][TotalPluginStartup] 8.969009ms
,2016-08-31 12:06:35.518 ThaliTest[1442:2615166] Resetting plugins due to page load.
,2016-08-31 12:06:39.618 ThaliTest[1442:2615166] Finished load of: file:///var/mobile/Containers/Bundle/Application/4465372A-1E92-4AD1-AC8B-6F3AA950B4E8/ThaliTest.app/www/index.html
,2016-08-31 12:06:39.825 ThaliTest[1442:2615166] JXcore Cordova plugin initializing
2016-08-31 12:06:39.826 ThaliTest[1442:2615456] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 12:06:45.971 ThaliTest[1442:2615456] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-31 12:06:45.971 ThaliTest[1442:2615456] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-31 12:06:45.971 ThaliTest[1442:2615456] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-31 12:06:45.973 ThaliTest[1442:2615456] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-31 12:06:46.259 ThaliTest[1442:2615456] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.004597008228302002
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
