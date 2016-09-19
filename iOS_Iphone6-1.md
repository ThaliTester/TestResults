#### Test 85525887fe3c967_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/52A05906-8D08-4B93-A80D-84CE5A9C783F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/52A05906-8D08-4B93-A80D-84CE5A9C783F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85525887fe3c967/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DBC7EA90-AA4D-4E36-965C-4D222D4DE35A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59051"
,(lldb)     command script import "/tmp/52A05906-8D08-4B93-A80D-84CE5A9C783F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-19 15:01:19.943 ThaliTest[899:1357344] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B9AB43E-E766-4895-B526-7043846C00D5/Library/Cookies/Cookies.binarycookies
,2016-09-19 15:01:20.215 ThaliTest[899:1357344] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-19 15:01:20.216 ThaliTest[899:1357344] Multi-tasking -> Device: YES, App: YES
,2016-09-19 15:01:20.240 ThaliTest[899:1357344] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-19 15:01:20.702 ThaliTest[899:1357344] Using UIWebView
,2016-09-19 15:01:20.708 ThaliTest[899:1357344] [CDVTimer][handleopenurl] 0.545025ms
,2016-09-19 15:01:20.716 ThaliTest[899:1357344] [CDVTimer][intentandnavigationfilter] 7.207990ms
2016-09-19 15:01:20.717 ThaliTest[899:1357344] [CDVTimer][gesturehandler] 0.307024ms
2016-09-19 15:01:20.717 ThaliTest[899:1357344] [CDVTimer][TotalPluginStar,tup] 9.618044ms
,2016-09-19 15:01:26.259 ThaliTest[899:1357344] Resetting plugins due to page load.
,2016-09-19 15:01:26.534 ThaliTest[899:1357344] Finished load of: file:///var/containers/Bundle/Application/DBC7EA90-AA4D-4E36-965C-4D222D4DE35A/ThaliTest.app/www/index.html
,2016-09-19 15:01:26.863 ThaliTest[899:1357344] JXcore Cordova plugin initializing
,2016-09-19 15:01:26.864 ThaliTest[899:1357532] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-19 15:01:33.524 ThaliTest[899:1357532] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-19 15:01:33.524 ThaliTest[899:1357532] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-19 15:01:33.525 ThaliTest[899:1357532] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-19 15:01:33.526 ThaliTest[899:1357532] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-19 15:01:33.915 ThaliTest[899:1357532] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.003591001033782959
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
