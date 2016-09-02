#### Test 832688936f8f85f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/C7E0460A-E732-4153-A46B-97CF47CE5B0D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/C7E0460A-E732-4153-A46B-97CF47CE5B0D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688936f8f85f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BCC36A0B-AEBE-472B-898E-56CDF655D5E9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53317"
,(lldb)     command script import "/tmp/C7E0460A-E732-4153-A46B-97CF47CE5B0D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-02 11:34:09.032 ThaliTest[1485:2984388] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D1942542-3AFF-40D8-8FF4-E7D06DA19CF3/Library/Cookies/Cookies.binarycookies
,2016-09-02 11:34:09.418 ThaliTest[1485:2984388] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-02 11:34:09.420 ThaliTest[1485:2984388] Multi-tasking -> Device: YES, App: YES
,2016-09-02 11:34:09.447 ThaliTest[1485:2984388] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-02 11:34:11.374 ThaliTest[1485:2984388] Using UIWebView
,2016-09-02 11:34:11.383 ThaliTest[1485:2984388] [CDVTimer][handleopenurl] 1.528978ms
,2016-09-02 11:34:11.391 ThaliTest[1485:2984388] [CDVTimer][intentandnavigationfilter] 8.116007ms
2016-09-02 11:34:11.392 ThaliTest[1485:2984388] [CDVTimer][gesturehandler] 0.395000ms
2016-09-02 11:34:11.393 ThaliTest[1485:2984388] [CDVTimer][TotalPluginStartup] 12.067020ms
,2016-09-02 11:34:17.911 ThaliTest[1485:2984388] Resetting plugins due to page load.
,2016-09-02 11:34:21.131 ThaliTest[1485:2984388] Finished load of: file:///var/mobile/Containers/Bundle/Application/BCC36A0B-AEBE-472B-898E-56CDF655D5E9/ThaliTest.app/www/index.html
,2016-09-02 11:34:21.376 ThaliTest[1485:2984388] JXcore Cordova plugin initializing
,2016-09-02 11:34:21.377 ThaliTest[1485:2984628] JXcore instance initializing
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
Total number of executed tests:  25
Number of passed tests:  25
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  42.2124810218811
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
