#### Test 98312760b2c4df9_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/9AC9E541-54F8-4E9B-B2D3-BC72CAEC05BF/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/9AC9E541-54F8-4E9B-B2D3-BC72CAEC05BF/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98312760b2c4df9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/049BC5BA-DC9C-463F-A0DD-B37C30C266A0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61376"
,(lldb)     command script import "/tmp/9AC9E541-54F8-4E9B-B2D3-BC72CAEC05BF/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 15:12:39.717 ThaliTest[737:1894967] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F3D293DD-911E-4897-ABED-57D6EA79FF7C/Library/Cookies/Cookies.binarycookies
,2016-12-19 15:12:39.850 ThaliTest[737:1894967] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 15:12:39.852 ThaliTest[737:1894967] Multi-tasking -> Device: YES, App: YES
,2016-12-19 15:12:39.878 ThaliTest[737:1894967] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 15:12:40.522 ThaliTest[737:1894967] Using UIWebView
,2016-12-19 15:12:40.530 ThaliTest[737:1894967] [CDVTimer][handleopenurl] 0.445962ms
,2016-12-19 15:12:40.538 ThaliTest[737:1894967] [CDVTimer][intentandnavigationfilter] 7.185996ms
2016-12-19 15:12:40.539 ThaliTest[737:1894967] [CDVTimer][gesturehandler] 0.370979ms
2016-12-19 15:12:40.539 ThaliTest[737:1894967] [CDVTimer][TotalPluginStartup] 9.365022ms
,2016-12-19 15:12:49.528 ThaliTest[737:1894967] Resetting plugins due to page load.
,2016-12-19 15:12:50.206 ThaliTest[737:1894967] Finished load of: file:///var/containers/Bundle/Application/049BC5BA-DC9C-463F-A0DD-B37C30C266A0/ThaliTest.app/www/index.html
,2016-12-19 15:12:50.442 ThaliTest[737:1894967] JXcore Cordova plugin initializing
,2016-12-19 15:12:50.443 ThaliTest[737:1895121] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 14:13:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-19 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 14:13:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-19 14:13:55 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  28.80076801776886
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
