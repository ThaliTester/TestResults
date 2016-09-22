#### Test 85046911aad23fc_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911aad23fc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E66E1596-D242-4B29-A98A-6F26BD1E59E6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/E66E1596-D242-4B29-A98A-6F26BD1E59E6/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911aad23fc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911aad23fc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1503A8E7-903A-4EE6-B1BF-81640262824B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59136"
,(lldb)     command script import "/tmp/E66E1596-D242-4B29-A98A-6F26BD1E59E6/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 10:48:00.280 ThaliTest[2996:5424411] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AB6F60C1-D788-4259-BF27-2C97FB82F808/Library/Cookies/Cookies.binarycookies
,2016-09-22 10:48:00.561 ThaliTest[2996:5424411] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 10:48:00.561 ThaliTest[2996:5424411] Multi-tasking -> Device: YES, App: YES
,2016-09-22 10:48:00.577 ThaliTest[2996:5424411] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 10:48:02.284 ThaliTest[2996:5424411] Using UIWebView
,2016-09-22 10:48:02.293 ThaliTest[2996:5424411] [CDVTimer][handleopenurl] 0.325978ms
,2016-09-22 10:48:02.300 ThaliTest[2996:5424411] [CDVTimer][intentandnavigationfilter] 6.617963ms
,2016-09-22 10:48:02.301 ThaliTest[2996:5424411] [CDVTimer][gesturehandler] 0.288010ms
,2016-09-22 10:48:02.301 ThaliTest[2996:5424411] [CDVTimer][TotalPluginStartup] 8.879006ms
,2016-09-22 10:48:08.827 ThaliTest[2996:5424411] Resetting plugins due to page load.
,2016-09-22 10:48:12.063 ThaliTest[2996:5424411] Finished load of: file:///var/mobile/Containers/Bundle/Application/1503A8E7-903A-4EE6-B1BF-81640262824B/ThaliTest.app/www/index.html
,2016-09-22 10:48:12.273 ThaliTest[2996:5424411] JXcore Cordova plugin initializing
,2016-09-22 10:48:12.274 ThaliTest[2996:5424665] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 10:48:18.949 ThaliTest[2996:5424411] BTM: attaching to BTServer
,2016-09-22 10:48:19.750 ThaliTest[2996:5424411] BTM: local device power state changed
2016-09-22 10:48:19.750 ThaliTest[2996:5424411] BTM: power is now on
,2016-09-22 10:48:24.432 ThaliTest[2996:5424411] BTM: local device power state changed
2016-09-22 10:48:24.432 ThaliTest[2996:5424411] BTM: power is now off
,received session: <ThaliCore.Session: 0x129649cb0>
,Optional("D8CFD11B-4286-4E93-AF9A-04E541A97609")
,nil
,nil
,Optional("A5EDB1D6-D104-4B6C-AC85-BC014D4A43F6")
,Optional("6C2C25D8-0994-4F05-9438-796C0DE3D83C")
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.01758700609207
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
