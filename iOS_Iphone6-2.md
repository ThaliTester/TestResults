#### Test 8712674671a25ec_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/879BF87D-230D-4EEC-81DC-2C5BE7B4B617/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/879BF87D-230D-4EEC-81DC-2C5BE7B4B617/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8712674671a25ec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/08E8AE36-7190-4909-95F2-E95AD079829D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64211"
,(lldb)     command script import "/tmp/879BF87D-230D-4EEC-81DC-2C5BE7B4B617/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-29 00:40:43.077 ThaliTest[1846:2433870] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1A8D6B77-DC7C-4DC5-ADD7-90B3FC72D304/Library/Cookies/Cookies.binarycookies
,2016-09-29 00:40:43.118 ThaliTest[1846:2433870] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-29 00:40:43.119 ThaliTest[1846:2433870] Multi-tasking -> Device: YES, App: YES
,2016-09-29 00:40:43.131 ThaliTest[1846:2433870] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-29 00:40:43.458 ThaliTest[1846:2433870] Using UIWebView
,2016-09-29 00:40:43.463 ThaliTest[1846:2433870] [CDVTimer][handleopenurl] 0.262976ms
,2016-09-29 00:40:43.467 ThaliTest[1846:2433870] [CDVTimer][intentandnavigationfilter] 3.875971ms
2016-09-29 00:40:43.467 ThaliTest[1846:2433870] [CDVTimer][gesturehandler] 0.137985ms
2016-09-29 00:40:43.468 ThaliTest[1846:2433870] [CDVTimer][TotalPluginStartup] 5.207002ms
,2016-09-29 00:40:49.218 ThaliTest[1846:2433870] Resetting plugins due to page load.
,2016-09-29 00:40:49.720 ThaliTest[1846:2433870] Finished load of: file:///var/containers/Bundle/Application/08E8AE36-7190-4909-95F2-E95AD079829D/ThaliTest.app/www/index.html
,2016-09-29 00:40:50.092 ThaliTest[1846:2433870] JXcore Cordova plugin initializing
,2016-09-29 00:40:50.092 ThaliTest[1846:2434031] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x15702d370>
,Optional("4F148AF4-F206-4B5E-94A7-6BA036F45D95")
nil
,nil
,Optional("037081D2-60EB-4CE7-A433-26A731D66EDF")
,Optional("D26DF7A6-8AC6-4922-BDFE-401E60CB93A9")
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  13.72766298055649
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
