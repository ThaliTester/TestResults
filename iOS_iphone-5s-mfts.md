#### Test 99448283f49b3a7_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F047861A-09E9-4476-AB8D-BE0BEB8128E4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/F047861A-09E9-4476-AB8D-BE0BEB8128E4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99448283f49b3a7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/925016A6-82CF-4652-B8EF-1333D2942537/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51148"
,(lldb)     command script import "/tmp/F047861A-09E9-4476-AB8D-BE0BEB8128E4/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-28 16:58:28.645 ThaliTest[1396:2613777] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F368AF3C-C132-4A03-91F8-CD55B83B4F4E/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:58:28.692 ThaliTest[1396:2613777] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:58:28.693 ThaliTest[1396:2613777] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:58:28.709 ThaliTest[1396:2613777] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:58:29.046 ThaliTest[1396:2613777] Using UIWebView
,2016-12-28 16:58:29.051 ThaliTest[1396:2613777] [CDVTimer][handleopenurl] 0.415027ms
,2016-12-28 16:58:29.059 ThaliTest[1396:2613777] [CDVTimer][intentandnavigationfilter] 7.215023ms
2016-12-28 16:58:29.059 ThaliTest[1396:2613777] [CDVTimer][gesturehandler] 0.248969ms
2016-12-28 16:58:29.060 ThaliTest[1396:2613777] [CDVTimer][TotalPluginS,tartup] 9.196997ms
,2016-12-28 16:58:34.980 ThaliTest[1396:2613777] Resetting plugins due to page load.
,2016-12-28 16:58:35.402 ThaliTest[1396:2613777] Finished load of: file:///var/containers/Bundle/Application/925016A6-82CF-4652-B8EF-1333D2942537/ThaliTest.app/www/index.html
,2016-12-28 16:58:35.795 ThaliTest[1396:2613777] JXcore Cordova plugin initializing
,2016-12-28 16:58:35.796 ThaliTest[1396:2613951] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:58:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:58:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:58:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-28 15:58:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:58:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 15:59:14 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.90181201696396
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
