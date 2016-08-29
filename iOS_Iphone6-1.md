#### Test 79763830f89c62d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830f89c62d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8E67E1FB-07B7-4979-B76F-C13B8D5871A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8E67E1FB-07B7-4979-B76F-C13B8D5871A9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830f89c62d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830f89c62d/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/620D8BAF-EC5A-4CDD-B46E-6620F544B6C0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64079"
,(lldb)     command script import "/tmp/8E67E1FB-07B7-4979-B76F-C13B8D5871A9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 14:19:29.296 ThaliTest[751:994189] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4E0E4FED-2FD6-4BBC-B5B4-1CDAE8D45C39/Library/Cookies/Cookies.binarycookies
,2016-08-29 14:19:29.736 ThaliTest[751:994189] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 14:19:29.738 ThaliTest[751:994189] Multi-tasking -> Device: YES, App: YES
,2016-08-29 14:19:29.760 ThaliTest[751:994189] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 14:19:31.465 ThaliTest[751:994189] Using UIWebView
,2016-08-29 14:19:31.472 ThaliTest[751:994189] [CDVTimer][handleopenurl] 0.585020ms
,2016-08-29 14:19:31.480 ThaliTest[751:994189] [CDVTimer][intentandnavigationfilter] 7.255018ms
2016-08-29 14:19:31.481 ThaliTest[751:994189] [CDVTimer][gesturehandler] 0.353992ms
2016-08-29 14:19:31.481 ThaliTest[751:994189] [CDVTimer][TotalPluginStartup,] 9.824991ms
,2016-08-29 14:19:37.398 ThaliTest[751:994189] Resetting plugins due to page load.
,2016-08-29 14:19:40.419 ThaliTest[751:994189] Finished load of: file:///var/mobile/Containers/Bundle/Application/620D8BAF-EC5A-4CDD-B46E-6620F544B6C0/ThaliTest.app/www/index.html
,2016-08-29 14:19:40.646 ThaliTest[751:994189] JXcore Cordova plugin initializing
,2016-08-29 14:19:40.648 ThaliTest[751:994417] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-29 14:19:47.569 ThaliTest[751:994417] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-29 14:19:47.569 ThaliTest[751:994417] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-29 14:19:47.570 ThaliTest[751:994417] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-29 14:19:47.571 ThaliTest[751:994417] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-29 14:19:47.898 ThaliTest[751:994417] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003760993480682373
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
