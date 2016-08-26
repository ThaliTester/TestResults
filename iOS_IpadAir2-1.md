#### Test 81444731251ddd8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E7804980-C6C5-4407-8EAD-27DAF4D81A7D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E7804980-C6C5-4407-8EAD-27DAF4D81A7D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81444731251ddd8/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B1477AA2-D63F-4EFA-AEF6-FECC65BC35FF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56005"
,(lldb)     command script import "/tmp/E7804980-C6C5-4407-8EAD-27DAF4D81A7D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 19:01:27.880 ThaliTest[1106:2011358] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/68BC983D-275C-474E-8325-04A0CC9660A5/Library/Cookies/Cookies.binarycookies
,2016-08-26 19:01:28.180 ThaliTest[1106:2011358] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 19:01:28.181 ThaliTest[1106:2011358] Multi-tasking -> Device: YES, App: YES
,2016-08-26 19:01:28.196 ThaliTest[1106:2011358] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 19:01:29.794 ThaliTest[1106:2011358] Using UIWebView
,2016-08-26 19:01:29.800 ThaliTest[1106:2011358] [CDVTimer][handleopenurl] 0.397980ms
,2016-08-26 19:01:29.807 ThaliTest[1106:2011358] [CDVTimer][intentandnavigationfilter] 6.625950ms
,2016-08-26 19:01:29.808 ThaliTest[1106:2011358] [CDVTimer][gesturehandler] 0.295997ms
,2016-08-26 19:01:29.808 ThaliTest[1106:2011358] [CDVTimer][TotalPluginStartup] 8.834004ms
,2016-08-26 19:01:35.961 ThaliTest[1106:2011358] Resetting plugins due to page load.
,2016-08-26 19:01:39.619 ThaliTest[1106:2011358] Finished load of: file:///var/mobile/Containers/Bundle/Application/B1477AA2-D63F-4EFA-AEF6-FECC65BC35FF/ThaliTest.app/www/index.html
,2016-08-26 19:01:39.854 ThaliTest[1106:2011358] JXcore Cordova plugin initializing
,2016-08-26 19:01:39.854 ThaliTest[1106:2011610] JXcore instance initializing
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
,Total number of executed tests:  15
,Number of passed tests:  15
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.40643298625946
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
