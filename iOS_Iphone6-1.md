#### Test 8617437964e1086_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/9AD4B085-60B8-40DF-AEA1-A635110F9BB9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/9AD4B085-60B8-40DF-AEA1-A635110F9BB9/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8617437964e1086/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/33511911-70EA-4E6D-91BA-A80B1814AB4F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53748"
,(lldb)     command script import "/tmp/9AD4B085-60B8-40DF-AEA1-A635110F9BB9/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 15:04:41.182 ThaliTest[1337:1890008] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/56965C3C-478E-46F0-895C-BE3C2F353552/Library/Cookies/Cookies.binarycookies
,2016-09-23 15:04:41.256 ThaliTest[1337:1890008] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 15:04:41.257 ThaliTest[1337:1890008] Multi-tasking -> Device: YES, App: YES
,2016-09-23 15:04:41.276 ThaliTest[1337:1890008] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 15:04:41.725 ThaliTest[1337:1890008] Using UIWebView
,2016-09-23 15:04:41.732 ThaliTest[1337:1890008] [CDVTimer][handleopenurl] 0.351012ms
,2016-09-23 15:04:41.740 ThaliTest[1337:1890008] [CDVTimer][intentandnavigationfilter] 6.924987ms
2016-09-23 15:04:41.740 ThaliTest[1337:1890008] [CDVTimer][gesturehandler] 0.290990ms
2016-09-23 15:04:41.741 ThaliTest[1337:1890008] [CDVTimer][TotalPluginStartup] 9.079993ms
,2016-09-23 15:04:47.105 ThaliTest[1337:1890008] Resetting plugins due to page load.
,2016-09-23 15:04:47.450 ThaliTest[1337:1890008] Finished load of: file:///var/containers/Bundle/Application/33511911-70EA-4E6D-91BA-A80B1814AB4F/ThaliTest.app/www/index.html
,2016-09-23 15:04:47.780 ThaliTest[1337:1890008] JXcore Cordova plugin initializing
2016-09-23 15:04:47.781 ThaliTest[1337:1890167] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
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
,2016-09-23 15:04:55.116 ThaliTest[1337:1890008] Getting shared instance of BTmanager
2016-09-23 15:04:55.116 ThaliTest[1337:1890008] Dispatch_once working
,2016-09-23 15:04:55.218 ThaliTest[1337:1890008] Initializing BluetoothHardwareControlManager
2016-09-23 15:04:55.218 ThaliTest[1337:1890008] Getting private API's class
2016-09-23 15:04:55.218 ThaliTest[1337:1890008] Finishing getting private API's class, BluetoothManager
2016-09-23 15:04:55.219 ThaliTest[1337:1890008] BTM: attaching to BTServer
2016-09-23 15:04:55.219 ThaliTest[1337:1890008] Adding notification in BluetoothHardwareControlManager
2016-09-23 15:04:55.219 ThaliTest[1337:1890008] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 15:04:55.219 ThaliTest[1337:1890008] Finishing initializing BluetoothHardwareControlManager
2016-09-23 15:04:55.219 ThaliTest[1337:1890008] Finishing dispatch_once working with handle: 0xffeeddcc00,00d400 and BTmanager: <BluetoothHardwareControlManager: 0x13e5cfeb0>
2016-09-23 15:04:55.220 ThaliTest[1337:1890008] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e5cfeb0>
,2016-09-23 15:04:55.220 ThaliTest[1337:1890008] Registering observer in BluetoothHardwareControlManager
2016-09-23 15:04:55.220 ThaliTest[1337:1890008] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 15:04:55.230 ThaliTest[1337:1890008] Getting shared instance of BTmanager
2016-09-23 15:04:55.231 ThaliTest[1337:1890008] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e5cfeb0>
2016-09-23 15:04:55.231 ThaliTest[1337:1890008] Checking BT private state
,2016-09-23 15:04:55.231 ThaliTest[1337:1890008] Getting shared instance of BTmanager
2016-09-23 15:04:55.231 ThaliTest[1337:1890008] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e5cfeb0>
2016-09-23 15:04:55.231 Tha,liTest[1337:1890008] Checking BT private state
,2016-09-23 15:04:55.232 ThaliTest[1337:1890008] Changing BT private state to On
,2016-09-23 15:04:55.957 ThaliTest[1337:1890008] BTM: local device power state changed
2016-09-23 15:04:55.958 ThaliTest[1337:1890008] BTM: power is now on
2016-09-23 15:04:55.975 ThaliTest[1337:1890008] BluetoothHardwareControlManager notification received.
,2016-09-23 15:04:56.013 ThaliTest[1337:1890008] Getting shared instance of BTmanager
2016-09-23 15:04:56.013 ThaliTest[1337:1890008] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e5cfeb0>
2016-09-23 15:04:56.013 Tha,liTest[1337:1890008] Checking BT private state
2016-09-23 15:04:56.014 ThaliTest[1337:1890008] Changing BT private state to Off
,2016-09-23 15:05:00.708 ThaliTest[1337:1890008] BTM: local device power state changed
2016-09-23 15:05:00.709 ThaliTest[1337:1890008] BTM: power is now off
2016-09-23 15:05:00.713 ThaliTest[1337:1890008] BluetoothHardwareControlManager notification received.
,2016-09-23 15:05:00.734 ThaliTest[1337:1890008] Getting shared instance of BTmanager
2016-09-23 15:05:00.735 ThaliTest[1337:1890008] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13e5cfeb0>
2016-09-23 15:05:00.735 Tha,liTest[1337:1890008] Checking BT private state
2016-09-23 15:05:00.735 ThaliTest[1337:1890008] Getting shared instance of BTmanager
2016-09-23 15:05:00.735 ThaliTest[1337:1890008] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x13e5cfeb0>
2016-09-23 15:05:00.735 ThaliTest[1337:1890008] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 15:05:00.736 ThaliTest[1337:1890008] Observers:
2016-09-23 15:05:00.736 ThaliTest[1337:1890008] Finishing unregister,ing observer in BluetoothHardwareControlManager
,received session: <ThaliCore.Session: 0x13e189830>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Optional("1CA7D5CA-9E41-4224-9ED0-97BAC56673BD")
nil
,nil
,Optional("B4D35A43-569B-4AD6-8DEF-BAEB23905BEA")
,Optional("9DAA5D37-7502-49C5-9104-70E0D15980C6")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  53
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  20.87332201004028
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
