#### Test 797638307ede68b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F1690B1B-45EA-42E6-9DD8-4DEFAE2802B8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F1690B1B-45EA-42E6-9DD8-4DEFAE2802B8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638307ede68b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F0C534A2-BAB4-4CCC-8621-16E757A72B74/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64441"
,(lldb)     command script import "/tmp/F1690B1B-45EA-42E6-9DD8-4DEFAE2802B8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:27:23.921 ThaliTest[1251:2555777] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A02F8DAE-B86C-4EE3-8911-AF43188EE83C/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:27:24.376 ThaliTest[1251:2555777] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:27:24.378 ThaliTest[1251:2555777] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:27:24.402 ThaliTest[1251:2555777] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:27:26.046 ThaliTest[1251:2555777] Using UIWebView
,2016-08-30 15:27:26.052 ThaliTest[1251:2555777] [CDVTimer][handleopenurl] 0.521004ms
,2016-08-30 15:27:26.058 ThaliTest[1251:2555777] [CDVTimer][intentandnavigationfilter] 5.495965ms
2016-08-30 15:27:26.058 ThaliTest[1251:2555777] [CDVTimer][gesturehandler] 0.264049ms
2016-08-30 15:27:26.059 ThaliTest[1251:2555777] [CDVTimer][TotalPluginStartup] 7.556021ms
,2016-08-30 15:27:31.690 ThaliTest[1251:2555777] Resetting plugins due to page load.
,2016-08-30 15:27:34.663 ThaliTest[1251:2555777] Finished load of: file:///var/mobile/Containers/Bundle/Application/F0C534A2-BAB4-4CCC-8621-16E757A72B74/ThaliTest.app/www/index.html
,2016-08-30 15:27:34.914 ThaliTest[1251:2555777] JXcore Cordova plugin initializing
,2016-08-30 15:27:34.915 ThaliTest[1251:2556005] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 15:27:42.992 ThaliTest[1251:2556005] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 15:27:42.993 ThaliTest[1251:2556005] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 15:27:42.994 ThaliTest[1251:2556005] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 15:27:42.996 ThaliTest[1251:2556005] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 15:27:43.389 ThaliTest[1251:2556005] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003387987613677979
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
