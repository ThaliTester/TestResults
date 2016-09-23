#### Test 864825820901bf9_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E6767BE3-71B8-4C99-9565-0CADA1530598/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E6767BE3-71B8-4C99-9565-0CADA1530598/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F7AD8CAA-2091-4C24-A6F0-F4A15EF189BD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56075"
,(lldb)     command script import "/tmp/E6767BE3-71B8-4C99-9565-0CADA1530598/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 12:01:49.976 ThaliTest[3152:5570282] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F5B8BB62-5DE5-499B-B04C-44E22683EBCA/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:01:50.327 ThaliTest[3152:5570282] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:01:50.329 ThaliTest[3152:5570282] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:01:50.347 ThaliTest[3152:5570282] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:01:52.335 ThaliTest[3152:5570282] Using UIWebView
,2016-09-23 12:01:52.342 ThaliTest[3152:5570282] [CDVTimer][handleopenurl] 0.318050ms
,2016-09-23 12:01:52.349 ThaliTest[3152:5570282] [CDVTimer][intentandnavigationfilter] 6.820023ms
,2016-09-23 12:01:52.350 ThaliTest[3152:5570282] [CDVTimer][gesturehandler] 0.328958ms
,2016-09-23 12:01:52.350 ThaliTest[3152:5570282] [CDVTimer][TotalPluginStartup] 9.109974ms
,2016-09-23 12:01:58.738 ThaliTest[3152:5570282] Resetting plugins due to page load.
,2016-09-23 12:02:01.741 ThaliTest[3152:5570282] Finished load of: file:///var/mobile/Containers/Bundle/Application/F7AD8CAA-2091-4C24-A6F0-F4A15EF189BD/ThaliTest.app/www/index.html
,2016-09-23 12:02:01.887 ThaliTest[3152:5570282] JXcore Cordova plugin initializing
,2016-09-23 12:02:01.887 ThaliTest[3152:5570526] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x147662420>
,Optional("AEBEA0AB-68D6-4327-ABC0-57F9F18DCC80")
,nil
,nil
,Optional("CCF31C20-3175-4A55-96E8-7746D7083C7B")
,Optional("9A0CB408-DD83-4481-938F-854548A2211E")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 12:02:28.608 ThaliTest[3152:5570282] BTM: attaching to BTServer
,2016-09-23 12:02:29.406 ThaliTest[3152:5570282] BTM: local device power state changed
2016-09-23 12:02:29.407 ThaliTest[3152:5570282] BTM: power is now on
,2016-09-23 12:02:34.079 ThaliTest[3152:5570282] BTM: local device power state changed
2016-09-23 12:02:34.079 ThaliTest[3152:5570282] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.65425896644592
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
