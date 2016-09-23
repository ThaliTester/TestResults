#### Test 861743792a210c8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0E1E4651-2D8D-4371-B195-E3D331E59AD0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0E1E4651-2D8D-4371-B195-E3D331E59AD0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8DA33FCA-5EFE-413A-BCD5-042906BA0BEB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52401"
,(lldb)     command script import "/tmp/0E1E4651-2D8D-4371-B195-E3D331E59AD0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 14:48:41.908 ThaliTest[3086:6157965] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F1168EF0-C1EE-4C4D-B5DA-60CDD954A37B/Library/Cookies/Cookies.binarycookies
,2016-09-23 14:48:42.026 ThaliTest[3086:6157965] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 14:48:42.028 ThaliTest[3086:6157965] Multi-tasking -> Device: YES, App: YES
,2016-09-23 14:48:42.052 ThaliTest[3086:6157965] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 14:48:43.606 ThaliTest[3086:6157965] Using UIWebView
,2016-09-23 14:48:43.614 ThaliTest[3086:6157965] [CDVTimer][handleopenurl] 0.426948ms
,2016-09-23 14:48:43.624 ThaliTest[3086:6157965] [CDVTimer][intentandnavigationfilter] 9.121001ms
2016-09-23 14:48:43.625 ThaliTest[3086:6157965] [CDVTimer][gesturehandler] 0.371993ms
2016-09-23 14:48:43.625 ThaliTest[3086:6157965] [CDVTimer][TotalPluginStartup] 11.923015ms
,2016-09-23 14:48:49.266 ThaliTest[3086:6157965] Resetting plugins due to page load.
,2016-09-23 14:48:52.675 ThaliTest[3086:6157965] Finished load of: file:///var/mobile/Containers/Bundle/Application/8DA33FCA-5EFE-413A-BCD5-042906BA0BEB/ThaliTest.app/www/index.html
,2016-09-23 14:48:52.980 ThaliTest[3086:6157965] JXcore Cordova plugin initializing
,2016-09-23 14:48:52.981 ThaliTest[3086:6158204] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x154ee7bd0>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("EB7B1212-DB5D-4130-81B0-FA465D811828")
,nil
,nil
,Optional("B7B4F143-7AC0-42FD-948B-2099E3F1923C")
,Optional("F2130C6A-7A6B-4950-83F7-C3706D665941")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 14:49:17.530 ThaliTest[3086:6157965] Getting shared instance of BTmanager
2016-09-23 14:49:17.530 ThaliTest[3086:6157965] Dispatch_once working
,2016-09-23 14:49:17.747 ThaliTest[3086:6157965] Initializing BluetoothHardwareControlManager
2016-09-23 14:49:17.748 ThaliTest[3086:6157965] Getting private API's class
2016-09-23 14:49:17.749 ThaliTest[3086:6157965] Finishing getting private API's class, BluetoothManager
,2016-09-23 14:49:17.749 ThaliTest[3086:6157965] BTM: attaching to BTServer
2016-09-23 14:49:17.750 ThaliTest[3086:6157965] Adding notification in BluetoothHardwareControlManager
,2016-09-23 14:49:17.750 ThaliTest[3086:6157965] Adding notification in BluetoothHardwareControlManager
2016-09-23 14:49:17.751 ThaliTest[3086:6157965] Finishing initializing BluetoothHardwareControlManager
2016-09-23 14:49:17.751 ThaliTest[3086:6157965] ,Finishing dispatch_once working with handle: 0xffeeddcc00010a00 and BTmanager: <BluetoothHardwareControlManager: 0x157478da0>
2016-09-23 14:49:17.751 ThaliTest[3086:6157965] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: ,0x157478da0>
2016-09-23 14:49:17.752 ThaliTest[3086:6157965] Registering observer in BluetoothHardwareControlManager
2016-09-23 14:49:17.752 ThaliTest[3086:6157965] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 14:49:17.787 ThaliTest[3086:6157965] Getting shared instance of BTmanager
2016-09-23 14:49:17.788 ThaliTest[3086:6157965] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x157478da0>
2016-09-23 14:49:17.788 Tha,liTest[3086:6157965] Checking BT private state
,2016-09-23 14:49:17.788 ThaliTest[3086:6157965] Getting shared instance of BTmanager
2016-09-23 14:49:17.788 ThaliTest[3086:6157965] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x157478da0>
2016-09-23 14:49:17.789 Tha,liTest[3086:6157965] Checking BT private state
2016-09-23 14:49:17.789 ThaliTest[3086:6157965] Changing BT private state to On
,2016-09-23 14:49:18.566 ThaliTest[3086:6157965] BTM: local device power state changed
2016-09-23 14:49:18.567 ThaliTest[3086:6157965] BTM: power is now on
2016-09-23 14:49:18.568 ThaliTest[3086:6157965] BluetoothHardwareControlManager notification received.
,2016-09-23 14:49:18.640 ThaliTest[3086:6157965] Getting shared instance of BTmanager
2016-09-23 14:49:18.640 ThaliTest[3086:6157965] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x157478da0>
2016-09-23 14:49:18.640 Tha,liTest[3086:6157965] Checking BT private state
,2016-09-23 14:49:18.641 ThaliTest[3086:6157965] Changing BT private state to Off
,2016-09-23 14:49:23.268 ThaliTest[3086:6157965] BTM: local device power state changed
2016-09-23 14:49:23.268 ThaliTest[3086:6157965] BTM: power is now off
2016-09-23 14:49:23.269 ThaliTest[3086:6157965] BluetoothHardwareControlManager notification received.
,2016-09-23 14:49:23.300 ThaliTest[3086:6157965] Getting shared instance of BTmanager
2016-09-23 14:49:23.300 ThaliTest[3086:6157965] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x157478da0>
2016-09-23 14:49:23.300 Tha,liTest[3086:6157965] Checking BT private state
2016-09-23 14:49:23.301 ThaliTest[3086:6157965] Getting shared instance of BTmanager
2016-09-23 14:49:23.301 ThaliTest[3086:6157965] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x157478da0>
2016-09-23 14:49:23.301 ThaliTest[3086:6157965] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 14:49:23.301 ThaliTest[3086:6157965] Observers:
2016-09-23 14:49:23.301 ThaliTest[3086:6157965] Finishing unregister,ing observer in BluetoothHardwareControlManager
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  21.59465497732162
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
