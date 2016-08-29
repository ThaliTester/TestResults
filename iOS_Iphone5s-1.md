#### Test 81444731606602a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8FFFF3A8-B2D8-4D33-B1CE-7B939C2AC5B8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/8FFFF3A8-B2D8-4D33-B1CE-7B939C2AC5B8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A79B8DD-7F0B-4604-8A7C-87205AB4D59B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60438"
,(lldb)     command script import "/tmp/8FFFF3A8-B2D8-4D33-B1CE-7B939C2AC5B8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:26:57.131 ThaliTest[1149:2392352] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/048F6D5F-C2CB-48D9-BE98-9ADE149C0921/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:26:57.552 ThaliTest[1149:2392352] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 13:26:57.554 ThaliTest[1149:2392352] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:26:57.583 ThaliTest[1149:2392352] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:26:59.189 ThaliTest[1149:2392352] Using UIWebView
,2016-08-29 13:26:59.197 ThaliTest[1149:2392352] [CDVTimer][handleopenurl] 0.431001ms
,2016-08-29 13:26:59.206 ThaliTest[1149:2392352] [CDVTimer][intentandnavigationfilter] 8.433044ms
2016-08-29 13:26:59.207 ThaliTest[1149:2392352] [CDVTimer][gesturehandler] 0.527024ms
2016-08-29 13:26:59.207 ThaliTest[1149:2392352] [CDVTimer][TotalPluginS,tartup] 11.316001ms
,2016-08-29 13:27:05.007 ThaliTest[1149:2392352] Resetting plugins due to page load.
,2016-08-29 13:27:07.955 ThaliTest[1149:2392352] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A79B8DD-7F0B-4604-8A7C-87205AB4D59B/ThaliTest.app/www/index.html
,2016-08-29 13:27:08.212 ThaliTest[1149:2392352] JXcore Cordova plugin initializing
,2016-08-29 13:27:08.213 ThaliTest[1149:2392582] JXcore instance initializing
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
Total number of executed tests:  15
Number of passed tests:  15
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  38.65839201211929
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackgroun
```
