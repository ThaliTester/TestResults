#### Test 8326112021d0a60_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C6E3C7B7-E9E0-4872-A6C0-7F58DCEF8DEB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C6E3C7B7-E9E0-4872-A6C0-7F58DCEF8DEB/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A883A0F1-F7FF-44A4-A079-CC2E3F38C6E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61147"
,(lldb)     command script import "/tmp/C6E3C7B7-E9E0-4872-A6C0-7F58DCEF8DEB/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 14:55:08.102 ThaliTest[825:1140702] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B4254899-914C-494B-9162-A89A01EB4166/Library/Cookies/Cookies.binarycookies
,2016-08-30 14:55:08.544 ThaliTest[825:1140702] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 14:55:08.545 ThaliTest[825:1140702] Multi-tasking -> Device: YES, App: YES
,2016-08-30 14:55:08.566 ThaliTest[825:1140702] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 14:55:10.225 ThaliTest[825:1140702] Using UIWebView
,2016-08-30 14:55:10.232 ThaliTest[825:1140702] [CDVTimer][handleopenurl] 0.537992ms
,2016-08-30 14:55:10.240 ThaliTest[825:1140702] [CDVTimer][intentandnavigationfilter] 7.319987ms
2016-08-30 14:55:10.241 ThaliTest[825:1140702] [CDVTimer][gesturehandler] 0.355005ms
2016-08-30 14:55:10.242 ThaliTest[825:1140702] [CDVTimer][TotalPluginStartup] 9.841025ms
,2016-08-30 14:55:16.319 ThaliTest[825:1140702] Resetting plugins due to page load.
,2016-08-30 14:55:19.092 ThaliTest[825:1140702] Finished load of: file:///var/mobile/Containers/Bundle/Application/A883A0F1-F7FF-44A4-A079-CC2E3F38C6E9/ThaliTest.app/www/index.html
,2016-08-30 14:55:19.323 ThaliTest[825:1140702] JXcore Cordova plugin initializing
,2016-08-30 14:55:19.325 ThaliTest[825:1140927] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 14:55:26.201 ThaliTest[825:1140927] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-30 14:55:26.201 ThaliTest[825:1140927] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 14:55:26.201 ThaliTest[825:1140927] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 14:55:26.203 ThaliTest[825:1140927] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 14:55:26.528 ThaliTest[825:1140927] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003508985042572021
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
