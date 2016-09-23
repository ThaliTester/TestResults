#### Test 85046911dcbf444_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/88CAA3AF-F752-4887-9EEC-6F62A121A9DD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/88CAA3AF-F752-4887-9EEC-6F62A121A9DD/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911dcbf444/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A4C40CBC-94B3-4A58-A301-46A7BC73DCC6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61767"
,(lldb)     command script import "/tmp/88CAA3AF-F752-4887-9EEC-6F62A121A9DD/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 23:39:27.412 ThaliTest[1417:1754963] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/736BBC3A-F636-4D39-9B1E-00620B8F9BFF/Library/Cookies/Cookies.binarycookies
,2016-09-22 23:39:27.493 ThaliTest[1417:1754963] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-22 23:39:27.495 ThaliTest[1417:1754963] Multi-tasking -> Device: YES, App: YES
,2016-09-22 23:39:27.521 ThaliTest[1417:1754963] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 23:39:27.991 ThaliTest[1417:1754963] Using UIWebView
,2016-09-22 23:39:28.001 ThaliTest[1417:1754963] [CDVTimer][handleopenurl] 0.371993ms
,2016-09-22 23:39:28.009 ThaliTest[1417:1754963] [CDVTimer][intentandnavigationfilter] 7.694006ms
2016-09-22 23:39:28.010 ThaliTest[1417:1754963] [CDVTimer][gesturehandler] 0.293970ms
2016-09-22 23:39:28.010 ThaliTest[1417:1754963] [CDVTimer][TotalPluginStartup] 10.163963ms
,2016-09-22 23:39:33.730 ThaliTest[1417:1754963] Resetting plugins due to page load.
,2016-09-22 23:39:34.196 ThaliTest[1417:1754963] Finished load of: file:///var/containers/Bundle/Application/A4C40CBC-94B3-4A58-A301-46A7BC73DCC6/ThaliTest.app/www/index.html
,2016-09-22 23:39:34.541 ThaliTest[1417:1754963] JXcore Cordova plugin initializing
,2016-09-22 23:39:34.542 ThaliTest[1417:1755151] JXcore instance initializing
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
Optional(false)
,Optional(false)
Optional(true)
,2016-09-22 23:39:41.912 ThaliTest[1417:1754963] BTM: attaching to BTServer
,2016-09-22 23:39:42.672 ThaliTest[1417:1754963] BTM: local device power state changed
,2016-09-22 23:39:42.686 ThaliTest[1417:1754963] BTM: power is now on
,2016-09-22 23:39:47.411 ThaliTest[1417:1754963] BTM: local device power state changed
2016-09-22 23:39:47.416 ThaliTest[1417:1754963] BTM: power is now off
,*Native tests were executed*
Total number of executed tests:  7
Number of passed tests:  7
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  5.664224028587341
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
