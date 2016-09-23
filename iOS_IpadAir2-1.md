#### Test 8617437964e1086_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7559895C-9069-437F-88F8-ABBAFEE40231/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7559895C-9069-437F-88F8-ABBAFEE40231/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1109E00E-E357-41B1-8199-59255DBEECBF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53776"
,(lldb)     command script import "/tmp/7559895C-9069-437F-88F8-ABBAFEE40231/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 15:04:48.971 ThaliTest[3205:5592833] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DB83865E-6400-4D1E-B0F4-D0D5CF067F2A/Library/Cookies/Cookies.binarycookies
,2016-09-23 15:04:49.309 ThaliTest[3205:5592833] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 15:04:49.311 ThaliTest[3205:5592833] Multi-tasking -> Device: YES, App: YES
,2016-09-23 15:04:49.329 ThaliTest[3205:5592833] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 15:04:51.256 ThaliTest[3205:5592833] Using UIWebView
,2016-09-23 15:04:51.263 ThaliTest[3205:5592833] [CDVTimer][handleopenurl] 0.374019ms
,2016-09-23 15:04:51.270 ThaliTest[3205:5592833] [CDVTimer][intentandnavigationfilter] 6.415009ms
,2016-09-23 15:04:51.271 ThaliTest[3205:5592833] [CDVTimer][gesturehandler] 0.299990ms
,2016-09-23 15:04:51.271 ThaliTest[3205:5592833] [CDVTimer][TotalPluginStartup] 8.844018ms
,2016-09-23 15:04:57.722 ThaliTest[3205:5592833] Resetting plugins due to page load.
,2016-09-23 15:05:00.821 ThaliTest[3205:5592833] Finished load of: file:///var/mobile/Containers/Bundle/Application/1109E00E-E357-41B1-8199-59255DBEECBF/ThaliTest.app/www/index.html
,2016-09-23 15:05:00.962 ThaliTest[3205:5592833] JXcore Cordova plugin initializing
,2016-09-23 15:05:00.963 ThaliTest[3205:5593087] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 15:05:07.438 ThaliTest[3205:5592833] Getting shared instance of BTmanager
2016-09-23 15:05:07.438 ThaliTest[3205:5592833] Dispatch_once working
,2016-09-23 15:05:07.561 ThaliTest[3205:5592833] Initializing BluetoothHardwareControlManager
2016-09-23 15:05:07.561 ThaliTest[3205:5592833] Getting private API's class
,2016-09-23 15:05:07.561 ThaliTest[3205:5592833] Finishing getting private API's class BluetoothManager
2016-09-23 15:05:07.561 ThaliTest[3205:5592833] BTM: attaching to BTServer
2016-09-23 15:05:07.562 ThaliTest[3205:5592833] Adding notification in Bluet,oothHardwareControlManager
2016-09-23 15:05:07.562 ThaliTest[3205:5592833] Adding notification in BluetoothHardwareControlManager
2016-09-23 15:05:07.562 ThaliTest[3205:5592833] Finishing initializing BluetoothHardwareControlManager
2016-09-23 15:05:07.,562 ThaliTest[3205:5592833] Finishing dispatch_once working with handle: 0xffeeddcc00010800 and BTmanager: <BluetoothHardwareControlManager: 0x14e70b640>
2016-09-23 15:05:07.562 ThaliTest[3205:5592833] Finishing getting shared instance of BTmanager <Bluet,oothHardwareControlManager: 0x14e70b640>
2016-09-23 15:05:07.562 ThaliTest[3205:5592833] Registering observer in BluetoothHardwareControlManager
2016-09-23 15:05:07.562 ThaliTest[3205:5592833] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 15:05:07.569 ThaliTest[3205:5592833] Getting shared instance of BTmanager
2016-09-23 15:05:07.569 ThaliTest[3205:5592833] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14e70b640>
2016-09-23 15:05:07.569 ThaliTest[3205:5592833] Checking BT private state
,2016-09-23 15:05:07.569 ThaliTest[3205:5592833] Getting shared instance of BTmanager
2016-09-23 15:05:07.569 ThaliTest[3205:5592833] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14e70b640>
2016-09-23 15:05:07.569 ThaliTest[3205:5592833] Checking BT private state
2016-09-23 15:05:07.570 ThaliTest[3205:5592833] Changing BT private state to On
,2016-09-23 15:05:08.368 ThaliTest[3205:5592833] BTM: local device power state changed
2016-09-23 15:05:08.368 ThaliTest[3205:5592833] BTM: power is now on
2016-09-23 15:05:08.369 ThaliTest[3205:5592833] BluetoothHardwareControlManager notification received.
,2016-09-23 15:05:08.415 ThaliTest[3205:5592833] Getting shared instance of BTmanager
2016-09-23 15:05:08.415 ThaliTest[3205:5592833] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14e70b640>
2016-09-23 15:05:08.415 ThaliTest[3205:5592833] Checking BT private state
2016-09-23 15:05:08.416 ThaliTest[3205:5592833] Changing BT private state to Off
,2016-09-23 15:05:13.055 ThaliTest[3205:5592833] BTM: local device power state changed
2016-09-23 15:05:13.055 ThaliTest[3205:5592833] BTM: power is now off
,2016-09-23 15:05:13.056 ThaliTest[3205:5592833] BluetoothHardwareControlManager notification received.
,2016-09-23 15:05:13.091 ThaliTest[3205:5592833] Getting shared instance of BTmanager
2016-09-23 15:05:13.091 ThaliTest[3205:5592833] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14e70b640>
2016-09-23 15:05:13.092 Tha,liTest[3205:5592833] Checking BT private state
2016-09-23 15:05:13.092 ThaliTest[3205:5592833] Getting shared instance of BTmanager
2016-09-23 15:05:13.092 ThaliTest[3205:5592833] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x14e70b640>
2016-09-23 15:05:13.092 ThaliTest[3205:5592833] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 15:05:13.092 ThaliTest[3205:5592833] Observers:
2016-09-23 15:05:13.093 ThaliTest[3205:5592833] Finishing unregistering observer in BluetoothHardwareControlManager
,received session: <ThaliCore.Session: 0x14e788300>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("AC967C49-435C-4450-9CE3-630AA963289D")
,nil
,nil
,Optional("E9107CD8-D7F6-4BA4-8F67-781097D043F9")
,Optional("0C35AC3E-07AD-4590-A7E6-4D432EADDAAE")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  53
Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  25.00701797008514
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
