#### Test 98115565db523c3_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/5E5AEAB7-BC60-4746-AEAA-D059EC1EF350/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/5E5AEAB7-BC60-4746-AEAA-D059EC1EF350/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98115565db523c3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/55690C42-3FB5-41C1-86A2-EA2B80F7E5F3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49570"
,(lldb)     command script import "/tmp/5E5AEAB7-BC60-4746-AEAA-D059EC1EF350/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-15 12:12:29.924 ThaliTest[810:1032622] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4AEC1FDD-B01B-4A77-B3AA-23FC164F12A8/Library/Cookies/Cookies.binarycookies
,2016-12-15 12:12:30.008 ThaliTest[810:1032622] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 12:12:30.010 ThaliTest[810:1032622] Multi-tasking -> Device: YES, App: YES
,2016-12-15 12:12:30.031 ThaliTest[810:1032622] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 12:12:30.469 ThaliTest[810:1032622] Using UIWebView
,2016-12-15 12:12:30.476 ThaliTest[810:1032622] [CDVTimer][handleopenurl] 0.337005ms
,2016-12-15 12:12:30.486 ThaliTest[810:1032622] [CDVTimer][intentandnavigationfilter] 9.268999ms
2016-12-15 12:12:30.487 ThaliTest[810:1032622] [CDVTimer][gesturehandler] 0.340998ms
2016-12-15 12:12:30.487 ThaliTest[810:1032622] [CDVTimer][TotalPluginStartup] 11.789024ms
,2016-12-15 12:12:37.648 ThaliTest[810:1032622] Resetting plugins due to page load.
,2016-12-15 12:12:38.120 ThaliTest[810:1032622] Finished load of: file:///var/containers/Bundle/Application/55690C42-3FB5-41C1-86A2-EA2B80F7E5F3/ThaliTest.app/www/index.html
,2016-12-15 12:12:38.623 ThaliTest[810:1032622] JXcore Cordova plugin initializing
2016-12-15 12:12:38.624 ThaliTest[810:1032822] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 11:12:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 11:12:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 11:12:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-15 11:12:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 11:12:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-15 11:13:16 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.39890098571777
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
