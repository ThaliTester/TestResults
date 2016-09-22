#### Test 8617437951c5913_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/E1270228-504A-407A-9CCC-BCB95B72E63E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
Executing commands in '/tmp/E1270228-504A-407A-9CCC-BCB95B72E63E/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437951c5913/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F413781B-84B2-424F-AE81-BA4945DBB839/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60370"
,(lldb)     command script import "/tmp/E1270228-504A-407A-9CCC-BCB95B72E63E/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 16:52:42.096 ThaliTest[3056:5463039] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F14F4A04-04F6-4A5A-A643-0DDB1D11F635/Library/Cookies/Cookies.binarycookies
,2016-09-22 16:52:42.461 ThaliTest[3056:5463039] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 16:52:42.462 ThaliTest[3056:5463039] Multi-tasking -> Device: YES, App: YES
,2016-09-22 16:52:42.481 ThaliTest[3056:5463039] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 16:52:44.422 ThaliTest[3056:5463039] Using UIWebView
,2016-09-22 16:52:44.428 ThaliTest[3056:5463039] [CDVTimer][handleopenurl] 0.497997ms
,2016-09-22 16:52:44.435 ThaliTest[3056:5463039] [CDVTimer][intentandnavigationfilter] 6.850004ms
,2016-09-22 16:52:44.436 ThaliTest[3056:5463039] [CDVTimer][gesturehandler] 0.288963ms
,2016-09-22 16:52:44.437 ThaliTest[3056:5463039] [CDVTimer][TotalPluginStartup] 9.238958ms
,2016-09-22 16:52:50.639 ThaliTest[3056:5463039] Resetting plugins due to page load.
,2016-09-22 16:52:53.592 ThaliTest[3056:5463039] Finished load of: file:///var/mobile/Containers/Bundle/Application/F413781B-84B2-424F-AE81-BA4945DBB839/ThaliTest.app/www/index.html
,2016-09-22 16:52:53.811 ThaliTest[3056:5463039] JXcore Cordova plugin initializing
,2016-09-22 16:52:53.813 ThaliTest[3056:5463291] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x149126840>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("9F92DC36-C69B-49F4-A81F-4B8C8052CF03")
,nil
,nil
,Optional("426FD1C2-6BEE-44F2-BD08-3E7BBF99E0E6")
,Optional("04FCE9F7-4A2A-443E-B695-8E9DA7725B74")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 16:53:20.304 ThaliTest[3056:5463039] BTM: attaching to BTServer
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  47
,Number of failed tests:  9
,Number of ignored tests:  0
,Total duration:  40.05965203046799
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
