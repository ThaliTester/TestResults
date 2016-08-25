#### Test 797638306764640_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A26D9FA6-FFAF-4820-BC81-D8D450322F14/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A26D9FA6-FFAF-4820-BC81-D8D450322F14/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/797638306764640/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/97500D4E-6932-4C2D-A176-7E11F924E95C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50651"
,(lldb)     command script import "/tmp/A26D9FA6-FFAF-4820-BC81-D8D450322F14/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-25 15:23:43.592 ThaliTest[837:1810816] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3F2EC63F-83A1-4DEA-A214-CA3128C25DFC/Library/Cookies/Cookies.binarycookies
,2016-08-25 15:23:43.936 ThaliTest[837:1810816] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-25 15:23:43.938 ThaliTest[837:1810816] Multi-tasking -> Device: YES, App: YES
,2016-08-25 15:23:43.960 ThaliTest[837:1810816] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-25 15:23:45.604 ThaliTest[837:1810816] Using UIWebView
,2016-08-25 15:23:45.615 ThaliTest[837:1810816] [CDVTimer][handleopenurl] 0.640988ms
,2016-08-25 15:23:45.623 ThaliTest[837:1810816] [CDVTimer][intentandnavigationfilter] 7.884979ms
2016-08-25 15:23:45.624 ThaliTest[837:1810816] [CDVTimer][gesturehandler] 0.391960ms
2016-08-25 15:23:45.625 ThaliTest[837:1810816] [CDVTimer][TotalPluginStar,tup] 10.863006ms
,2016-08-25 15:23:51.449 ThaliTest[837:1810816] Resetting plugins due to page load.
,2016-08-25 15:23:54.652 ThaliTest[837:1810816] Finished load of: file:///var/mobile/Containers/Bundle/Application/97500D4E-6932-4C2D-A176-7E11F924E95C/ThaliTest.app/www/index.html
,2016-08-25 15:23:54.907 ThaliTest[837:1810816] JXcore Cordova plugin initializing
,2016-08-25 15:23:54.908 ThaliTest[837:1811030] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-25 15:24:02.998 ThaliTest[837:1811030] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-25 15:24:02.999 ThaliTest[837:1811030] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-25 15:24:03.000 ThaliTest[837:1811030] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-25 15:24:03.002 ThaliTest[837:1811030] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-25 15:24:03.412 ThaliTest[837:1811030] jxcore: executeNativeTests: success
Total number of executed tests:  3
,Number of passed tests:  2
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  0.01717603206634521
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
