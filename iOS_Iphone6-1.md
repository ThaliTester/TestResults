#### Test 82914073713e010_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/80822B0B-3A7C-46E5-A79F-DD51806CEA49/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/80822B0B-3A7C-46E5-A79F-DD51806CEA49/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/82914073713e010/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E3BFF1B4-3E7D-4787-8042-7AF900FE3860/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60828"
,(lldb)     command script import "/tmp/80822B0B-3A7C-46E5-A79F-DD51806CEA49/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 18:56:32.677 ThaliTest[739:892185] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3E8DBB79-CEE1-4D81-AF29-B80E970E54B1/Library/Cookies/Cookies.binarycookies
,2016-09-15 18:56:32.716 ThaliTest[739:892185] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 18:56:32.717 ThaliTest[739:892185] Multi-tasking -> Device: YES, App: YES
,2016-09-15 18:56:32.728 ThaliTest[739:892185] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 18:56:33.052 ThaliTest[739:892185] Using UIWebView
,2016-09-15 18:56:33.055 ThaliTest[739:892185] [CDVTimer][handleopenurl] 0.187993ms
,2016-09-15 18:56:33.059 ThaliTest[739:892185] [CDVTimer][intentandnavigationfilter] 3.543973ms
2016-09-15 18:56:33.059 ThaliTest[739:892185] [CDVTimer][gesturehandler] 0.159979ms
2016-09-15 18:56:33.059 ThaliTest[739:892185] [CDVTimer][TotalPluginStartup,] 4.714012ms
,2016-09-15 18:56:38.381 ThaliTest[739:892185] Resetting plugins due to page load.
,2016-09-15 18:56:38.796 ThaliTest[739:892185] Finished load of: file:///var/containers/Bundle/Application/E3BFF1B4-3E7D-4787-8042-7AF900FE3860/ThaliTest.app/www/index.html
,2016-09-15 18:56:39.262 ThaliTest[739:892185] JXcore Cordova plugin initializing
,2016-09-15 18:56:39.263 ThaliTest[739:892356] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
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
,received session: <ThaliCore.Session: 0x13804f350>
,8081F5A0-F636-41F8-82E2-33C5EA090DC7
Optional("8081F5A0-F636-41F8-82E2-33C5EA090DC7")
nil
,nil
,
,91951435-C1A9-4472-A867-B0533BC53441
Optional("91951435-C1A9-4472-A867-B0533BC53441")
E18EA3DB-1B18-4E19-85E8-F8ABC3DCEA54
Optional("E18EA3DB-1B18-4E19-85E8-F8ABC3DCEA54")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-09-15 18:56:57.789 ThaliTest[739:892185] BTM: attaching to BTServer
,2016-09-15 18:56:59.906 ThaliTest[739:892185] BTM: local device power state changed
2016-09-15 18:56:59.907 ThaliTest[739:892185] BTM: power is now off
,2016-09-15 18:57:00.661 ThaliTest[739:892185] BTM: local device power state changed
2016-09-15 18:57:00.661 ThaliTest[739:892185] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  46
Number of passed tests:  46
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  14.04378497600555
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteringBackgroun
```
