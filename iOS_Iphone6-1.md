#### Test 83627337381d561_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/68D6A819-6074-4ACA-8084-B4AF855A700B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/68D6A819-6074-4ACA-8084-B4AF855A700B/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337381d561/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/943A07B2-A4F8-4EE9-84E3-3A002AAF5444/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64546"
,(lldb)     command script import "/tmp/68D6A819-6074-4ACA-8084-B4AF855A700B/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 11:35:51.189 ThaliTest[1361:2290433] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D2915EAA-270B-44CC-8675-D518F61288C0/Library/Cookies/Cookies.binarycookies
,2016-09-07 11:35:51.605 ThaliTest[1361:2290433] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 11:35:51.607 ThaliTest[1361:2290433] Multi-tasking -> Device: YES, App: YES
,2016-09-07 11:35:51.630 ThaliTest[1361:2290433] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 11:35:53.374 ThaliTest[1361:2290433] Using UIWebView
,2016-09-07 11:35:53.384 ThaliTest[1361:2290433] [CDVTimer][handleopenurl] 0.443995ms
,2016-09-07 11:35:53.392 ThaliTest[1361:2290433] [CDVTimer][intentandnavigationfilter] 7.246971ms
2016-09-07 11:35:53.393 ThaliTest[1361:2290433] [CDVTimer][gesturehandler] 0.342011ms
2016-09-07 11:35:53.393 ThaliTest[1361:2290433] [CDVTimer][TotalPluginS,tartup] 9.769022ms
,2016-09-07 11:35:59.268 ThaliTest[1361:2290433] Resetting plugins due to page load.
,2016-09-07 11:36:01.758 ThaliTest[1361:2290433] Finished load of: file:///var/mobile/Containers/Bundle/Application/943A07B2-A4F8-4EE9-84E3-3A002AAF5444/ThaliTest.app/www/index.html
,2016-09-07 11:36:01.921 ThaliTest[1361:2290433] JXcore Cordova plugin initializing
2016-09-07 11:36:01.921 ThaliTest[1361:2290659] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-07 11:36:08.843 ThaliTest[1361:2290659] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-07 11:36:08.843 ThaliTest[1361:2290659] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-07 11:36:08.845 ThaliTest[1361:2290659] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-07 11:36:08.847 ThaliTest[1361:2290659] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
