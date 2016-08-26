#### Test 797638308bd3e25_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/EDE19286-F96C-496F-BAEF-FDD4466692C1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/EDE19286-F96C-496F-BAEF-FDD4466692C1/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638308bd3e25/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1294B6A0-9B7C-41DA-B99E-F51325622B45/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63170"
,(lldb)     command script import "/tmp/EDE19286-F96C-496F-BAEF-FDD4466692C1/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 12:43:48.629 ThaliTest[934:1946464] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/588A2E20-909C-4BF2-842D-1986CC5D9930/Library/Cookies/Cookies.binarycookies
,2016-08-26 12:43:49.084 ThaliTest[934:1946464] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 12:43:49.086 ThaliTest[934:1946464] Multi-tasking -> Device: YES, App: YES
,2016-08-26 12:43:49.114 ThaliTest[934:1946464] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 12:43:50.990 ThaliTest[934:1946464] Using UIWebView
,2016-08-26 12:43:50.998 ThaliTest[934:1946464] [CDVTimer][handleopenurl] 0.464976ms
,2016-08-26 12:43:51.006 ThaliTest[934:1946464] [CDVTimer][intentandnavigationfilter] 8.042991ms
2016-08-26 12:43:51.007 ThaliTest[934:1946464] [CDVTimer][gesturehandler] 0.423014ms
2016-08-26 12:43:51.008 ThaliTest[934:1946464] [CDVTimer][TotalPluginStar,tup] 10.850966ms
,2016-08-26 12:43:57.167 ThaliTest[934:1946464] Resetting plugins due to page load.
,2016-08-26 12:43:59.843 ThaliTest[934:1946464] Finished load of: file:///var/mobile/Containers/Bundle/Application/1294B6A0-9B7C-41DA-B99E-F51325622B45/ThaliTest.app/www/index.html
,2016-08-26 12:44:00.155 ThaliTest[934:1946464] JXcore Cordova plugin initializing
,2016-08-26 12:44:00.156 ThaliTest[934:1946709] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 12:44:08.317 ThaliTest[934:1946709] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 12:44:08.317 ThaliTest[934:1946709] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-08-26 12:44:08.317 ThaliTest[934:1946709] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 12:44:08.320 ThaliTest[934:1946709] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 12:44:08.708 ThaliTest[934:1946709] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  3
Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01418203115463257
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
