#### Test 861743792a210c8_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/40875140-3D2C-4F26-8ECE-D73C2AD96539/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/40875140-3D2C-4F26-8ECE-D73C2AD96539/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/57C853FA-8873-42E9-B08E-AAA703B790B4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52379"
,(lldb)     command script import "/tmp/40875140-3D2C-4F26-8ECE-D73C2AD96539/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 05:48:41.047 ThaliTest[1496:1791387] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/51E08DB3-130A-4384-9FD6-CB3F296315B0/Library/Cookies/Cookies.binarycookies
,2016-09-23 05:48:41.086 ThaliTest[1496:1791387] Apache Cordova native platform version 4.2.1 is starting.
2016-09-23 05:48:41.087 ThaliTest[1496:1791387] Multi-tasking -> Device: YES, App: YES
,2016-09-23 05:48:41.102 ThaliTest[1496:1791387] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 05:48:41.468 ThaliTest[1496:1791387] Using UIWebView
,2016-09-23 05:48:41.474 ThaliTest[1496:1791387] [CDVTimer][handleopenurl] 0.259995ms
,2016-09-23 05:48:41.479 ThaliTest[1496:1791387] [CDVTimer][intentandnavigationfilter] 4.604995ms
2016-09-23 05:48:41.480 ThaliTest[1496:1791387] [CDVTimer][gesturehandler] 0.199020ms
2016-09-23 05:48:41.480 ThaliTest[1496:1791387] [CDVTimer][TotalPluginStartup] 6.187022ms
,2016-09-23 05:48:46.840 ThaliTest[1496:1791387] Resetting plugins due to page load.
,2016-09-23 05:48:47.282 ThaliTest[1496:1791387] Finished load of: file:///var/containers/Bundle/Application/57C853FA-8873-42E9-B08E-AAA703B790B4/ThaliTest.app/www/index.html
,2016-09-23 05:48:47.615 ThaliTest[1496:1791387] JXcore Cordova plugin initializing
,2016-09-23 05:48:47.616 ThaliTest[1496:1791571] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13faa7590>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("E8553D14-0099-4AB3-AA86-469E87B0A152")
nil
,nil
,Optional("5FCC2C4E-E933-467F-B812-8C390BDE5D68")
,Optional("22381456-DE29-4C9D-83BD-BE217F12870C")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 05:49:09.611 ThaliTest[1496:1791387] Getting shared instance of BTmanager
2016-09-23 05:49:09.611 ThaliTest[1496:1791387] Dispatch_once working
,2016-09-23 05:49:09.813 ThaliTest[1496:1791387] Initializing BluetoothHardwareControlManager
2016-09-23 05:49:09.814 ThaliTest[1496:1791387] Getting private API's class
2016-09-23 05:49:09.814 ThaliTest[1496:1791387] Finishing getting private API's class, BluetoothManager
2016-09-23 05:49:09.814 ThaliTest[1496:1791387] BTM: attaching to BTServer
2016-09-23 05:49:09.814 ThaliTest[1496:1791387] Adding notification in BluetoothHardwareControlManager
2016-09-23 05:49:09.815 ThaliTest[1496:1791387] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 05:49:09.815 ThaliTest[1496:1791387] Finishing initializing BluetoothHardwareControlManager
2016-09-23 05:49:09.815 ThaliTest[1496:1791387] Finishing dispatch_once working with handle: 0xffeeddcc00,00d400 and BTmanager: <BluetoothHardwareControlManager: 0x14032b080>
2016-09-23 05:49:09.817 ThaliTest[1496:1791387] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14032b080>
2016-09-23 05:49:09.818 ThaliTest[1496:1791,387] Registering observer in BluetoothHardwareControlManager
2016-09-23 05:49:09.818 ThaliTest[1496:1791387] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 05:49:09.843 ThaliTest[1496:1791387] Getting shared instance of BTmanager
2016-09-23 05:49:09.843 ThaliTest[1496:1791387] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14032b080>
2016-09-23 05:49:09.843 ThaliTest[1496:1791387] Checking BT private state
,2016-09-23 05:49:09.844 ThaliTest[1496:1791387] Getting shared instance of BTmanager
2016-09-23 05:49:09.844 ThaliTest[1496:1791387] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14032b080>
,2016-09-23 05:49:09.844 ThaliTest[1496:1791387] Checking BT private state
,2016-09-23 05:49:09.845 ThaliTest[1496:1791387] Changing BT private state to On
,2016-09-23 05:49:10.610 ThaliTest[1496:1791387] BTM: local device power state changed
2016-09-23 05:49:10.613 ThaliTest[1496:1791387] BTM: power is now on
2016-09-23 05:49:10.614 ThaliTest[1496:1791387] BluetoothHardwareControlManager notification received.
,2016-09-23 05:49:10.658 ThaliTest[1496:1791387] Getting shared instance of BTmanager
2016-09-23 05:49:10.658 ThaliTest[1496:1791387] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14032b080>
2016-09-23 05:49:10.658 Tha,liTest[1496:1791387] Checking BT private state
2016-09-23 05:49:10.659 ThaliTest[1496:1791387] Changing BT private state to Off
,2016-09-23 05:49:15.316 ThaliTest[1496:1791387] BTM: local device power state changed
2016-09-23 05:49:15.316 ThaliTest[1496:1791387] BTM: power is now off
2016-09-23 05:49:15.317 ThaliTest[1496:1791387] BluetoothHardwareControlManager notification received.
,2016-09-23 05:49:15.343 ThaliTest[1496:1791387] Getting shared instance of BTmanager
2016-09-23 05:49:15.344 ThaliTest[1496:1791387] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14032b080>
2016-09-23 05:49:15.344 Tha,liTest[1496:1791387] Checking BT private state
2016-09-23 05:49:15.344 ThaliTest[1496:1791387] Getting shared instance of BTmanager
2016-09-23 05:49:15.344 ThaliTest[1496:1791387] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x14032b080>
2016-09-23 05:49:15.345 ThaliTest[1496:1791387] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 05:49:15.345 ThaliTest[1496:1791387] Observers:
2016-09-23 05:49:15.345 ThaliTest[1496:1791387] Finishing unregister,ing observer in BluetoothHardwareControlManager
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  53
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  20.60059398412704
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
```
