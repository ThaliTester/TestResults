#### Test 832611203a07957_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/42E580BD-2A86-4AF1-81F7-6FB6F38BBE35/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/42E580BD-2A86-4AF1-81F7-6FB6F38BBE35/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F10C634E-C402-4171-BF6E-9DC110EA8A3D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60537"
,(lldb)     command script import "/tmp/42E580BD-2A86-4AF1-81F7-6FB6F38BBE35/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 17:39:06.761 ThaliTest[1399:2521951] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8C41A4E6-523F-49A7-8907-A8387F3998AC/Library/Cookies/Cookies.binarycookies
,2016-08-30 17:39:07.154 ThaliTest[1399:2521951] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 17:39:07.156 ThaliTest[1399:2521951] Multi-tasking -> Device: YES, App: YES
,2016-08-30 17:39:07.175 ThaliTest[1399:2521951] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 17:39:09.321 ThaliTest[1399:2521951] Using UIWebView
,2016-08-30 17:39:09.328 ThaliTest[1399:2521951] [CDVTimer][handleopenurl] 0.482023ms
,2016-08-30 17:39:09.335 ThaliTest[1399:2521951] [CDVTimer][intentandnavigationfilter] 7.123947ms
,2016-08-30 17:39:09.336 ThaliTest[1399:2521951] [CDVTimer][gesturehandler] 0.325024ms
,2016-08-30 17:39:09.337 ThaliTest[1399:2521951] [CDVTimer][TotalPluginStartup] 9.736001ms
,2016-08-30 17:39:16.459 ThaliTest[1399:2521951] Resetting plugins due to page load.
,2016-08-30 17:39:20.201 ThaliTest[1399:2521951] Finished load of: file:///var/mobile/Containers/Bundle/Application/F10C634E-C402-4171-BF6E-9DC110EA8A3D/ThaliTest.app/www/index.html
,2016-08-30 17:39:20.407 ThaliTest[1399:2521951] JXcore Cordova plugin initializing
,2016-08-30 17:39:20.408 ThaliTest[1399:2522216] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 17:39:26.598 ThaliTest[1399:2522216] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 17:39:26.598 ThaliTest[1399:2522216] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-30 17:39:26.598 ThaliTest[1399:2522216] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-08-30 17:39:26.600 ThaliTest[1399:2522216] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 17:39:26.897 ThaliTest[1399:2522216] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.004426002502441406
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
