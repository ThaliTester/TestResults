#### Test 9856377493d976a_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9856377493d976a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7BF133D0-DD41-4898-94B7-192DBE894F87/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/7BF133D0-DD41-4898-94B7-192DBE894F87/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9856377493d976a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9856377493d976a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0EA2591E-DAD3-4C9C-92DB-F1F267C72EFC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62909"
,(lldb)     command script import "/tmp/7BF133D0-DD41-4898-94B7-192DBE894F87/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 15:37:30.034 ThaliTest[742:1898467] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B9E4FAC8-E051-4DBB-AA64-F4D9B28CBC6A/Library/Cookies/Cookies.binarycookies
,2016-12-19 15:37:30.182 ThaliTest[742:1898467] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 15:37:30.185 ThaliTest[742:1898467] Multi-tasking -> Device: YES, App: YES
,2016-12-19 15:37:30.214 ThaliTest[742:1898467] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 15:37:30.963 ThaliTest[742:1898467] Using UIWebView
,2016-12-19 15:37:30.972 ThaliTest[742:1898467] [CDVTimer][handleopenurl] 0.446022ms
,2016-12-19 15:37:30.979 ThaliTest[742:1898467] [CDVTimer][intentandnavigationfilter] 7.075012ms
2016-12-19 15:37:30.980 ThaliTest[742:1898467] [CDVTimer][gesturehandler] 0.335991ms
2016-12-19 15:37:30.980 ThaliTest[742:1898467] [CDVTimer][TotalPluginStartup] 9.266019ms
,2016-12-19 15:37:41.474 ThaliTest[742:1898467] Resetting plugins due to page load.
,2016-12-19 15:37:42.251 ThaliTest[742:1898467] Finished load of: file:///var/containers/Bundle/Application/0EA2591E-DAD3-4C9C-92DB-F1F267C72EFC/ThaliTest.app/www/index.html
,2016-12-19 15:37:42.478 ThaliTest[742:1898467] JXcore Cordova plugin initializing
,2016-12-19 15:37:42.481 ThaliTest[742:1898636] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 14:38:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 14:38:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 14:38:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-19 14:38:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 14:38:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-19 14:38:47 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  28.96138000488281
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
