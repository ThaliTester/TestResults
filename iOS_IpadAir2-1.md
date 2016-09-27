#### Test 850469118f5d139_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/641D011C-6920-4063-B186-FF58750125A5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/641D011C-6920-4063-B186-FF58750125A5/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469118f5d139/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FCCC2A1C-5886-4659-90B9-28504B81269A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58034"
,(lldb)     command script import "/tmp/641D011C-6920-4063-B186-FF58750125A5/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 14:01:51.938 ThaliTest[3470:6093166] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E4BD4A52-73DD-4688-96DB-BACA4BFF0AB7/Library/Cookies/Cookies.binarycookies
,2016-09-27 14:01:52.261 ThaliTest[3470:6093166] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 14:01:52.262 ThaliTest[3470:6093166] Multi-tasking -> Device: YES, App: YES
,2016-09-27 14:01:52.279 ThaliTest[3470:6093166] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 14:01:54.112 ThaliTest[3470:6093166] Using UIWebView
,2016-09-27 14:01:54.119 ThaliTest[3470:6093166] [CDVTimer][handleopenurl] 0.398040ms
,2016-09-27 14:01:54.127 ThaliTest[3470:6093166] [CDVTimer][intentandnavigationfilter] 7.385969ms
,2016-09-27 14:01:54.128 ThaliTest[3470:6093166] [CDVTimer][gesturehandler] 0.322998ms
,2016-09-27 14:01:54.129 ThaliTest[3470:6093166] [CDVTimer][TotalPluginStartup] 9.822011ms
,2016-09-27 14:02:00.863 ThaliTest[3470:6093166] Resetting plugins due to page load.
,2016-09-27 14:02:04.477 ThaliTest[3470:6093166] Finished load of: file:///var/mobile/Containers/Bundle/Application/FCCC2A1C-5886-4659-90B9-28504B81269A/ThaliTest.app/www/index.html
,2016-09-27 14:02:04.737 ThaliTest[3470:6093166] JXcore Cordova plugin initializing
,2016-09-27 14:02:04.738 ThaliTest[3470:6093433] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x15c5f4b20>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("2DB09E43-CEBF-45DF-A712-09F36AA95253")
,nil
,nil
,Optional("D3F590AD-0CD6-43B2-86F6-3065B90A2457")
,Optional("C375CA57-72D4-435C-99D9-876562437363")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  53
,Number of failed tests:  2
,Number of ignored tests:  0
Total duration:  18.91247701644897
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
