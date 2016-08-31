#### Test 8344405013e13cf_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8344405013e13cf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/270CA50A-A724-4732-95E5-D111B38246DC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/270CA50A-A724-4732-95E5-D111B38246DC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8344405013e13cf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8344405013e13cf/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D8032EC1-F9A1-4060-A043-E7DDB0F94385/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61842"
,(lldb)     command script import "/tmp/270CA50A-A724-4732-95E5-D111B38246DC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-31 14:54:11.117 ThaliTest[1455:2630331] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A325EF41-AA6B-4AAC-A2C8-8114C87AF387/Library/Cookies/Cookies.binarycookies
,2016-08-31 14:54:11.534 ThaliTest[1455:2630331] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-31 14:54:11.535 ThaliTest[1455:2630331] Multi-tasking -> Device: YES, App: YES
,2016-08-31 14:54:11.556 ThaliTest[1455:2630331] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-31 14:54:13.575 ThaliTest[1455:2630331] Using UIWebView
,2016-08-31 14:54:13.581 ThaliTest[1455:2630331] [CDVTimer][handleopenurl] 0.406981ms
,2016-08-31 14:54:13.589 ThaliTest[1455:2630331] [CDVTimer][intentandnavigationfilter] 7.196963ms
,2016-08-31 14:54:13.590 ThaliTest[1455:2630331] [CDVTimer][gesturehandler] 0.338972ms
,2016-08-31 14:54:13.590 ThaliTest[1455:2630331] [CDVTimer][TotalPluginStartup] 9.676993ms
,2016-08-31 14:54:20.490 ThaliTest[1455:2630331] Resetting plugins due to page load.
,2016-08-31 14:54:23.920 ThaliTest[1455:2630331] Finished load of: file:///var/mobile/Containers/Bundle/Application/D8032EC1-F9A1-4060-A043-E7DDB0F94385/ThaliTest.app/www/index.html
,2016-08-31 14:54:24.131 ThaliTest[1455:2630331] JXcore Cordova plugin initializing
,2016-08-31 14:54:24.132 ThaliTest[1455:2630596] JXcore instance initializing
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
,Total duration:  38.53348004817963
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
