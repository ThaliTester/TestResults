#### Test 8504691135967af_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F2C9EBD2-2DA1-4EAF-9D1A-170D38E8E067/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F2C9EBD2-2DA1-4EAF-9D1A-170D38E8E067/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691135967af/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7C5AA70F-16B1-4632-B9B7-F4193BDBADB2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59797"
,(lldb)     command script import "/tmp/F2C9EBD2-2DA1-4EAF-9D1A-170D38E8E067/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 09:41:39.674 ThaliTest[1587:2490196] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BBF57B54-DE38-4C71-BF9C-43F23355B9C9/Library/Cookies/Cookies.binarycookies
,2016-09-28 09:41:39.758 ThaliTest[1587:2490196] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 09:41:39.760 ThaliTest[1587:2490196] Multi-tasking -> Device: YES, App: YES
,2016-09-28 09:41:39.779 ThaliTest[1587:2490196] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 09:41:40.127 ThaliTest[1587:2490196] Using UIWebView
,2016-09-28 09:41:40.131 ThaliTest[1587:2490196] [CDVTimer][handleopenurl] 0.344992ms
,2016-09-28 09:41:40.137 ThaliTest[1587:2490196] [CDVTimer][intentandnavigationfilter] 5.132020ms
2016-09-28 09:41:40.137 ThaliTest[1587:2490196] [CDVTimer][gesturehandler] 0.223994ms
2016-09-28 09:41:40.138 ThaliTest[1587:2490196] [CDVTimer][TotalPluginS,tartup] 6.830990ms
,2016-09-28 09:41:45.305 ThaliTest[1587:2490196] Resetting plugins due to page load.
,2016-09-28 09:41:45.648 ThaliTest[1587:2490196] Finished load of: file:///var/containers/Bundle/Application/7C5AA70F-16B1-4632-B9B7-F4193BDBADB2/ThaliTest.app/www/index.html
,2016-09-28 09:41:45.997 ThaliTest[1587:2490196] JXcore Cordova plugin initializing
,2016-09-28 09:41:45.998 ThaliTest[1587:2490354] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x130c854f0>
,Optional("B4E2C580-FE08-4BD6-A367-2C29DF718269")
nil
,nil
,Optional("4E8E5305-51FA-4603-AA59-5EAA7740AC09")
,Optional("95FF84BA-5871-4C93-9762-4663AE018068")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  13.74081897735596
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
