#### Test 9953060646c88db_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/32FA8B07-A065-4716-A2FC-6D57219C86E3/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/32FA8B07-A065-4716-A2FC-6D57219C86E3/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FA2100D6-9356-4104-B467-D31CC9BEAA4C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59066"
,(lldb)     command script import "/tmp/32FA8B07-A065-4716-A2FC-6D57219C86E3/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 11:52:10.382 ThaliTest[1355:2582874] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/18EE3A52-E200-4190-BF40-C920E6AF9B2D/Library/Cookies/Cookies.binarycookies
,2016-12-28 11:52:10.436 ThaliTest[1355:2582874] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 11:52:10.438 ThaliTest[1355:2582874] Multi-tasking -> Device: YES, App: YES
,2016-12-28 11:52:10.453 ThaliTest[1355:2582874] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 11:52:10.782 ThaliTest[1355:2582874] Using UIWebView
,2016-12-28 11:52:10.786 ThaliTest[1355:2582874] [CDVTimer][handleopenurl] 0.256002ms
,2016-12-28 11:52:10.792 ThaliTest[1355:2582874] [CDVTimer][intentandnavigationfilter] 5.419016ms
2016-12-28 11:52:10.792 ThaliTest[1355:2582874] [CDVTimer][gesturehandler] 0.191033ms
2016-12-28 11:52:10.793 ThaliTest[1355:2582874] [CDVTimer][TotalPluginStartup] 6.980002ms
,2016-12-28 11:52:16.938 ThaliTest[1355:2582874] Resetting plugins due to page load.
,2016-12-28 11:52:17.415 ThaliTest[1355:2582874] Finished load of: file:///var/containers/Bundle/Application/FA2100D6-9356-4104-B467-D31CC9BEAA4C/ThaliTest.app/www/index.html
,2016-12-28 11:52:17.814 ThaliTest[1355:2582874] JXcore Cordova plugin initializing
,2016-12-28 11:52:17.815 ThaliTest[1355:2583062] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 10:52:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 10:52:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 10:52:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-28 10:52:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 10:52:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 10:53:12 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  40.86723798513412
,Failed to execute UT.
,2016-12-28 10:53:12 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
