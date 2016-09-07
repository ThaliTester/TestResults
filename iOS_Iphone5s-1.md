#### Test 834440500e39eda_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/395E0F38-F77A-4771-AC81-B6B926C8837B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/395E0F38-F77A-4771-AC81-B6B926C8837B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/834440500e39eda/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F43897D9-31BC-421F-98BC-17B0F8ADE15D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62922"
,(lldb)     command script import "/tmp/395E0F38-F77A-4771-AC81-B6B926C8837B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-07 10:30:28.137 ThaliTest[1776:3713837] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0B80A320-0E35-44F5-8B2C-B0B109103219/Library/Cookies/Cookies.binarycookies
,2016-09-07 10:30:28.398 ThaliTest[1776:3713837] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-07 10:30:28.399 ThaliTest[1776:3713837] Multi-tasking -> Device: YES, App: YES
,2016-09-07 10:30:28.419 ThaliTest[1776:3713837] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-07 10:30:29.195 ThaliTest[1776:3713837] Using UIWebView
2016-09-07 10:30:29.197 ThaliTest[1776:3713837] [CDVTimer][handleopenurl] 0.145018ms
,2016-09-07 10:30:29.202 ThaliTest[1776:3713837] [CDVTimer][intentandnavigationfilter] 4.004002ms
2016-09-07 10:30:29.202 ThaliTest[1776:3713837] [CDVTimer][gesturehandler] 0.163019ms
2016-09-07 10:30:29.202 ThaliTest[1776:3713837] [CDVTimer][TotalPluginStartup] 4.931986ms
,2016-09-07 10:30:32.112 ThaliTest[1776:3713837] Resetting plugins due to page load.
,2016-09-07 10:30:33.530 ThaliTest[1776:3713837] Finished load of: file:///var/mobile/Containers/Bundle/Application/F43897D9-31BC-421F-98BC-17B0F8ADE15D/ThaliTest.app/www/index.html
,2016-09-07 10:30:33.717 ThaliTest[1776:3713837] JXcore Cordova plugin initializing
2016-09-07 10:30:33.718 ThaliTest[1776:3714007] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  38.67491501569748
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
