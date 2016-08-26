#### Test 79763830d186b13_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830d186b13/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F5DCD2EA-B9DF-44BE-92BC-1DB49F13C018/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F5DCD2EA-B9DF-44BE-92BC-1DB49F13C018/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830d186b13/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830d186b13/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/63EDE5F6-64D2-4CFD-B123-B75CE7DBB63A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59776"
,(lldb)     command script import "/tmp/F5DCD2EA-B9DF-44BE-92BC-1DB49F13C018/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 21:09:17.487 ThaliTest[1008:2005673] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/69CC292B-A2E9-4875-8CBC-0F2188B01363/Library/Cookies/Cookies.binarycookies
,2016-08-26 21:09:17.955 ThaliTest[1008:2005673] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 21:09:17.957 ThaliTest[1008:2005673] Multi-tasking -> Device: YES, App: YES
,2016-08-26 21:09:17.978 ThaliTest[1008:2005673] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 21:09:19.900 ThaliTest[1008:2005673] Using UIWebView
,2016-08-26 21:09:19.908 ThaliTest[1008:2005673] [CDVTimer][handleopenurl] 0.432968ms
,2016-08-26 21:09:19.916 ThaliTest[1008:2005673] [CDVTimer][intentandnavigationfilter] 8.083999ms
2016-08-26 21:09:19.917 ThaliTest[1008:2005673] [CDVTimer][gesturehandler] 0.375986ms
2016-08-26 21:09:19.918 ThaliTest[1008:2005673] [CDVTimer][TotalPluginStartup] 10.771036ms
,2016-08-26 21:09:26.079 ThaliTest[1008:2005673] Resetting plugins due to page load.
,2016-08-26 21:09:29.735 ThaliTest[1008:2005673] Finished load of: file:///var/mobile/Containers/Bundle/Application/63EDE5F6-64D2-4CFD-B123-B75CE7DBB63A/ThaliTest.app/www/index.html
,2016-08-26 21:09:29.990 ThaliTest[1008:2005673] JXcore Cordova plugin initializing
,2016-08-26 21:09:29.991 ThaliTest[1008:2005899] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-26 21:09:38.148 ThaliTest[1008:2005899] jxcore: didRegisterToNative peerAvailabilityChanged
2016-08-26 21:09:38.148 ThaliTest[1008:2005899] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-26 21:09:38.149 ThaliTest[1008:2005899] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-26 21:09:38.152 ThaliTest[1008:2005899] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-26 21:09:38.537 ThaliTest[1008:2005899] jxcore: executeNativeTests: success
*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005773007869720459
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
