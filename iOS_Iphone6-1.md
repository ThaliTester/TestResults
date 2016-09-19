#### Test 85046911783e9ea_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/38EE2CDD-1FF6-4D46-8F97-04ED2AA661F8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/38EE2CDD-1FF6-4D46-8F97-04ED2AA661F8/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911783e9ea/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/33DF71D3-CE32-446D-B5E9-01F659E3BB7D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64835"
,(lldb)     command script import "/tmp/38EE2CDD-1FF6-4D46-8F97-04ED2AA661F8/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-09-19 18:59:02.300 ThaliTest[908:1377900] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D23F7E8F-FAEB-4813-A666-63E9C6D27CDA/Library/Cookies/Cookies.binarycookies
,2016-09-19 18:59:02.599 ThaliTest[908:1377900] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 18:59:02.601 ThaliTest[908:1377900] Multi-tasking -> Device: YES, App: YES
,2016-09-19 18:59:02.626 ThaliTest[908:1377900] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 18:59:03.115 ThaliTest[908:1377900] Using UIWebView
,2016-09-19 18:59:03.122 ThaliTest[908:1377900] [CDVTimer][handleopenurl] 0.367045ms
,2016-09-19 18:59:03.129 ThaliTest[908:1377900] [CDVTimer][intentandnavigationfilter] 7.121027ms
2016-09-19 18:59:03.130 ThaliTest[908:1377900] [CDVTimer][gesturehandler] 0.333965ms
2016-09-19 18:59:03.130 ThaliTest[908:1377900] [CDVTimer][TotalPluginStartup] 9.313047ms
,2016-09-19 18:59:08.533 ThaliTest[908:1377900] Resetting plugins due to page load.
,2016-09-19 18:59:08.863 ThaliTest[908:1377900] Finished load of: file:///var/containers/Bundle/Application/33DF71D3-CE32-446D-B5E9-01F659E3BB7D/ThaliTest.app/www/index.html
,2016-09-19 18:59:09.188 ThaliTest[908:1377900] JXcore Cordova plugin initializing
,2016-09-19 18:59:09.189 ThaliTest[908:1378077] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 18:59:15.836 ThaliTest[908:1378077] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-19 18:59:15.836 ThaliTest[908:1378077] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 18:59:15.837 ThaliTest[908:1378077] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-19 18:59:15.838 ThaliTest[908:1378077] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 18:59:16.229 ThaliTest[908:1378077] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003753006458282471
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
