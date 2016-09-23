#### Test 850469116954903_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/40E923AB-9FD5-4FEC-B32D-8ABD0949CB31/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/40E923AB-9FD5-4FEC-B32D-8ABD0949CB31/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/850469116954903/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A8253D7C-577E-4E89-B8C6-4AB00DD98F36/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60487"
,(lldb)     command script import "/tmp/40E923AB-9FD5-4FEC-B32D-8ABD0949CB31/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 08:23:21.485 ThaliTest[1249:1844685] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7ECA8A8B-430B-4AEC-A049-1BEDF0ECA4B0/Library/Cookies/Cookies.binarycookies
,2016-09-23 08:23:21.528 ThaliTest[1249:1844685] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 08:23:21.529 ThaliTest[1249:1844685] Multi-tasking -> Device: YES, App: YES
,2016-09-23 08:23:21.542 ThaliTest[1249:1844685] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 08:23:21.902 ThaliTest[1249:1844685] Using UIWebView
,2016-09-23 08:23:21.907 ThaliTest[1249:1844685] [CDVTimer][handleopenurl] 0.352025ms
,2016-09-23 08:23:21.912 ThaliTest[1249:1844685] [CDVTimer][intentandnavigationfilter] 4.684031ms
2016-09-23 08:23:21.912 ThaliTest[1249:1844685] [CDVTimer][gesturehandler] 0.189006ms
2016-09-23 08:23:21.912 ThaliTest[1249:1844685] [CDVTimer][TotalPluginStartup] 6.309986ms
,2016-09-23 08:23:27.118 ThaliTest[1249:1844685] Resetting plugins due to page load.
,2016-09-23 08:23:27.503 ThaliTest[1249:1844685] Finished load of: file:///var/containers/Bundle/Application/A8253D7C-577E-4E89-B8C6-4AB00DD98F36/ThaliTest.app/www/index.html
,2016-09-23 08:23:27.833 ThaliTest[1249:1844685] JXcore Cordova plugin initializing
,2016-09-23 08:23:27.834 ThaliTest[1249:1844860] JXcore instance initializing
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
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-23 08:23:35.338 ThaliTest[1249:1844685] BTM: attaching to BTServer
,2016-09-23 08:23:36.084 ThaliTest[1249:1844685] BTM: local device power state changed
2016-09-23 08:23:36.090 ThaliTest[1249:1844685] BTM: power is now on
,2016-09-23 08:23:40.825 ThaliTest[1249:1844685] BTM: local device power state changed
2016-09-23 08:23:40.828 ThaliTest[1249:1844685] BTM: power is now off
,received session: <ThaliCore.Session: 0x130610840>
,Optional("37E7CED2-91D0-4537-8673-22C76DDBA8C0")
nil
,nil
,Optional("F152E584-413D-492F-822E-3D9EFB7C519A")
,Optional("206631DA-CE89-4931-8622-AF0900FBB083")
,*Native tests were executed*
,Total number of executed tests:  50
Number of passed tests:  50
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  20.59427499771118
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
