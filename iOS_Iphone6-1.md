#### Test 85046911dcbf444_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/ADF83542-5588-4ED4-9818-E6C2CB04CA55/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/ADF83542-5588-4ED4-9818-E6C2CB04CA55/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7D2368D5-23FD-4AE0-8025-7B8CAA10AEA3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61766"
,(lldb)     command script import "/tmp/ADF83542-5588-4ED4-9818-E6C2CB04CA55/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:39:26.290 ThaliTest[1256:1846897] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/311AA0DC-0C24-4536-901F-09A1E7CD107A/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:39:26.362 ThaliTest[1256:1846897] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:39:26.363 ThaliTest[1256:1846897] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:39:26.378 ThaliTest[1256:1846897] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:39:26.850 ThaliTest[1256:1846897] Using UIWebView
,2016-09-23 08:39:26.857 ThaliTest[1256:1846897] [CDVTimer][handleopenurl] 0.508010ms
,2016-09-23 08:39:26.864 ThaliTest[1256:1846897] [CDVTimer][intentandnavigationfilter] 6.887019ms
2016-09-23 08:39:26.865 ThaliTest[1256:1846897] [CDVTimer][gesturehandler] 0.302017ms
2016-09-23 08:39:26.865 ThaliTest[1256:1846897] [CDVTimer][TotalPluginStartup] 9.274960ms
,2016-09-23 08:39:31.980 ThaliTest[1256:1846897] Resetting plugins due to page load.
,2016-09-23 08:39:32.345 ThaliTest[1256:1846897] Finished load of: file:///var/containers/Bundle/Application/7D2368D5-23FD-4AE0-8025-7B8CAA10AEA3/ThaliTest.app/www/index.html
,2016-09-23 08:39:32.676 ThaliTest[1256:1846897] JXcore Cordova plugin initializing
,2016-09-23 08:39:32.677 ThaliTest[1256:1847080] JXcore instance initializing
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
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 08:39:40.188 ThaliTest[1256:1846897] BTM: attaching to BTServer
,2016-09-23 08:39:40.945 ThaliTest[1256:1846897] BTM: local device power state changed
2016-09-23 08:39:40.956 ThaliTest[1256:1846897] BTM: power is now on
,2016-09-23 08:39:45.669 ThaliTest[1256:1846897] BTM: local device power state changed
2016-09-23 08:39:45.670 ThaliTest[1256:1846897] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  7
,Number of passed tests:  7
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.625311017036438
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
