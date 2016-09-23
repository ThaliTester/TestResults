#### Test 861743796628be0_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/221BEB2C-B49D-44D7-AF1E-5D9071A97473/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/221BEB2C-B49D-44D7-AF1E-5D9071A97473/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743796628be0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5BE7ABA9-44C9-4688-A643-B651B88E42F8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58192"
,(lldb)     command script import "/tmp/221BEB2C-B49D-44D7-AF1E-5D9071A97473/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 12:39:34.135 ThaliTest[3162:5574830] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DAB08267-C53A-4144-849C-AB0D43CE5DBB/Library/Cookies/Cookies.binarycookies
,2016-09-23 12:39:34.456 ThaliTest[3162:5574830] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 12:39:34.457 ThaliTest[3162:5574830] Multi-tasking -> Device: YES, App: YES
,2016-09-23 12:39:34.471 ThaliTest[3162:5574830] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 12:39:36.266 ThaliTest[3162:5574830] Using UIWebView
,2016-09-23 12:39:36.276 ThaliTest[3162:5574830] [CDVTimer][handleopenurl] 0.397027ms
,2016-09-23 12:39:36.284 ThaliTest[3162:5574830] [CDVTimer][intentandnavigationfilter] 7.060945ms
,2016-09-23 12:39:36.285 ThaliTest[3162:5574830] [CDVTimer][gesturehandler] 0.322998ms
,2016-09-23 12:39:36.286 ThaliTest[3162:5574830] [CDVTimer][TotalPluginStartup] 9.822011ms
,2016-09-23 12:39:42.599 ThaliTest[3162:5574830] Resetting plugins due to page load.
,2016-09-23 12:39:45.559 ThaliTest[3162:5574830] Finished load of: file:///var/mobile/Containers/Bundle/Application/5BE7ABA9-44C9-4688-A643-B651B88E42F8/ThaliTest.app/www/index.html
,2016-09-23 12:39:45.772 ThaliTest[3162:5574830] JXcore Cordova plugin initializing
,2016-09-23 12:39:45.773 ThaliTest[3162:5575080] JXcore instance initializing
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
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 12:39:52.426 ThaliTest[3162:5574830] BTM: attaching to BTServer
,XCTAssertNil failed: "Error Domain=com.apple.XCTestErrorDomain Code=0 "(null)"" - Can not turn on Bluetooth hardware - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 520
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Bluetooth is turned on". - <unknown> - 0
,XCTAssertEqual failed: ("Optional("off")") is not equal to ("Optional("on")") - Wrong bluetooth state.Expected: on, actual: Optional("off")) - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 265
XCTAssertEqual failed: ("Optional("off")") is not equal to ("Optional("on")") - Wrong bluetoothLowEnergyState state. Expected: on, actual: Optional("off")) - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 273
,XCTAssertNil failed: "Error Domain=com.apple.XCTestErrorDomain Code=0 "(null)"" - Can not turn off Bluetooth hardware - /Users/thali/Github/ThaliTest/platforms/ios/ThaliTest/Plugins/org.thaliproject.p2p/AppContextTests.swift - 520
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Bluetooth is turned off". - <unknown> - 0
,received session: <ThaliCore.Session: 0x141ac1d80>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
XCTAssertNotEqual failed: ("Optional(1)") is equal to (,"Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugi,ns/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("A575E108-6974-47D2-A4D7-96183834602F")
,nil
,nil
,Optional("4E7017F0-0CA6-4357-AAFF-E0D6C38EF750")
,Optional("3C098823-54F3-4E6B-9270-09ECFCF86C36")
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  47
,Number of failed tests:  9
,Number of ignored tests:  0
,Total duration:  39.00302201509476
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
