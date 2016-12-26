#### Test 993736741c2a2c8_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993736741c2a2c8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AB42229D-B309-4F10-80B8-93391A3B1F1D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/AB42229D-B309-4F10-80B8-93391A3B1F1D/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993736741c2a2c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993736741c2a2c8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/02845F8D-542A-4F9A-B91D-C862A0F3E518/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51618"
,(lldb)     command script import "/tmp/AB42229D-B309-4F10-80B8-93391A3B1F1D/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 17:24:27.456 ThaliTest[1332:2425785] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5216A448-3B95-4F5E-B4CD-A12E7A0043BC/Library/Cookies/Cookies.binarycookies
,2016-12-26 17:24:27.498 ThaliTest[1332:2425785] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 17:24:27.500 ThaliTest[1332:2425785] Multi-tasking -> Device: YES, App: YES
,2016-12-26 17:24:27.512 ThaliTest[1332:2425785] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 17:24:27.855 ThaliTest[1332:2425785] Using UIWebView
,2016-12-26 17:24:27.860 ThaliTest[1332:2425785] [CDVTimer][handleopenurl] 0.230014ms
,2016-12-26 17:24:27.867 ThaliTest[1332:2425785] [CDVTimer][intentandnavigationfilter] 5.783975ms
2016-12-26 17:24:27.867 ThaliTest[1332:2425785] [CDVTimer][gesturehandler] 0.198007ms
2016-12-26 17:24:27.867 ThaliTest[1332:2425785] [CDVTimer][TotalPluginS,tartup] 7.335007ms
,2016-12-26 17:24:33.525 ThaliTest[1332:2425785] Resetting plugins due to page load.
,2016-12-26 17:24:33.926 ThaliTest[1332:2425785] Finished load of: file:///var/containers/Bundle/Application/02845F8D-542A-4F9A-B91D-C862A0F3E518/ThaliTest.app/www/index.html
,2016-12-26 17:24:34.257 ThaliTest[1332:2425785] JXcore Cordova plugin initializing
,2016-12-26 17:24:34.258 ThaliTest[1332:2425968] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 16:24:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 16:24:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 16:24:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-26 16:24:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 16:24:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-26 16:25:11 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.39660996198654
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
