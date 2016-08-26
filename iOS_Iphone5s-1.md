#### Test 82914073856d1c8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/363E13E7-05AE-46AC-B894-5734F70C22DD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/363E13E7-05AE-46AC-B894-5734F70C22DD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073856d1c8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/641A5EEC-C800-4C3C-B703-1CFB52D5D75A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59601"
,(lldb)     command script import "/tmp/363E13E7-05AE-46AC-B894-5734F70C22DD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 19:44:02.560 ThaliTest[999:1996429] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B95FBD4A-648A-4FD4-9173-3826F4BAE328/Library/Cookies/Cookies.binarycookies
,2016-08-26 19:44:03.006 ThaliTest[999:1996429] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 19:44:03.008 ThaliTest[999:1996429] Multi-tasking -> Device: YES, App: YES
,2016-08-26 19:44:03.031 ThaliTest[999:1996429] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 19:44:05.040 ThaliTest[999:1996429] Using UIWebView
,2016-08-26 19:44:05.048 ThaliTest[999:1996429] [CDVTimer][handleopenurl] 0.442028ms
,2016-08-26 19:44:05.057 ThaliTest[999:1996429] [CDVTimer][intentandnavigationfilter] 8.065999ms
2016-08-26 19:44:05.058 ThaliTest[999:1996429] [CDVTimer][gesturehandler] 0.423968ms
2016-08-26 19:44:05.058 ThaliTest[999:1996429] [CDVTimer][TotalPluginStartup] 10.827959ms
,2016-08-26 19:44:11.236 ThaliTest[999:1996429] Resetting plugins due to page load.
,2016-08-26 19:44:14.628 ThaliTest[999:1996429] Finished load of: file:///var/mobile/Containers/Bundle/Application/641A5EEC-C800-4C3C-B703-1CFB52D5D75A/ThaliTest.app/www/index.html
,2016-08-26 19:44:14.882 ThaliTest[999:1996429] JXcore Cordova plugin initializing
,2016-08-26 19:44:14.883 ThaliTest[999:1996675] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
Total number of executed tests:  20
,Number of passed tests:  20
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  42.38979405164719
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
