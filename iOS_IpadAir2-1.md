#### Test 850469112dc361b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/6219CC8F-BBF2-49B3-A1E0-275E3925F955/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/6219CC8F-BBF2-49B3-A1E0-275E3925F955/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469112dc361b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BC972190-179C-400C-944A-F75A8900B1F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53143"
,(lldb)     command script import "/tmp/6219CC8F-BBF2-49B3-A1E0-275E3925F955/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:27:03.430 ThaliTest[3428:6079539] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6596DD81-A78A-4246-91E5-37BE1F89B122/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:27:03.785 ThaliTest[3428:6079539] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:27:03.787 ThaliTest[3428:6079539] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:27:03.806 ThaliTest[3428:6079539] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:27:05.794 ThaliTest[3428:6079539] Using UIWebView
,2016-09-27 12:27:05.801 ThaliTest[3428:6079539] [CDVTimer][handleopenurl] 0.340998ms
,2016-09-27 12:27:05.808 ThaliTest[3428:6079539] [CDVTimer][intentandnavigationfilter] 6.853998ms
,2016-09-27 12:27:05.809 ThaliTest[3428:6079539] [CDVTimer][gesturehandler] 0.404000ms
2016-09-27 12:27:05.810 ThaliTest[3428:6079539] [CDVTimer][TotalPluginStartup] 9.293020ms
,2016-09-27 12:27:12.216 ThaliTest[3428:6079539] Resetting plugins due to page load.
,2016-09-27 12:27:15.233 ThaliTest[3428:6079539] Finished load of: file:///var/mobile/Containers/Bundle/Application/BC972190-179C-400C-944A-F75A8900B1F8/ThaliTest.app/www/index.html
,2016-09-27 12:27:15.438 ThaliTest[3428:6079539] JXcore Cordova plugin initializing
,2016-09-27 12:27:15.439 ThaliTest[3428:6079811] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12e26faa0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("AE1BDFDC-3208-48E2-B99D-F95E9B479B01")
,nil
,nil
,Optional("F4A12E23-3FBC-4632-AA72-2097FF7D9BBE")
,Optional("742451EA-3D45-4B81-8739-1CA36B466CEF")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  55
Number of passed tests:  53
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  20.6450070142746
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
