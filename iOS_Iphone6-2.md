#### Test 8326889394d960a_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/525C8E76-2D82-482B-BAB1-4C69DAA742ED/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/525C8E76-2D82-482B-BAB1-4C69DAA742ED/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889394d960a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1D8DE230-C84F-4446-A4AA-A0614EB88CE6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53758"
,(lldb)     command script import "/tmp/525C8E76-2D82-482B-BAB1-4C69DAA742ED/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 06:06:31.673 ThaliTest[941:1001478] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/AE860640-724C-4895-88B8-AE59A150E741/Library/Cookies/Cookies.binarycookies
,2016-09-16 06:06:31.747 ThaliTest[941:1001478] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 06:06:31.748 ThaliTest[941:1001478] Multi-tasking -> Device: YES, App: YES
,2016-09-16 06:06:31.765 ThaliTest[941:1001478] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 06:06:32.226 ThaliTest[941:1001478] Using UIWebView
,2016-09-16 06:06:32.233 ThaliTest[941:1001478] [CDVTimer][handleopenurl] 0.356019ms
,2016-09-16 06:06:32.241 ThaliTest[941:1001478] [CDVTimer][intentandnavigationfilter] 7.203996ms
2016-09-16 06:06:32.241 ThaliTest[941:1001478] [CDVTimer][gesturehandler] 0.259995ms
2016-09-16 06:06:32.242 ThaliTest[941:1001478] [CDVTimer][TotalPluginStar,tup] 9.341002ms
,2016-09-16 06:06:37.917 ThaliTest[941:1001478] Resetting plugins due to page load.
,2016-09-16 06:06:38.442 ThaliTest[941:1001478] Finished load of: file:///var/containers/Bundle/Application/1D8DE230-C84F-4446-A4AA-A0614EB88CE6/ThaliTest.app/www/index.html
,2016-09-16 06:06:38.844 ThaliTest[941:1001478] JXcore Cordova plugin initializing
,2016-09-16 06:06:38.844 ThaliTest[941:1001641] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x14d6db070>
,D8695C00-C51A-4A94-91E7-85C329CEDF26
Optional("D8695C00-C51A-4A94-91E7-85C329CEDF26")
nil
,nil

F1CB864A-EB8C-4133-9AAE-ADFC4A4C4BCC
Optional("F1CB864A-EB8C-4133-9AAE-ADFC4A4C4BCC")
0107651F-33F4-4F5C-8365-7C12872A90AA
Optional("0107651F-33F4-4F5C-8365-7C12872A90AA")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-09-16 06:06:57.495 ThaliTest[941:1001478] BTM: attaching to BTServer
,2016-09-16 06:06:58.649 ThaliTest[941:1001478] BTM: local device power state changed
2016-09-16 06:06:58.650 ThaliTest[941:1001478] BTM: power is now off
,2016-09-16 06:06:59.435 ThaliTest[941:1001478] BTM: local device power state changed
2016-09-16 06:06:59.436 ThaliTest[941:1001478] BTM: power is now on
,*Native tests were executed*
Total number of executed tests:  52
Number of passed tests:  52
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  13.33812600374222
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
