#### Test 797638307ede68b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3FD26CE1-90FC-4E57-A508-F64354D91D2F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/3FD26CE1-90FC-4E57-A508-F64354D91D2F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DDDC9BCB-8620-4800-90FB-B405A683A60E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64438"
,(lldb)     command script import "/tmp/3FD26CE1-90FC-4E57-A508-F64354D91D2F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:27:22.793 ThaliTest[832:1145115] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0AA0EBE5-C6B0-4DFB-9DE8-550D1F8822FA/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:27:23.141 ThaliTest[832:1145115] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:27:23.143 ThaliTest[832:1145115] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:27:23.160 ThaliTest[832:1145115] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:27:24.754 ThaliTest[832:1145115] Using UIWebView
,2016-08-30 15:27:24.761 ThaliTest[832:1145115] [CDVTimer][handleopenurl] 0.388026ms
,2016-08-30 15:27:24.769 ThaliTest[832:1145115] [CDVTimer][intentandnavigationfilter] 7.290959ms
2016-08-30 15:27:24.770 ThaliTest[832:1145115] [CDVTimer][gesturehandler] 0.838041ms
2016-08-30 15:27:24.771 ThaliTest[832:1145115] [CDVTimer][TotalPluginStartup] 10.488033ms
,2016-08-30 15:27:30.953 ThaliTest[832:1145115] Resetting plugins due to page load.
,2016-08-30 15:27:33.839 ThaliTest[832:1145115] Finished load of: file:///var/mobile/Containers/Bundle/Application/DDDC9BCB-8620-4800-90FB-B405A683A60E/ThaliTest.app/www/index.html
,2016-08-30 15:27:34.069 ThaliTest[832:1145115] JXcore Cordova plugin initializing
,2016-08-30 15:27:34.070 ThaliTest[832:1145342] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 15:27:40.947 ThaliTest[832:1145342] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-30 15:27:40.948 ThaliTest[832:1145342] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 15:27:40.948 ThaliTest[832:1145342] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 15:27:40.950 ThaliTest[832:1145342] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 15:27:41.271 ThaliTest[832:1145342] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003705024719238281
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
