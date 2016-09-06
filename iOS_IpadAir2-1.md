#### Test 83444050adbb179_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83444050adbb179/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B9A4BD19-EB2C-41DA-BDF1-BCC0F8BE89E9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B9A4BD19-EB2C-41DA-BDF1-BCC0F8BE89E9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83444050adbb179/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83444050adbb179/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/38F6ACAE-CA67-4F72-A2DB-5CD820093AE7/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57520"
,(lldb)     command script import "/tmp/B9A4BD19-EB2C-41DA-BDF1-BCC0F8BE89E9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:20:52.442 ThaliTest[1810:3400135] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E9367665-5B28-442B-A893-E7045E1D9D42/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:20:52.677 ThaliTest[1810:3400135] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:20:52.678 ThaliTest[1810:3400135] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:20:52.691 ThaliTest[1810:3400135] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:20:53.478 ThaliTest[1810:3400135] Using UIWebView
,2016-09-06 19:20:53.480 ThaliTest[1810:3400135] [CDVTimer][handleopenurl] 0.101984ms
,2016-09-06 19:20:53.482 ThaliTest[1810:3400135] [CDVTimer][intentandnavigationfilter] 1.823962ms
2016-09-06 19:20:53.482 ThaliTest[1810:3400135] [CDVTimer][gesturehandler] 0.082970ms
2016-09-06 19:20:53.483 ThaliTest[1810:3400135] [CDVTimer][TotalPluginStartup] 2.436996ms
,2016-09-06 19:20:56.473 ThaliTest[1810:3400135] Resetting plugins due to page load.
,2016-09-06 19:20:57.875 ThaliTest[1810:3400135] Finished load of: file:///var/mobile/Containers/Bundle/Application/38F6ACAE-CA67-4F72-A2DB-5CD820093AE7/ThaliTest.app/www/index.html
,2016-09-06 19:20:58.010 ThaliTest[1810:3400135] JXcore Cordova plugin initializing
,2016-09-06 19:20:58.011 ThaliTest[1810:3400312] JXcore instance initializing
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
Total number of executed tests:  15
Number of passed tests:  15
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  38.50828403234482
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
