#### Test 797638308bd3e25_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CA73A344-B02F-4D61-BCBF-AAC357DF91D1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/CA73A344-B02F-4D61-BCBF-AAC357DF91D1/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D790772E-6B29-4ED3-8E5F-58E01C685E02/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63163"
,(lldb)     command script import "/tmp/CA73A344-B02F-4D61-BCBF-AAC357DF91D1/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 12:43:46.930 ThaliTest[518:567203] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1D4DE3F3-36B7-4E5D-83BE-E269921BC686/Library/Cookies/Cookies.binarycookies
,2016-08-26 12:43:47.325 ThaliTest[518:567203] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 12:43:47.327 ThaliTest[518:567203] Multi-tasking -> Device: YES, App: YES
,2016-08-26 12:43:47.349 ThaliTest[518:567203] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 12:43:49.233 ThaliTest[518:567203] Using UIWebView
,2016-08-26 12:43:49.240 ThaliTest[518:567203] [CDVTimer][handleopenurl] 0.521004ms
,2016-08-26 12:43:49.247 ThaliTest[518:567203] [CDVTimer][intentandnavigationfilter] 7.270038ms
2016-08-26 12:43:49.248 ThaliTest[518:567203] [CDVTimer][gesturehandler] 0.325024ms
2016-08-26 12:43:49.249 ThaliTest[518:567203] [CDVTimer][TotalPluginStartup] 9.694040ms
,2016-08-26 12:43:55.559 ThaliTest[518:567203] Resetting plugins due to page load.
,2016-08-26 12:43:58.789 ThaliTest[518:567203] Finished load of: file:///var/mobile/Containers/Bundle/Application/D790772E-6B29-4ED3-8E5F-58E01C685E02/ThaliTest.app/www/index.html
,2016-08-26 12:43:59.018 ThaliTest[518:567203] JXcore Cordova plugin initializing
2016-08-26 12:43:59.020 ThaliTest[518:567421] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 12:44:05.984 ThaliTest[518:567421] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 12:44:05.984 ThaliTest[518:567421] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-26 12:44:05.985 ThaliTest[518:567421] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 12:44:05.987 ThaliTest[518:567421] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 12:44:06.323 ThaliTest[518:567421] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01067900657653809
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
