#### Test 8359140042466a2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8359140042466a2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F99F86EE-B6E4-42C9-B48C-3C07EF3CB019/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/F99F86EE-B6E4-42C9-B48C-3C07EF3CB019/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8359140042466a2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8359140042466a2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D9655088-D268-4E14-A79C-B465350E9016/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59312"
,(lldb)     command script import "/tmp/F99F86EE-B6E4-42C9-B48C-3C07EF3CB019/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-01 10:58:00.587 ThaliTest[994:1410049] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2275AD88-5866-45BB-A482-4BCE18714327/Library/Cookies/Cookies.binarycookies
,2016-09-01 10:58:01.037 ThaliTest[994:1410049] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-01 10:58:01.038 ThaliTest[994:1410049] Multi-tasking -> Device: YES, App: YES
,2016-09-01 10:58:01.057 ThaliTest[994:1410049] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-01 10:58:02.723 ThaliTest[994:1410049] Using UIWebView
,2016-09-01 10:58:02.730 ThaliTest[994:1410049] [CDVTimer][handleopenurl] 0.519991ms
,2016-09-01 10:58:02.738 ThaliTest[994:1410049] [CDVTimer][intentandnavigationfilter] 7.146955ms
2016-09-01 10:58:02.739 ThaliTest[994:1410049] [CDVTimer][gesturehandler] 0.320017ms
2016-09-01 10:58:02.739 ThaliTest[994:1410049] [CDVTimer][TotalPluginStartup] 9.459019ms
,2016-09-01 10:58:09.050 ThaliTest[994:1410049] Resetting plugins due to page load.
,2016-09-01 10:58:11.932 ThaliTest[994:1410049] Finished load of: file:///var/mobile/Containers/Bundle/Application/D9655088-D268-4E14-A79C-B465350E9016/ThaliTest.app/www/index.html
,2016-09-01 10:58:12.159 ThaliTest[994:1410049] JXcore Cordova plugin initializing
,2016-09-01 10:58:12.160 ThaliTest[994:1410300] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-01 10:58:19.058 ThaliTest[994:1410300] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-01 10:58:19.058 ThaliTest[994:1410300] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-01 10:58:19.059 ThaliTest[994:1410300] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-01 10:58:19.061 ThaliTest[994:1410300] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-01 10:58:19.389 ThaliTest[994:1410300] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.002457976341247559
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
