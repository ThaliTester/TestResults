#### Test 80912877691b6a3_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/80912877691b6a3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5BFCFED8-8DAB-4E87-9D42-81046F667A93/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/5BFCFED8-8DAB-4E87-9D42-81046F667A93/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/80912877691b6a3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/80912877691b6a3/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/05F7A14D-8C7D-4F97-937A-3CB02E33BAE0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65155"
,(lldb)     command script import "/tmp/5BFCFED8-8DAB-4E87-9D42-81046F667A93/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 12:44:06.389 ThaliTest[768:1649302] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D6A3BB3F-C0D1-4E7D-8605-07FB7453C6A2/Library/Cookies/Cookies.binarycookies
,2016-08-24 12:44:06.811 ThaliTest[768:1649302] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 12:44:06.812 ThaliTest[768:1649302] Multi-tasking -> Device: YES, App: YES
,2016-08-24 12:44:06.837 ThaliTest[768:1649302] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 12:44:08.622 ThaliTest[768:1649302] Using UIWebView
,2016-08-24 12:44:08.633 ThaliTest[768:1649302] [CDVTimer][handleopenurl] 0.513017ms
,2016-08-24 12:44:08.642 ThaliTest[768:1649302] [CDVTimer][intentandnavigationfilter] 8.608997ms
2016-08-24 12:44:08.643 ThaliTest[768:1649302] [CDVTimer][gesturehandler] 0.482976ms
2016-08-24 12:44:08.644 ThaliTest[768:1649302] [CDVTimer][TotalPluginStartup] 11.637986ms
,2016-08-24 12:44:14.501 ThaliTest[768:1649302] Resetting plugins due to page load.
,2016-08-24 12:44:17.199 ThaliTest[768:1649302] Finished load of: file:///var/mobile/Containers/Bundle/Application/05F7A14D-8C7D-4F97-937A-3CB02E33BAE0/ThaliTest.app/www/index.html
,2016-08-24 12:44:17.453 ThaliTest[768:1649302] JXcore Cordova plugin initializing
,2016-08-24 12:44:17.454 ThaliTest[768:1649546] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 12:44:25.533 ThaliTest[768:1649546] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-24 12:44:25.534 ThaliTest[768:1649546] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-24 12:44:25.534 ThaliTest[768:1649546] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 12:44:25.537 ThaliTest[768:1649546] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 12:44:25.868 ThaliTest[768:1649546] Native method executeNativeTests not found.
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
