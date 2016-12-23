#### Test 992481310a19089_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992481310a19089/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/E41B3D68-4586-44FB-BAC0-D573EF45AF08/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/E41B3D68-4586-44FB-BAC0-D573EF45AF08/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992481310a19089/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992481310a19089/build_ios/ThaliTest.app' (arm64).
,(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/589F4C1D-4FB2-4415-8731-490528B9F394/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55553"
,(lldb)     command script import "/tmp/E41B3D68-4586-44FB-BAC0-D573EF45AF08/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-23 16:22:17.526 ThaliTest[861:2474535] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A2BFC7BC-CE1E-4E58-B6A5-A93DC714E9E9/Library/Cookies/Cookies.binarycookies
,2016-12-23 16:22:17.666 ThaliTest[861:2474535] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-23 16:22:17.669 ThaliTest[861:2474535] Multi-tasking -> Device: YES, App: YES
,2016-12-23 16:22:17.693 ThaliTest[861:2474535] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-23 16:22:18.469 ThaliTest[861:2474535] Using UIWebView
,2016-12-23 16:22:18.475 ThaliTest[861:2474535] [CDVTimer][handleopenurl] 0.615001ms
,2016-12-23 16:22:18.483 ThaliTest[861:2474535] [CDVTimer][intentandnavigationfilter] 7.234991ms
2016-12-23 16:22:18.484 ThaliTest[861:2474535] [CDVTimer][gesturehandler] 0.364006ms
2016-12-23 16:22:18.484 ThaliTest[861:2474535] [CDVTimer][TotalPluginStartup] 9.581983ms
,2016-12-23 16:22:29.003 ThaliTest[861:2474535] Resetting plugins due to page load.
,2016-12-23 16:22:29.790 ThaliTest[861:2474535] Finished load of: file:///var/containers/Bundle/Application/589F4C1D-4FB2-4415-8731-490528B9F394/ThaliTest.app/www/index.html
,2016-12-23 16:22:30.022 ThaliTest[861:2474535] JXcore Cordova plugin initializing
,2016-12-23 16:22:30.024 ThaliTest[861:2474717] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-23 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-23 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-23 15:23:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-23 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-23 15:23:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-23 15:23:38 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  31.41024798154831
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
