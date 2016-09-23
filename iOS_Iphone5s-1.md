#### Test 864728853590d1f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AC4A4016-AFB4-4235-B54E-6DCD0C09FE5B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AC4A4016-AFB4-4235-B54E-6DCD0C09FE5B/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864728853590d1f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D694C465-E7D6-4D44-9730-DBAC8CB20F3C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63272"
,(lldb)     command script import "/tmp/AC4A4016-AFB4-4235-B54E-6DCD0C09FE5B/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 13:49:56.172 ThaliTest[3077:6150546] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/113D8263-B1E0-4770-BB0A-E34A177549B3/Library/Cookies/Cookies.binarycookies
,2016-09-23 13:49:56.283 ThaliTest[3077:6150546] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 13:49:56.285 ThaliTest[3077:6150546] Multi-tasking -> Device: YES, App: YES
,2016-09-23 13:49:56.310 ThaliTest[3077:6150546] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 13:49:57.800 ThaliTest[3077:6150546] Using UIWebView
,2016-09-23 13:49:57.808 ThaliTest[3077:6150546] [CDVTimer][handleopenurl] 0.546992ms
,2016-09-23 13:49:57.817 ThaliTest[3077:6150546] [CDVTimer][intentandnavigationfilter] 8.287966ms
2016-09-23 13:49:57.818 ThaliTest[3077:6150546] [CDVTimer][gesturehandler] 0.419974ms
2016-09-23 13:49:57.818 ThaliTest[3077:6150546] [CDVTimer][TotalPluginStartup] 11.215031ms
,2016-09-23 13:50:03.935 ThaliTest[3077:6150546] Resetting plugins due to page load.
,2016-09-23 13:50:07.363 ThaliTest[3077:6150546] Finished load of: file:///var/mobile/Containers/Bundle/Application/D694C465-E7D6-4D44-9730-DBAC8CB20F3C/ThaliTest.app/www/index.html
,2016-09-23 13:50:07.670 ThaliTest[3077:6150546] JXcore Cordova plugin initializing
,2016-09-23 13:50:07.671 ThaliTest[3077:6150751] JXcore instance initializing
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
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 13:50:16.650 ThaliTest[3077:6150546] Getting shared instance of BTmanager
2016-09-23 13:50:16.650 ThaliTest[3077:6150546] Dispatch_once working
,2016-09-23 13:50:16.763 ThaliTest[3077:6150546] Initializing BluetoothHardwareControlManager
2016-09-23 13:50:16.764 ThaliTest[3077:6150546] Getting private API's class
2016-09-23 13:50:16.764 ThaliTest[3077:6150546] Finishing getting private API's class BluetoothManager
2016-09-23 13:50:16.764 ThaliTest[3077:6150546] BTM: attaching to BTServer
2016-09-23 13:50:16.764 ThaliTest[3077:6150546] Adding notification in BluetoothHardwareControlManager
2016-09-23 13:50:16.764 ThaliTest[3077:6150546] Adding no,tification in BluetoothHardwareControlManager
2016-09-23 13:50:16.764 ThaliTest[3077:6150546] Finishing initializing BluetoothHardwareControlManager
2016-09-23 13:50:16.765 ThaliTest[3077:6150546] Finishing dispatch_once working with handle: 0xffeeddcc00,010a00 and BTmanager: <BluetoothHardwareControlManager: 0x15ec9f830>
2016-09-23 13:50:16.765 ThaliTest[3077:6150546] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x15ec9f830>
2016-09-23 13:50:16.766 ThaliTest[3077:6150,546] Registering observer in BluetoothHardwareControlManager
2016-09-23 13:50:16.766 ThaliTest[3077:6150546] Finishing registering observer in BluetoothHardwareControlManager
,2016-09-23 13:50:16.782 ThaliTest[3077:6150546] Getting shared instance of BTmanager
2016-09-23 13:50:16.783 ThaliTest[3077:6150546] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x15ec9f830>
2016-09-23 13:50:16.783 ThaliTest[3077:6150546] Checking BT private state
,2016-09-23 13:50:16.783 ThaliTest[3077:6150546] Getting shared instance of BTmanager
2016-09-23 13:50:16.783 ThaliTest[3077:6150546] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x15ec9f830>
2016-09-23 13:50:16.784 ThaliTest[3077:6150546] Checking BT private state
2016-09-23 13:50:16.784 ThaliTest[3077:6150546] Changing BT private state to On
,2016-09-23 13:50:17.558 ThaliTest[3077:6150546] BTM: local device power state changed
2016-09-23 13:50:17.558 ThaliTest[3077:6150546] BTM: power is now on
2016-09-23 13:50:17.573 ThaliTest[3077:6150546] BluetoothHardwareControlManager notification received.
,2016-09-23 13:50:17.610 ThaliTest[3077:6150546] Getting shared instance of BTmanager
2016-09-23 13:50:17.611 ThaliTest[3077:6150546] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x15ec9f830>
2016-09-23 13:50:17.611 Tha,liTest[3077:6150546] Checking BT private state
2016-09-23 13:50:17.611 ThaliTest[3077:6150546] Changing BT private state to Off
,2016-09-23 13:50:22.270 ThaliTest[3077:6150546] BTM: local device power state changed
2016-09-23 13:50:22.271 ThaliTest[3077:6150546] BTM: power is now off
2016-09-23 13:50:22.274 ThaliTest[3077:6150546] BluetoothHardwareControlManager notification received.
,2016-09-23 13:50:22.293 ThaliTest[3077:6150546] Getting shared instance of BTmanager
2016-09-23 13:50:22.293 ThaliTest[3077:6150546] Finishing getting shared instance of BTmanager <BluetoothHardwareControlManager: 0x15ec9f830>
2016-09-23 13:50:22.294 Tha,liTest[3077:6150546] Checking BT private state
2016-09-23 13:50:22.294 ThaliTest[3077:6150546] Getting shared instance of BTmanager
2016-09-23 13:50:22.294 ThaliTest[3077:6150546] Finishing getting shared instance of BTmanager <BluetoothHardwareControlMa,nager: 0x15ec9f830>
2016-09-23 13:50:22.294 ThaliTest[3077:6150546] Unregistering observer in BluetoothHardwareControlManager
2016-09-23 13:50:22.294 ThaliTest[3077:6150546] Observers:
2016-09-23 13:50:22.294 ThaliTest[3077:6150546] Finishing unregister,ing observer in BluetoothHardwareControlManager
,received session: <ThaliCore.Session: 0x15f115450>
,Optional("617C54C6-9CF5-433F-B6AD-5BCDC1BA1634")
,nil
,nil
,Optional("FFDC2D16-3122-4E37-AF6B-8C63DFA7B4D3")
,Optional("F82C1BA8-2B84-4401-B82C-C25EC8A22D0D")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  19.83302503824234
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
