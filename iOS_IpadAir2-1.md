#### Test 82914073b1ed9e5_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6290E869-6C24-4ED6-B948-E7EF56CA53C0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6290E869-6C24-4ED6-B948-E7EF56CA53C0/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073b1ed9e5/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B8FB4FE7-D598-4BAC-BE6A-7C484C3E35B0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56199"
,(lldb)     command script import "/tmp/6290E869-6C24-4ED6-B948-E7EF56CA53C0/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 18:46:32.534 ThaliTest[1490:2654434] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C80962D8-CC4D-4183-8A46-0404BF76392D/Library/Cookies/Cookies.binarycookies
,2016-08-31 18:46:32.922 ThaliTest[1490:2654434] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 18:46:32.923 ThaliTest[1490:2654434] Multi-tasking -> Device: YES, App: YES
,2016-08-31 18:46:32.943 ThaliTest[1490:2654434] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 18:46:34.787 ThaliTest[1490:2654434] Using UIWebView
,2016-08-31 18:46:34.796 ThaliTest[1490:2654434] [CDVTimer][handleopenurl] 0.532985ms
,2016-08-31 18:46:34.804 ThaliTest[1490:2654434] [CDVTimer][intentandnavigationfilter] 6.670952ms
,2016-08-31 18:46:34.804 ThaliTest[1490:2654434] [CDVTimer][gesturehandler] 0.317037ms
,2016-08-31 18:46:34.805 ThaliTest[1490:2654434] [CDVTimer][TotalPluginStartup] 9.455979ms
,2016-08-31 18:46:41.115 ThaliTest[1490:2654434] Resetting plugins due to page load.
,2016-08-31 18:46:44.602 ThaliTest[1490:2654434] Finished load of: file:///var/mobile/Containers/Bundle/Application/B8FB4FE7-D598-4BAC-BE6A-7C484C3E35B0/ThaliTest.app/www/index.html
,2016-08-31 18:46:44.805 ThaliTest[1490:2654434] JXcore Cordova plugin initializing
,2016-08-31 18:46:44.806 ThaliTest[1490:2654690] JXcore instance initializing
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
,Total number of executed tests:  22
Number of passed tests:  22
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  43.70934396982193
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
