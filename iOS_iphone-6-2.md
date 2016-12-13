#### Test 978514903f1da2e_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/94931114-C6A5-4295-B5F0-B3C64B6EF890/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/94931114-C6A5-4295-B5F0-B3C64B6EF890/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B9BD3DFB-D101-4B7D-B441-5065633A8A5F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59843"
,(lldb)     command script import "/tmp/94931114-C6A5-4295-B5F0-B3C64B6EF890/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 00:09:01.343 ThaliTest[711:848692] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0F24EC9F-DE08-4CF3-B649-34B90305D00C/Library/Cookies/Cookies.binarycookies
,2016-12-14 00:09:01.421 ThaliTest[711:848692] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 00:09:01.423 ThaliTest[711:848692] Multi-tasking -> Device: YES, App: YES
,2016-12-14 00:09:01.448 ThaliTest[711:848692] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 00:09:02.001 ThaliTest[711:848692] Using UIWebView
2016-12-14 00:09:02.008 ThaliTest[711:848692] [CDVTimer][handleopenurl] 0.302017ms
,2016-12-14 00:09:02.018 ThaliTest[711:848692] [CDVTimer][intentandnavigationfilter] 9.784043ms
2016-12-14 00:09:02.019 ThaliTest[711:848692] [CDVTimer][gesturehandler] 0.302017ms
2016-12-14 00:09:02.019 ThaliTest[711:848692] [CDVTimer][TotalPluginStartup,] 11.980951ms
,2016-12-14 00:09:07.843 ThaliTest[711:848692] Resetting plugins due to page load.
,2016-12-14 00:09:08.281 ThaliTest[711:848692] Finished load of: file:///var/containers/Bundle/Application/B9BD3DFB-D101-4B7D-B441-5065633A8A5F/ThaliTest.app/www/index.html
,2016-12-14 00:09:08.633 ThaliTest[711:848692] JXcore Cordova plugin initializing
,2016-12-14 00:09:08.634 ThaliTest[711:848882] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 23:09:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 23:09:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 23:09:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 23:09:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 23:09:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-13 23:09:46 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.49914199113846
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
