#### Test 832688932759c28_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/121D43F7-7D63-4C6F-BA87-6ED468A334A6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/121D43F7-7D63-4C6F-BA87-6ED468A334A6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/832688932759c28/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6A8D13E3-6CD6-4534-9872-C77BF3348045/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56363"
,(lldb)     command script import "/tmp/121D43F7-7D63-4C6F-BA87-6ED468A334A6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 16:51:50.320 ThaliTest[1383:2515652] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/183D49C3-6C11-47DE-A98C-6C21F1582E2E/Library/Cookies/Cookies.binarycookies
,2016-08-30 16:51:50.766 ThaliTest[1383:2515652] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 16:51:50.767 ThaliTest[1383:2515652] Multi-tasking -> Device: YES, App: YES
,2016-08-30 16:51:50.786 ThaliTest[1383:2515652] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 16:51:52.685 ThaliTest[1383:2515652] Using UIWebView
,2016-08-30 16:51:52.693 ThaliTest[1383:2515652] [CDVTimer][handleopenurl] 1.302958ms
,2016-08-30 16:51:52.701 ThaliTest[1383:2515652] [CDVTimer][intentandnavigationfilter] 7.619023ms
,2016-08-30 16:51:52.702 ThaliTest[1383:2515652] [CDVTimer][gesturehandler] 0.358999ms
2016-08-30 16:51:52.703 ThaliTest[1383:2515652] [CDVTimer][TotalPluginStartup] 11.256993ms
,2016-08-30 16:51:59.018 ThaliTest[1383:2515652] Resetting plugins due to page load.
,2016-08-30 16:52:02.118 ThaliTest[1383:2515652] Finished load of: file:///var/mobile/Containers/Bundle/Application/6A8D13E3-6CD6-4534-9872-C77BF3348045/ThaliTest.app/www/index.html
,2016-08-30 16:52:02.258 ThaliTest[1383:2515652] JXcore Cordova plugin initializing
,2016-08-30 16:52:02.258 ThaliTest[1383:2515903] JXcore instance initializing
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
Total number of executed tests:  22
Number of passed tests:  22
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  42.96547198295593
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
