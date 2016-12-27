#### Test 99373674dc17873_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/DDFAA8F3-FDE3-4384-8E0B-93E9693B8D03/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/DDFAA8F3-FDE3-4384-8E0B-93E9693B8D03/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99373674dc17873/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BC26DF2E-9C99-45AE-93F3-4EE0BA1FF22E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56605"
,(lldb)     command script import "/tmp/DDFAA8F3-FDE3-4384-8E0B-93E9693B8D03/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 10:51:52.249 ThaliTest[1383:2521988] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A8955FD4-B000-4366-A1C5-F0D7FA57F8D6/Library/Cookies/Cookies.binarycookies
,2016-12-27 10:51:52.353 ThaliTest[1383:2521988] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 10:51:52.355 ThaliTest[1383:2521988] Multi-tasking -> Device: YES, App: YES
,2016-12-27 10:51:52.380 ThaliTest[1383:2521988] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 10:51:52.804 ThaliTest[1383:2521988] Using UIWebView
,2016-12-27 10:51:52.814 ThaliTest[1383:2521988] [CDVTimer][handleopenurl] 0.347018ms
,2016-12-27 10:51:52.823 ThaliTest[1383:2521988] [CDVTimer][intentandnavigationfilter] 8.224010ms
2016-12-27 10:51:52.823 ThaliTest[1383:2521988] [CDVTimer][gesturehandler] 0.292003ms
2016-12-27 10:51:52.824 ThaliTest[1383:2521988] [CDVTimer][TotalPluginS,tartup] 10.514975ms
,2016-12-27 10:51:59.707 ThaliTest[1383:2521988] Resetting plugins due to page load.
,2016-12-27 10:52:00.253 ThaliTest[1383:2521988] Finished load of: file:///var/containers/Bundle/Application/BC26DF2E-9C99-45AE-93F3-4EE0BA1FF22E/ThaliTest.app/www/index.html
,2016-12-27 10:52:00.618 ThaliTest[1383:2521988] JXcore Cordova plugin initializing
,2016-12-27 10:52:00.619 ThaliTest[1383:2522158] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 09:52:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 09:52:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 09:52:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-27 09:52:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 09:52:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,XCTAssertNil failed: "ConnectionFailed" -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/SocketConnectionTests/TCPListenerTests.swift"), line: 340
,2016-12-27 09:52:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  24.95196896791458
F,ailed to execute UT.
2016-12-27 09:52:36 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
