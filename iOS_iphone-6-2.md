#### Test 9965213169fe96d_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/B69C9EAB-36EF-47FC-8B33-003243609BF3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/B69C9EAB-36EF-47FC-8B33-003243609BF3/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9965213169fe96d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F0B459CB-844D-4A7E-94BF-AFC3C816059C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63264"
,(lldb)     command script import "/tmp/B69C9EAB-36EF-47FC-8B33-003243609BF3/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-12-29 14:37:44.927 ThaliTest[1587:2819803] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B37E98A3-5757-4CDB-A387-864ACD2CE425/Library/Cookies/Cookies.binarycookies
,2016-12-29 14:37:44.966 ThaliTest[1587:2819803] Apache Cordova native platform version 4.3.1 is starting.
2016-12-29 14:37:44.967 ThaliTest[1587:2819803] Multi-tasking -> Device: YES, App: YES
,2016-12-29 14:37:44.983 ThaliTest[1587:2819803] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 14:37:45.294 ThaliTest[1587:2819803] Using UIWebView
,2016-12-29 14:37:45.297 ThaliTest[1587:2819803] [CDVTimer][handleopenurl] 0.231981ms
,2016-12-29 14:37:45.302 ThaliTest[1587:2819803] [CDVTimer][intentandnavigationfilter] 4.410028ms
2016-12-29 14:37:45.303 ThaliTest[1587:2819803] [CDVTimer][gesturehandler] 0.180006ms
2016-12-29 14:37:45.303 ThaliTest[1587:2819803] [CDVTimer][TotalPluginS,tartup] 5.647004ms
,2016-12-29 14:37:50.966 ThaliTest[1587:2819803] Resetting plugins due to page load.
,2016-12-29 14:37:51.282 ThaliTest[1587:2819803] Finished load of: file:///var/containers/Bundle/Application/F0B459CB-844D-4A7E-94BF-AFC3C816059C/ThaliTest.app/www/index.html
,2016-12-29 14:37:51.619 ThaliTest[1587:2819803] JXcore Cordova plugin initializing
2016-12-29 14:37:51.619 ThaliTest[1587:2819996] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 13:38:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 13:38:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 13:38:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-29 13:38:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 13:38:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-29 13:38:29 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.01622700691223
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
