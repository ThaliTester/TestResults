#### Test 8552588743283b2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8552588743283b2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C42DF453-35D4-41C1-8BC2-943FC3867D16/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C42DF453-35D4-41C1-8BC2-943FC3867D16/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8552588743283b2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8552588743283b2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/2D4CE498-AEF6-4535-8137-C86ED846A7FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51542"
,(lldb)     command script import "/tmp/C42DF453-35D4-41C1-8BC2-943FC3867D16/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 08:21:14.711 ThaliTest[934:1447963] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FA730678-DA44-4AD9-80D0-1485E8B087BE/Library/Cookies/Cookies.binarycookies
,2016-09-20 08:21:15.059 ThaliTest[934:1447963] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-20 08:21:15.061 ThaliTest[934:1447963] Multi-tasking -> Device: YES, App: YES
,2016-09-20 08:21:15.086 ThaliTest[934:1447963] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 08:21:15.587 ThaliTest[934:1447963] Using UIWebView
,2016-09-20 08:21:15.594 ThaliTest[934:1447963] [CDVTimer][handleopenurl] 0.369012ms
,2016-09-20 08:21:15.601 ThaliTest[934:1447963] [CDVTimer][intentandnavigationfilter] 7.180989ms
2016-09-20 08:21:15.602 ThaliTest[934:1447963] [CDVTimer][gesturehandler] 0.299990ms
2016-09-20 08:21:15.602 ThaliTest[934:1447963] [CDVTimer][TotalPluginStar,tup] 9.325027ms
,2016-09-20 08:21:21.092 ThaliTest[934:1447963] Resetting plugins due to page load.
,2016-09-20 08:21:21.357 ThaliTest[934:1447963] Finished load of: file:///var/containers/Bundle/Application/2D4CE498-AEF6-4535-8137-C86ED846A7FF/ThaliTest.app/www/index.html
,2016-09-20 08:21:21.728 ThaliTest[934:1447963] JXcore Cordova plugin initializing
,2016-09-20 08:21:21.729 ThaliTest[934:1448144] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 08:21:28.476 ThaliTest[934:1448144] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 08:21:28.476 ThaliTest[934:1448144] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 08:21:28.477 ThaliTest[934:1448144] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 08:21:28.479 ThaliTest[934:1448144] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 08:21:28.871 ThaliTest[934:1448144] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.002336025238037109
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
