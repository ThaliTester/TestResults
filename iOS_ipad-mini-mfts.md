#### Test 98312760e1b00a5_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7DBE5012-CDA5-4B71-B747-5E0D582DBDD0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/7DBE5012-CDA5-4B71-B747-5E0D582DBDD0/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98312760e1b00a5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/38196B10-CB80-425B-A240-D0A6BF7A395D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56318"
,(lldb)     command script import "/tmp/7DBE5012-CDA5-4B71-B747-5E0D582DBDD0/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success,
,(lldb)     autoexit
,2016-12-19 13:17:05.675 ThaliTest[720:1880325] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E318B758-7E53-4D8F-BBD9-B6D24BCB48A5/Library/Cookies/Cookies.binarycookies
,2016-12-19 13:17:05.810 ThaliTest[720:1880325] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 13:17:05.813 ThaliTest[720:1880325] Multi-tasking -> Device: YES, App: YES
,2016-12-19 13:17:05.844 ThaliTest[720:1880325] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 13:17:06.591 ThaliTest[720:1880325] Using UIWebView
,2016-12-19 13:17:06.597 ThaliTest[720:1880325] [CDVTimer][handleopenurl] 0.486016ms
,2016-12-19 13:17:06.605 ThaliTest[720:1880325] [CDVTimer][intentandnavigationfilter] 7.342994ms
2016-12-19 13:17:06.606 ThaliTest[720:1880325] [CDVTimer][gesturehandler] 0.396013ms
2016-12-19 13:17:06.606 ThaliTest[720:1880325] [CDVTimer][TotalPluginStartup] 9.698987ms
,2016-12-19 13:17:17.284 ThaliTest[720:1880325] Resetting plugins due to page load.
,2016-12-19 13:17:18.069 ThaliTest[720:1880325] Finished load of: file:///var/containers/Bundle/Application/38196B10-CB80-425B-A240-D0A6BF7A395D/ThaliTest.app/www/index.html
,2016-12-19 13:17:18.304 ThaliTest[720:1880325] JXcore Cordova plugin initializing
,2016-12-19 13:17:18.306 ThaliTest[720:1880491] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 12:17:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 12:17:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 12:17:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-19 12:17:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 12:17:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-19 12:18:38 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  115
,Number of failed tests:  1
,Number of ignored tests:  0
,Total duration:  44.3301540017128
,Failed to execute UT.
,2016-12-19 12:18:38 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
