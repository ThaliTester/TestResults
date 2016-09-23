#### Test 864825827cea8e2_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4B82DAC8-B245-434F-BEE6-E33F57BBA170/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/4B82DAC8-B245-434F-BEE6-E33F57BBA170/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/864825827cea8e2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A5E3B242-E514-4AEC-A6D2-E27611C1FE77/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61172"
,(lldb)     command script import "/tmp/4B82DAC8-B245-434F-BEE6-E33F57BBA170/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 13:11:20.567 ThaliTest[1314:1877471] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6D30E8F2-21AB-4BAA-8629-86704712517D/Library/Cookies/Cookies.binarycookies
,2016-09-23 13:11:20.608 ThaliTest[1314:1877471] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 13:11:20.609 ThaliTest[1314:1877471] Multi-tasking -> Device: YES, App: YES
,2016-09-23 13:11:20.622 ThaliTest[1314:1877471] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 13:11:20.978 ThaliTest[1314:1877471] Using UIWebView
,2016-09-23 13:11:20.983 ThaliTest[1314:1877471] [CDVTimer][handleopenurl] 0.338972ms
,2016-09-23 13:11:20.988 ThaliTest[1314:1877471] [CDVTimer][intentandnavigationfilter] 4.755974ms
2016-09-23 13:11:20.989 ThaliTest[1314:1877471] [CDVTimer][gesturehandler] 0.200033ms
2016-09-23 13:11:20.989 ThaliTest[1314:1877471] [CDVTimer][TotalPluginStartup] 6.407022ms
,2016-09-23 13:11:26.419 ThaliTest[1314:1877471] Resetting plugins due to page load.
,2016-09-23 13:11:26.793 ThaliTest[1314:1877471] Finished load of: file:///var/containers/Bundle/Application/A5E3B242-E514-4AEC-A6D2-E27611C1FE77/ThaliTest.app/www/index.html
,2016-09-23 13:11:27.123 ThaliTest[1314:1877471] JXcore Cordova plugin initializing
,2016-09-23 13:11:27.125 ThaliTest[1314:1877643] JXcore instance initializing
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
,2016-09-23 13:11:34.714 ThaliTest[1314:1877471] BTM: attaching to BTServer
,2016-09-23 13:11:35.456 ThaliTest[1314:1877471] BTM: local device power state changed
2016-09-23 13:11:35.457 ThaliTest[1314:1877471] BTM: power is now on
,2016-09-23 13:11:40.206 ThaliTest[1314:1877471] BTM: local device power state changed
2016-09-23 13:11:40.210 ThaliTest[1314:1877471] BTM: power is now off
,received session: <ThaliCore.Session: 0x13650f6b0>
,Asynchronous wait failed: Exceeded timeout of 2 seconds, with unfulfilled expectations: "found peer advertiser's identifier". in file: Optional("<unknown>"), line: 0
,XCTAssertEqual failed: ("nil") is not equal to ("Optional(true)") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/MultipeerConnectivityTests/BrowserManagerTests.swift"), line: 176
XCTAssert,Equal failed: ("Optional(ThaliCore.PeerIdentifier(uuid: "2DA3186D-CF6C-4BF0-A263-4FF02B0FBF1C", generation: 0))") is not equal to ("nil") -  in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Mult,ipeerConnectivityTests/BrowserManagerTests.swift"), line: 177
,Optional("106D8957-6E70-441B-AD97-E61A07DDEEA0")
nil
,nil
,Optional("4AA3D301-ACF0-4861-8DDE-403C11C7E74C")
,Optional("F0EA2AA1-3AA4-4C20-B29E-C20024DC3247")
,*Native tests were executed*
Total number of executed tests:  50
,Number of passed tests:  47
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  20.87764799594879
,Failed to execute UT.
,****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****

```
