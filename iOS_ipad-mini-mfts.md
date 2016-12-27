#### Test 99448283c38bc5f_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/024291B9-F862-41BA-8A5C-EE96A1005343/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/024291B9-F862-41BA-8A5C-EE96A1005343/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99448283c38bc5f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D7F69902-B790-4A53-9FE5-AF639B03257D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52000"
,(lldb)     command script import "/tmp/024291B9-F862-41BA-8A5C-EE96A1005343/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 15:50:28.738 ThaliTest[1030:3052308] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/83881D9D-3683-4484-8B9C-503F4FAFE640/Library/Cookies/Cookies.binarycookies
,2016-12-27 15:50:28.885 ThaliTest[1030:3052308] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 15:50:28.887 ThaliTest[1030:3052308] Multi-tasking -> Device: YES, App: YES
,2016-12-27 15:50:28.911 ThaliTest[1030:3052308] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 15:50:29.559 ThaliTest[1030:3052308] Using UIWebView
,2016-12-27 15:50:29.565 ThaliTest[1030:3052308] [CDVTimer][handleopenurl] 0.503957ms
,2016-12-27 15:50:29.573 ThaliTest[1030:3052308] [CDVTimer][intentandnavigationfilter] 7.113039ms
2016-12-27 15:50:29.573 ThaliTest[1030:3052308] [CDVTimer][gesturehandler] 0.361979ms
2016-12-27 15:50:29.574 ThaliTest[1030:3052308] [CDVTimer][TotalPluginStartup] 9.341002ms
,2016-12-27 15:50:38.326 ThaliTest[1030:3052308] Resetting plugins due to page load.
,2016-12-27 15:50:39.009 ThaliTest[1030:3052308] Finished load of: file:///var/containers/Bundle/Application/D7F69902-B790-4A53-9FE5-AF639B03257D/ThaliTest.app/www/index.html
,2016-12-27 15:50:39.244 ThaliTest[1030:3052308] JXcore Cordova plugin initializing
,2016-12-27 15:50:39.246 ThaliTest[1030:3052486] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 14:51:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 14:51:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 14:51:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-27 14:51:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 14:51:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 14:51:49 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  33.93330198526382
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
