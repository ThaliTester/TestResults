#### Test 79763830cb90817_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DD5F6695-1E21-4F45-99BD-31A8B2074ADD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/DD5F6695-1E21-4F45-99BD-31A8B2074ADD/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E52FCB07-A859-4683-AB9D-1B995892A5D5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57357"
,(lldb)     command script import "/tmp/DD5F6695-1E21-4F45-99BD-31A8B2074ADD/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 16:34:48.745 ThaliTest[372:311807] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D6E0D9D-BDDD-4AEE-8042-5A9AEEA57444/Library/Cookies/Cookies.binarycookies
,2016-08-24 16:34:49.140 ThaliTest[372:311807] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 16:34:49.142 ThaliTest[372:311807] Multi-tasking -> Device: YES, App: YES
,2016-08-24 16:34:49.164 ThaliTest[372:311807] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 16:34:51.120 ThaliTest[372:311807] Using UIWebView
,2016-08-24 16:34:51.127 ThaliTest[372:311807] [CDVTimer][handleopenurl] 0.523984ms
,2016-08-24 16:34:51.135 ThaliTest[372:311807] [CDVTimer][intentandnavigationfilter] 7.293046ms
2016-08-24 16:34:51.136 ThaliTest[372:311807] [CDVTimer][gesturehandler] 0.351965ms
2016-08-24 16:34:51.136 ThaliTest[372:311807] [CDVTimer][TotalPluginStartup] 10.081053ms
,2016-08-24 16:34:57.758 ThaliTest[372:311807] Resetting plugins due to page load.
,2016-08-24 16:35:01.089 ThaliTest[372:311807] Finished load of: file:///var/mobile/Containers/Bundle/Application/E52FCB07-A859-4683-AB9D-1B995892A5D5/ThaliTest.app/www/index.html
,2016-08-24 16:35:01.252 ThaliTest[372:311807] JXcore Cordova plugin initializing
,2016-08-24 16:35:01.253 ThaliTest[372:312049] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 16:35:08.113 ThaliTest[372:312049] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-24 16:35:08.114 ThaliTest[372:312049] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-24 16:35:08.114 ThaliTest[372:312049] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 16:35:08.116 ThaliTest[372:312049] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 16:35:08.397 ThaliTest[372:312049] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
