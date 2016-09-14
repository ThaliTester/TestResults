#### Test 8526390229a14d1_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B895F6E4-0895-44CB-B437-4A88C2D49876/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B895F6E4-0895-44CB-B437-4A88C2D49876/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8526390229a14d1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A5C1B4B0-0E1F-4922-AA04-93361CE2CA96/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50119"
,(lldb)     command script import "/tmp/B895F6E4-0895-44CB-B437-4A88C2D49876/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 22:15:04.220 ThaliTest[2350:4452893] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/49E6572A-4A1B-4B3F-918A-20EFDAEA2ED8/Library/Cookies/Cookies.binarycookies
,2016-09-14 22:15:04.570 ThaliTest[2350:4452893] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 22:15:04.572 ThaliTest[2350:4452893] Multi-tasking -> Device: YES, App: YES
,2016-09-14 22:15:04.592 ThaliTest[2350:4452893] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 22:15:06.855 ThaliTest[2350:4452893] Using UIWebView
,2016-09-14 22:15:06.861 ThaliTest[2350:4452893] [CDVTimer][handleopenurl] 0.335991ms
,2016-09-14 22:15:06.868 ThaliTest[2350:4452893] [CDVTimer][intentandnavigationfilter] 6.291986ms
,2016-09-14 22:15:06.869 ThaliTest[2350:4452893] [CDVTimer][gesturehandler] 0.274003ms
,2016-09-14 22:15:06.869 ThaliTest[2350:4452893] [CDVTimer][TotalPluginStartup] 8.377969ms
,2016-09-14 22:15:14.945 ThaliTest[2350:4452893] Resetting plugins due to page load.
,2016-09-14 22:15:19.322 ThaliTest[2350:4452893] Finished load of: file:///var/mobile/Containers/Bundle/Application/A5C1B4B0-0E1F-4922-AA04-93361CE2CA96/ThaliTest.app/www/index.html
,2016-09-14 22:15:19.534 ThaliTest[2350:4452893] JXcore Cordova plugin initializing
,2016-09-14 22:15:19.535 ThaliTest[2350:4453126] JXcore instance initializing
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
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x13febdc20>
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-14 22:15:43.376 ThaliTest[2350:4452893] BTM: attaching to BTServer
,2016-09-14 22:15:44.449 ThaliTest[2350:4452893] BTM: local device power state changed
2016-09-14 22:15:44.450 ThaliTest[2350:4452893] BTM: power is now off
,2016-09-14 22:15:45.252 ThaliTest[2350:4452893] BTM: local device power state changed
2016-09-14 22:15:45.253 ThaliTest[2350:4452893] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  19.22152400016785
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
