#### Test 79763830cb90817_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/783DF398-6EB8-4ACE-97AE-EE41EE23955C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/783DF398-6EB8-4ACE-97AE-EE41EE23955C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/895F91B0-3331-400C-B27D-34A4E53123F5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57356"
,(lldb)     command script import "/tmp/783DF398-6EB8-4ACE-97AE-EE41EE23955C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 16:34:50.510 ThaliTest[897:1698351] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F88D1F6-5DB2-440F-9706-5B04A8BBD75F/Library/Cookies/Cookies.binarycookies
,2016-08-24 16:34:50.935 ThaliTest[897:1698351] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 16:34:50.936 ThaliTest[897:1698351] Multi-tasking -> Device: YES, App: YES
,2016-08-24 16:34:50.952 ThaliTest[897:1698351] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 16:34:53.045 ThaliTest[897:1698351] Using UIWebView
,2016-08-24 16:34:53.052 ThaliTest[897:1698351] [CDVTimer][handleopenurl] 0.459969ms
,2016-08-24 16:34:53.060 ThaliTest[897:1698351] [CDVTimer][intentandnavigationfilter] 6.710052ms
,2016-08-24 16:34:53.061 ThaliTest[897:1698351] [CDVTimer][gesturehandler] 0.317991ms
,2016-08-24 16:34:53.061 ThaliTest[897:1698351] [CDVTimer][TotalPluginStartup] 9.193003ms
,2016-08-24 16:35:00.217 ThaliTest[897:1698351] Resetting plugins due to page load.
,2016-08-24 16:35:04.155 ThaliTest[897:1698351] Finished load of: file:///var/mobile/Containers/Bundle/Application/895F91B0-3331-400C-B27D-34A4E53123F5/ThaliTest.app/www/index.html
,2016-08-24 16:35:04.377 ThaliTest[897:1698351] JXcore Cordova plugin initializing
,2016-08-24 16:35:04.378 ThaliTest[897:1698612] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 16:35:10.539 ThaliTest[897:1698612] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-24 16:35:10.539 ThaliTest[897:1698612] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-24 16:35:10.540 ThaliTest[897:1698612] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 16:35:10.541 ThaliTest[897:1698612] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 16:35:10.791 ThaliTest[897:1698612] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
