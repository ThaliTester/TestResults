#### Test 79763830e108614_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/67759E86-3ECA-4BCE-BB91-A79B3D795262/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/67759E86-3ECA-4BCE-BB91-A79B3D795262/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/91652984-0CE8-4CBA-B1EE-4FF664489B7F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51252"
,(lldb)     command script import "/tmp/67759E86-3ECA-4BCE-BB91-A79B3D795262/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 13:22:43.733 ThaliTest[363:294352] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C59C9214-D168-4DCB-83E7-B4F6A4F320E4/Library/Cookies/Cookies.binarycookies
,2016-08-24 13:22:44.185 ThaliTest[363:294352] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 13:22:44.186 ThaliTest[363:294352] Multi-tasking -> Device: YES, App: YES
,2016-08-24 13:22:44.209 ThaliTest[363:294352] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 13:22:46.107 ThaliTest[363:294352] Using UIWebView
,2016-08-24 13:22:46.117 ThaliTest[363:294352] [CDVTimer][handleopenurl] 0.416994ms
,2016-08-24 13:22:46.124 ThaliTest[363:294352] [CDVTimer][intentandnavigationfilter] 7.221997ms
2016-08-24 13:22:46.125 ThaliTest[363:294352] [CDVTimer][gesturehandler] 0.387013ms
2016-08-24 13:22:46.126 ThaliTest[363:294352] [CDVTimer][TotalPluginStartup,] 9.870946ms
,2016-08-24 13:22:52.497 ThaliTest[363:294352] Resetting plugins due to page load.
,2016-08-24 13:22:55.933 ThaliTest[363:294352] Finished load of: file:///var/mobile/Containers/Bundle/Application/91652984-0CE8-4CBA-B1EE-4FF664489B7F/ThaliTest.app/www/index.html
,2016-08-24 13:22:56.160 ThaliTest[363:294352] JXcore Cordova plugin initializing
2016-08-24 13:22:56.161 ThaliTest[363:294592] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 13:23:03.067 ThaliTest[363:294592] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-24 13:23:03.068 ThaliTest[363:294592] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-24 13:23:03.068 ThaliTest[363:294592] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 13:23:03.070 ThaliTest[363:294592] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 13:23:03.353 ThaliTest[363:294592] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
