#### Test 100139766aeece48_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/100139766aeece48/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F70B19B2-49A9-4B6F-93D1-CF0E28E7EC8C/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/F70B19B2-49A9-4B6F-93D1-CF0E28E7EC8C/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/100139766aeece48/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/100139766aeece48/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/AC46ECCC-C9D2-4C61-A5AD-828E3617E23E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61903"
,(lldb)     command script import "/tmp/F70B19B2-49A9-4B6F-93D1-CF0E28E7EC8C/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-05 16:59:43.610 ThaliTest[1326:4343208] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF0829FD-CC58-4C7B-850D-6E082BF46DF9/Library/Cookies/Cookies.binarycookies
,2017-01-05 16:59:43.771 ThaliTest[1326:4343208] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-05 16:59:43.774 ThaliTest[1326:4343208] Multi-tasking -> Device: YES, App: YES
,2017-01-05 16:59:43.802 ThaliTest[1326:4343208] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-05 16:59:44.290 ThaliTest[1326:4343208] Using UIWebView
,2017-01-05 16:59:44.296 ThaliTest[1326:4343208] [CDVTimer][handleopenurl] 0.590980ms
2017-01-05 16:59:44.304 ThaliTest[1326:4343208] [CDVTimer][intentandnavigationfilter] 7.581949ms
2017-01-05 16:59:44.304 ThaliTest[1326:4343208] [CDVTimer][gesturehandler] 0.349998ms
2017-01-05 16:59:44.305 ThaliTest[1326:4343208] [CDVTimer][TotalPluginStartup] 9.850979ms
,2017-01-05 16:59:51.217 ThaliTest[1326:4343208] Resetting plugins due to page load.
,2017-01-05 16:59:51.778 ThaliTest[1326:4343208] Finished load of: file:///var/containers/Bundle/Application/AC46ECCC-C9D2-4C61-A5AD-828E3617E23E/ThaliTest.app/www/index.html
,2017-01-05 16:59:52.025 ThaliTest[1326:4343208] JXcore Cordova plugin initializing
2017-01-05 16:59:52.027 ThaliTest[1326:4343358] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-05 16:00:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-05 16:00:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-05 16:00:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
2017-01-05 16:00:26 - DEBUG thaliMobileNativeWrapper: ,'Method networkChanged registered to native'
2017-01-05 16:00:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-05 16:01:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  36.39585500955582
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
