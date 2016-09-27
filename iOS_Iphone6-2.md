#### Test 85046911c0a96fd_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6D1B7715-67D7-4A82-9DC3-DFADD3546F80/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/6D1B7715-67D7-4A82-9DC3-DFADD3546F80/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911c0a96fd/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C72BEC79-CD57-4753-87E5-F73FDCC5B163/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56549"
,(lldb)     command script import "/tmp/6D1B7715-67D7-4A82-9DC3-DFADD3546F80/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-27 04:05:12.765 ThaliTest[1725:2231394] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/13D8E191-40C5-4B9F-AD7B-D31708FDD812/Library/Cookies/Cookies.binarycookies
,2016-09-27 04:05:12.856 ThaliTest[1725:2231394] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-27 04:05:12.859 ThaliTest[1725:2231394] Multi-tasking -> Device: YES, App: YES
,2016-09-27 04:05:12.879 ThaliTest[1725:2231394] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-27 04:05:13.372 ThaliTest[1725:2231394] Using UIWebView
,2016-09-27 04:05:13.382 ThaliTest[1725:2231394] [CDVTimer][handleopenurl] 0.422001ms
,2016-09-27 04:05:13.389 ThaliTest[1725:2231394] [CDVTimer][intentandnavigationfilter] 7.091999ms
2016-09-27 04:05:13.390 ThaliTest[1725:2231394] [CDVTimer][gesturehandler] 0.288963ms
2016-09-27 04:05:13.391 ThaliTest[1725:2231394] [CDVTimer][TotalPluginStartup] 9.463012ms
,2016-09-27 04:05:18.949 ThaliTest[1725:2231394] Resetting plugins due to page load.
,2016-09-27 04:05:19.362 ThaliTest[1725:2231394] Finished load of: file:///var/containers/Bundle/Application/C72BEC79-CD57-4753-87E5-F73FDCC5B163/ThaliTest.app/www/index.html
,2016-09-27 04:05:19.688 ThaliTest[1725:2231394] JXcore Cordova plugin initializing
,2016-09-27 04:05:19.688 ThaliTest[1725:2231562] JXcore instance initializing
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
,received session: <ThaliCore.Session: 0x13efd2920>
,Optional("210CABA5-C670-4E5F-ADBF-40DC9C5F6168")
nil
,nil
,Optional("ABDAD7A6-BF85-40BC-AEF5-29BDD2D9495D")
,Optional("E6B289DF-9541-4DF1-9ECA-BD9BAE9EF8A4")
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.32471495866776
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
