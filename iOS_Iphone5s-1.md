#### Test 85046911920cb66_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/42ED703D-4C2B-474F-BA1D-7198C4684062/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/42ED703D-4C2B-474F-BA1D-7198C4684062/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911920cb66/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F7566BBE-C12B-4A5D-AA09-A1E9E6A63685/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61284"
,(lldb)     command script import "/tmp/42ED703D-4C2B-474F-BA1D-7198C4684062/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 10:04:48.988 ThaliTest[3421:6927163] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B6D038D6-5D13-48D8-B194-28F52A4EC19B/Library/Cookies/Cookies.binarycookies
,2016-09-28 10:04:49.100 ThaliTest[3421:6927163] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 10:04:49.102 ThaliTest[3421:6927163] Multi-tasking -> Device: YES, App: YES
,2016-09-28 10:04:49.125 ThaliTest[3421:6927163] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 10:04:51.097 ThaliTest[3421:6927163] Using UIWebView
,2016-09-28 10:04:51.105 ThaliTest[3421:6927163] [CDVTimer][handleopenurl] 0.521004ms
,2016-09-28 10:04:51.114 ThaliTest[3421:6927163] [CDVTimer][intentandnavigationfilter] 8.316994ms
2016-09-28 10:04:51.115 ThaliTest[3421:6927163] [CDVTimer][gesturehandler] 0.405014ms
2016-09-28 10:04:51.116 ThaliTest[3421:6927163] [CDVTimer][TotalPluginS,tartup] 11.045992ms
,2016-09-28 10:04:58.002 ThaliTest[3421:6927163] Resetting plugins due to page load.
,2016-09-28 10:05:02.386 ThaliTest[3421:6927163] Finished load of: file:///var/mobile/Containers/Bundle/Application/F7566BBE-C12B-4A5D-AA09-A1E9E6A63685/ThaliTest.app/www/index.html
,2016-09-28 10:05:02.581 ThaliTest[3421:6927163] JXcore Cordova plugin initializing
,2016-09-28 10:05:02.581 ThaliTest[3421:6927391] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x126c085b0>
,Optional("56205A3E-1A19-47E7-B336-DD2BF5F0627F")
,nil
,nil
,Optional("A65C053E-8A61-4542-B1D5-9DB14F87936C")
,Optional("C97FB863-A73F-457A-B736-C5D902CDAD15")
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.57839900255203
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
