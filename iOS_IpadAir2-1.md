#### Test 86174379d95f7ab_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/52F9B08A-3E22-45D4-98C6-03D30A6853BC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/52F9B08A-3E22-45D4-98C6-03D30A6853BC/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379d95f7ab/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D21D6514-F722-4953-BE98-6BD3CE19F346/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61829"
,(lldb)     command script import "/tmp/52F9B08A-3E22-45D4-98C6-03D30A6853BC/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 17:08:37.583 ThaliTest[3064:5465609] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/371BB5DF-DBB6-4CB7-AC9A-E5114F1EAFAB/Library/Cookies/Cookies.binarycookies
,2016-09-22 17:08:37.911 ThaliTest[3064:5465609] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 17:08:37.912 ThaliTest[3064:5465609] Multi-tasking -> Device: YES, App: YES
,2016-09-22 17:08:37.927 ThaliTest[3064:5465609] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 17:08:39.510 ThaliTest[3064:5465609] Using UIWebView
,2016-09-22 17:08:39.518 ThaliTest[3064:5465609] [CDVTimer][handleopenurl] 0.388980ms
,2016-09-22 17:08:39.525 ThaliTest[3064:5465609] [CDVTimer][intentandnavigationfilter] 6.519973ms
,2016-09-22 17:08:39.525 ThaliTest[3064:5465609] [CDVTimer][gesturehandler] 0.304997ms
,2016-09-22 17:08:39.526 ThaliTest[3064:5465609] [CDVTimer][TotalPluginStartup] 8.886993ms
,2016-09-22 17:08:46.070 ThaliTest[3064:5465609] Resetting plugins due to page load.
,2016-09-22 17:08:49.215 ThaliTest[3064:5465609] Finished load of: file:///var/mobile/Containers/Bundle/Application/D21D6514-F722-4953-BE98-6BD3CE19F346/ThaliTest.app/www/index.html
,2016-09-22 17:08:49.426 ThaliTest[3064:5465609] JXcore Cordova plugin initializing
,2016-09-22 17:08:49.427 ThaliTest[3064:5465849] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12e983800>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("B366C14C-F214-4B15-B475-642B1B9B7398")
,nil
,nil
,Optional("A3A2644E-741C-46F2-A1C9-0A92AC9DA44B")
,Optional("A369C168-2A76-4706-AF74-79DB1B7F9B02")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 17:09:16.321 ThaliTest[3064:5465609] BTM: attaching to BTServer
,2016-09-22 17:09:17.117 ThaliTest[3064:5465609] BTM: local device power state changed
2016-09-22 17:09:17.118 ThaliTest[3064:5465609] BTM: power is now on
,2016-09-22 17:09:21.779 ThaliTest[3064:5465609] BTM: local device power state changed
2016-09-22 17:09:21.779 ThaliTest[3064:5465609] BTM: power is now off
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  25.83439499139786
Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
