#### Test 75789268514fc25_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268514fc25/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4A585863-6DFC-4B9F-A2DF-CB6ACB7D4773/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4A585863-6DFC-4B9F-A2DF-CB6ACB7D4773/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268514fc25/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268514fc25/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/197860A3-9034-40BE-948C-F75E632C1D6D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53102"
,(lldb)     command script import "/tmp/4A585863-6DFC-4B9F-A2DF-CB6ACB7D4773/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-15 15:19:10.789 ThaliTest[366:401053] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3E51B5A-55F1-4979-A3A7-5A9198F0961F/Library/Cookies/Cookies.binarycookies
,2016-07-15 15:19:11.165 ThaliTest[366:401053] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-15 15:19:11.167 ThaliTest[366:401053] Multi-tasking -> Device: YES, App: YES
,2016-07-15 15:19:11.188 ThaliTest[366:401053] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-15 15:19:13.111 ThaliTest[366:401053] Using UIWebView
,2016-07-15 15:19:13.118 ThaliTest[366:401053] [CDVTimer][handleopenurl] 0.593007ms
,2016-07-15 15:19:13.126 ThaliTest[366:401053] [CDVTimer][intentandnavigationfilter] 7.148027ms
2016-07-15 15:19:13.127 ThaliTest[366:401053] [CDVTimer][gesturehandler] 0.365019ms
2016-07-15 15:19:13.127 ThaliTest[366:401053] [CDVTimer][TotalPluginStartup,] 9.833038ms
,2016-07-15 15:19:19.985 ThaliTest[366:401053] Resetting plugins due to page load.
,2016-07-15 15:19:23.271 ThaliTest[366:401053] Finished load of: file:///var/mobile/Containers/Bundle/Application/197860A3-9034-40BE-948C-F75E632C1D6D/ThaliTest.app/www/index.html
,2016-07-15 15:19:23.501 ThaliTest[366:401053] JXcore Cordova plugin initializing
,2016-07-15 15:19:23.503 ThaliTest[366:401300] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-15 15:19:31.258 ThaliTest[366:401300] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-15 15:19:31.259 ThaliTest[366:401300] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-15 15:19:31.259 ThaliTest[366:401300] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-15 15:19:31.261 ThaliTest[366:401300] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-07-15 15:19:31.571 ThaliTest[366:401300] Native method ExecuteNativeTests not found.

```
