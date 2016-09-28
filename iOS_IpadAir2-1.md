#### Test 87126746a66927d_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5B13E2EB-90CA-4E94-81E6-38E75F91A88B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5B13E2EB-90CA-4E94-81E6-38E75F91A88B/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/87126746a66927d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/720D5A6D-F9C4-4E1C-B8D0-B45BCB0E76E5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54535"
,(lldb)     command script import "/tmp/5B13E2EB-90CA-4E94-81E6-38E75F91A88B/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 16:30:22.764 ThaliTest[3540:6229846] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/70E57E85-052B-41E3-A48D-85FCD297A569/Library/Cookies/Cookies.binarycookies
,2016-09-28 16:30:23.091 ThaliTest[3540:6229846] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 16:30:23.092 ThaliTest[3540:6229846] Multi-tasking -> Device: YES, App: YES
,2016-09-28 16:30:23.109 ThaliTest[3540:6229846] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 16:30:24.950 ThaliTest[3540:6229846] Using UIWebView
,2016-09-28 16:30:24.957 ThaliTest[3540:6229846] [CDVTimer][handleopenurl] 0.497043ms
,2016-09-28 16:30:24.963 ThaliTest[3540:6229846] [CDVTimer][intentandnavigationfilter] 6.313980ms
,2016-09-28 16:30:24.964 ThaliTest[3540:6229846] [CDVTimer][gesturehandler] 0.269949ms
,2016-09-28 16:30:24.964 ThaliTest[3540:6229846] [CDVTimer][TotalPluginStartup] 8.665025ms
,2016-09-28 16:30:31.418 ThaliTest[3540:6229846] Resetting plugins due to page load.
,2016-09-28 16:30:34.371 ThaliTest[3540:6229846] Finished load of: file:///var/mobile/Containers/Bundle/Application/720D5A6D-F9C4-4E1C-B8D0-B45BCB0E76E5/ThaliTest.app/www/index.html
,2016-09-28 16:30:34.647 ThaliTest[3540:6229846] JXcore Cordova plugin initializing
,2016-09-28 16:30:34.648 ThaliTest[3540:6230091] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1356716c0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("F2518981-3283-409B-BDBA-0967BF5DACD3")
,nil
,nil
,Optional("6D5F9E54-EA33-4FDF-AA2D-C90AD7BF1294")
,Optional("AD50DBF1-5826-427E-9467-D7DE245D5104")
,objc[3540]: _XCInternalTestRun object 0x137b1f670 overreleased while already deallocating; break on objc_overrelease_during_dealloc_error to debug
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  54
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  19.09315901994705
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
