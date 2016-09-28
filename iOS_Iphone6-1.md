#### Test 850469114456a2a_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/17773A10-0E25-4F3F-B9E8-24CE09AC78CC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/17773A10-0E25-4F3F-B9E8-24CE09AC78CC/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469114456a2a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/85D40212-9DCB-40A2-9871-AD6E2874C7E3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62754"
,(lldb)     command script import "/tmp/17773A10-0E25-4F3F-B9E8-24CE09AC78CC/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 10:49:40.428 ThaliTest[1605:2497907] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/22A69B01-81CF-466D-A171-96C586589FB1/Library/Cookies/Cookies.binarycookies
,2016-09-28 10:49:40.502 ThaliTest[1605:2497907] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 10:49:40.504 ThaliTest[1605:2497907] Multi-tasking -> Device: YES, App: YES
,2016-09-28 10:49:40.523 ThaliTest[1605:2497907] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 10:49:40.990 ThaliTest[1605:2497907] Using UIWebView
,2016-09-28 10:49:40.997 ThaliTest[1605:2497907] [CDVTimer][handleopenurl] 0.492036ms
,2016-09-28 10:49:41.004 ThaliTest[1605:2497907] [CDVTimer][intentandnavigationfilter] 6.887972ms
2016-09-28 10:49:41.005 ThaliTest[1605:2497907] [CDVTimer][gesturehandler] 0.263989ms
2016-09-28 10:49:41.005 ThaliTest[1605:2497907] [CDVTimer][TotalPluginStartup] 9.189963ms
,2016-09-28 10:49:46.458 ThaliTest[1605:2497907] Resetting plugins due to page load.
,2016-09-28 10:49:46.814 ThaliTest[1605:2497907] Finished load of: file:///var/containers/Bundle/Application/85D40212-9DCB-40A2-9871-AD6E2874C7E3/ThaliTest.app/www/index.html
,2016-09-28 10:49:47.149 ThaliTest[1605:2497907] JXcore Cordova plugin initializing
,2016-09-28 10:49:47.150 ThaliTest[1605:2498067] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x15dc5bf60>
,Optional("6F80892A-60D1-4E7A-89AF-D71BD5A52C28")
nil
,nil
,Optional("D07DF71D-198F-4F83-8329-482BF86226B4")
,Optional("6984B94C-F2C0-4874-BB38-C0ED7485F8C8")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.49597603082657
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
