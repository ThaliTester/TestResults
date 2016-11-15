#### Test 9376531715755df_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/189923CC-E455-4BB1-8B82-9A4E036B33E0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/189923CC-E455-4BB1-8B82-9A4E036B33E0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9376531715755df/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EA8D7000-1C8A-47C7-B4B8-17EA7CA7015C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63798"
,(lldb)     command script import "/tmp/189923CC-E455-4BB1-8B82-9A4E036B33E0/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-15 09:29:20.714 ThaliTest[3510:7954929] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/ED12DFC3-43DB-45B9-8EB0-CED0B1DECECE/Library/Cookies/Cookies.binarycookies
,2016-11-15 09:29:20.754 ThaliTest[3510:7954929] Apache Cordova native platform version 4.2.1 is starting.
2016-11-15 09:29:20.755 ThaliTest[3510:7954929] Multi-tasking -> Device: YES, App: YES
,2016-11-15 09:29:20.768 ThaliTest[3510:7954929] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-15 09:29:21.080 ThaliTest[3510:7954929] Using UIWebView
2016-11-15 09:29:21.083 ThaliTest[3510:7954929] [CDVTimer][handleopenurl] 0.189006ms
2016-11-15 09:29:21.087 ThaliTest[3510:7954929] [CDVTimer][intentandnavigationfilter] 3.392041ms
,2016-11-15 09:29:21.088 ThaliTest[3510:7954929] [CDVTimer][gesturehandler] 1.183987ms
2016-11-15 09:29:21.088 ThaliTest[3510:7954929] [CDVTimer][TotalPluginStartup] 5.508006ms
,2016-11-15 09:29:27.094 ThaliTest[3510:7954929] Resetting plugins due to page load.
,2016-11-15 09:29:27.485 ThaliTest[3510:7954929] Finished load of: file:///var/containers/Bundle/Application/EA8D7000-1C8A-47C7-B4B8-17EA7CA7015C/ThaliTest.app/www/index.html
,2016-11-15 09:29:27.816 ThaliTest[3510:7954929] JXcore Cordova plugin initializing
2016-11-15 09:29:27.817 ThaliTest[3510:7955121] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-15 17:29:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-15 17:29:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-15 17:29:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-15 17:29:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-15 17:29:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
,2016-11-15 17:30:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  25.21254003047943
F,ailed to execute UT.
2016-11-15 17:30:03 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
```
