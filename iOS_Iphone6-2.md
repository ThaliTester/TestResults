#### Test 83268893ec4b63c_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CCCF29E6-8C49-4749-832B-AFD17BD4420D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/CCCF29E6-8C49-4749-832B-AFD17BD4420D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83268893ec4b63c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/61F5604F-CA05-4160-AF16-CBE1DC0CBB11/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63808"
,(lldb)     command script import "/tmp/CCCF29E6-8C49-4749-832B-AFD17BD4420D/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-21 07:48:07.309 ThaliTest[1229:1557574] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/49A0CE30-C6DB-43CB-A3DC-8218EF546731/Library/Cookies/Cookies.binarycookies
,2016-09-21 07:48:07.390 ThaliTest[1229:1557574] Apache Cordova native platform version 4.2.1 is starting.
2016-09-21 07:48:07.392 ThaliTest[1229:1557574] Multi-tasking -> Device: YES, App: YES
,2016-09-21 07:48:07.413 ThaliTest[1229:1557574] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-21 07:48:07.836 ThaliTest[1229:1557574] Using UIWebView
,2016-09-21 07:48:07.846 ThaliTest[1229:1557574] [CDVTimer][handleopenurl] 0.328958ms
,2016-09-21 07:48:07.854 ThaliTest[1229:1557574] [CDVTimer][intentandnavigationfilter] 6.964982ms
2016-09-21 07:48:07.855 ThaliTest[1229:1557574] [CDVTimer][gesturehandler] 0.295997ms
2016-09-21 07:48:07.855 ThaliTest[1229:1557574] [CDVTimer][TotalPluginStartup] 9.232998ms
,2016-09-21 07:48:13.447 ThaliTest[1229:1557574] Resetting plugins due to page load.
,2016-09-21 07:48:13.996 ThaliTest[1229:1557574] Finished load of: file:///var/containers/Bundle/Application/61F5604F-CA05-4160-AF16-CBE1DC0CBB11/ThaliTest.app/www/index.html
,2016-09-21 07:48:14.411 ThaliTest[1229:1557574] JXcore Cordova plugin initializing
,2016-09-21 07:48:14.412 ThaliTest[1229:1557728] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-09-21 07:48:21.878 ThaliTest[1229:1557574] BTM: attaching to BTServer
,2016-09-21 07:48:33.132 ThaliTest[1229:1557574] BTM: local device power state changed
2016-09-21 07:48:33.132 ThaliTest[1229:1557574] BTM: power is now off
,received session: <ThaliCore.Session: 0x13f334a90>
,Optional("1CF5D0DF-2EC9-4E7A-9E80-6D1E4A7707F0")
,nil
,nil
,Optional("C15F7CFA-633A-44DC-AD02-4B00EB9F7600")
,Optional("2D80E9E3-B9BC-407B-B332-1B637EC1A5B9")
,*Native tests were executed*
,Total number of executed tests:  56
,Number of passed tests:  54
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  24.62450402975082
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
