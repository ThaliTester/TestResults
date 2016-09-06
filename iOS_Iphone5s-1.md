#### Test 83268893665f77c_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CF7BCFB4-043D-4C0E-B97F-189EC218641B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CF7BCFB4-043D-4C0E-B97F-189EC218641B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893665f77c/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/59465E56-872E-4012-87C6-3865F996D335/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50252"
,(lldb)     command script import "/tmp/CF7BCFB4-043D-4C0E-B97F-189EC218641B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 16:54:31.778 ThaliTest[1684:3603572] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/33031306-BB84-4ED0-98AB-B82CECBC3590/Library/Cookies/Cookies.binarycookies
,2016-09-06 16:54:32.213 ThaliTest[1684:3603572] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 16:54:32.215 ThaliTest[1684:3603572] Multi-tasking -> Device: YES, App: YES
,2016-09-06 16:54:32.238 ThaliTest[1684:3603572] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 16:54:33.900 ThaliTest[1684:3603572] Using UIWebView
,2016-09-06 16:54:33.908 ThaliTest[1684:3603572] [CDVTimer][handleopenurl] 0.509977ms
,2016-09-06 16:54:33.921 ThaliTest[1684:3603572] [CDVTimer][intentandnavigationfilter] 12.089968ms
2016-09-06 16:54:33.922 ThaliTest[1684:3603572] [CDVTimer][gesturehandler] 0.432014ms
2016-09-06 16:54:33.922 ThaliTest[1684:3603572] [CDVTimer][TotalPlugin,Startup] 14.971972ms
,2016-09-06 16:54:39.702 ThaliTest[1684:3603572] Resetting plugins due to page load.
,2016-09-06 16:54:42.517 ThaliTest[1684:3603572] Finished load of: file:///var/mobile/Containers/Bundle/Application/59465E56-872E-4012-87C6-3865F996D335/ThaliTest.app/www/index.html
,2016-09-06 16:54:42.761 ThaliTest[1684:3603572] JXcore Cordova plugin initializing
,2016-09-06 16:54:42.762 ThaliTest[1684:3603796] JXcore instance initializing
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
,Total number of executed tests:  44
,Number of passed tests:  44
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  12.07887399196625
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
