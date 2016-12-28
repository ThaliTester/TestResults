#### Test 99530606d5b5815_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/1D5E7B49-25FE-4C0F-87AD-A668AF8E95E9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/1D5E7B49-25FE-4C0F-87AD-A668AF8E95E9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606d5b5815/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8A5B4B83-BA2A-42C9-9734-5AC40D9B56A1/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49362"
,(lldb)     command script import "/tmp/1D5E7B49-25FE-4C0F-87AD-A668AF8E95E9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 16:33:33.229 ThaliTest[1518:2695310] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F5AD1259-FDE2-4EA1-8F22-9A9926719A4B/Library/Cookies/Cookies.binarycookies
,2016-12-28 16:33:33.280 ThaliTest[1518:2695310] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 16:33:33.281 ThaliTest[1518:2695310] Multi-tasking -> Device: YES, App: YES
,2016-12-28 16:33:33.293 ThaliTest[1518:2695310] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 16:33:33.619 ThaliTest[1518:2695310] Using UIWebView
,2016-12-28 16:33:33.624 ThaliTest[1518:2695310] [CDVTimer][handleopenurl] 0.235975ms
,2016-12-28 16:33:33.629 ThaliTest[1518:2695310] [CDVTimer][intentandnavigationfilter] 5.068004ms
2016-12-28 16:33:33.630 ThaliTest[1518:2695310] [CDVTimer][gesturehandler] 0.156999ms
2016-12-28 16:33:33.630 ThaliTest[1518:2695310] [CDVTimer][TotalPluginStartup] 6.412983ms
,2016-12-28 16:33:39.418 ThaliTest[1518:2695310] Resetting plugins due to page load.
,2016-12-28 16:33:39.753 ThaliTest[1518:2695310] Finished load of: file:///var/containers/Bundle/Application/8A5B4B83-BA2A-42C9-9734-5AC40D9B56A1/ThaliTest.app/www/index.html
,2016-12-28 16:33:40.091 ThaliTest[1518:2695310] JXcore Cordova plugin initializing
2016-12-28 16:33:40.092 ThaliTest[1518:2695534] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 15:33:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 15:33:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 15:33:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-28 15:33:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 15:33:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 15:34:15 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.08330804109573
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
