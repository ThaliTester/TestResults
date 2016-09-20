#### Test 85960304ae0496b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/88CAA5DE-924F-4C18-8D1C-1483E1EA9FBB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/88CAA5DE-924F-4C18-8D1C-1483E1EA9FBB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304ae0496b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3A9546A4-885F-4472-82B6-60855BAB3044/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58075"
,(lldb)     command script import "/tmp/88CAA5DE-924F-4C18-8D1C-1483E1EA9FBB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 14:11:19.928 ThaliTest[959:1480914] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/250FF891-1621-4162-8E77-36AC20F3547E/Library/Cookies/Cookies.binarycookies
,2016-09-20 14:11:20.233 ThaliTest[959:1480914] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 14:11:20.234 ThaliTest[959:1480914] Multi-tasking -> Device: YES, App: YES
,2016-09-20 14:11:20.260 ThaliTest[959:1480914] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 14:11:20.778 ThaliTest[959:1480914] Using UIWebView
,2016-09-20 14:11:20.785 ThaliTest[959:1480914] [CDVTimer][handleopenurl] 0.388980ms
,2016-09-20 14:11:20.793 ThaliTest[959:1480914] [CDVTimer][intentandnavigationfilter] 7.834971ms
2016-09-20 14:11:20.794 ThaliTest[959:1480914] [CDVTimer][gesturehandler] 0.374973ms
2016-09-20 14:11:20.794 ThaliTest[959:1480914] [CDVTimer][TotalPluginStartup] 10.203004ms
,2016-09-20 14:11:26.322 ThaliTest[959:1480914] Resetting plugins due to page load.
,2016-09-20 14:11:26.578 ThaliTest[959:1480914] Finished load of: file:///var/containers/Bundle/Application/3A9546A4-885F-4472-82B6-60855BAB3044/ThaliTest.app/www/index.html
,2016-09-20 14:11:26.906 ThaliTest[959:1480914] JXcore Cordova plugin initializing
,2016-09-20 14:11:26.908 ThaliTest[959:1481091] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 14:11:33.676 ThaliTest[959:1481091] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 14:11:33.676 ThaliTest[959:1481091] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 14:11:33.676 ThaliTest[959:1481091] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 14:11:33.678 ThaliTest[959:1481091] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 14:11:34.078 ThaliTest[959:1481091] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003319978713989258
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
