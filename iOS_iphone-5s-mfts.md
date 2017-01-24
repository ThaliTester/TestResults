#### Test 102706742b5bb046_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102706742b5bb046/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/95509219-64CA-4AF7-8111-F622AB9D92B0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/95509219-64CA-4AF7-8111-F622AB9D92B0/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102706742b5bb046/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102706742b5bb046/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/79F2E358-3569-44D6-A8EC-D24ABE1EFEBD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57866"
,(lldb)     command script import "/tmp/95509219-64CA-4AF7-8111-F622AB9D92B0/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 09:42:50.751 ThaliTest[658:1487479] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6A5FAA92-D7AB-4973-9CCE-57D641350BD7/Library/Cookies/Cookies.binarycookies
,2017-01-24 09:42:50.843 ThaliTest[658:1487479] Apache Cordova native platform version 4.3.1 is starting.
2017-01-24 09:42:50.845 ThaliTest[658:1487479] Multi-tasking -> Device: YES, App: YES
,2017-01-24 09:42:50.869 ThaliTest[658:1487479] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 09:42:51.469 ThaliTest[658:1487479] Using UIWebView
,2017-01-24 09:42:51.478 ThaliTest[658:1487479] [CDVTimer][handleopenurl] 0.428975ms
,2017-01-24 09:42:51.489 ThaliTest[658:1487479] [CDVTimer][intentandnavigationfilter] 10.286987ms
2017-01-24 09:42:51.489 ThaliTest[658:1487479] [CDVTimer][gesturehandler] 0.261009ms
2017-01-24 09:42:51.490 ThaliTest[658:1487479] [CDVTimer][TotalPluginStartup] 12.658000ms
,2017-01-24 09:42:58.594 ThaliTest[658:1487479] Resetting plugins due to page load.
,2017-01-24 09:42:59.083 ThaliTest[658:1487479] Finished load of: file:///var/containers/Bundle/Application/79F2E358-3569-44D6-A8EC-D24ABE1EFEBD/ThaliTest.app/www/index.html
,2017-01-24 09:42:59.566 ThaliTest[658:1487479] JXcore Cordova plugin initializing
,2017-01-24 09:42:59.567 ThaliTest[658:1487678] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 08:43:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-24 08:43:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 08:43:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-24 08:43:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-24 08:43:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-24 08:43:38 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.25146001577377
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
