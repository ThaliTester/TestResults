#### Test 8617437964e1086_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B2B40E92-6A46-49EA-880F-95C5A49EE409/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B2B40E92-6A46-49EA-880F-95C5A49EE409/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/634875BC-46DD-4337-BF85-4D1E954A0267/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53786"
,(lldb)     command script import "/tmp/B2B40E92-6A46-49EA-880F-95C5A49EE409/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 15:04:44.956 ThaliTest[3093:6161690] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2459536A-ECCE-4A58-817C-151B1F6E2FF9/Library/Cookies/Cookies.binarycookies
,2016-09-23 15:04:45.071 ThaliTest[3093:6161690] Apache Cordova native platform version 4.2.1 is starting.
2016-09-23 15:04:45.072 ThaliTest[3093:6161690] Multi-tasking -> Device: YES, App: YES
,2016-09-23 15:04:45.096 ThaliTest[3093:6161690] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 15:04:46.668 ThaliTest[3093:6161690] Using UIWebView
,2016-09-23 15:04:46.677 ThaliTest[3093:6161690] [CDVTimer][handleopenurl] 0.758052ms
,2016-09-23 15:04:46.685 ThaliTest[3093:6161690] [CDVTimer][intentandnavigationfilter] 8.190036ms
2016-09-23 15:04:46.686 ThaliTest[3093:6161690] [CDVTimer][gesturehandler] 0.386000ms
2016-09-23 15:04:46.687 ThaliTest[3093:6161690] [CDVTimer][TotalPluginStartup] 11.285007ms
,2016-09-23 15:04:52.605 ThaliTest[3093:6161690] Resetting plugins due to page load.
,2016-09-23 15:04:56.105 ThaliTest[3093:6161690] Finished load of: file:///var/mobile/Containers/Bundle/Application/634875BC-46DD-4337-BF85-4D1E954A0267/ThaliTest.app/www/index.html
,2016-09-23 15:04:56.406 ThaliTest[3093:6161690] JXcore Cordova plugin initializing
,2016-09-23 15:04:56.407 ThaliTest[3093:6161938] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12ef1a700>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("EC8A54D5-3523-470E-A884-994149E60D3C")
,nil
,nil
,Optional("E9715A05-4B55-40B3-A4E7-F2BFB36515BD")
,Optional("D221D03F-49FB-49E4-941C-398F8594C52E")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 15:05:20.157 ThaliTest[3093:6161690] Getting shared instance of BTmanager
,2016-09-23 15:05:20.157 ThaliTest[3093:6161690] Dispatch_once working
,2016-09-23 15:05:20.378 ThaliTest[3093:6161690] Initializing BluetoothHardwareControlManager
2016-09-23 15:05:20.379 ThaliTest[3093:6161690] Getting private API's class
2016-09-23 15:05:20.379 ThaliTest[3093:6161690] Finishing getting private API's class, BluetoothManager
2016-09-23 15:05:20.379 ThaliTest[3093:6161690] BTM: attaching to BTServer
2016-09-23 15:05:20.379 ThaliTest[3093:6161690] Adding notification in BluetoothHardwareControlManager
2016-09-23 15:05:20.380 ThaliTest[3093:6161690] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 15:05:20.380 ThaliTest[3093:6161690] Finishing initializing BluetoothHardwareControlManager
2016-09-23 15:05:20.380 ThaliTest[3093:6161690] Finishing dispatch_once working with handle: 0xffeeddcc00,010a00 and BTmanager: <BluetoothHardwareControlManager: 0x12e35a030>
2016-09-23 15:05:20.380 ThaliTest[3093:6161690] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12e35a030>
2016-09-23 15:05:20.380 ThaliTest[3093:6161,690] Registering observer in BluetoothHardwareControlManager
2016-09-23 15:05:20.380 ThaliTest[3093:6161690] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 15:05:20.403 ThaliTest[3093:6161690] Getting shared instance of BTmanager
2016-09-23 15:05:20.403 ThaliTest[3093:6161690] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12e35a030>
2016-09-23 15:05:20.403 Tha,liTest[3093:6161690] Checking BT private state
2016-09-23 15:05:20.404 ThaliTest[3093:6161690] Getting shared instance of BTmanager
2016-09-23 15:05:20.404 ThaliTest[3093:6161690] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x12e35a030>
2016-09-23 15:05:20.404 ThaliTest[3093:6161690] Checking BT private state
2016-09-23 15:05:20.404 ThaliTest[3093:6161690] Changing BT private state to On
,2016-09-23 15:05:21.065 ThaliTest[3093:6161690] BTM: local device power state changed
2016-09-23 15:05:21.065 ThaliTest[3093:6161690] BTM: power is now on
2016-09-23 15:05:21.066 ThaliTest[3093:6161690] BluetoothHardwareControlManager notification receiv,ed.
,2016-09-23 15:05:21.154 ThaliTest[3093:6161690] Getting shared instance of BTmanager
2016-09-23 15:05:21.154 ThaliTest[3093:6161690] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12e35a030>
2016-09-23 15:05:21.154 ThaliTest[3093:6161690] Checking BT private state
2016-09-23 15:05:21.155 ThaliTest[3093:6161690] Changing BT private state to Off
,2016-09-23 15:05:25.781 ThaliTest[3093:6161690] BTM: local device power state changed
2016-09-23 15:05:25.781 ThaliTest[3093:6161690] BTM: power is now off
2016-09-23 15:05:25.782 ThaliTest[3093:6161690] BluetoothHardwareControlManager notification received.
,2016-09-23 15:05:25.807 ThaliTest[3093:6161690] Getting shared instance of BTmanager
2016-09-23 15:05:25.808 ThaliTest[3093:6161690] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12e35a030>
2016-09-23 15:05:25.808 Tha,liTest[3093:6161690] Checking BT private state
2016-09-23 15:05:25.808 ThaliTest[3093:6161690] Getting shared instance of BTmanager
2016-09-23 15:05:25.808 ThaliTest[3093:6161690] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x12e35a030>
2016-09-23 15:05:25.809 ThaliTest[3093:6161690] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 15:05:25.809 ThaliTest[3093:6161690] Observers:
2016-09-23 15:05:25.809 ThaliTest[3093:6161690] Finishing unregister,ing observer in BluetoothHardwareControlManager
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  20.64655900001526
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
