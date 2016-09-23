#### Test 864728853590d1f_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/49F2603E-59BB-40D8-8EBF-D8602F542AF9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/49F2603E-59BB-40D8-8EBF-D8602F542AF9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D9CE9939-2499-437D-81B6-CC0132B88CF4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63245"
,(lldb)     command script import "/tmp/49F2603E-59BB-40D8-8EBF-D8602F542AF9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 04:49:53.049 ThaliTest[1487:1786095] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EA03D79E-E138-441C-8C84-E3455568D1FE/Library/Cookies/Cookies.binarycookies
,2016-09-23 04:49:53.126 ThaliTest[1487:1786095] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 04:49:53.128 ThaliTest[1487:1786095] Multi-tasking -> Device: YES, App: YES
,2016-09-23 04:49:53.148 ThaliTest[1487:1786095] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 04:49:53.605 ThaliTest[1487:1786095] Using UIWebView
,2016-09-23 04:49:53.614 ThaliTest[1487:1786095] [CDVTimer][handleopenurl] 0.325024ms
,2016-09-23 04:49:53.622 ThaliTest[1487:1786095] [CDVTimer][intentandnavigationfilter] 7.167041ms
2016-09-23 04:49:53.623 ThaliTest[1487:1786095] [CDVTimer][gesturehandler] 0.272036ms
2016-09-23 04:49:53.623 ThaliTest[1487:1786095] [CDVTimer][TotalPluginStartup] 9.351969ms
,2016-09-23 04:49:59.679 ThaliTest[1487:1786095] Resetting plugins due to page load.
,2016-09-23 04:50:00.260 ThaliTest[1487:1786095] Finished load of: file:///var/containers/Bundle/Application/D9CE9939-2499-437D-81B6-CC0132B88CF4/ThaliTest.app/www/index.html
,2016-09-23 04:50:00.591 ThaliTest[1487:1786095] JXcore Cordova plugin initializing
,2016-09-23 04:50:00.592 ThaliTest[1487:1786273] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14f9fa300>
,Optional("2329F901-1B3F-42B8-82CC-854E09142169")
nil
,nil
,Optional("C3C1B524-4AE0-41DB-8407-E49DACA4FCD5")
,Optional("15913474-F5E5-4D66-B36A-9FF1FA3FDC85")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 04:50:23.457 ThaliTest[1487:1786095] Getting shared instance of BTmanager
2016-09-23 04:50:23.457 ThaliTest[1487:1786095] Dispatch_once working
,2016-09-23 04:50:23.633 ThaliTest[1487:1786095] Initializing BluetoothHardwareControlManager
2016-09-23 04:50:23.633 ThaliTest[1487:1786095] Getting private API's class
2016-09-23 04:50:23.634 ThaliTest[1487:1786095] Finishing getting private API's class, BluetoothManager
2016-09-23 04:50:23.634 ThaliTest[1487:1786095] BTM: attaching to BTServer
2016-09-23 04:50:23.634 ThaliTest[1487:1786095] Adding notification in BluetoothHardwareControlManager
2016-09-23 04:50:23.634 ThaliTest[1487:1786095] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 04:50:23.634 ThaliTest[1487:1786095] Finishing initializing BluetoothHardwareControlManager
2016-09-23 04:50:23.635 ThaliTest[1487:1786095] Finishing dispatch_once working with handle: 0xffeeddcc00,00d400 and BTmanager: <BluetoothHardwareControlManager: 0x14df71fa0>
2016-09-23 04:50:23.635 ThaliTest[1487:1786095] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14df71fa0>
,2016-09-23 04:50:23.635 ThaliTest[1487:1786095] Registering observer in BluetoothHardwareControlManager
2016-09-23 04:50:23.635 ThaliTest[1487:1786095] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 04:50:23.662 ThaliTest[1487:1786095] Getting shared instance of BTmanager
2016-09-23 04:50:23.662 ThaliTest[1487:1786095] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14df71fa0>
2016-09-23 04:50:23.662 Tha,liTest[1487:1786095] Checking BT private state
2016-09-23 04:50:23.662 ThaliTest[1487:1786095] Getting shared instance of BTmanager
2016-09-23 04:50:23.663 ThaliTest[1487:1786095] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x14df71fa0>
2016-09-23 04:50:23.663 ThaliTest[1487:1786095] Checking BT private state
2016-09-23 04:50:23.663 ThaliTest[1487:1786095] Changing BT private state to On
,2016-09-23 04:50:24.413 ThaliTest[1487:1786095] BTM: local device power state changed
2016-09-23 04:50:24.413 ThaliTest[1487:1786095] BTM: power is now on
2016-09-23 04:50:24.414 ThaliTest[1487:1786095] BluetoothHardwareControlManager notification received.
,2016-09-23 04:50:24.473 ThaliTest[1487:1786095] Getting shared instance of BTmanager
2016-09-23 04:50:24.474 ThaliTest[1487:1786095] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14df71fa0>
2016-09-23 04:50:24.474 Tha,liTest[1487:1786095] Checking BT private state
2016-09-23 04:50:24.474 ThaliTest[1487:1786095] Changing BT private state to Off
,2016-09-23 04:50:29.138 ThaliTest[1487:1786095] BTM: local device power state changed
2016-09-23 04:50:29.139 ThaliTest[1487:1786095] BTM: power is now off
2016-09-23 04:50:29.139 ThaliTest[1487:1786095] BluetoothHardwareControlManager notification recei,ved.
,2016-09-23 04:50:29.170 ThaliTest[1487:1786095] Getting shared instance of BTmanager
2016-09-23 04:50:29.170 ThaliTest[1487:1786095] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x14df71fa0>
2016-09-23 04:50:29.171 Tha,liTest[1487:1786095] Checking BT private state
2016-09-23 04:50:29.172 ThaliTest[1487:1786095] Getting shared instance of BTmanager
2016-09-23 04:50:29.172 ThaliTest[1487:1786095] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x14df71fa0>
2016-09-23 04:50:29.172 ThaliTest[1487:1786095] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 04:50:29.172 ThaliTest[1487:1786095] Observers:
2016-09-23 04:50:29.172 ThaliTest[1487:1786095] Finishing unregister,ing observer in BluetoothHardwareControlManager
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  21.24032598733902
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
