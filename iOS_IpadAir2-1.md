#### Test 83070177977a8d1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/00652272-B3A7-483A-9F10-FB5B4BF3FB4D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/00652272-B3A7-483A-9F10-FB5B4BF3FB4D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83070177977a8d1/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/784B421A-469F-4A38-8DC8-4742E7670429/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61905"
,(lldb)     command script import "/tmp/00652272-B3A7-483A-9F10-FB5B4BF3FB4D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:43:04.687 ThaliTest[1261:2366178] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0CC08EB9-CE96-4099-85CE-E5B5528E01BD/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:43:05.074 ThaliTest[1261:2366178] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 13:43:05.075 ThaliTest[1261:2366178] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:43:05.095 ThaliTest[1261:2366178] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:43:07.012 ThaliTest[1261:2366178] Using UIWebView
,2016-08-29 13:43:07.020 ThaliTest[1261:2366178] [CDVTimer][handleopenurl] 0.455976ms
,2016-08-29 13:43:07.028 ThaliTest[1261:2366178] [CDVTimer][intentandnavigationfilter] 7.115960ms
,2016-08-29 13:43:07.029 ThaliTest[1261:2366178] [CDVTimer][gesturehandler] 0.373006ms
,2016-08-29 13:43:07.029 ThaliTest[1261:2366178] [CDVTimer][TotalPluginStartup] 9.729028ms
,2016-08-29 13:43:13.626 ThaliTest[1261:2366178] Resetting plugins due to page load.
,2016-08-29 13:43:17.071 ThaliTest[1261:2366178] Finished load of: file:///var/mobile/Containers/Bundle/Application/784B421A-469F-4A38-8DC8-4742E7670429/ThaliTest.app/www/index.html
,2016-08-29 13:43:17.083 ThaliTest[1261:2366178] JXcore Cordova plugin initializing
,2016-08-29 13:43:17.085 ThaliTest[1261:2366415] JXcore instance initializing
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
,Total number of executed tests:  15
,Number of passed tests:  15
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.61050599813461
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
