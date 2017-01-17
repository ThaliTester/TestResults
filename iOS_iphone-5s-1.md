#### Test 101910573e732e55_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/101910573e732e55/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/F7A273DC-19EF-4CE1-82BC-8009847C7C08/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F7A273DC-19EF-4CE1-82BC-8009847C7C08/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/101910573e732e55/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/101910573e732e55/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/42F27020-3EA2-45CC-9B40-8BFABFA70C7A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58856"
,(lldb)     command script import "/tmp/F7A273DC-19EF-4CE1-82BC-8009847C7C08/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-17 19:05:27.364 ThaliTest[2454:6000629] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/164F1F74-0767-459D-9E25-3406B27B0B7E/Library/Cookies/Cookies.binarycookies
,2017-01-17 19:05:27.443 ThaliTest[2454:6000629] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-17 19:05:27.444 ThaliTest[2454:6000629] Multi-tasking -> Device: YES, App: YES
,2017-01-17 19:05:27.466 ThaliTest[2454:6000629] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-17 19:05:28.307 ThaliTest[2454:6000629] Using UIWebView
2017-01-17 19:05:28.311 ThaliTest[2454:6000629] [CDVTimer][handleopenurl] 0.163972ms
2017-01-17 19:05:28.316 ThaliTest[2454:6000629] [CDVTimer][intentandnavigationfilter] 4.715025ms
2017-01-17 19:05:28.316 ThaliTest[2454:6000629] [CDVTimer][gesturehandler] 0.149012ms
2017-01-17 19:05:28.316 ThaliTest[2454:6000629] [CDVTimer][TotalPluginStartup] 5.744040ms
,2017-01-17 19:05:31.650 ThaliTest[2454:6000629] Resetting plugins due to page load.
,2017-01-17 19:05:33.493 ThaliTest[2454:6000629] Finished load of: file:///var/mobile/Containers/Bundle/Application/42F27020-3EA2-45CC-9B40-8BFABFA70C7A/ThaliTest.app/www/index.html
,2017-01-17 19:05:33.705 ThaliTest[2454:6000629] JXcore Cordova plugin initializing
,2017-01-17 19:05:33.706 ThaliTest[2454:6000834] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-17 18:05:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-17 18:05:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-17 18:05:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2017-01-17 18:05:49 - DEBUG thaliMobileNativeWrapper: 'Metho,d networkChanged registered to native'
2017-01-17 18:05:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-17 18:06:14 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.7224839925766
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
