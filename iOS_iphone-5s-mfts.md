#### Test 98312760e1b00a5_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/720B0B48-C3EB-4E85-8089-1D7EF8ADB377/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/720B0B48-C3EB-4E85-8089-1D7EF8ADB377/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F5F93D51-E654-463B-A2DF-EA822564EDBA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56322"
,(lldb)     command script import "/tmp/720B0B48-C3EB-4E85-8089-1D7EF8ADB377/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 13:17:52.491 ThaliTest[889:1512729] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CC160DBD-0513-4486-B1B6-9973397E5BD8/Library/Cookies/Cookies.binarycookies
,2016-12-19 13:17:52.578 ThaliTest[889:1512729] Apache Cordova native platform version 4.3.1 is starting.
2016-12-19 13:17:52.580 ThaliTest[889:1512729] Multi-tasking -> Device: YES, App: YES
,2016-12-19 13:17:52.606 ThaliTest[889:1512729] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 13:17:52.968 ThaliTest[889:1512729] Using UIWebView
,2016-12-19 13:17:52.974 ThaliTest[889:1512729] [CDVTimer][handleopenurl] 0.297010ms
,2016-12-19 13:17:52.982 ThaliTest[889:1512729] [CDVTimer][intentandnavigationfilter] 7.689953ms
2016-12-19 13:17:52.983 ThaliTest[889:1512729] [CDVTimer][gesturehandler] 0.250995ms
2016-12-19 13:17:52.983 ThaliTest[889:1512729] [CDVTimer][TotalPluginStar,tup] 9.768009ms
,2016-12-19 13:17:58.887 ThaliTest[889:1512729] Resetting plugins due to page load.
,2016-12-19 13:17:59.220 ThaliTest[889:1512729] Finished load of: file:///var/containers/Bundle/Application/F5F93D51-E654-463B-A2DF-EA822564EDBA/ThaliTest.app/www/index.html
,2016-12-19 13:17:59.624 ThaliTest[889:1512729] JXcore Cordova plugin initializing
,2016-12-19 13:17:59.625 ThaliTest[889:1512939] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 12:18:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 12:18:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 12:18:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-19 12:18:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 12:18:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-19 12:18:53 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  40.58474797010422
,Failed to execute UT.
,2016-12-19 12:18:53 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
