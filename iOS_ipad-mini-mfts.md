#### Test 983548825638cdd_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/69F09EBC-DFF6-466C-BB04-A49D96D3A5A8/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/69F09EBC-DFF6-466C-BB04-A49D96D3A5A8/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F7B14FC7-BF2E-4E51-B744-8E907D173560/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57977"
,(lldb)     command script import "/tmp/69F09EBC-DFF6-466C-BB04-A49D96D3A5A8/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 14:11:11.560 ThaliTest[726:1886446] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9D795A2F-68CF-456B-ADF6-3BAB6973A38F/Library/Cookies/Cookies.binarycookies
,2016-12-19 14:11:11.699 ThaliTest[726:1886446] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 14:11:11.702 ThaliTest[726:1886446] Multi-tasking -> Device: YES, App: YES
,2016-12-19 14:11:11.731 ThaliTest[726:1886446] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 14:11:12.512 ThaliTest[726:1886446] Using UIWebView
,2016-12-19 14:11:12.518 ThaliTest[726:1886446] [CDVTimer][handleopenurl] 0.467002ms
,2016-12-19 14:11:12.526 ThaliTest[726:1886446] [CDVTimer][intentandnavigationfilter] 7.347047ms
2016-12-19 14:11:12.526 ThaliTest[726:1886446] [CDVTimer][gesturehandler] 0.328004ms
2016-12-19 14:11:12.527 ThaliTest[726:1886446] [CDVTimer][TotalPluginStar,tup] 9.492993ms
,2016-12-19 14:11:23.097 ThaliTest[726:1886446] Resetting plugins due to page load.
,2016-12-19 14:11:23.876 ThaliTest[726:1886446] Finished load of: file:///var/containers/Bundle/Application/F7B14FC7-BF2E-4E51-B744-8E907D173560/ThaliTest.app/www/index.html
,2016-12-19 14:11:24.108 ThaliTest[726:1886446] JXcore Cordova plugin initializing
,2016-12-19 14:11:24.110 ThaliTest[726:1886843] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 13:11:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 13:11:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 13:11:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-19 13:11:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 13:11:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-19 13:12:28 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  28.47083097696304
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
