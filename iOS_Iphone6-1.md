#### Test 86174379abea55c_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6D5B65DA-4B97-4860-A6DC-588439DA53FA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/6D5B65DA-4B97-4860-A6DC-588439DA53FA/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86174379abea55c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/86904987-2C11-424C-8F3A-031A0B0C8720/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56116"
,(lldb)     command script import "/tmp/6D5B65DA-4B97-4860-A6DC-588439DA53FA/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 18:28:50.582 ThaliTest[1076:1635548] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/43BE4464-EC0E-409E-95EA-C025751C30DA/Library/Cookies/Cookies.binarycookies
,2016-09-21 18:28:50.677 ThaliTest[1076:1635548] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 18:28:50.680 ThaliTest[1076:1635548] Multi-tasking -> Device: YES, App: YES
,2016-09-21 18:28:50.702 ThaliTest[1076:1635548] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 18:28:51.166 ThaliTest[1076:1635548] Using UIWebView
,2016-09-21 18:28:51.176 ThaliTest[1076:1635548] [CDVTimer][handleopenurl] 0.347018ms
,2016-09-21 18:28:51.184 ThaliTest[1076:1635548] [CDVTimer][intentandnavigationfilter] 7.053971ms
2016-09-21 18:28:51.185 ThaliTest[1076:1635548] [CDVTimer][gesturehandler] 0.320971ms
2016-09-21 18:28:51.185 ThaliTest[1076:1635548] [CDVTimer][TotalPluginS,tartup] 9.352982ms
,2016-09-21 18:28:56.514 ThaliTest[1076:1635548] Resetting plugins due to page load.
,2016-09-21 18:28:56.870 ThaliTest[1076:1635548] Finished load of: file:///var/containers/Bundle/Application/86904987-2C11-424C-8F3A-031A0B0C8720/ThaliTest.app/www/index.html
,2016-09-21 18:28:57.237 ThaliTest[1076:1635548] JXcore Cordova plugin initializing
,2016-09-21 18:28:57.238 ThaliTest[1076:1635710] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14e618160>
,Optional("BACDFC97-4374-4967-83F6-F1826BB2A53A")
nil
,nil
,Optional("41BC4A31-772B-4430-A6B5-E2A3C27AAD5A")
,Optional("F80C8371-CB4E-4DD9-8E2F-1D1BB9FF4009")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 18:29:19.334 ThaliTest[1076:1635548] BTM: attaching to BTServer
,2016-09-21 18:29:20.086 ThaliTest[1076:1635548] BTM: local device power state changed
2016-09-21 18:29:20.087 ThaliTest[1076:1635548] BTM: power is now on
,2016-09-21 18:29:24.828 ThaliTest[1076:1635548] BTM: local device power state changed
2016-09-21 18:29:24.831 ThaliTest[1076:1635548] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  56
Number of passed tests:  56
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  20.03219103813171
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
