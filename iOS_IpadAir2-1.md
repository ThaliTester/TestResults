#### Test 82914073a71b108_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073a71b108/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/AE779762-3EB0-41D1-8ED8-87042B1D7F18/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AE779762-3EB0-41D1-8ED8-87042B1D7F18/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073a71b108/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073a71b108/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1B3858A0-3628-43C1-86E5-B44193E50F72/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59583"
,(lldb)     command script import "/tmp/AE779762-3EB0-41D1-8ED8-87042B1D7F18/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-30 14:39:23.682 ThaliTest[1339:2499185] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/34394C51-B648-4524-B04A-599A6723A480/Library/Cookies/Cookies.binarycookies
,2016-08-30 14:39:24.114 ThaliTest[1339:2499185] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-30 14:39:24.115 ThaliTest[1339:2499185] Multi-tasking -> Device: YES, App: YES
,2016-08-30 14:39:24.134 ThaliTest[1339:2499185] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-30 14:39:25.973 ThaliTest[1339:2499185] Using UIWebView
,2016-08-30 14:39:25.981 ThaliTest[1339:2499185] [CDVTimer][handleopenurl] 0.530005ms
,2016-08-30 14:39:25.988 ThaliTest[1339:2499185] [CDVTimer][intentandnavigationfilter] 6.645024ms
,2016-08-30 14:39:25.989 ThaliTest[1339:2499185] [CDVTimer][gesturehandler] 0.313997ms
2016-08-30 14:39:25.989 ThaliTest[1339:2499185] [CDVTimer][TotalPluginStartup] 9.109020ms
,2016-08-30 14:39:32.731 ThaliTest[1339:2499185] Resetting plugins due to page load.
,2016-08-30 14:39:36.247 ThaliTest[1339:2499185] Finished load of: file:///var/mobile/Containers/Bundle/Application/1B3858A0-3628-43C1-86E5-B44193E50F72/ThaliTest.app/www/index.html
,2016-08-30 14:39:36.452 ThaliTest[1339:2499185] JXcore Cordova plugin initializing
2016-08-30 14:39:36.453 ThaliTest[1339:2499440] JXcore instance initializing
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
,Total number of executed tests:  21
,Number of passed tests:  21
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  42.80412501096725
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
