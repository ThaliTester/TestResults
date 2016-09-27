#### Test 8689130568a1443_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/DBF93F27-15D9-45E7-82CA-DBC7E1EE9F84/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/DBF93F27-15D9-45E7-82CA-DBC7E1EE9F84/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8689130568a1443/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/55C4034F-138A-4355-847C-5E6CB7711024/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56344"
,(lldb)     command script import "/tmp/DBF93F27-15D9-45E7-82CA-DBC7E1EE9F84/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 12:51:54.769 ThaliTest[3445:6083998] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/442957D2-C98E-438E-876C-634B36C13132/Library/Cookies/Cookies.binarycookies
,2016-09-27 12:51:55.124 ThaliTest[3445:6083998] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 12:51:55.125 ThaliTest[3445:6083998] Multi-tasking -> Device: YES, App: YES
,2016-09-27 12:51:55.141 ThaliTest[3445:6083998] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 12:51:57.030 ThaliTest[3445:6083998] Using UIWebView
,2016-09-27 12:51:57.037 ThaliTest[3445:6083998] [CDVTimer][handleopenurl] 0.379980ms
,2016-09-27 12:51:57.044 ThaliTest[3445:6083998] [CDVTimer][intentandnavigationfilter] 6.591022ms
,2016-09-27 12:51:57.045 ThaliTest[3445:6083998] [CDVTimer][gesturehandler] 0.280976ms
,2016-09-27 12:51:57.045 ThaliTest[3445:6083998] [CDVTimer][TotalPluginStartup] 8.979976ms
,2016-09-27 12:52:03.477 ThaliTest[3445:6083998] Resetting plugins due to page load.
,2016-09-27 12:52:06.430 ThaliTest[3445:6083998] Finished load of: file:///var/mobile/Containers/Bundle/Application/55C4034F-138A-4355-847C-5E6CB7711024/ThaliTest.app/www/index.html
,2016-09-27 12:52:06.650 ThaliTest[3445:6083998] JXcore Cordova plugin initializing
,2016-09-27 12:52:06.651 ThaliTest[3445:6084247] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12c744e80>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found advertiser's peer". in file: Optional("<unknown>"), line: 0
,failed - peer identifier should be not nil in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 45
,XCTAssertEqual failed: ("Optional(0)") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 224
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". in file: Optional("<unknown>"), line: 0
,Optional("21282387-57A3-4FE9-935F-4BC9C6019B39")
,nil
,nil
,Optional("65C50A65-0007-4346-BADE-5984BF5AD445")
,Optional("9618A50B-486B-484F-A308-F77086CF9D07")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
,Total number of executed tests:  56
Number of passed tests:  52
Number of failed tests:  4
Number of ignored tests:  0
,Total duration:  18.22323399782181
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
