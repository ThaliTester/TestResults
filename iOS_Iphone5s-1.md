#### Test 79763830cb90817_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E03D899A-A29A-446B-85DE-CD1F7E5BB2BC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E03D899A-A29A-446B-85DE-CD1F7E5BB2BC/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830cb90817/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1C35C00A-FBE8-47E3-B7D1-85A89476F5F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57360"
,(lldb)     command script import "/tmp/E03D899A-A29A-446B-85DE-CD1F7E5BB2BC/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 16:34:50.004 ThaliTest[785:1673737] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6E333E6C-BD69-46AA-9FED-F914EA7B2D48/Library/Cookies/Cookies.binarycookies
,2016-08-24 16:34:50.514 ThaliTest[785:1673737] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 16:34:50.516 ThaliTest[785:1673737] Multi-tasking -> Device: YES, App: YES
,2016-08-24 16:34:50.540 ThaliTest[785:1673737] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 16:34:52.470 ThaliTest[785:1673737] Using UIWebView
,2016-08-24 16:34:52.478 ThaliTest[785:1673737] [CDVTimer][handleopenurl] 0.522017ms
,2016-08-24 16:34:52.487 ThaliTest[785:1673737] [CDVTimer][intentandnavigationfilter] 8.237958ms
2016-08-24 16:34:52.488 ThaliTest[785:1673737] [CDVTimer][gesturehandler] 0.388026ms
2016-08-24 16:34:52.489 ThaliTest[785:1673737] [CDVTimer][TotalPluginStar,tup] 11.057019ms
,2016-08-24 16:34:58.769 ThaliTest[785:1673737] Resetting plugins due to page load.
,2016-08-24 16:35:02.172 ThaliTest[785:1673737] Finished load of: file:///var/mobile/Containers/Bundle/Application/1C35C00A-FBE8-47E3-B7D1-85A89476F5F0/ThaliTest.app/www/index.html
,2016-08-24 16:35:02.367 ThaliTest[785:1673737] JXcore Cordova plugin initializing
,2016-08-24 16:35:02.368 ThaliTest[785:1673974] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 16:35:10.441 ThaliTest[785:1673974] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-24 16:35:10.442 ThaliTest[785:1673974] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-24 16:35:10.442 ThaliTest[785:1673974] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 16:35:10.445 ThaliTest[785:1673974] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 16:35:10.781 ThaliTest[785:1673974] Native method executeNativeTests not found.
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
