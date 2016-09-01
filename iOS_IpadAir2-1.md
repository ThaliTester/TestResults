#### Test 83268893751f823_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893751f823/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/ADF27B82-D8E5-4F6D-8A50-3EEDD9994DBD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/ADF27B82-D8E5-4F6D-8A50-3EEDD9994DBD/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893751f823/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893751f823/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/55A711B8-0B4F-4AEE-B0EA-FC627B57E5CA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49842"
,(lldb)     command script import "/tmp/ADF27B82-D8E5-4F6D-8A50-3EEDD9994DBD/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-01 18:47:41.485 ThaliTest[1555:2780706] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/05D463C5-2F06-4E52-AAC4-DE3DD78AE295/Library/Cookies/Cookies.binarycookies
,2016-09-01 18:47:41.902 ThaliTest[1555:2780706] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-01 18:47:41.904 ThaliTest[1555:2780706] Multi-tasking -> Device: YES, App: YES
,2016-09-01 18:47:41.922 ThaliTest[1555:2780706] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-01 18:47:43.744 ThaliTest[1555:2780706] Using UIWebView
,2016-09-01 18:47:43.751 ThaliTest[1555:2780706] [CDVTimer][handleopenurl] 0.455976ms
,2016-09-01 18:47:43.758 ThaliTest[1555:2780706] [CDVTimer][intentandnavigationfilter] 6.649971ms
,2016-09-01 18:47:43.759 ThaliTest[1555:2780706] [CDVTimer][gesturehandler] 0.440001ms
,2016-09-01 18:47:43.760 ThaliTest[1555:2780706] [CDVTimer][TotalPluginStartup] 9.456038ms
,2016-09-01 18:47:50.574 ThaliTest[1555:2780706] Resetting plugins due to page load.
,2016-09-01 18:47:54.160 ThaliTest[1555:2780706] Finished load of: file:///var/mobile/Containers/Bundle/Application/55A711B8-0B4F-4AEE-B0EA-FC627B57E5CA/ThaliTest.app/www/index.html
,2016-09-01 18:47:54.363 ThaliTest[1555:2780706] JXcore Cordova plugin initializing
,2016-09-01 18:47:54.364 ThaliTest[1555:2780999] JXcore instance initializing
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
Total duration:  43.65338999032974
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
