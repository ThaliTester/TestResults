#### Test 861743792a210c8_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9E22289B-E48C-45D0-A22E-5222826F80D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9E22289B-E48C-45D0-A22E-5222826F80D0/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/84674B6A-0D9E-4AA7-914F-7DBAFE9A0DFB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52348"
,(lldb)     command script import "/tmp/9E22289B-E48C-45D0-A22E-5222826F80D0/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 14:48:37.578 ThaliTest[1330:1887273] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/52B09FA9-8971-4262-AAEC-997515600685/Library/Cookies/Cookies.binarycookies
,2016-09-23 14:48:37.615 ThaliTest[1330:1887273] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 14:48:37.616 ThaliTest[1330:1887273] Multi-tasking -> Device: YES, App: YES
,2016-09-23 14:48:37.626 ThaliTest[1330:1887273] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 14:48:37.993 ThaliTest[1330:1887273] Using UIWebView
,2016-09-23 14:48:37.999 ThaliTest[1330:1887273] [CDVTimer][handleopenurl] 0.239015ms
,2016-09-23 14:48:38.004 ThaliTest[1330:1887273] [CDVTimer][intentandnavigationfilter] 4.694998ms
2016-09-23 14:48:38.005 ThaliTest[1330:1887273] [CDVTimer][gesturehandler] 0.200987ms
2016-09-23 14:48:38.005 ThaliTest[1330:1887273] [CDVTimer][TotalPluginStartup] 6.281972ms
,2016-09-23 14:48:43.339 ThaliTest[1330:1887273] Resetting plugins due to page load.
,2016-09-23 14:48:43.697 ThaliTest[1330:1887273] Finished load of: file:///var/containers/Bundle/Application/84674B6A-0D9E-4AA7-914F-7DBAFE9A0DFB/ThaliTest.app/www/index.html
,2016-09-23 14:48:44.027 ThaliTest[1330:1887273] JXcore Cordova plugin initializing
2016-09-23 14:48:44.028 ThaliTest[1330:1887441] JXcore instance initializing
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
,2016-09-23 14:48:51.410 ThaliTest[1330:1887273] Getting shared instance of BTmanager
2016-09-23 14:48:51.410 ThaliTest[1330:1887273] Dispatch_once working
,2016-09-23 14:48:51.509 ThaliTest[1330:1887273] Initializing BluetoothHardwareControlManager
2016-09-23 14:48:51.509 ThaliTest[1330:1887273] Getting private API's class
2016-09-23 14:48:51.509 ThaliTest[1330:1887273] Finishing getting private API's class, BluetoothManager
2016-09-23 14:48:51.509 ThaliTest[1330:1887273] BTM: attaching to BTServer
2016-09-23 14:48:51.509 ThaliTest[1330:1887273] Adding notification in BluetoothHardwareControlManager
2016-09-23 14:48:51.510 ThaliTest[1330:1887273] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 14:48:51.510 ThaliTest[1330:1887273] Finishing initializing BluetoothHardwareControlManager
,2016-09-23 14:48:51.510 ThaliTest[1330:1887273] Finishing dispatch_once working with handle: 0xffeeddcc0000d400 and BTmanager: <BluetoothHardwareControlManager: 0x13e557c10>
2016-09-23 14:48:51.510 ThaliTest[1330:1887273] Finishing getting shared instance, of BTmanager <BluetoothHardwareControlManager: 0x13e557c10>
2016-09-23 14:48:51.511 ThaliTest[1330:1887273] Registering observer in BluetoothHardwareControlManager
2016-09-23 14:48:51.511 ThaliTest[1330:1887273] Finishing registering observer in Bluetoo,thHardwareControlManager
,2016-09-23 14:48:51.523 ThaliTest[1330:1887273] Getting shared instance of BTmanager
2016-09-23 14:48:51.523 ThaliTest[1330:1887273] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e557c10>
2016-09-23 14:48:51.523 Tha,liTest[1330:1887273] Checking BT private state
,2016-09-23 14:48:51.523 ThaliTest[1330:1887273] Getting shared instance of BTmanager
2016-09-23 14:48:51.523 ThaliTest[1330:1887273] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e557c10>
,2016-09-23 14:48:51.524 ThaliTest[1330:1887273] Checking BT private state
2016-09-23 14:48:51.524 ThaliTest[1330:1887273] Changing BT private state to On
,2016-09-23 14:48:52.267 ThaliTest[1330:1887273] BTM: local device power state changed
2016-09-23 14:48:52.279 ThaliTest[1330:1887273] BTM: power is now on
2016-09-23 14:48:52.279 ThaliTest[1330:1887273] BluetoothHardwareControlManager notification received.
,2016-09-23 14:48:52.317 ThaliTest[1330:1887273] Getting shared instance of BTmanager
2016-09-23 14:48:52.317 ThaliTest[1330:1887273] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e557c10>
2016-09-23 14:48:52.317 Tha,liTest[1330:1887273] Checking BT private state
2016-09-23 14:48:52.318 ThaliTest[1330:1887273] Changing BT private state to Off
,2016-09-23 14:48:57.015 ThaliTest[1330:1887273] BTM: local device power state changed
,2016-09-23 14:48:57.015 ThaliTest[1330:1887273] BTM: power is now off
2016-09-23 14:48:57.019 ThaliTest[1330:1887273] BluetoothHardwareControlManager notification received.
,2016-09-23 14:48:57.038 ThaliTest[1330:1887273] Getting shared instance of BTmanager
2016-09-23 14:48:57.038 ThaliTest[1330:1887273] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e557c10>
2016-09-23 14:48:57.038 Tha,liTest[1330:1887273] Checking BT private state
2016-09-23 14:48:57.039 ThaliTest[1330:1887273] Getting shared instance of BTmanager
2016-09-23 14:48:57.039 ThaliTest[1330:1887273] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x13e557c10>
2016-09-23 14:48:57.039 ThaliTest[1330:1887273] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 14:48:57.039 ThaliTest[1330:1887273] Observers:
2016-09-23 14:48:57.040 ThaliTest[1330:1887273] Finishing unregister,ing observer in BluetoothHardwareControlManager
,received session: <ThaliCore.Session: 0x13ebc48e0>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("9A504A08-4C91-4C56-80E6-F9369158A0DD")
nil
,nil
,Optional("B05AEEA0-E043-4D24-8717-E32658BB7ECB")
,Optional("AA270163-071A-4BD5-AFE9-CAF96229510E")
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  53
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  21.55728495121002
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
