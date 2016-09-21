#### Test 85960304fe37dec_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A3A327B5-0028-430C-8B8D-45F9114F4A8B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/A3A327B5-0028-430C-8B8D-45F9114F4A8B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85960304fe37dec/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/082FB5E5-FADD-41B0-A5CE-FC7F02055133/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57882"
,(lldb)     command script import "/tmp/A3A327B5-0028-430C-8B8D-45F9114F4A8B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 14:57:59.830 ThaliTest[1041:1613063] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/759C3536-12E9-409A-A670-F9FDD9A0E921/Library/Cookies/Cookies.binarycookies
,2016-09-21 14:58:00.129 ThaliTest[1041:1613063] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 14:58:00.130 ThaliTest[1041:1613063] Multi-tasking -> Device: YES, App: YES
,2016-09-21 14:58:00.151 ThaliTest[1041:1613063] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 14:58:00.555 ThaliTest[1041:1613063] Using UIWebView
,2016-09-21 14:58:00.562 ThaliTest[1041:1613063] [CDVTimer][handleopenurl] 0.411987ms
,2016-09-21 14:58:00.570 ThaliTest[1041:1613063] [CDVTimer][intentandnavigationfilter] 7.219017ms
2016-09-21 14:58:00.570 ThaliTest[1041:1613063] [CDVTimer][gesturehandler] 0.304997ms
2016-09-21 14:58:00.571 ThaliTest[1041:1613063] [CDVTimer][TotalPluginStartup] 9.505987ms
,2016-09-21 14:58:06.459 ThaliTest[1041:1613063] Resetting plugins due to page load.
,2016-09-21 14:58:06.761 ThaliTest[1041:1613063] Finished load of: file:///var/containers/Bundle/Application/082FB5E5-FADD-41B0-A5CE-FC7F02055133/ThaliTest.app/www/index.html
,2016-09-21 14:58:07.088 ThaliTest[1041:1613063] JXcore Cordova plugin initializing
,2016-09-21 14:58:07.089 ThaliTest[1041:1613250] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-21 14:58:13.851 ThaliTest[1041:1613250] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-21 14:58:13.851 ThaliTest[1041:1613250] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-21 14:58:13.851 ThaliTest[1041:1,613250] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-21 14:58:13.854 ThaliTest[1041:1613250] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-21 14:58:14.240 ThaliTest[1041:1613250] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003287017345428467
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
