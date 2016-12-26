#### Test 99247393a8ecbf4_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99247393a8ecbf4/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/00DDC377-C7C4-4DFB-B7E1-0A6084A3697F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/00DDC377-C7C4-4DFB-B7E1-0A6084A3697F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/99247393a8ecbf4/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99247393a8ecbf4/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/686FC851-BC24-4C44-A431-714FCE0B691A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61220"
,(lldb)     command script import "/tmp/00DDC377-C7C4-4DFB-B7E1-0A6084A3697F/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 11:47:32.510 ThaliTest[1167:2325247] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7FA47B2B-A63E-4FF4-B217-C455DB2CE053/Library/Cookies/Cookies.binarycookies
,2016-12-26 11:47:32.559 ThaliTest[1167:2325247] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 11:47:32.560 ThaliTest[1167:2325247] Multi-tasking -> Device: YES, App: YES
,2016-12-26 11:47:32.574 ThaliTest[1167:2325247] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 11:47:32.897 ThaliTest[1167:2325247] Using UIWebView
,2016-12-26 11:47:32.902 ThaliTest[1167:2325247] [CDVTimer][handleopenurl] 0.227988ms
,2016-12-26 11:47:32.908 ThaliTest[1167:2325247] [CDVTimer][intentandnavigationfilter] 5.640984ms
2016-12-26 11:47:32.909 ThaliTest[1167:2325247] [CDVTimer][gesturehandler] 0.189960ms
2016-12-26 11:47:32.909 ThaliTest[1167:2325247] [CDVTimer][TotalPluginS,tartup] 7.063985ms
,2016-12-26 11:47:40.073 ThaliTest[1167:2325247] Resetting plugins due to page load.
,2016-12-26 11:47:40.728 ThaliTest[1167:2325247] Finished load of: file:///var/containers/Bundle/Application/686FC851-BC24-4C44-A431-714FCE0B691A/ThaliTest.app/www/index.html
,2016-12-26 11:47:41.218 ThaliTest[1167:2325247] JXcore Cordova plugin initializing
,2016-12-26 11:47:41.219 ThaliTest[1167:2325413] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 10:47:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 10:47:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 10:47:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-26 10:47:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 10:47:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-26 10:48:18 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.28128403425217
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
