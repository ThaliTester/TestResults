#### Test 8617437964e1086_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F1554FA0-5EB8-4A9E-BDB6-529B98DB71D3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/F1554FA0-5EB8-4A9E-BDB6-529B98DB71D3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/458F2D97-4E00-49B3-B2F5-60ADE8875681/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53766"
,(lldb)     command script import "/tmp/F1554FA0-5EB8-4A9E-BDB6-529B98DB71D3/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 06:04:41.694 ThaliTest[1503:1793534] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/725F0480-5A9F-4903-A514-EFEF1516FB5F/Library/Cookies/Cookies.binarycookies
,2016-09-23 06:04:41.733 ThaliTest[1503:1793534] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 06:04:41.734 ThaliTest[1503:1793534] Multi-tasking -> Device: YES, App: YES
,2016-09-23 06:04:41.746 ThaliTest[1503:1793534] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 06:04:42.079 ThaliTest[1503:1793534] Using UIWebView
,2016-09-23 06:04:42.083 ThaliTest[1503:1793534] [CDVTimer][handleopenurl] 0.225008ms
,2016-09-23 06:04:42.088 ThaliTest[1503:1793534] [CDVTimer][intentandnavigationfilter] 4.630029ms
2016-09-23 06:04:42.089 ThaliTest[1503:1793534] [CDVTimer][gesturehandler] 0.190020ms
2016-09-23 06:04:42.089 ThaliTest[1503:1793534] [CDVTimer][TotalPluginStartup] 6.157994ms
,2016-09-23 06:04:47.977 ThaliTest[1503:1793534] Resetting plugins due to page load.
,2016-09-23 06:04:48.410 ThaliTest[1503:1793534] Finished load of: file:///var/containers/Bundle/Application/458F2D97-4E00-49B3-B2F5-60ADE8875681/ThaliTest.app/www/index.html
,2016-09-23 06:04:48.745 ThaliTest[1503:1793534] JXcore Cordova plugin initializing
2016-09-23 06:04:48.746 ThaliTest[1503:1793708] JXcore instance initializing
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
,2016-09-23 06:04:55.894 ThaliTest[1503:1793534] Getting shared instance of BTmanager
2016-09-23 06:04:55.894 ThaliTest[1503:1793534] Dispatch_once working
,2016-09-23 06:04:56.003 ThaliTest[1503:1793534] Initializing BluetoothHardwareControlManager
2016-09-23 06:04:56.003 ThaliTest[1503:1793534] Getting private API's class
2016-09-23 06:04:56.003 ThaliTest[1503:1793534] Finishing getting private API's class, BluetoothManager
2016-09-23 06:04:56.003 ThaliTest[1503:1793534] BTM: attaching to BTServer
2016-09-23 06:04:56.003 ThaliTest[1503:1793534] Adding notification in BluetoothHardwareControlManager
2016-09-23 06:04:56.004 ThaliTest[1503:1793534] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 06:04:56.004 ThaliTest[1503:1793534] Finishing initializing BluetoothHardwareControlManager
2016-09-23 06:04:56.004 ThaliTest[1503:1793534] Finishing dispatch_once working with handle: 0xffeeddcc00,00d400 and BTmanager: <BluetoothHardwareControlManager: 0x136aaf5f0>
2016-09-23 06:04:56.004 ThaliTest[1503:1793534] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x136aaf5f0>
,2016-09-23 06:04:56.005 ThaliTest[1503:1793534] Registering observer in BluetoothHardwareControlManager
2016-09-23 06:04:56.005 ThaliTest[1503:1793534] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 06:04:56.017 ThaliTest[1503:1793534] Getting shared instance of BTmanager
2016-09-23 06:04:56.017 ThaliTest[1503:1793534] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x136aaf5f0>
2016-09-23 06:04:56.018 Tha,liTest[1503:1793534] Checking BT private state
2016-09-23 06:04:56.018 ThaliTest[1503:1793534] Getting shared instance of BTmanager
2016-09-23 06:04:56.018 ThaliTest[1503:1793534] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x136aaf5f0>
2016-09-23 06:04:56.018 ThaliTest[1503:1793534] Checking BT private state
,2016-09-23 06:04:56.018 ThaliTest[1503:1793534] Changing BT private state to On
,2016-09-23 06:04:56.775 ThaliTest[1503:1793534] BTM: local device power state changed
2016-09-23 06:04:56.788 ThaliTest[1503:1793534] BTM: power is now on
2016-09-23 06:04:56.789 ThaliTest[1503:1793534] BluetoothHardwareControlManager notification receiv,ed.
,2016-09-23 06:04:56.816 ThaliTest[1503:1793534] Getting shared instance of BTmanager
2016-09-23 06:04:56.816 ThaliTest[1503:1793534] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x136aaf5f0>
2016-09-23 06:04:56.817 ThaliTest[1503:1793534] Checking BT private state
2016-09-23 06:04:56.817 ThaliTest[1503:1793534] Changing BT private state to Off
,2016-09-23 06:05:01.492 ThaliTest[1503:1793534] BTM: local device power state changed
2016-09-23 06:05:01.493 ThaliTest[1503:1793534] BTM: power is now off
2016-09-23 06:05:01.493 ThaliTest[1503:1793534] BluetoothHardwareControlManager notification received.
,2016-09-23 06:05:01.517 ThaliTest[1503:1793534] Getting shared instance of BTmanager
2016-09-23 06:05:01.517 ThaliTest[1503:1793534] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x136aaf5f0>
2016-09-23 06:05:01.517 Tha,liTest[1503:1793534] Checking BT private state
2016-09-23 06:05:01.517 ThaliTest[1503:1793534] Getting shared instance of BTmanager
2016-09-23 06:05:01.517 ThaliTest[1503:1793534] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x136aaf5f0>
2016-09-23 06:05:01.518 ThaliTest[1503:1793534] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 06:05:01.518 ThaliTest[1503:1793534] Observers:
2016-09-23 06:05:01.518 ThaliTest[1503:1793534] Finishing unregistering observer in BluetoothHardwareControlManager
,received session: <ThaliCore.Session: 0x134e93880>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("399F3B3C-C843-4A31-B76A-C888F374926B")
nil
,nil
,Optional("DC60CA33-B78A-49CF-B7D4-9A0808A3FC49")
,Optional("BD8317F0-36A6-4E96-A12C-A4FCB9AE46F7")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  53
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  20.19355899095535
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
