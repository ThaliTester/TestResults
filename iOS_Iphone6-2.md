#### Test 8326889373d8814_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/794BBB51-2CE0-4086-985D-74A04F2B3771/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/794BBB51-2CE0-4086-985D-74A04F2B3771/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8235AE9B-3458-4DE6-AF86-BA6E751B4BEB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61500"
,(lldb)     command script import "/tmp/794BBB51-2CE0-4086-985D-74A04F2B3771/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 07:42:22.145 ThaliTest[1511:1801187] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F24317D-D367-4AF9-B3B9-7BD7B8DF3251/Library/Cookies/Cookies.binarycookies
,2016-09-23 07:42:22.180 ThaliTest[1511:1801187] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 07:42:22.181 ThaliTest[1511:1801187] Multi-tasking -> Device: YES, App: YES
,2016-09-23 07:42:22.192 ThaliTest[1511:1801187] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 07:42:22.534 ThaliTest[1511:1801187] Using UIWebView
,2016-09-23 07:42:22.539 ThaliTest[1511:1801187] [CDVTimer][handleopenurl] 0.277042ms
,2016-09-23 07:42:22.544 ThaliTest[1511:1801187] [CDVTimer][intentandnavigationfilter] 4.624963ms
2016-09-23 07:42:22.544 ThaliTest[1511:1801187] [CDVTimer][gesturehandler] 0.181973ms
2016-09-23 07:42:22.545 ThaliTest[1511:1801187] [CDVTimer][TotalPluginStartup] 6.170988ms
,2016-09-23 07:42:28.235 ThaliTest[1511:1801187] Resetting plugins due to page load.
,2016-09-23 07:42:28.635 ThaliTest[1511:1801187] Finished load of: file:///var/containers/Bundle/Application/8235AE9B-3458-4DE6-AF86-BA6E751B4BEB/ThaliTest.app/www/index.html
,2016-09-23 07:42:28.958 ThaliTest[1511:1801187] JXcore Cordova plugin initializing
,2016-09-23 07:42:28.959 ThaliTest[1511:1801343] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12884a740>
,Optional("A76C1B11-EC26-4115-892A-8EAB18A65433")
nil
,nil
,Optional("9AE86339-F8AB-4997-A4F5-33EBB6C851B1")
,Optional("D76E6FC8-87EC-4726-98BE-FCF70150C39F")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.32801598310471
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
