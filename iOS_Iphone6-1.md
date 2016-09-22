#### Test 85046911906f2db_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B2C396C6-F938-4934-9CD8-11D9D7530036/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/B2C396C6-F938-4934-9CD8-11D9D7530036/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911906f2db/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7DC4E235-7E33-45A7-8E52-B3B54D0622D7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51258"
,(lldb)     command script import "/tmp/B2C396C6-F938-4934-9CD8-11D9D7530036/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 08:58:39.448 ThaliTest[1112:1710056] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/49C69129-619A-4F97-9E98-52B5467FDAF0/Library/Cookies/Cookies.binarycookies
,2016-09-22 08:58:39.812 ThaliTest[1112:1710056] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 08:58:39.814 ThaliTest[1112:1710056] Multi-tasking -> Device: YES, App: YES
,2016-09-22 08:58:39.838 ThaliTest[1112:1710056] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 08:58:40.433 ThaliTest[1112:1710056] Using UIWebView
2016-09-22 08:58:40.440 ThaliTest[1112:1710056] [CDVTimer][handleopenurl] 0.391006ms
,2016-09-22 08:58:40.449 ThaliTest[1112:1710056] [CDVTimer][intentandnavigationfilter] 8.395016ms
2016-09-22 08:58:40.450 ThaliTest[1112:1710056] [CDVTimer][gesturehandler] 0.338972ms
2016-09-22 08:58:40.450 ThaliTest[1112:1710056] [CDVTimer][TotalPluginS,tartup] 10.748982ms
,2016-09-22 08:58:46.176 ThaliTest[1112:1710056] Resetting plugins due to page load.
,2016-09-22 08:58:46.489 ThaliTest[1112:1710056] Finished load of: file:///var/containers/Bundle/Application/7DC4E235-7E33-45A7-8E52-B3B54D0622D7/ThaliTest.app/www/index.html
,2016-09-22 08:58:46.819 ThaliTest[1112:1710056] JXcore Cordova plugin initializing
,2016-09-22 08:58:46.820 ThaliTest[1112:1710257] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-22 08:58:53.589 ThaliTest[1112:1710257] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-22 08:58:53.589 ThaliTest[1112:1710257] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-22 08:58:53.590 ThaliTest[1112:1710257] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-22 08:58:53.592 ThaliTest[1112:1710257] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-22 08:58:53.994 ThaliTest[1112:1710257] jxcore: executeNativeTests: success
,*Native tests were executed*
Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003224968910217285
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
