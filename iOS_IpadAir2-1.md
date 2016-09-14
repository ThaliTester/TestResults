#### Test 8526390230c731c_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/DA919613-7ED8-415B-8FAA-2976F389F1F9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DA919613-7ED8-415B-8FAA-2976F389F1F9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390230c731c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/24F37FF4-4F85-4064-8177-D89168794256/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50169"
,(lldb)     command script import "/tmp/DA919613-7ED8-415B-8FAA-2976F389F1F9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 22:57:43.771 ThaliTest[2358:4457487] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/61373615-9114-432B-8C09-21913D85169E/Library/Cookies/Cookies.binarycookies
,2016-09-14 22:57:44.089 ThaliTest[2358:4457487] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 22:57:44.090 ThaliTest[2358:4457487] Multi-tasking -> Device: YES, App: YES
,2016-09-14 22:57:44.106 ThaliTest[2358:4457487] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 22:57:45.993 ThaliTest[2358:4457487] Using UIWebView
,2016-09-14 22:57:46.000 ThaliTest[2358:4457487] [CDVTimer][handleopenurl] 0.353038ms
,2016-09-14 22:57:46.007 ThaliTest[2358:4457487] [CDVTimer][intentandnavigationfilter] 6.503999ms
,2016-09-14 22:57:46.008 ThaliTest[2358:4457487] [CDVTimer][gesturehandler] 0.283003ms
,2016-09-14 22:57:46.009 ThaliTest[2358:4457487] [CDVTimer][TotalPluginStartup] 8.693039ms
,2016-09-14 22:57:53.149 ThaliTest[2358:4457487] Resetting plugins due to page load.
,2016-09-14 22:57:56.598 ThaliTest[2358:4457487] Finished load of: file:///var/mobile/Containers/Bundle/Application/24F37FF4-4F85-4064-8177-D89168794256/ThaliTest.app/www/index.html
,2016-09-14 22:57:56.813 ThaliTest[2358:4457487] JXcore Cordova plugin initializing
,2016-09-14 22:57:56.814 ThaliTest[2358:4457736] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 22:58:03.478 ThaliTest[2358:4457487] BTM: attaching to BTServer
,2016-09-14 22:58:08.037 ThaliTest[2358:4457487] BTM: local device power state changed
2016-09-14 22:58:08.037 ThaliTest[2358:4457487] BTM: power is now off
,2016-09-14 22:58:08.853 ThaliTest[2358:4457487] BTM: local device power state changed
2016-09-14 22:58:08.853 ThaliTest[2358:4457487] BTM: power is now on
,received session: <ThaliCore.Session: 0x13d62ce10>
,*Native tests were executed*
,Total number of executed tests:  51
Number of passed tests:  51
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  23.61177599430084
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
