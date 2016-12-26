#### Test 993736741c2a2c8_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993736741c2a2c8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7F622F86-AB6F-47BE-9CF0-3A4F6A2744E6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/7F622F86-AB6F-47BE-9CF0-3A4F6A2744E6/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993736741c2a2c8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993736741c2a2c8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0B517596-BB3B-469C-AF32-D5745B52FE23/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51265"
,(lldb)     command script import "/tmp/7F622F86-AB6F-47BE-9CF0-3A4F6A2744E6/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-12-26 17:23:14.053 ThaliTest[967:2909135] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/36CF0018-1E7F-4904-8650-0C94367236D5/Library/Cookies/Cookies.binarycookies
,2016-12-26 17:23:14.210 ThaliTest[967:2909135] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 17:23:14.213 ThaliTest[967:2909135] Multi-tasking -> Device: YES, App: YES
,2016-12-26 17:23:14.243 ThaliTest[967:2909135] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 17:23:14.876 ThaliTest[967:2909135] Using UIWebView
,2016-12-26 17:23:14.883 ThaliTest[967:2909135] [CDVTimer][handleopenurl] 0.597954ms
,2016-12-26 17:23:14.890 ThaliTest[967:2909135] [CDVTimer][intentandnavigationfilter] 7.259011ms
2016-12-26 17:23:14.891 ThaliTest[967:2909135] [CDVTimer][gesturehandler] 0.370026ms
2016-12-26 17:23:14.891 ThaliTest[967:2909135] [CDVTimer][TotalPluginStar,tup] 9.598017ms
,2016-12-26 17:23:23.559 ThaliTest[967:2909135] Resetting plugins due to page load.
,2016-12-26 17:23:24.240 ThaliTest[967:2909135] Finished load of: file:///var/containers/Bundle/Application/0B517596-BB3B-469C-AF32-D5745B52FE23/ThaliTest.app/www/index.html
,2016-12-26 17:23:24.474 ThaliTest[967:2909135] JXcore Cordova plugin initializing
,2016-12-26 17:23:24.476 ThaliTest[967:2909291] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 16:23:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 16:23:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 16:24:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-26 16:24:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 16:24:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 16:24:34 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.8713670372963
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
