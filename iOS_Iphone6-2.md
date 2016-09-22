#### Test 85046911f11c404_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DE3CB857-62D7-41A7-B1A2-8880E4588E04/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/DE3CB857-62D7-41A7-B1A2-8880E4588E04/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911f11c404/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/238F0717-96D4-4433-AFC6-419E470BB1AE/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62004"
,(lldb)     command script import "/tmp/DE3CB857-62D7-41A7-B1A2-8880E4588E04/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 03:23:45.533 ThaliTest[1329:1656213] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/8EB7E3A9-79EF-42E8-BF02-43B1559B8318/Library/Cookies/Cookies.binarycookies
,2016-09-22 03:23:45.656 ThaliTest[1329:1656213] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 03:23:45.657 ThaliTest[1329:1656213] Multi-tasking -> Device: YES, App: YES
,2016-09-22 03:23:45.673 ThaliTest[1329:1656213] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 03:23:46.182 ThaliTest[1329:1656213] Using UIWebView
2016-09-22 03:23:46.186 ThaliTest[1329:1656213] [CDVTimer][handleopenurl] 0.236034ms
,2016-09-22 03:23:46.192 ThaliTest[1329:1656213] [CDVTimer][intentandnavigationfilter] 5.452037ms
2016-09-22 03:23:46.193 ThaliTest[1329:1656213] [CDVTimer][gesturehandler] 0.222027ms
2016-09-22 03:23:46.193 ThaliTest[1329:1656213] [CDVTimer][TotalPluginS,tartup] 7.026970ms
,2016-09-22 03:23:53.084 ThaliTest[1329:1656213] Resetting plugins due to page load.
,2016-09-22 03:23:53.780 ThaliTest[1329:1656213] Finished load of: file:///var/containers/Bundle/Application/238F0717-96D4-4433-AFC6-419E470BB1AE/ThaliTest.app/www/index.html
,2016-09-22 03:23:54.265 ThaliTest[1329:1656213] JXcore Cordova plugin initializing
,2016-09-22 03:23:54.267 ThaliTest[1329:1656399] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x12750c340>
,Optional("A65CB365-FB45-4DEE-BBEB-FA98A1D69E69")
,nil
,nil
,Optional("EA852F9A-7C3B-4448-AA9D-99B60D2AF86D")
,Optional("18614916-2750-47E5-B991-E5A490C7320C")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 03:24:17.483 ThaliTest[1329:1656213] BTM: attaching to BTServer
,2016-09-22 03:24:18.273 ThaliTest[1329:1656213] BTM: local device power state changed
2016-09-22 03:24:18.274 ThaliTest[1329:1656213] BTM: power is now on
,2016-09-22 03:24:22.982 ThaliTest[1329:1656213] BTM: local device power state changed
2016-09-22 03:24:22.983 ThaliTest[1329:1656213] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  50
Number of passed tests:  48
Number of failed tests:  2
Number of ignored tests:  0
,Total duration:  20.96937000751495
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackground wasn't registered
appEnteringBackground wasn't registered

```
