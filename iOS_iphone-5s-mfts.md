#### Test 9945185497797f9_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9945185497797f9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/68C74D43-F6BF-436A-80FA-DB62849853DE/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/68C74D43-F6BF-436A-80FA-DB62849853DE/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9945185497797f9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9945185497797f9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/47EF7CBF-463B-431E-ACB6-8FF0C957C82F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53693"
,(lldb)     command script import "/tmp/68C74D43-F6BF-436A-80FA-DB62849853DE/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 16:20:11.584 ThaliTest[1298:2481145] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A53071CF-2388-4B46-B632-BF0D7DC5E94B/Library/Cookies/Cookies.binarycookies
,2016-12-27 16:20:11.635 ThaliTest[1298:2481145] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 16:20:11.637 ThaliTest[1298:2481145] Multi-tasking -> Device: YES, App: YES
,2016-12-27 16:20:11.651 ThaliTest[1298:2481145] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 16:20:11.982 ThaliTest[1298:2481145] Using UIWebView
,2016-12-27 16:20:11.987 ThaliTest[1298:2481145] [CDVTimer][handleopenurl] 0.202000ms
,2016-12-27 16:20:11.992 ThaliTest[1298:2481145] [CDVTimer][intentandnavigationfilter] 4.854023ms
2016-12-27 16:20:11.992 ThaliTest[1298:2481145] [CDVTimer][gesturehandler] 0.189960ms
2016-12-27 16:20:11.992 ThaliTest[1298:2481145] [CDVTimer][TotalPluginS,tartup] 6.236017ms
,2016-12-27 16:20:17.897 ThaliTest[1298:2481145] Resetting plugins due to page load.
,2016-12-27 16:20:18.267 ThaliTest[1298:2481145] Finished load of: file:///var/containers/Bundle/Application/47EF7CBF-463B-431E-ACB6-8FF0C957C82F/ThaliTest.app/www/index.html
,2016-12-27 16:20:18.672 ThaliTest[1298:2481145] JXcore Cordova plugin initializing
,2016-12-27 16:20:18.674 ThaliTest[1298:2481317] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 15:20:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 15:20:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 15:20:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-27 15:20:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 15:20:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-27 15:21:14 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  42.1321730017662
,Failed to execute UT.
,2016-12-27 15:21:14 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
