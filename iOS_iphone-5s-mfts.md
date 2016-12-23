#### Test 992612784a4c081_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992612784a4c081/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/8976377D-5EFA-47D2-88D1-64934163C05F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/8976377D-5EFA-47D2-88D1-64934163C05F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992612784a4c081/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992612784a4c081/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4D44E99E-2A92-4ED6-9F62-4FF2F14DCCC8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57415"
,(lldb)     command script import "/tmp/8976377D-5EFA-47D2-88D1-64934163C05F/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-23 18:10:52.964 ThaliTest[1097:2009367] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0043BBBF-1CEF-4EFA-8AAD-2A2F7BAD27E5/Library/Cookies/Cookies.binarycookies
,2016-12-23 18:10:53.056 ThaliTest[1097:2009367] Apache Cordova native platform version 4.3.1 is starting.
2016-12-23 18:10:53.058 ThaliTest[1097:2009367] Multi-tasking -> Device: YES, App: YES
,2016-12-23 18:10:53.077 ThaliTest[1097:2009367] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-23 18:10:53.403 ThaliTest[1097:2009367] Using UIWebView
,2016-12-23 18:10:53.408 ThaliTest[1097:2009367] [CDVTimer][handleopenurl] 0.370979ms
,2016-12-23 18:10:53.414 ThaliTest[1097:2009367] [CDVTimer][intentandnavigationfilter] 5.366981ms
2016-12-23 18:10:53.414 ThaliTest[1097:2009367] [CDVTimer][gesturehandler] 0.189006ms
2016-12-23 18:10:53.414 ThaliTest[1097:2009367] [CDVTimer][TotalPluginS,tartup] 6.955028ms
,2016-12-23 18:10:59.825 ThaliTest[1097:2009367] Resetting plugins due to page load.
,2016-12-23 18:11:00.336 ThaliTest[1097:2009367] Finished load of: file:///var/containers/Bundle/Application/4D44E99E-2A92-4ED6-9F62-4FF2F14DCCC8/ThaliTest.app/www/index.html
,2016-12-23 18:11:00.723 ThaliTest[1097:2009367] JXcore Cordova plugin initializing
,2016-12-23 18:11:00.724 ThaliTest[1097:2009549] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-23 17:11:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-23 17:11:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-23 17:11:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-23 17:11:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-23 17:11:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-23 17:11:38 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.70939099788666
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
