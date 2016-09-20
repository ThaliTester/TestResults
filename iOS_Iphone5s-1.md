#### Test 850469116350bd7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/D5D0887E-EC49-4A79-BA15-E55577662606/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D5D0887E-EC49-4A79-BA15-E55577662606/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116350bd7/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D57B77A2-CAE4-403B-AAD0-07D4AA03E0E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53891"
,(lldb)     command script import "/tmp/D5D0887E-EC49-4A79-BA15-E55577662606/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-20 09:35:29.138 ThaliTest[2660:5632073] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8519DD57-AF22-4B4E-BBEA-7F8E79C0EBC5/Library/Cookies/Cookies.binarycookies
,2016-09-20 09:35:29.556 ThaliTest[2660:5632073] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-20 09:35:29.558 ThaliTest[2660:5632073] Multi-tasking -> Device: YES, App: YES
,2016-09-20 09:35:29.584 ThaliTest[2660:5632073] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-20 09:35:31.508 ThaliTest[2660:5632073] Using UIWebView
,2016-09-20 09:35:31.517 ThaliTest[2660:5632073] [CDVTimer][handleopenurl] 0.793993ms
,2016-09-20 09:35:31.525 ThaliTest[2660:5632073] [CDVTimer][intentandnavigationfilter] 7.990003ms
2016-09-20 09:35:31.526 ThaliTest[2660:5632073] [CDVTimer][gesturehandler] 0.395954ms
2016-09-20 09:35:31.527 ThaliTest[2660:5632073] [CDVTimer][TotalPluginStartup] 11.071026ms
,2016-09-20 09:35:38.310 ThaliTest[2660:5632073] Resetting plugins due to page load.
,2016-09-20 09:35:41.929 ThaliTest[2660:5632073] Finished load of: file:///var/mobile/Containers/Bundle/Application/D57B77A2-CAE4-403B-AAD0-07D4AA03E0E2/ThaliTest.app/www/index.html
,2016-09-20 09:35:42.171 ThaliTest[2660:5632073] JXcore Cordova plugin initializing
,2016-09-20 09:35:42.172 ThaliTest[2660:5632316] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-20 09:35:50.244 ThaliTest[2660:5632316] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-20 09:35:50.245 ThaliTest[2660:5632316] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-20 09:35:50.245 ThaliTest[2660:5632316] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-20 09:35:50.248 ThaliTest[2660:5632316] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-20 09:35:50.648 ThaliTest[2660:5632316] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005086004734039307
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
