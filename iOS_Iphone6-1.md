#### Test 850469112dc361b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4A5334C1-D2C5-4C0E-B60F-D548C2101A8E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4A5334C1-D2C5-4C0E-B60F-D548C2101A8E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/62E8BBDD-71E5-4AB3-8287-E90F7DC30687/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53122"
,(lldb)     command script import "/tmp/4A5334C1-D2C5-4C0E-B60F-D548C2101A8E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:26:55.776 ThaliTest[1512:2372178] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6F47F0FF-1114-49F1-BEF9-9CD4FE324E11/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:26:55.816 ThaliTest[1512:2372178] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:26:55.817 ThaliTest[1512:2372178] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:26:55.829 ThaliTest[1512:2372178] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:26:56.132 ThaliTest[1512:2372178] Using UIWebView
,2016-09-27 12:26:56.136 ThaliTest[1512:2372178] [CDVTimer][handleopenurl] 0.263989ms
,2016-09-27 12:26:56.140 ThaliTest[1512:2372178] [CDVTimer][intentandnavigationfilter] 3.573000ms
2016-09-27 12:26:56.140 ThaliTest[1512:2372178] [CDVTimer][gesturehandler] 0.136971ms
2016-09-27 12:26:56.141 ThaliTest[1512:2372178] [CDVTimer][TotalPluginStartup] 4.794955ms
,2016-09-27 12:27:01.419 ThaliTest[1512:2372178] Resetting plugins due to page load.
,2016-09-27 12:27:01.784 ThaliTest[1512:2372178] Finished load of: file:///var/containers/Bundle/Application/62E8BBDD-71E5-4AB3-8287-E90F7DC30687/ThaliTest.app/www/index.html
,2016-09-27 12:27:02.116 ThaliTest[1512:2372178] JXcore Cordova plugin initializing
2016-09-27 12:27:02.117 ThaliTest[1512:2372342] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x109f341e0>
,Optional("816E2A90-9147-41C8-9837-197C405BD083")
,nil
,nil
,Optional("3B5DEFEC-85A5-4DD1-9ED4-B91CAE5B9B27")
,Optional("57DDEFEB-C1CB-4CCF-98BF-114010F2DC41")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.12698298692703
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
