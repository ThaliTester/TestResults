#### Test 82914073f44248e_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C4CE07E1-8375-42E7-AF1E-B6ACF0B607EF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C4CE07E1-8375-42E7-AF1E-B6ACF0B607EF/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073f44248e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2A190ED5-D0D2-4AD9-8537-638D0D07136B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57248"
,(lldb)     command script import "/tmp/C4CE07E1-8375-42E7-AF1E-B6ACF0B607EF/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-06 18:55:18.187 ThaliTest[1776:3393272] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D81E2C4D-3436-47AD-8C7E-209CA01343C6/Library/Cookies/Cookies.binarycookies
,2016-09-06 18:55:18.433 ThaliTest[1776:3393272] Apache Cordova native platform version 4.1.1 is starting.
2016-09-06 18:55:18.434 ThaliTest[1776:3393272] Multi-tasking -> Device: YES, App: YES
,2016-09-06 18:55:18.448 ThaliTest[1776:3393272] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-06 18:55:19.262 ThaliTest[1776:3393272] Using UIWebView
,2016-09-06 18:55:19.264 ThaliTest[1776:3393272] [CDVTimer][handleopenurl] 0.113010ms
,2016-09-06 18:55:19.266 ThaliTest[1776:3393272] [CDVTimer][intentandnavigationfilter] 1.817048ms
2016-09-06 18:55:19.266 ThaliTest[1776:3393272] [CDVTimer][gesturehandler] 0.079989ms
2016-09-06 18:55:19.266 ThaliTest[1776:3393272] [CDVTimer][TotalPluginStartup] 2.427042ms
,2016-09-06 18:55:22.372 ThaliTest[1776:3393272] Resetting plugins due to page load.
,2016-09-06 18:55:23.771 ThaliTest[1776:3393272] Finished load of: file:///var/mobile/Containers/Bundle/Application/2A190ED5-D0D2-4AD9-8537-638D0D07136B/ThaliTest.app/www/index.html
,2016-09-06 18:55:23.909 ThaliTest[1776:3393272] JXcore Cordova plugin initializing
2016-09-06 18:55:23.909 ThaliTest[1776:3393459] JXcore instance initializing
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
Total number of executed tests:  38
Number of passed tests:  38
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  13.56679505109787
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
