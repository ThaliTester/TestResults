#### Test 83261120b3e784a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E1ED1C66-6C36-4E12-ADFB-DC22005E7E6C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/E1ED1C66-6C36-4E12-ADFB-DC22005E7E6C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83261120b3e784a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/12918E59-04F0-4584-9B7E-08F166B2960E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60259"
,(lldb)     command script import "/tmp/E1ED1C66-6C36-4E12-ADFB-DC22005E7E6C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 12:06:20.983 ThaliTest[915:1272430] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E4FCBC1F-BA12-4658-8266-ED87DE3E2A1B/Library/Cookies/Cookies.binarycookies
,2016-08-31 12:06:21.454 ThaliTest[915:1272430] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 12:06:21.456 ThaliTest[915:1272430] Multi-tasking -> Device: YES, App: YES
,2016-08-31 12:06:21.478 ThaliTest[915:1272430] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 12:06:23.377 ThaliTest[915:1272430] Using UIWebView
,2016-08-31 12:06:23.387 ThaliTest[915:1272430] [CDVTimer][handleopenurl] 0.496984ms
,2016-08-31 12:06:23.394 ThaliTest[915:1272430] [CDVTimer][intentandnavigationfilter] 7.290959ms
2016-08-31 12:06:23.395 ThaliTest[915:1272430] [CDVTimer][gesturehandler] 0.348985ms
2016-08-31 12:06:23.396 ThaliTest[915:1272430] [CDVTimer][TotalPluginStartup] 9.833992ms
,2016-08-31 12:06:29.795 ThaliTest[915:1272430] Resetting plugins due to page load.
,2016-08-31 12:06:33.028 ThaliTest[915:1272430] Finished load of: file:///var/mobile/Containers/Bundle/Application/12918E59-04F0-4584-9B7E-08F166B2960E/ThaliTest.app/www/index.html
,2016-08-31 12:06:33.333 ThaliTest[915:1272430] JXcore Cordova plugin initializing
,2016-08-31 12:06:33.334 ThaliTest[915:1272659] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-31 12:06:40.207 ThaliTest[915:1272659] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-31 12:06:40.208 ThaliTest[915:1272659] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-31 12:06:40.208 ThaliTest[915:1272659] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-31 12:06:40.210 ThaliTest[915:1272659] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-31 12:06:40.533 ThaliTest[915:1272659] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.00361400842666626
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
