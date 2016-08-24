#### Test 80912877ffdb7be_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/80912877ffdb7be/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AFF5AA18-AC74-4AAA-9517-9A7D31AC56E4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/AFF5AA18-AC74-4AAA-9517-9A7D31AC56E4/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/80912877ffdb7be/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/80912877ffdb7be/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B949BDD8-1608-4182-85EC-873DD95FFAA7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63636"
,(lldb)     command script import "/tmp/AFF5AA18-AC74-4AAA-9517-9A7D31AC56E4/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 10:03:15.550 ThaliTest[345:275666] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4E9CBDF0-E057-45B9-9748-1808307236A6/Library/Cookies/Cookies.binarycookies
,2016-08-24 10:03:15.987 ThaliTest[345:275666] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 10:03:15.988 ThaliTest[345:275666] Multi-tasking -> Device: YES, App: YES
,2016-08-24 10:03:16.011 ThaliTest[345:275666] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 10:03:17.948 ThaliTest[345:275666] Using UIWebView
,2016-08-24 10:03:17.955 ThaliTest[345:275666] [CDVTimer][handleopenurl] 0.410020ms
,2016-08-24 10:03:17.963 ThaliTest[345:275666] [CDVTimer][intentandnavigationfilter] 7.353961ms
2016-08-24 10:03:17.964 ThaliTest[345:275666] [CDVTimer][gesturehandler] 0.375986ms
2016-08-24 10:03:17.965 ThaliTest[345:275666] [CDVTimer][TotalPluginStartup] 9.860992ms
,2016-08-24 10:03:24.412 ThaliTest[345:275666] Resetting plugins due to page load.
,2016-08-24 10:03:27.579 ThaliTest[345:275666] Finished load of: file:///var/mobile/Containers/Bundle/Application/B949BDD8-1608-4182-85EC-873DD95FFAA7/ThaliTest.app/www/index.html
,2016-08-24 10:03:27.801 ThaliTest[345:275666] JXcore Cordova plugin initializing
,2016-08-24 10:03:27.803 ThaliTest[345:275916] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 10:03:34.707 ThaliTest[345:275916] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-24 10:03:34.708 ThaliTest[345:275916] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-24 10:03:34.708 ThaliTest[345:275916] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 10:03:34.710 ThaliTest[345:275916] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 10:03:34.993 ThaliTest[345:275916] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
