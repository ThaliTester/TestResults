#### Test 86185956533f65d_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/12788BC9-D666-4588-BC7C-1E76B727C44F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/12788BC9-D666-4588-BC7C-1E76B727C44F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/86185956533f65d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C155E9F6-4BFC-4B52-BBD5-A93A97A58934/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53473"
,(lldb)     command script import "/tmp/12788BC9-D666-4588-BC7C-1E76B727C44F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 17:55:31.968 ThaliTest[1069:1631597] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CE6C0FAA-5F86-4806-A012-BDEE9CE85597/Library/Cookies/Cookies.binarycookies
,2016-09-21 17:55:32.004 ThaliTest[1069:1631597] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-21 17:55:32.005 ThaliTest[1069:1631597] Multi-tasking -> Device: YES, App: YES
,2016-09-21 17:55:32.015 ThaliTest[1069:1631597] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 17:55:32.331 ThaliTest[1069:1631597] Using UIWebView
2016-09-21 17:55:32.334 ThaliTest[1069:1631597] [CDVTimer][handleopenurl] 0.182986ms
,2016-09-21 17:55:32.338 ThaliTest[1069:1631597] [CDVTimer][intentandnavigationfilter] 3.682017ms
2016-09-21 17:55:32.338 ThaliTest[1069:1631597] [CDVTimer][gesturehandler] 0.164986ms
2016-09-21 17:55:32.338 ThaliTest[1069:1631597] [CDVTimer][TotalPluginStartup] 4.900992ms
,2016-09-21 17:55:37.855 ThaliTest[1069:1631597] Resetting plugins due to page load.
,2016-09-21 17:55:38.232 ThaliTest[1069:1631597] Finished load of: file:///var/containers/Bundle/Application/C155E9F6-4BFC-4B52-BBD5-A93A97A58934/ThaliTest.app/www/index.html
,2016-09-21 17:55:38.563 ThaliTest[1069:1631597] JXcore Cordova plugin initializing
,2016-09-21 17:55:38.564 ThaliTest[1069:1631777] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14ea816b0>
,Optional("1A418BE3-C35A-4013-B01D-79E45E9BF30E")
nil
,nil
,Optional("AD5A5E6C-5484-4229-8970-740C4D9E5AFF")
,Optional("5A4236D2-5A6C-4317-A572-9F350377E283")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-21 17:56:00.505 ThaliTest[1069:1631597] BTM: attaching to BTServer
,2016-09-21 17:56:01.245 ThaliTest[1069:1631597] BTM: local device power state changed
2016-09-21 17:56:01.245 ThaliTest[1069:1631597] BTM: power is now on
,2016-09-21 17:56:05.961 ThaliTest[1069:1631597] BTM: local device power state changed
2016-09-21 17:56:05.962 ThaliTest[1069:1631597] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  50
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  19.94140100479126
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
