#### Test 864825820901bf9_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A5E6D9C2-AFB9-430C-8755-6B0213E284F3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/A5E6D9C2-AFB9-430C-8755-6B0213E284F3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825820901bf9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/913370DB-0184-413A-9271-A6E1B808F15D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56077"
,(lldb)     command script import "/tmp/A5E6D9C2-AFB9-430C-8755-6B0213E284F3/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 03:01:50.130 ThaliTest[1456:1774501] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E6022B96-82F0-4460-A333-AFD45C556E84/Library/Cookies/Cookies.binarycookies
,2016-09-23 03:01:50.186 ThaliTest[1456:1774501] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 03:01:50.187 ThaliTest[1456:1774501] Multi-tasking -> Device: YES, App: YES
,2016-09-23 03:01:50.200 ThaliTest[1456:1774501] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 03:01:50.507 ThaliTest[1456:1774501] Using UIWebView
,2016-09-23 03:01:50.511 ThaliTest[1456:1774501] [CDVTimer][handleopenurl] 0.195026ms
,2016-09-23 03:01:50.515 ThaliTest[1456:1774501] [CDVTimer][intentandnavigationfilter] 3.437042ms
2016-09-23 03:01:50.515 ThaliTest[1456:1774501] [CDVTimer][gesturehandler] 0.153005ms
2016-09-23 03:01:50.516 ThaliTest[1456:1774501] [CDVTimer][TotalPluginStartup] 4.593968ms
,2016-09-23 03:01:56.662 ThaliTest[1456:1774501] Resetting plugins due to page load.
,2016-09-23 03:01:57.015 ThaliTest[1456:1774501] Finished load of: file:///var/containers/Bundle/Application/913370DB-0184-413A-9271-A6E1B808F15D/ThaliTest.app/www/index.html
,2016-09-23 03:01:57.341 ThaliTest[1456:1774501] JXcore Cordova plugin initializing
,2016-09-23 03:01:57.342 ThaliTest[1456:1774676] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x137d32e90>
,Optional("B5D85F23-7994-4597-9723-25E5BC284D9E")
nil
,nil
,Optional("60390D42-3E3D-4844-A62F-C747FE021918")
,Optional("10D0AE12-8CCE-4F37-B1F7-530DA441A49B")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-23 03:02:18.598 ThaliTest[1456:1774501] BTM: attaching to BTServer
,2016-09-23 03:02:19.372 ThaliTest[1456:1774501] BTM: local device power state changed
2016-09-23 03:02:19.383 ThaliTest[1456:1774501] BTM: power is now on
,2016-09-23 03:02:24.078 ThaliTest[1456:1774501] BTM: local device power state changed
2016-09-23 03:02:24.082 ThaliTest[1456:1774501] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  19.37918001413345
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
