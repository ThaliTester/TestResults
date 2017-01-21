#### Test 102585911579949a_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/8C593FFF-82DD-499D-B74D-644F6FBEE94A/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/8C593FFF-82DD-499D-B74D-644F6FBEE94A/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F15E03D1-C9FF-43A7-90D7-465E4C71D252/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62951"
,(lldb)     command script import "/tmp/8C593FFF-82DD-499D-B74D-644F6FBEE94A/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-21 17:00:03.371 ThaliTest[544:1123898] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5E057F04-B455-4008-A0F6-F0727ABE1E60/Library/Cookies/Cookies.binarycookies
,2017-01-21 17:00:03.463 ThaliTest[544:1123898] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-21 17:00:03.465 ThaliTest[544:1123898] Multi-tasking -> Device: YES, App: YES
,2017-01-21 17:00:03.485 ThaliTest[544:1123898] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-21 17:00:04.094 ThaliTest[544:1123898] Using UIWebView
,2017-01-21 17:00:04.103 ThaliTest[544:1123898] [CDVTimer][handleopenurl] 0.415027ms
,2017-01-21 17:00:04.114 ThaliTest[544:1123898] [CDVTimer][intentandnavigationfilter] 10.836005ms
2017-01-21 17:00:04.115 ThaliTest[544:1123898] [CDVTimer][gesturehandler] 0.388980ms
2017-01-21 17:00:04.115 ThaliTest[544:1123898] [CDVTimer][TotalPluginStartup] 13.579011ms
,2017-01-21 17:00:10.943 ThaliTest[544:1123898] Resetting plugins due to page load.
,2017-01-21 17:00:11.497 ThaliTest[544:1123898] Finished load of: file:///var/containers/Bundle/Application/F15E03D1-C9FF-43A7-90D7-465E4C71D252/ThaliTest.app/www/index.html
,2017-01-21 17:00:11.924 ThaliTest[544:1123898] JXcore Cordova plugin initializing
2017-01-21 17:00:11.925 ThaliTest[544:1124107] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-21 16:00:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-21 16:00:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-21 16:00:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-21 16:00:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-21 16:00:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-21 16:00:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.13857597112656
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).

```
