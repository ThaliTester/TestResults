#### Test 850469116954903_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C59418AE-734F-4418-AAB6-2DCCC1B04017/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C59418AE-734F-4418-AAB6-2DCCC1B04017/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9CC66C21-138D-4C8D-8991-77F4EB76F8A8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60491"
,(lldb)     command script import "/tmp/C59418AE-734F-4418-AAB6-2DCCC1B04017/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:23:28.159 ThaliTest[3105:5545904] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1E7A44D5-47B8-43A5-BD6A-2796523441D4/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:23:28.478 ThaliTest[3105:5545904] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:23:28.479 ThaliTest[3105:5545904] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:23:28.493 ThaliTest[3105:5545904] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:23:30.219 ThaliTest[3105:5545904] Using UIWebView
,2016-09-23 08:23:30.226 ThaliTest[3105:5545904] [CDVTimer][handleopenurl] 0.381052ms
,2016-09-23 08:23:30.232 ThaliTest[3105:5545904] [CDVTimer][intentandnavigationfilter] 6.390989ms
,2016-09-23 08:23:30.233 ThaliTest[3105:5545904] [CDVTimer][gesturehandler] 0.283003ms
,2016-09-23 08:23:30.234 ThaliTest[3105:5545904] [CDVTimer][TotalPluginStartup] 8.535981ms
,2016-09-23 08:23:36.479 ThaliTest[3105:5545904] Resetting plugins due to page load.
,2016-09-23 08:23:39.497 ThaliTest[3105:5545904] Finished load of: file:///var/mobile/Containers/Bundle/Application/9CC66C21-138D-4C8D-8991-77F4EB76F8A8/ThaliTest.app/www/index.html
,2016-09-23 08:23:39.763 ThaliTest[3105:5545904] JXcore Cordova plugin initializing
,2016-09-23 08:23:39.763 ThaliTest[3105:5546142] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x12e685060>
,Optional("5B91F86D-8D0C-46C4-98F0-690560951B63")
,nil
,nil
,Optional("DEE80B92-E739-44F8-B07A-0A7B02485C3B")
,Optional("0776F0E7-E2FD-4F2B-AA2A-28B166EAB2A7")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 08:24:06.444 ThaliTest[3105:5545904] BTM: attaching to BTServer
,2016-09-23 08:24:07.252 ThaliTest[3105:5545904] BTM: local device power state changed
2016-09-23 08:24:07.252 ThaliTest[3105:5545904] BTM: power is now on
,2016-09-23 08:24:11.925 ThaliTest[3105:5545904] BTM: local device power state changed
2016-09-23 08:24:11.925 ThaliTest[3105:5545904] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.69924300909042
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
