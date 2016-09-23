#### Test 864728853590d1f_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8F2B0966-5426-47A0-8C5D-EBA54BE69887/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8F2B0966-5426-47A0-8C5D-EBA54BE69887/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/77C8D45F-73FB-4CE4-8B1E-2CAFDB7CF849/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63232"
,(lldb)     command script import "/tmp/8F2B0966-5426-47A0-8C5D-EBA54BE69887/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-09-23 13:49:51.834 ThaliTest[1322:1881435] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/21C1CAA6-52B1-4B24-80C4-C65463BB11F1/Library/Cookies/Cookies.binarycookies
,2016-09-23 13:49:51.874 ThaliTest[1322:1881435] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 13:49:51.875 ThaliTest[1322:1881435] Multi-tasking -> Device: YES, App: YES
,2016-09-23 13:49:51.887 ThaliTest[1322:1881435] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 13:49:52.208 ThaliTest[1322:1881435] Using UIWebView
,2016-09-23 13:49:52.212 ThaliTest[1322:1881435] [CDVTimer][handleopenurl] 0.245988ms
,2016-09-23 13:49:52.216 ThaliTest[1322:1881435] [CDVTimer][intentandnavigationfilter] 3.584027ms
2016-09-23 13:49:52.216 ThaliTest[1322:1881435] [CDVTimer][gesturehandler] 0.153005ms
2016-09-23 13:49:52.216 ThaliTest[1322:1881435] [CDVTimer][TotalPluginStartup] 4.795015ms
,2016-09-23 13:49:57.294 ThaliTest[1322:1881435] Resetting plugins due to page load.
,2016-09-23 13:49:57.676 ThaliTest[1322:1881435] Finished load of: file:///var/containers/Bundle/Application/77C8D45F-73FB-4CE4-8B1E-2CAFDB7CF849/ThaliTest.app/www/index.html
,2016-09-23 13:49:58.006 ThaliTest[1322:1881435] JXcore Cordova plugin initializing
,2016-09-23 13:49:58.008 ThaliTest[1322:1881609] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x1277c4620>
,Optional("A859C8B4-AFF0-4EA4-B15C-ED1F5CA1B152")
nil
,nil
,Optional("8E287DD5-737C-435C-8391-5CAB344466AC")
,Optional("27918F7B-CB56-473F-B8A0-3E59653AE448")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 13:50:19.995 ThaliTest[1322:1881435] Getting shared instance of BTmanager
2016-09-23 13:50:19.995 ThaliTest[1322:1881435] Dispatch_once working
,2016-09-23 13:50:20.129 ThaliTest[1322:1881435] Initializing BluetoothHardwareControlManager
2016-09-23 13:50:20.129 ThaliTest[1322:1881435] Getting private API's class
2016-09-23 13:50:20.129 ThaliTest[1322:1881435] Finishing getting private API's class, BluetoothManager
2016-09-23 13:50:20.129 ThaliTest[1322:1881435] BTM: attaching to BTServer
2016-09-23 13:50:20.129 ThaliTest[1322:1881435] Adding notification in BluetoothHardwareControlManager
2016-09-23 13:50:20.130 ThaliTest[1322:1881435] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 13:50:20.130 ThaliTest[1322:1881435] Finishing initializing BluetoothHardwareControlManager
2016-09-23 13:50:20.130 ThaliTest[1322:1881435] Finishing dispatch_once working with handle: 0xffeeddcc00,00d400 and BTmanager: <BluetoothHardwareControlManager: 0x12734b360>
2016-09-23 13:50:20.130 ThaliTest[1322:1881435] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12734b360>
2016-09-23 13:50:20.130 ThaliTest[1322:1881,435] Registering observer in BluetoothHardwareControlManager
,2016-09-23 13:50:20.130 ThaliTest[1322:1881435] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 13:50:20.149 ThaliTest[1322:1881435] Getting shared instance of BTmanager
2016-09-23 13:50:20.150 ThaliTest[1322:1881435] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12734b360>
2016-09-23 13:50:20.150 Tha,liTest[1322:1881435] Checking BT private state
2016-09-23 13:50:20.150 ThaliTest[1322:1881435] Getting shared instance of BTmanager
2016-09-23 13:50:20.150 ThaliTest[1322:1881435] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x12734b360>
2016-09-23 13:50:20.150 ThaliTest[1322:1881435] Checking BT private state
,2016-09-23 13:50:20.150 ThaliTest[1322:1881435] Changing BT private state to On
,2016-09-23 13:50:20.865 ThaliTest[1322:1881435] BTM: local device power state changed
2016-09-23 13:50:20.865 ThaliTest[1322:1881435] BTM: power is now on
2016-09-23 13:50:20.880 ThaliTest[1322:1881435] BluetoothHardwareControlManager notification received.
,2016-09-23 13:50:20.938 ThaliTest[1322:1881435] Getting shared instance of BTmanager
2016-09-23 13:50:20.938 ThaliTest[1322:1881435] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12734b360>
2016-09-23 13:50:20.938 Tha,liTest[1322:1881435] Checking BT private state
2016-09-23 13:50:20.938 ThaliTest[1322:1881435] Changing BT private state to Off
,2016-09-23 13:50:25.588 ThaliTest[1322:1881435] BTM: local device power state changed
,2016-09-23 13:50:25.588 ThaliTest[1322:1881435] BTM: power is now off
,2016-09-23 13:50:25.593 ThaliTest[1322:1881435] BluetoothHardwareControlManager notification received.
,2016-09-23 13:50:25.613 ThaliTest[1322:1881435] Getting shared instance of BTmanager
2016-09-23 13:50:25.613 ThaliTest[1322:1881435] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x12734b360>
2016-09-23 13:50:25.613 Tha,liTest[1322:1881435] Checking BT private state
2016-09-23 13:50:25.613 ThaliTest[1322:1881435] Getting shared instance of BTmanager
2016-09-23 13:50:25.614 ThaliTest[1322:1881435] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x12734b360>
2016-09-23 13:50:25.614 ThaliTest[1322:1881435] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 13:50:25.614 ThaliTest[1322:1881435] Observers:
2016-09-23 13:50:25.614 ThaliTest[1322:1881435] Finishing unregister,ing observer in BluetoothHardwareControlManager
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.13428300619125
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
