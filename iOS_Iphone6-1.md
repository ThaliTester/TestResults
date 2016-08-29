#### Test 82914073a7b15c1_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0BDCCEDD-BB3C-4E75-B533-0AA6ACEE8501/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/0BDCCEDD-BB3C-4E75-B533-0AA6ACEE8501/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a7b15c1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/59B753AC-4A33-4F00-9440-42E41CE16746/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57798"
,(lldb)     command script import "/tmp/0BDCCEDD-BB3C-4E75-B533-0AA6ACEE8501/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 18:38:32.544 ThaliTest[771:1020550] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7BB020FC-F5CF-4CEC-9328-08EDC6E05ED6/Library/Cookies/Cookies.binarycookies
,2016-08-29 18:38:33.054 ThaliTest[771:1020550] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 18:38:33.056 ThaliTest[771:1020550] Multi-tasking -> Device: YES, App: YES
,2016-08-29 18:38:33.079 ThaliTest[771:1020550] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 18:38:34.996 ThaliTest[771:1020550] Using UIWebView
,2016-08-29 18:38:35.003 ThaliTest[771:1020550] [CDVTimer][handleopenurl] 0.604987ms
,2016-08-29 18:38:35.011 ThaliTest[771:1020550] [CDVTimer][intentandnavigationfilter] 7.560015ms
2016-08-29 18:38:35.012 ThaliTest[771:1020550] [CDVTimer][gesturehandler] 0.312030ms
2016-08-29 18:38:35.012 ThaliTest[771:1020550] [CDVTimer][TotalPluginStartup] 10.104001ms
,2016-08-29 18:38:41.505 ThaliTest[771:1020550] Resetting plugins due to page load.
,2016-08-29 18:38:44.721 ThaliTest[771:1020550] Finished load of: file:///var/mobile/Containers/Bundle/Application/59B753AC-4A33-4F00-9440-42E41CE16746/ThaliTest.app/www/index.html
,2016-08-29 18:38:44.948 ThaliTest[771:1020550] JXcore Cordova plugin initializing
,2016-08-29 18:38:44.949 ThaliTest[771:1020802] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,Total number of executed tests:  20
,Number of passed tests:  20
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  43.04577100276947
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
