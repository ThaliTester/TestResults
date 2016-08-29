#### Test 8291407379492e1_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/01142A8B-5EB4-40E8-9BA8-053E34021F39/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/01142A8B-5EB4-40E8-9BA8-053E34021F39/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8291407379492e1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DCD45A7D-53D9-4542-8E70-1C385FA29827/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52879"
,(lldb)     command script import "/tmp/01142A8B-5EB4-40E8-9BA8-053E34021F39/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-08-29 10:22:28.065 ThaliTest[1123:2370448] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B25B54DB-64B8-4F7F-9E08-9002D1F48CB7/Library/Cookies/Cookies.binarycookies
,2016-08-29 10:22:28.524 ThaliTest[1123:2370448] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 10:22:28.526 ThaliTest[1123:2370448] Multi-tasking -> Device: YES, App: YES
,2016-08-29 10:22:28.555 ThaliTest[1123:2370448] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 10:22:30.582 ThaliTest[1123:2370448] Using UIWebView
,2016-08-29 10:22:30.589 ThaliTest[1123:2370448] [CDVTimer][handleopenurl] 0.446975ms
,2016-08-29 10:22:30.598 ThaliTest[1123:2370448] [CDVTimer][intentandnavigationfilter] 8.199036ms
2016-08-29 10:22:30.599 ThaliTest[1123:2370448] [CDVTimer][gesturehandler] 0.386000ms
2016-08-29 10:22:30.600 ThaliTest[1123:2370448] [CDVTimer][TotalPluginStartup] 10.983050ms
,2016-08-29 10:22:36.792 ThaliTest[1123:2370448] Resetting plugins due to page load.
,2016-08-29 10:22:40.294 ThaliTest[1123:2370448] Finished load of: file:///var/mobile/Containers/Bundle/Application/DCD45A7D-53D9-4542-8E70-1C385FA29827/ThaliTest.app/www/index.html
,2016-08-29 10:22:40.550 ThaliTest[1123:2370448] JXcore Cordova plugin initializing
,2016-08-29 10:22:40.552 ThaliTest[1123:2370699] JXcore instance initializing
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
,Total number of executed tests:  20
,Number of passed tests:  20
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  42.15834999084473
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
