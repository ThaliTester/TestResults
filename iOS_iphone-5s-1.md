#### Test 99261278b72b2a5_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99261278b72b2a5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B2AC824A-FDDE-4948-BA39-759E7F7AFE58/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B2AC824A-FDDE-4948-BA39-759E7F7AFE58/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99261278b72b2a5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99261278b72b2a5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FCE469C7-E5DE-41E6-B200-AEC2C2FDDE05/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64597"
,(lldb)     command script import "/tmp/B2AC824A-FDDE-4948-BA39-759E7F7AFE58/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 15:08:06.449 ThaliTest[1679:3519168] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BBA1C3B3-C67F-4CCB-BB9F-FE1CFE50AEF5/Library/Cookies/Cookies.binarycookies
,2016-12-29 15:08:06.567 ThaliTest[1679:3519168] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 15:08:06.569 ThaliTest[1679:3519168] Multi-tasking -> Device: YES, App: YES
,2016-12-29 15:08:06.590 ThaliTest[1679:3519168] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 15:08:08.079 ThaliTest[1679:3519168] Using UIWebView
,2016-12-29 15:08:08.090 ThaliTest[1679:3519168] [CDVTimer][handleopenurl] 0.498950ms
,2016-12-29 15:08:08.102 ThaliTest[1679:3519168] [CDVTimer][intentandnavigationfilter] 11.285961ms
2016-12-29 15:08:08.103 ThaliTest[1679:3519168] [CDVTimer][gesturehandler] 0.391960ms
2016-12-29 15:08:08.104 ThaliTest[1679:3519168] [CDVTimer][TotalPlugin,Startup] 14.158010ms
,2016-12-29 15:08:13.940 ThaliTest[1679:3519168] Resetting plugins due to page load.
,2016-12-29 15:08:16.954 ThaliTest[1679:3519168] Finished load of: file:///var/mobile/Containers/Bundle/Application/FCE469C7-E5DE-41E6-B200-AEC2C2FDDE05/ThaliTest.app/www/index.html
,2016-12-29 15:08:17.261 ThaliTest[1679:3519168] JXcore Cordova plugin initializing
,2016-12-29 15:08:17.262 ThaliTest[1679:3519399] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 14:08:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 14:08:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 14:08:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-29 14:08:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 14:08:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-29 14:08:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.45470601320267
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
