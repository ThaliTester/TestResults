#### Test 864728853590d1f_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/F5EA6460-673B-41E5-BFA9-88AFA1D97D07/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F5EA6460-673B-41E5-BFA9-88AFA1D97D07/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/69203A99-1F6F-46BD-8E41-CA4BA14E64A5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63261"
,(lldb)     command script import "/tmp/F5EA6460-673B-41E5-BFA9-88AFA1D97D07/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 13:49:58.951 ThaliTest[3187:5584160] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EE05CA02-17D9-4064-847A-2AC2E11F93B8/Library/Cookies/Cookies.binarycookies
,2016-09-23 13:49:59.265 ThaliTest[3187:5584160] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 13:49:59.266 ThaliTest[3187:5584160] Multi-tasking -> Device: YES, App: YES
,2016-09-23 13:49:59.280 ThaliTest[3187:5584160] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 13:50:00.957 ThaliTest[3187:5584160] Using UIWebView
,2016-09-23 13:50:00.964 ThaliTest[3187:5584160] [CDVTimer][handleopenurl] 0.469983ms
,2016-09-23 13:50:00.971 ThaliTest[3187:5584160] [CDVTimer][intentandnavigationfilter] 6.608963ms
,2016-09-23 13:50:00.972 ThaliTest[3187:5584160] [CDVTimer][gesturehandler] 0.319004ms
,2016-09-23 13:50:00.972 ThaliTest[3187:5584160] [CDVTimer][TotalPluginStartup] 9.007990ms
,2016-09-23 13:50:07.239 ThaliTest[3187:5584160] Resetting plugins due to page load.
,2016-09-23 13:50:10.055 ThaliTest[3187:5584160] Finished load of: file:///var/mobile/Containers/Bundle/Application/69203A99-1F6F-46BD-8E41-CA4BA14E64A5/ThaliTest.app/www/index.html
,2016-09-23 13:50:10.324 ThaliTest[3187:5584160] JXcore Cordova plugin initializing
,2016-09-23 13:50:10.325 ThaliTest[3187:5584422] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x13fb1e750>
,Optional("B2321A92-3250-4173-BB56-6F88DA05C450")
,nil
,nil
,Optional("528B3A62-C755-4812-83E6-B6CACE19B927")
,Optional("EEFD59AA-E4B6-4DC1-94C8-9213E60681A2")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 13:50:35.642 ThaliTest[3187:5584160] Getting shared instance of BTmanager
2016-09-23 13:50:35.642 ThaliTest[3187:5584160] Dispatch_once working
,2016-09-23 13:50:35.864 ThaliTest[3187:5584160] Initializing BluetoothHardwareControlManager
2016-09-23 13:50:35.864 ThaliTest[3187:5584160] Getting private API's class
2016-09-23 13:50:35.864 ThaliTest[3187:5584160] Finishing getting private API's class BluetoothManager
,2016-09-23 13:50:35.864 ThaliTest[3187:5584160] BTM: attaching to BTServer
2016-09-23 13:50:35.864 ThaliTest[3187:5584160] Adding notification in BluetoothHardwareControlManager
,2016-09-23 13:50:35.864 ThaliTest[3187:5584160] Adding notification in BluetoothHardwareControlManager
2016-09-23 13:50:35.864 ThaliTest[3187:5584160] Finishing initializing BluetoothHardwareControlManager
,2016-09-23 13:50:35.865 ThaliTest[3187:5584160] Finishing dispatch_once working with handle: 0xffeeddcc00010800 and BTmanager: <BluetoothHardwareControlManager: 0x13d71f8f0>
,2016-09-23 13:50:35.865 ThaliTest[3187:5584160] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13d71f8f0>
2016-09-23 13:50:35.865 ThaliTest[3187:5584160] Registering observer in BluetoothHardwareControlManager
2016-09-,23 13:50:35.865 ThaliTest[3187:5584160] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 13:50:35.874 ThaliTest[3187:5584160] Getting shared instance of BTmanager
,2016-09-23 13:50:35.874 ThaliTest[3187:5584160] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13d71f8f0>
2016-09-23 13:50:35.874 ThaliTest[3187:5584160] Checking BT private state
,2016-09-23 13:50:35.874 ThaliTest[3187:5584160] Getting shared instance of BTmanager
2016-09-23 13:50:35.874 ThaliTest[3187:5584160] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13d71f8f0>
2016-09-23 13:50:35.874 ThaliTest[3187:5584160] Checking BT private state
,2016-09-23 13:50:35.874 ThaliTest[3187:5584160] Changing BT private state to On
,2016-09-23 13:50:45.961 ThaliTest[3187:5584160] Getting shared instance of BTmanager
2016-09-23 13:50:45.961 ThaliTest[3187:5584160] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13d71f8f0>
2016-09-23 13:50:45.961 ThaliTest[3187:5584160] Checking BT private state
,2016-09-23 13:50:55.975 ThaliTest[3187:5584160] Getting shared instance of BTmanager
,2016-09-23 13:50:55.976 ThaliTest[3187:5584160] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13d71f8f0>
,2016-09-23 13:50:55.976 ThaliTest[3187:5584160] Checking BT private state
,2016-09-23 13:50:55.977 ThaliTest[3187:5584160] Getting shared instance of BTmanager
,2016-09-23 13:50:55.977 ThaliTest[3187:5584160] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x13d71f8f0>
,2016-09-23 13:50:55.977 ThaliTest[3187:5584160] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 13:50:55.978 ThaliTest[3187:5584160] Observers:
,2016-09-23 13:50:55.978 ThaliTest[3187:5584160] Finishing unregistering observer in BluetoothHardwareControlManager
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  50
,Number of failed tests:  6
,Number of ignored tests:  0
,Total duration:  39.09526401758194
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
