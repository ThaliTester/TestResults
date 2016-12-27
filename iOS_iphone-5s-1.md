#### Test 99374565145ad70_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99374565145ad70/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FD98316F-8866-44E2-85E5-17B43D95A73E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FD98316F-8866-44E2-85E5-17B43D95A73E/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99374565145ad70/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99374565145ad70/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EA92AB21-54E1-4419-8327-9BEAF8A960DD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58403"
,(lldb)     command script import "/tmp/FD98316F-8866-44E2-85E5-17B43D95A73E/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 12:06:52.796 ThaliTest[1491:3185049] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3C047C51-FE3A-4A02-AB89-41ECC9D54A5C/Library/Cookies/Cookies.binarycookies
,2016-12-27 12:06:52.912 ThaliTest[1491:3185049] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 12:06:52.913 ThaliTest[1491:3185049] Multi-tasking -> Device: YES, App: YES
,2016-12-27 12:06:52.937 ThaliTest[1491:3185049] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 12:06:54.405 ThaliTest[1491:3185049] Using UIWebView
,2016-12-27 12:06:54.414 ThaliTest[1491:3185049] [CDVTimer][handleopenurl] 0.536025ms
,2016-12-27 12:06:54.425 ThaliTest[1491:3185049] [CDVTimer][intentandnavigationfilter] 10.200024ms
2016-12-27 12:06:54.426 ThaliTest[1491:3185049] [CDVTimer][gesturehandler] 0.389993ms
2016-12-27 12:06:54.426 ThaliTest[1491:3185049] [CDVTimer][TotalPluginStartup] 13.297975ms
,2016-12-27 12:07:00.699 ThaliTest[1491:3185049] Resetting plugins due to page load.
,2016-12-27 12:07:04.673 ThaliTest[1491:3185049] Finished load of: file:///var/mobile/Containers/Bundle/Application/EA92AB21-54E1-4419-8327-9BEAF8A960DD/ThaliTest.app/www/index.html
,2016-12-27 12:07:04.994 ThaliTest[1491:3185049] JXcore Cordova plugin initializing
,2016-12-27 12:07:04.995 ThaliTest[1491:3185248] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 11:07:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 11:07:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 11:07:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-27 11:07:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 11:07:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 11:07:43 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.01714301109314
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
