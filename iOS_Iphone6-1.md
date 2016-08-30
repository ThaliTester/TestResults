#### Test 832611203a07957_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/08236A03-DF2E-4F62-960C-579D7E855C3A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/08236A03-DF2E-4F62-960C-579D7E855C3A/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832611203a07957/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5B19DA8C-8393-4968-9EA1-175F227A3DAB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60538"
,(lldb)     command script import "/tmp/08236A03-DF2E-4F62-960C-579D7E855C3A/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 17:39:04.022 ThaliTest[871:1162804] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0DDFBA42-83E4-4617-8155-3EC52A784213/Library/Cookies/Cookies.binarycookies
,2016-08-30 17:39:04.504 ThaliTest[871:1162804] Apache Cordova native platform version 4.1.1 is starting.
2016-08-30 17:39:04.506 ThaliTest[871:1162804] Multi-tasking -> Device: YES, App: YES
,2016-08-30 17:39:04.527 ThaliTest[871:1162804] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 17:39:06.484 ThaliTest[871:1162804] Using UIWebView
,2016-08-30 17:39:06.491 ThaliTest[871:1162804] [CDVTimer][handleopenurl] 0.400007ms
,2016-08-30 17:39:06.499 ThaliTest[871:1162804] [CDVTimer][intentandnavigationfilter] 7.193983ms
2016-08-30 17:39:06.500 ThaliTest[871:1162804] [CDVTimer][gesturehandler] 0.324011ms
2016-08-30 17:39:06.500 ThaliTest[871:1162804] [CDVTimer][TotalPluginStartup] 9.608030ms
,2016-08-30 17:39:13.123 ThaliTest[871:1162804] Resetting plugins due to page load.
,2016-08-30 17:39:16.499 ThaliTest[871:1162804] Finished load of: file:///var/mobile/Containers/Bundle/Application/5B19DA8C-8393-4968-9EA1-175F227A3DAB/ThaliTest.app/www/index.html
,2016-08-30 17:39:16.729 ThaliTest[871:1162804] JXcore Cordova plugin initializing
,2016-08-30 17:39:16.730 ThaliTest[871:1163054] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 17:39:23.598 ThaliTest[871:1163054] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 17:39:23.598 ThaliTest[871:1163054] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 17:39:23.599 ThaliTest[871:1163054] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 17:39:23.601 ThaliTest[871:1163054] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 17:39:23.923 ThaliTest[871:1163054] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.003376007080078125
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
