#### Test 861743792a210c8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/B75D4EF1-0D51-453B-9821-8AF4DFE50890/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/B75D4EF1-0D51-453B-9821-8AF4DFE50890/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/861743792a210c8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B19F34F3-60EB-482F-B818-61410A15FC2B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52392"
,(lldb)     command script import "/tmp/B75D4EF1-0D51-453B-9821-8AF4DFE50890/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 14:48:44.302 ThaliTest[3196:5590126] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/222B27E1-B89E-495D-B895-CE3603C27977/Library/Cookies/Cookies.binarycookies
,2016-09-23 14:48:44.685 ThaliTest[3196:5590126] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 14:48:44.687 ThaliTest[3196:5590126] Multi-tasking -> Device: YES, App: YES
,2016-09-23 14:48:44.710 ThaliTest[3196:5590126] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 14:48:46.745 ThaliTest[3196:5590126] Using UIWebView
,2016-09-23 14:48:46.755 ThaliTest[3196:5590126] [CDVTimer][handleopenurl] 0.362992ms
,2016-09-23 14:48:46.762 ThaliTest[3196:5590126] [CDVTimer][intentandnavigationfilter] 6.422997ms
,2016-09-23 14:48:46.762 ThaliTest[3196:5590126] [CDVTimer][gesturehandler] 0.280976ms
,2016-09-23 14:48:46.763 ThaliTest[3196:5590126] [CDVTimer][TotalPluginStartup] 8.675039ms
,2016-09-23 14:48:52.784 ThaliTest[3196:5590126] Resetting plugins due to page load.
,2016-09-23 14:48:55.595 ThaliTest[3196:5590126] Finished load of: file:///var/mobile/Containers/Bundle/Application/B19F34F3-60EB-482F-B818-61410A15FC2B/ThaliTest.app/www/index.html
,2016-09-23 14:48:55.869 ThaliTest[3196:5590126] JXcore Cordova plugin initializing
2016-09-23 14:48:55.870 ThaliTest[3196:5590364] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13296ff00>
,XCTAssertNotEqual failed: ("Optional(2)") is equal to ("Optional(2)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 42
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 48
,XCTAssertNotEqual failed: ("Optional(1)") is equal to ("Optional(1)") -  - /Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/CoreTests/AtomicTests.swift - 36
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "connected to peer identifier". - <unknown> - 0
,Optional("3BE4A88C-134A-4CE7-88B0-6C3843765A97")
,nil
,nil
,Optional("84B6D048-6F57-45CD-946C-2B3C69932E99")
,Optional("43BCC8B1-48C9-4659-BC76-1A64967F01B9")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 14:49:22.323 ThaliTest[3196:5590126] Getting shared instance of BTmanager
2016-09-23 14:49:22.323 ThaliTest[3196:5590126] Dispatch_once working
,2016-09-23 14:49:22.557 ThaliTest[3196:5590126] Initializing BluetoothHardwareControlManager
2016-09-23 14:49:22.558 ThaliTest[3196:5590126] Getting private API's class
2016-09-23 14:49:22.558 ThaliTest[3196:5590126] Finishing getting private API's class BluetoothManager
,2016-09-23 14:49:22.558 ThaliTest[3196:5590126] BTM: attaching to BTServer
2016-09-23 14:49:22.558 ThaliTest[3196:5590126] Adding notification in BluetoothHardwareControlManager
2016-09-23 14:49:22.558 ThaliTest[3196:5590126] Adding notification in Bluet,oothHardwareControlManager
2016-09-23 14:49:22.558 ThaliTest[3196:5590126] Finishing initializing BluetoothHardwareControlManager
,2016-09-23 14:49:22.559 ThaliTest[3196:5590126] Finishing dispatch_once working with handle: 0xffeeddcc00010800 and BTmanager: <BluetoothHardwareControlManager: 0x131f695a0>
2016-09-23 14:49:22.559 ThaliTest[3196:5590126] Finishing getting shared instance, of BTmanager <BluetoothHardwareControlManager: 0x131f695a0>
2016-09-23 14:49:22.559 ThaliTest[3196:5590126] Registering observer in BluetoothHardwareControlManager
2016-09-23 14:49:22.559 ThaliTest[3196:5590126] Finishing registering observer in Bluetoo,thHardwareControlManager
,2016-09-23 14:49:22.570 ThaliTest[3196:5590126] Getting shared instance of BTmanager
,2016-09-23 14:49:22.571 ThaliTest[3196:5590126] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x131f695a0>
2016-09-23 14:49:22.571 ThaliTest[3196:5590126] Checking BT private state
,2016-09-23 14:49:22.571 ThaliTest[3196:5590126] Getting shared instance of BTmanager
,2016-09-23 14:49:22.571 ThaliTest[3196:5590126] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x131f695a0>
,2016-09-23 14:49:22.571 ThaliTest[3196:5590126] Checking BT private state
,2016-09-23 14:49:22.572 ThaliTest[3196:5590126] Changing BT private state to On
,2016-09-23 14:49:23.368 ThaliTest[3196:5590126] BTM: local device power state changed
2016-09-23 14:49:23.369 ThaliTest[3196:5590126] BTM: power is now on
2016-09-23 14:49:23.370 ThaliTest[3196:5590126] BluetoothHardwareControlManager notification received.
,2016-09-23 14:49:23.426 ThaliTest[3196:5590126] Getting shared instance of BTmanager
2016-09-23 14:49:23.426 ThaliTest[3196:5590126] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x131f695a0>
2016-09-23 14:49:23.426 ThaliTest[3196:5590126] Checking BT private state
2016-09-23 14:49:23.427 ThaliTest[3196:5590126] Changing BT private state to Off
,2016-09-23 14:49:28.034 ThaliTest[3196:5590126] BTM: local device power state changed
2016-09-23 14:49:28.035 ThaliTest[3196:5590126] BTM: power is now off
2016-09-23 14:49:28.035 ThaliTest[3196:5590126] BluetoothHardwareControlManager notification received.
,2016-09-23 14:49:28.061 ThaliTest[3196:5590126] Getting shared instance of BTmanager
2016-09-23 14:49:28.061 ThaliTest[3196:5590126] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x131f695a0>
2016-09-23 14:49:28.061 Tha,liTest[3196:5590126] Checking BT private state
2016-09-23 14:49:28.062 ThaliTest[3196:5590126] Getting shared instance of BTmanager
2016-09-23 14:49:28.062 ThaliTest[3196:5590126] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x131f695a0>
2016-09-23 14:49:28.062 ThaliTest[3196:5590126] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 14:49:28.062 ThaliTest[3196:5590126] Observers:
2016-09-23 14:49:28.062 ThaliTest[3196:5590126] Finishing unregistering observer in BluetoothHardwareControlManager
,Process 3196 stopped
* thread #3: tid = 0x554ccf, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
    frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
libobjc.A.dylib`objc_msgSend:
->  0x19abf1bd0 <+16>: ldp    x10, x11, [x9, #16]
    0x19abf1bd4 <+20>: and    w12, w1, w11
    0x19abf1bd8 <+24>: add    x12, x10, x12, lsl #4
    0x19abf1bdc <+28>: ldp    x16, x17, [x12]
,* thread #3: tid = 0x554ccf, 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16, queue = 'com.apple.root.background-qos', stop reason = EXC_BAD_ACCESS (code=1, address=0x10)
  * frame #0: 0x000000019abf1bd0 libobjc.A.dylib`objc_msgSend + 16
    frame #1: 0x0000000186dc2f70 Foundation`<redacted> + 68
    frame #2: 0x00000001000bdc78 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed> of ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 236
    frame #3: 0x00000001000ba210 ThaliTest`@objc ThaliTest.AppContext.centralManagerDidUpdateState (__ObjC.CBCentralManager) -> () + 48
    frame #4: 0x0000000185be8ee0 CoreBluetooth`<redacted> + 60
    frame #5: 0x000000019b3f16e8 libdispatch.dylib`<redacted> + 24
    frame #6: 0x000000019b3f16a8 libdispatch.dylib`<redacted> + 16
    frame #7: 0x000000019b3fd6ec libdispatch.dylib`<redacted> + 864
    frame #8: 0x000000019b3f51ac libdispatch.dylib`<redacted> + 464
    frame #9: 0x000000019b3ff5bc libdispatch.dylib`<redacted> + 728
    frame #10: 0x000000019b3ff2dc libdispatch.dylib`<redacted> + 112
    frame #11: 0x000000019b611470 libsystem_pthread.dylib`_pthread_wqthread + 1092
    frame #12: 0x000000019b611020 libsystem_pthread.dylib`start_wqthread + 4

```
