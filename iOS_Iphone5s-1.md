#### Test 83070177977a8d1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3B0228C9-63B5-47D0-A671-EE4C08CAF064/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3B0228C9-63B5-47D0-A671-EE4C08CAF064/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/86A3D87F-19C6-4D19-8BCB-661C1126D6AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61937"
,(lldb)     command script import "/tmp/3B0228C9-63B5-47D0-A671-EE4C08CAF064/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:43:03.063 ThaliTest[1157:2394971] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/85E3BAF9-E943-4F08-BBC4-6ADD025B8438/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:43:03.497 ThaliTest[1157:2394971] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 13:43:03.498 ThaliTest[1157:2394971] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:43:03.524 ThaliTest[1157:2394971] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:43:05.215 ThaliTest[1157:2394971] Using UIWebView
,2016-08-29 13:43:05.223 ThaliTest[1157:2394971] [CDVTimer][handleopenurl] 0.431001ms
,2016-08-29 13:43:05.232 ThaliTest[1157:2394971] [CDVTimer][intentandnavigationfilter] 7.993996ms
2016-08-29 13:43:05.233 ThaliTest[1157:2394971] [CDVTimer][gesturehandler] 0.384986ms
2016-08-29 13:43:05.233 ThaliTest[1157:2394971] [CDVTimer][TotalPluginStartup] 10.762036ms
,2016-08-29 13:43:11.012 ThaliTest[1157:2394971] Resetting plugins due to page load.
,2016-08-29 13:43:13.757 ThaliTest[1157:2394971] Finished load of: file:///var/mobile/Containers/Bundle/Application/86A3D87F-19C6-4D19-8BCB-661C1126D6AC/ThaliTest.app/www/index.html
,2016-08-29 13:43:14.016 ThaliTest[1157:2394971] JXcore Cordova plugin initializing
,2016-08-29 13:43:14.017 ThaliTest[1157:2395219] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.9617800116539
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
