#### Test 829140733a8c9ab_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8C44C7C9-E7F4-4EB3-959E-B5A9F40C93A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8C44C7C9-E7F4-4EB3-959E-B5A9F40C93A3/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/829140733a8c9ab/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D81225F2-630D-4BDE-8C8C-BE83334EBA14/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63345"
,(lldb)     command script import "/tmp/8C44C7C9-E7F4-4EB3-959E-B5A9F40C93A3/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 15:24:02.482 ThaliTest[1358:2708499] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6CF4ED3D-137C-46C0-ADA6-8DE9E896A113/Library/Cookies/Cookies.binarycookies
,2016-08-31 15:24:02.914 ThaliTest[1358:2708499] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 15:24:02.915 ThaliTest[1358:2708499] Multi-tasking -> Device: YES, App: YES
,2016-08-31 15:24:02.942 ThaliTest[1358:2708499] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 15:24:04.898 ThaliTest[1358:2708499] Using UIWebView
,2016-08-31 15:24:04.906 ThaliTest[1358:2708499] [CDVTimer][handleopenurl] 0.674009ms
,2016-08-31 15:24:04.914 ThaliTest[1358:2708499] [CDVTimer][intentandnavigationfilter] 8.096993ms
2016-08-31 15:24:04.915 ThaliTest[1358:2708499] [CDVTimer][gesturehandler] 0.412047ms
2016-08-31 15:24:04.916 ThaliTest[1358:2708499] [CDVTimer][TotalPluginStartup] 11.124015ms
,2016-08-31 15:24:11.174 ThaliTest[1358:2708499] Resetting plugins due to page load.
,2016-08-31 15:24:14.993 ThaliTest[1358:2708499] Finished load of: file:///var/mobile/Containers/Bundle/Application/D81225F2-630D-4BDE-8C8C-BE83334EBA14/ThaliTest.app/www/index.html
,2016-08-31 15:24:15.233 ThaliTest[1358:2708499] JXcore Cordova plugin initializing
,2016-08-31 15:24:15.234 ThaliTest[1358:2708729] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  22
Number of passed tests:  22
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  42.12259805202484
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
