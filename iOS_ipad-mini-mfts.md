#### Test 10414824498b4517_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/77224FC9-55B1-49C7-91BA-598E6D389B75/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/77224FC9-55B1-49C7-91BA-598E6D389B75/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10414824498b4517/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6C83FB74-F73E-4F3B-B435-BFF9AA4C361B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55931"
,(lldb)     command script import "/tmp/77224FC9-55B1-49C7-91BA-598E6D389B75/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-02-02 17:43:52.060 ThaliTest[2179:8186766] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C9743E34-044D-4CA0-9EC4-582E4601EC63/Library/Cookies/Cookies.binarycookies
,2017-02-02 17:43:52.198 ThaliTest[2179:8186766] Apache Cordova native platform version 4.3.1 is starting.
,2017-02-02 17:43:52.201 ThaliTest[2179:8186766] Multi-tasking -> Device: YES, App: YES
,2017-02-02 17:43:52.225 ThaliTest[2179:8186766] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-02-02 17:43:53.009 ThaliTest[2179:8186766] Using UIWebView
,2017-02-02 17:43:53.015 ThaliTest[2179:8186766] [CDVTimer][handleopenurl] 0.564992ms
,2017-02-02 17:43:53.024 ThaliTest[2179:8186766] [CDVTimer][intentandnavigationfilter] 7.409990ms
2017-02-02 17:43:53.024 ThaliTest[2179:8186766] [CDVTimer][gesturehandler] 0.330985ms
2017-02-02 17:43:53.025 ThaliTest[2179:8186766] [CDVTimer][TotalPluginStartup] 9.896040ms
,2017-02-02 17:44:03.506 ThaliTest[2179:8186766] Resetting plugins due to page load.
,2017-02-02 17:44:04.307 ThaliTest[2179:8186766] Finished load of: file:///var/containers/Bundle/Application/6C83FB74-F73E-4F3B-B435-BFF9AA4C361B/ThaliTest.app/www/index.html
,2017-02-02 17:44:04.543 ThaliTest[2179:8186766] JXcore Cordova plugin initializing
,2017-02-02 17:44:04.545 ThaliTest[2179:8186934] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-02-02 16:44:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-02-02 16:44:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-02-02 16:44:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2017-02-02 16:44:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-02-02 16:44:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-02-02 16:45:20 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  34.66201001405716
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
