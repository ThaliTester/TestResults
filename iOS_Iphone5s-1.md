#### Test 8326112021d0a60_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6AB48117-42BF-4F9C-9386-DD336F7E6242/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6AB48117-42BF-4F9C-9386-DD336F7E6242/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326112021d0a60/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F6F8251E-4C24-4E09-A0E3-99879908840E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61150"
,(lldb)     command script import "/tmp/6AB48117-42BF-4F9C-9386-DD336F7E6242/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 14:55:09.017 ThaliTest[1243:2551296] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/56D6F1A7-CCF7-44AA-A4E9-28F84A64FC15/Library/Cookies/Cookies.binarycookies
,2016-08-30 14:55:09.372 ThaliTest[1243:2551296] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 14:55:09.373 ThaliTest[1243:2551296] Multi-tasking -> Device: YES, App: YES
,2016-08-30 14:55:09.395 ThaliTest[1243:2551296] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 14:55:10.990 ThaliTest[1243:2551296] Using UIWebView
,2016-08-30 14:55:11.001 ThaliTest[1243:2551296] [CDVTimer][handleopenurl] 0.477016ms
,2016-08-30 14:55:11.010 ThaliTest[1243:2551296] [CDVTimer][intentandnavigationfilter] 8.635044ms
2016-08-30 14:55:11.011 ThaliTest[1243:2551296] [CDVTimer][gesturehandler] 0.391960ms
2016-08-30 14:55:11.012 ThaliTest[1243:2551296] [CDVTimer][TotalPluginS,tartup] 11.478961ms
,2016-08-30 14:55:16.567 ThaliTest[1243:2551296] Resetting plugins due to page load.
,2016-08-30 14:55:19.294 ThaliTest[1243:2551296] Finished load of: file:///var/mobile/Containers/Bundle/Application/F6F8251E-4C24-4E09-A0E3-99879908840E/ThaliTest.app/www/index.html
,2016-08-30 14:55:19.531 ThaliTest[1243:2551296] JXcore Cordova plugin initializing
,2016-08-30 14:55:19.532 ThaliTest[1243:2551530] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-30 14:55:27.608 ThaliTest[1243:2551530] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-30 14:55:27.609 ThaliTest[1243:2551530] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-30 14:55:27.609 ThaliTest[1243:2551530] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-30 14:55:27.612 ThaliTest[1243:2551530] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-30 14:55:27.997 ThaliTest[1243:2551530] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
Number of passed tests:  2
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  0.003236949443817139
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
