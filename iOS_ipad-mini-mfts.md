#### Test 993736745bf9b5a_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993736745bf9b5a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/0A8A6F40-006E-4041-8C30-3F1F2A756625/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/0A8A6F40-006E-4041-8C30-3F1F2A756625/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993736745bf9b5a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993736745bf9b5a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E1780579-A6DB-40EC-82C8-AA7AB66DB081/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63156"
,(lldb)     command script import "/tmp/0A8A6F40-006E-4041-8C30-3F1F2A756625/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-26 15:59:29.176 ThaliTest[955:2898236] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/29ED6331-598D-47A0-BD0E-99B9A6CD9C1F/Library/Cookies/Cookies.binarycookies
,2016-12-26 15:59:29.319 ThaliTest[955:2898236] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-26 15:59:29.322 ThaliTest[955:2898236] Multi-tasking -> Device: YES, App: YES
,2016-12-26 15:59:29.346 ThaliTest[955:2898236] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-26 15:59:29.984 ThaliTest[955:2898236] Using UIWebView
,2016-12-26 15:59:29.990 ThaliTest[955:2898236] [CDVTimer][handleopenurl] 0.478029ms
,2016-12-26 15:59:29.998 ThaliTest[955:2898236] [CDVTimer][intentandnavigationfilter] 7.472992ms
2016-12-26 15:59:29.999 ThaliTest[955:2898236] [CDVTimer][gesturehandler] 0.337005ms
2016-12-26 15:59:29.999 ThaliTest[955:2898236] [CDVTimer][TotalPluginStartup] 9.656966ms
,2016-12-26 15:59:38.917 ThaliTest[955:2898236] Resetting plugins due to page load.
,2016-12-26 15:59:39.603 ThaliTest[955:2898236] Finished load of: file:///var/containers/Bundle/Application/E1780579-A6DB-40EC-82C8-AA7AB66DB081/ThaliTest.app/www/index.html
,2016-12-26 15:59:39.870 ThaliTest[955:2898236] JXcore Cordova plugin initializing
,2016-12-26 15:59:39.872 ThaliTest[955:2898409] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 15:00:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 15:00:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 15:00:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-26 15:00:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 15:00:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 15:00:49 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  32.5147859454155
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
