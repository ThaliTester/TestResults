#### Test 8504691186bae88_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CB4CC2F6-C258-4E9A-B995-6BC58B1B9A39/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/CB4CC2F6-C258-4E9A-B995-6BC58B1B9A39/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691186bae88/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3E01B92A-94EF-44FE-A39E-B0135F56A4E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54936"
,(lldb)     command script import "/tmp/CB4CC2F6-C258-4E9A-B995-6BC58B1B9A39/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-22 00:59:26.357 ThaliTest[1293:1641275] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E8ED9F1D-289A-4D56-98D6-310CD37FAAD2/Library/Cookies/Cookies.binarycookies
,2016-09-22 00:59:26.392 ThaliTest[1293:1641275] Apache Cordova native platform version 4.2.1 is starting.
2016-09-22 00:59:26.393 ThaliTest[1293:1641275] Multi-tasking -> Device: YES, App: YES
,2016-09-22 00:59:26.404 ThaliTest[1293:1641275] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-22 00:59:26.714 ThaliTest[1293:1641275] Using UIWebView
,2016-09-22 00:59:26.718 ThaliTest[1293:1641275] [CDVTimer][handleopenurl] 0.196040ms
,2016-09-22 00:59:26.721 ThaliTest[1293:1641275] [CDVTimer][intentandnavigationfilter] 3.450036ms
2016-09-22 00:59:26.722 ThaliTest[1293:1641275] [CDVTimer][gesturehandler] 0.156999ms
2016-09-22 00:59:26.722 ThaliTest[1293:1641275] [CDVTimer][TotalPluginS,tartup] 4.601002ms
,2016-09-22 00:59:32.522 ThaliTest[1293:1641275] Resetting plugins due to page load.
,2016-09-22 00:59:32.887 ThaliTest[1293:1641275] Finished load of: file:///var/containers/Bundle/Application/3E01B92A-94EF-44FE-A39E-B0135F56A4E2/ThaliTest.app/www/index.html
,2016-09-22 00:59:33.251 ThaliTest[1293:1641275] JXcore Cordova plugin initializing
,2016-09-22 00:59:33.251 ThaliTest[1293:1641614] JXcore instance initializing
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
,2016-09-22 00:59:40.649 ThaliTest[1293:1641275] BTM: attaching to BTServer
,2016-09-22 00:59:51.526 ThaliTest[1293:1641275] BTM: local device power state changed
2016-09-22 00:59:51.530 ThaliTest[1293:1641275] BTM: power is now on
,2016-09-22 00:59:56.254 ThaliTest[1293:1641275] BTM: local device power state changed
2016-09-22 00:59:56.259 ThaliTest[1293:1641275] BTM: power is now off
,received session: <ThaliCore.Session: 0x1294063c0>
,Optional("DB0E2AA1-8601-4602-90AF-96E63239681F")
,nil
,nil
,Optional("86DDFB3A-60C2-4DE8-BFA8-6BAEA2B5A690")
,Optional("07C8CE02-5C06-4414-BFAA-70CF22D23DB5")
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  48
,Number of failed tests:  2
,Number of ignored tests:  0
,Total duration:  30.02634996175766
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
