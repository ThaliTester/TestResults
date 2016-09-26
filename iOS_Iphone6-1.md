#### Test 867085185d3628e_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/867085185d3628e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8F92DF55-D692-4A37-9C9B-C5A196B5ACCE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/8F92DF55-D692-4A37-9C9B-C5A196B5ACCE/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/867085185d3628e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/867085185d3628e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8CD1C198-EF31-4D76-A855-35AAE71E213C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55905"
,(lldb)     command script import "/tmp/8F92DF55-D692-4A37-9C9B-C5A196B5ACCE/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-26 21:32:27.030 ThaliTest[1476:2293717] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/28AA830D-6A61-4FB0-8467-67200389080E/Library/Cookies/Cookies.binarycookies
,2016-09-26 21:32:27.103 ThaliTest[1476:2293717] Apache Cordova native platform version 4.2.1 is starting.
2016-09-26 21:32:27.105 ThaliTest[1476:2293717] Multi-tasking -> Device: YES, App: YES
,2016-09-26 21:32:27.123 ThaliTest[1476:2293717] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-26 21:32:27.619 ThaliTest[1476:2293717] Using UIWebView
,2016-09-26 21:32:27.627 ThaliTest[1476:2293717] [CDVTimer][handleopenurl] 0.871003ms
,2016-09-26 21:32:27.635 ThaliTest[1476:2293717] [CDVTimer][intentandnavigationfilter] 7.755995ms
2016-09-26 21:32:27.636 ThaliTest[1476:2293717] [CDVTimer][gesturehandler] 0.293016ms
2016-09-26 21:32:27.636 ThaliTest[1476:2293717] [CDVTimer][TotalPluginStartup] 10.527015ms
,2016-09-26 21:32:32.783 ThaliTest[1476:2293717] Resetting plugins due to page load.
,2016-09-26 21:32:33.127 ThaliTest[1476:2293717] Finished load of: file:///var/containers/Bundle/Application/8CD1C198-EF31-4D76-A855-35AAE71E213C/ThaliTest.app/www/index.html
,2016-09-26 21:32:33.458 ThaliTest[1476:2293717] JXcore Cordova plugin initializing
,2016-09-26 21:32:33.459 ThaliTest[1476:2293895] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x1391ead60>
,Optional("60BEC9F3-9A5C-413C-BFD3-CF032A0E89E6")
,nil
,nil
,Optional("6FD2D723-68C6-438C-B257-7F540C0DBF02")
,Optional("D796EAD0-4842-444E-919F-B480E88D2D17")
,*Native tests were executed*
Total number of executed tests:  55
Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  14.1902340054512
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
