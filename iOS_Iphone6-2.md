#### Test 937653172c2e8c7_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/5E2443DB-0652-4D74-99BE-2CDF5E0D195B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/5E2443DB-0652-4D74-99BE-2CDF5E0D195B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6A8CD2A5-C846-4573-B638-23CD5424060C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51266"
,(lldb)     command script import "/tmp/5E2443DB-0652-4D74-99BE-2CDF5E0D195B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 02:51:58.714 ThaliTest[3605:8172077] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DA252048-6143-4204-A76B-52136090EEBD/Library/Cookies/Cookies.binarycookies
,2016-11-17 02:51:58.751 ThaliTest[3605:8172077] Apache Cordova native platform version 4.2.1 is starting.
2016-11-17 02:51:58.752 ThaliTest[3605:8172077] Multi-tasking -> Device: YES, App: YES
,2016-11-17 02:51:58.767 ThaliTest[3605:8172077] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 02:51:59.092 ThaliTest[3605:8172077] Using UIWebView
,2016-11-17 02:51:59.095 ThaliTest[3605:8172077] [CDVTimer][handleopenurl] 0.222981ms
,2016-11-17 02:51:59.099 ThaliTest[3605:8172077] [CDVTimer][intentandnavigationfilter] 3.335953ms
2016-11-17 02:51:59.099 ThaliTest[3605:8172077] [CDVTimer][gesturehandler] 0.164986ms
2016-11-17 02:51:59.100 ThaliTest[3605:8172077] [CDVTimer][TotalPluginStartup] 4.561007ms
,2016-11-17 02:52:04.641 ThaliTest[3605:8172077] Resetting plugins due to page load.
,2016-11-17 02:52:05.093 ThaliTest[3605:8172077] Finished load of: file:///var/containers/Bundle/Application/6A8CD2A5-C846-4573-B638-23CD5424060C/ThaliTest.app/www/index.html
,2016-11-17 02:52:05.434 ThaliTest[3605:8172077] JXcore Cordova plugin initializing
2016-11-17 02:52:05.434 ThaliTest[3605:8172253] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 10:52:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 10:52:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 10:52:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 10:52:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 10:52:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected disconnect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 44
failed - Unexpected disconnect received on socket <GCDAsy,ncSocket: 0x135d653c0> in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 56
,Asynchronous wait failed: Exceeded timeout of 10 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-17 10:52:51 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  113
,Number of failed tests:  3
,Number of ignored tests:  0
,Total duration:  35.66062700748444
,Failed to execute UT.
,2016-11-17 10:52:51 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
