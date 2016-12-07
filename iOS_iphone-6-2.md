#### Test 965327534acc906_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/CBE63E03-B1E0-4B52-8DCE-4628932BB92A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/CBE63E03-B1E0-4B52-8DCE-4628932BB92A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/965327534acc906/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4D1AA5DB-FBA3-4992-B69F-B06566AB1253/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62985"
,(lldb)     command script import "/tmp/CBE63E03-B1E0-4B52-8DCE-4628932BB92A/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 14:16:05.704 ThaliTest[309:123746] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D91DF98B-BDD3-4F25-9510-7874AE1CE278/Library/Cookies/Cookies.binarycookies
,2016-12-07 14:16:05.743 ThaliTest[309:123746] Apache Cordova native platform version 4.3.1 is starting.
2016-12-07 14:16:05.744 ThaliTest[309:123746] Multi-tasking -> Device: YES, App: YES
,2016-12-07 14:16:05.756 ThaliTest[309:123746] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 14:16:06.100 ThaliTest[309:123746] Using UIWebView
,2016-12-07 14:16:06.105 ThaliTest[309:123746] [CDVTimer][handleopenurl] 0.209987ms
,2016-12-07 14:16:06.111 ThaliTest[309:123746] [CDVTimer][intentandnavigationfilter] 5.771041ms
2016-12-07 14:16:06.111 ThaliTest[309:123746] [CDVTimer][gesturehandler] 0.212967ms
2016-12-07 14:16:06.111 ThaliTest[309:123746] [CDVTimer][TotalPluginStartup,] 7.317007ms
,2016-12-07 14:16:11.988 ThaliTest[309:123746] Resetting plugins due to page load.
,2016-12-07 14:16:12.370 ThaliTest[309:123746] Finished load of: file:///var/containers/Bundle/Application/4D1AA5DB-FBA3-4992-B69F-B06566AB1253/ThaliTest.app/www/index.html
,2016-12-07 14:16:12.736 ThaliTest[309:123746] JXcore Cordova plugin initializing
,2016-12-07 14:16:12.737 ThaliTest[309:123958] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 13:16:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 13:16:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 13:16:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 13:16:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 13:16:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 13:16:47 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  24.07670700550079
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
