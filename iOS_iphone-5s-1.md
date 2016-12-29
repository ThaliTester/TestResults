#### Test 9967484811caee1_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/9C44EFBF-5DEC-40AB-8701-8D6E863271A9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9C44EFBF-5DEC-40AB-8701-8D6E863271A9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9967484811caee1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3C807C4F-EF66-42B3-85B4-0C1285071BB0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50013"
,(lldb)     command script import "/tmp/9C44EFBF-5DEC-40AB-8701-8D6E863271A9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 18:13:41.558 ThaliTest[1692:3540279] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D241335A-D3CF-4C52-A0C8-B8BEEAE1163F/Library/Cookies/Cookies.binarycookies
,2016-12-29 18:13:41.676 ThaliTest[1692:3540279] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 18:13:41.678 ThaliTest[1692:3540279] Multi-tasking -> Device: YES, App: YES
,2016-12-29 18:13:41.701 ThaliTest[1692:3540279] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 18:13:43.062 ThaliTest[1692:3540279] Using UIWebView
,2016-12-29 18:13:43.070 ThaliTest[1692:3540279] [CDVTimer][handleopenurl] 0.418961ms
,2016-12-29 18:13:43.081 ThaliTest[1692:3540279] [CDVTimer][intentandnavigationfilter] 10.819972ms
2016-12-29 18:13:43.082 ThaliTest[1692:3540279] [CDVTimer][gesturehandler] 0.389993ms
2016-12-29 18:13:43.083 ThaliTest[1692:3540279] [CDVTimer][TotalPlugin,Startup] 13.650000ms
,2016-12-29 18:13:48.853 ThaliTest[1692:3540279] Resetting plugins due to page load.
,2016-12-29 18:13:52.420 ThaliTest[1692:3540279] Finished load of: file:///var/mobile/Containers/Bundle/Application/3C807C4F-EF66-42B3-85B4-0C1285071BB0/ThaliTest.app/www/index.html
,2016-12-29 18:13:52.730 ThaliTest[1692:3540279] JXcore Cordova plugin initializing
,2016-12-29 18:13:52.731 ThaliTest[1692:3540491] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 17:14:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 17:14:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 17:14:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-29 17:14:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 17:14:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-29 17:14:33 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.86459195613861
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registe
```
