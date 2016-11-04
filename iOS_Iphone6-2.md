#### Test 8962479671c5ab8_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/AFD9E194-B291-4A0A-85D2-3BFE8D467750/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/AFD9E194-B291-4A0A-85D2-3BFE8D467750/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E04E0C08-97FD-4FA3-9B1E-4549CE717CC3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49244"
,(lldb)     command script import "/tmp/AFD9E194-B291-4A0A-85D2-3BFE8D467750/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-04 06:14:44.306 ThaliTest[3012:6558449] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A1FF5FA7-DBFB-4294-9F3B-10210AC712AB/Library/Cookies/Cookies.binarycookies
,2016-11-04 06:14:44.397 ThaliTest[3012:6558449] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-04 06:14:44.399 ThaliTest[3012:6558449] Multi-tasking -> Device: YES, App: YES
,2016-11-04 06:14:44.418 ThaliTest[3012:6558449] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-04 06:14:44.927 ThaliTest[3012:6558449] Using UIWebView
,2016-11-04 06:14:44.937 ThaliTest[3012:6558449] [CDVTimer][handleopenurl] 0.473022ms
,2016-11-04 06:14:44.945 ThaliTest[3012:6558449] [CDVTimer][intentandnavigationfilter] 7.296979ms
2016-11-04 06:14:44.946 ThaliTest[3012:6558449] [CDVTimer][gesturehandler] 0.330985ms
2016-11-04 06:14:44.946 ThaliTest[3012:6558449] [CDVTimer][TotalPluginStartup] 9.832978ms
,2016-11-04 06:14:51.192 ThaliTest[3012:6558449] Resetting plugins due to page load.
,2016-11-04 06:14:51.605 ThaliTest[3012:6558449] Finished load of: file:///var/containers/Bundle/Application/E04E0C08-97FD-4FA3-9B1E-4549CE717CC3/ThaliTest.app/www/index.html
,2016-11-04 06:14:51.953 ThaliTest[3012:6558449] JXcore Cordova plugin initializing
,2016-11-04 06:14:51.954 ThaliTest[3012:6558634] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-04 13:15:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-04 13:15:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-04 13:15:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-04 13:15:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-04 13:15:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found two advertisers". in file: Optional("<unknown>"), line: 0
,XCTAssertEqual failed: ("nil") is not equal to ("Optional(1)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 224
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-04 13:15:43 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  113
Number of failed tests:  3
Number of ignored tests:  0
Total duration:  40.95925396680832
F,ailed to execute UT.
2016-11-04 13:15:43 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
