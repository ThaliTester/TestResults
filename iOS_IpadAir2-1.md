#### Test 82914073d0f9b46_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0939BA01-AB5F-4031-94B8-ACF1166BFF1D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0939BA01-AB5F-4031-94B8-ACF1166BFF1D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073d0f9b46/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1AD933C2-8BB8-49AF-9925-39BD5AA269A5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57451"
,(lldb)     command script import "/tmp/0939BA01-AB5F-4031-94B8-ACF1166BFF1D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 19:14:38.876 ThaliTest[1802:3398554] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/64E2B041-BD5F-47A9-9A28-1A45B2E041BB/Library/Cookies/Cookies.binarycookies
,2016-09-06 19:14:39.109 ThaliTest[1802:3398554] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-06 19:14:39.110 ThaliTest[1802:3398554] Multi-tasking -> Device: YES, App: YES
,2016-09-06 19:14:39.123 ThaliTest[1802:3398554] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 19:14:39.914 ThaliTest[1802:3398554] Using UIWebView
,2016-09-06 19:14:39.917 ThaliTest[1802:3398554] [CDVTimer][handleopenurl] 0.123024ms
,2016-09-06 19:14:39.919 ThaliTest[1802:3398554] [CDVTimer][intentandnavigationfilter] 1.868010ms
2016-09-06 19:14:39.919 ThaliTest[1802:3398554] [CDVTimer][gesturehandler] 0.084996ms
2016-09-06 19:14:39.919 ThaliTest[1802:3398554] [CDVTimer][TotalPluginS,tartup] 2.545953ms
,2016-09-06 19:14:42.908 ThaliTest[1802:3398554] Resetting plugins due to page load.
,2016-09-06 19:14:44.319 ThaliTest[1802:3398554] Finished load of: file:///var/mobile/Containers/Bundle/Application/1AD933C2-8BB8-49AF-9925-39BD5AA269A5/ThaliTest.app/www/index.html
,2016-09-06 19:14:44.447 ThaliTest[1802:3398554] JXcore Cordova plugin initializing
,2016-09-06 19:14:44.448 ThaliTest[1802:3398733] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  38
Number of passed tests:  38
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  12.37030601501465
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
