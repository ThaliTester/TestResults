#### Test 81095569cb9dee4_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/681D016D-1630-4E0D-B52D-D00ECAAC560C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/681D016D-1630-4E0D-B52D-D00ECAAC560C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81095569cb9dee4/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F4778995-C17C-4EE6-93C6-80DCBA6F8F02/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60389"
,(lldb)     command script import "/tmp/681D016D-1630-4E0D-B52D-D00ECAAC560C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-23 18:33:42.906 ThaliTest[310:191463] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F8FD92B9-147B-4A9D-B1A7-F7DA034E4643/Library/Cookies/Cookies.binarycookies
,2016-08-23 18:33:43.456 ThaliTest[310:191463] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-23 18:33:43.458 ThaliTest[310:191463] Multi-tasking -> Device: YES, App: YES
,2016-08-23 18:33:43.494 ThaliTest[310:191463] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-23 18:33:45.426 ThaliTest[310:191463] Using UIWebView
,2016-08-23 18:33:45.431 ThaliTest[310:191463] [CDVTimer][handleopenurl] 0.376999ms
,2016-08-23 18:33:45.438 ThaliTest[310:191463] [CDVTimer][intentandnavigationfilter] 6.002963ms
2016-08-23 18:33:45.438 ThaliTest[310:191463] [CDVTimer][gesturehandler] 0.344992ms
2016-08-23 18:33:45.439 ThaliTest[310:191463] [CDVTimer][TotalPluginStartup] 8.149028ms
,2016-08-23 18:33:52.951 ThaliTest[310:191463] Resetting plugins due to page load.
,2016-08-23 18:33:56.761 ThaliTest[310:191463] Finished load of: file:///var/mobile/Containers/Bundle/Application/F4778995-C17C-4EE6-93C6-80DCBA6F8F02/ThaliTest.app/www/index.html
,2016-08-23 18:33:57.041 ThaliTest[310:191463] JXcore Cordova plugin initializing
,2016-08-23 18:33:57.042 ThaliTest[310:191716] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-23 18:34:03.987 ThaliTest[310:191716] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-23 18:34:03.988 ThaliTest[310:191716] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-23 18:34:03.988 ThaliTest[310:191716,] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-23 18:34:03.990 ThaliTest[310:191716] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-23 18:34:04.271 ThaliTest[310:191716] Native method ExecuteNativeTests not found.
Is Android:  false
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
