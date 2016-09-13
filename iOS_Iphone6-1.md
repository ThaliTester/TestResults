#### Test 836273370459b7a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/09DEC89B-4F19-4BC5-B68E-CF0531921077/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/09DEC89B-4F19-4BC5-B68E-CF0531921077/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273370459b7a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A2BD5E7B-5336-4E4E-A8E3-605837AC5824/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49737"
,(lldb)     command script import "/tmp/09DEC89B-4F19-4BC5-B68E-CF0531921077/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 16:32:40.502 ThaliTest[514:616818] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/45988180-D022-4662-BF5D-0F991AAB0795/Library/Cookies/Cookies.binarycookies
,2016-09-13 16:32:40.796 ThaliTest[514:616818] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 16:32:40.798 ThaliTest[514:616818] Multi-tasking -> Device: YES, App: YES
,2016-09-13 16:32:40.823 ThaliTest[514:616818] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 16:32:41.258 ThaliTest[514:616818] Using UIWebView
,2016-09-13 16:32:41.268 ThaliTest[514:616818] [CDVTimer][handleopenurl] 0.411987ms
,2016-09-13 16:32:41.276 ThaliTest[514:616818] [CDVTimer][intentandnavigationfilter] 7.081985ms
2016-09-13 16:32:41.277 ThaliTest[514:616818] [CDVTimer][gesturehandler] 0.333965ms
2016-09-13 16:32:41.277 ThaliTest[514:616818] [CDVTimer][TotalPluginStartup,] 9.373009ms
,2016-09-13 16:32:47.486 ThaliTest[514:616818] Resetting plugins due to page load.
,2016-09-13 16:32:47.767 ThaliTest[514:616818] Finished load of: file:///var/containers/Bundle/Application/A2BD5E7B-5336-4E4E-A8E3-605837AC5824/ThaliTest.app/www/index.html
,2016-09-13 16:32:48.097 ThaliTest[514:616818] JXcore Cordova plugin initializing
,2016-09-13 16:32:48.098 ThaliTest[514:617020] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 16:32:54.771 ThaliTest[514:617020] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-13 16:32:54.772 ThaliTest[514:617020] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 16:32:54.772 ThaliTest[514:617020] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 16:32:54.774 ThaliTest[514:617020] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
