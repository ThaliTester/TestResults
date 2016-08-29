#### Test 81444731606602a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A7862D91-DC35-4037-84A6-21FE4E2AC78F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A7862D91-DC35-4037-84A6-21FE4E2AC78F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/81444731606602a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CB761D22-6C4E-4B81-B6B7-36C63718239B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60431"
,(lldb)     command script import "/tmp/A7862D91-DC35-4037-84A6-21FE4E2AC78F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-29 13:26:57.986 ThaliTest[1252:2363626] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FA50B26D-123A-4B79-9BBC-ABA9E1FC8970/Library/Cookies/Cookies.binarycookies
,2016-08-29 13:26:58.420 ThaliTest[1252:2363626] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-29 13:26:58.422 ThaliTest[1252:2363626] Multi-tasking -> Device: YES, App: YES
,2016-08-29 13:26:58.440 ThaliTest[1252:2363626] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-29 13:27:00.276 ThaliTest[1252:2363626] Using UIWebView
,2016-08-29 13:27:00.281 ThaliTest[1252:2363626] [CDVTimer][handleopenurl] 0.454962ms
,2016-08-29 13:27:00.287 ThaliTest[1252:2363626] [CDVTimer][intentandnavigationfilter] 5.573034ms
,2016-08-29 13:27:00.287 ThaliTest[1252:2363626] [CDVTimer][gesturehandler] 0.232995ms
,2016-08-29 13:27:00.288 ThaliTest[1252:2363626] [CDVTimer][TotalPluginStartup] 7.602990ms
,2016-08-29 13:27:06.643 ThaliTest[1252:2363626] Resetting plugins due to page load.
,2016-08-29 13:27:10.388 ThaliTest[1252:2363626] Finished load of: file:///var/mobile/Containers/Bundle/Application/CB761D22-6C4E-4B81-B6B7-36C63718239B/ThaliTest.app/www/index.html
,2016-08-29 13:27:10.596 ThaliTest[1252:2363626] JXcore Cordova plugin initializing
,2016-08-29 13:27:10.596 ThaliTest[1252:2363889] JXcore instance initializing
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
,Total number of executed tests:  15
,Number of passed tests:  15
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  38.49319899082184
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
