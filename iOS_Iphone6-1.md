#### Test 797638305c870dd_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/62B9ACEE-A747-42B2-9174-F617878BB776/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/62B9ACEE-A747-42B2-9174-F617878BB776/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638305c870dd/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/694EB8E9-F838-4B8A-9CF2-3D46D2DEE758/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50961"
,(lldb)     command script import "/tmp/62B9ACEE-A747-42B2-9174-F617878BB776/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 15:59:14.720 ThaliTest[847:1149969] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3B27CED9-7F70-40C2-B496-5ECA84BEFB6C/Library/Cookies/Cookies.binarycookies
,2016-08-30 15:59:15.165 ThaliTest[847:1149969] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 15:59:15.166 ThaliTest[847:1149969] Multi-tasking -> Device: YES, App: YES
,2016-08-30 15:59:15.189 ThaliTest[847:1149969] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 15:59:16.885 ThaliTest[847:1149969] Using UIWebView
,2016-08-30 15:59:16.892 ThaliTest[847:1149969] [CDVTimer][handleopenurl] 0.594020ms
,2016-08-30 15:59:16.900 ThaliTest[847:1149969] [CDVTimer][intentandnavigationfilter] 7.233024ms
2016-08-30 15:59:16.901 ThaliTest[847:1149969] [CDVTimer][gesturehandler] 0.349045ms
2016-08-30 15:59:16.901 ThaliTest[847:1149969] [CDVTimer][TotalPluginStartup] 9.872019ms
,2016-08-30 15:59:22.778 ThaliTest[847:1149969] Resetting plugins due to page load.
,2016-08-30 15:59:25.781 ThaliTest[847:1149969] Finished load of: file:///var/mobile/Containers/Bundle/Application/694EB8E9-F838-4B8A-9CF2-3D46D2DEE758/ThaliTest.app/www/index.html
,2016-08-30 15:59:26.015 ThaliTest[847:1149969] JXcore Cordova plugin initializing
,2016-08-30 15:59:26.016 ThaliTest[847:1150199] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 15:59:32.903 ThaliTest[847:1150199] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-30 15:59:32.903 ThaliTest[847:1150199] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 15:59:32.903 ThaliTest[847:1150199] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 15:59:32.905 ThaliTest[847:1150199] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 15:59:33.241 ThaliTest[847:1150199] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.003917992115020752
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
