#### Test 977271034c6c8cc_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/1BDBB244-8A30-4E24-83D3-27A6B2912123/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1BDBB244-8A30-4E24-83D3-27A6B2912123/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7D712299-9D05-41E3-93E9-9DFFFCF02986/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52723"
,(lldb)     command script import "/tmp/1BDBB244-8A30-4E24-83D3-27A6B2912123/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
,(lldb)     autoexit
,2016-12-13 12:18:50.474 ThaliTest[702:1097544] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E2D56674-FF4D-4B68-8D6C-7694D7372A7F/Library/Cookies/Cookies.binarycookies
,2016-12-13 12:18:50.603 ThaliTest[702:1097544] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 12:18:50.605 ThaliTest[702:1097544] Multi-tasking -> Device: YES, App: YES
,2016-12-13 12:18:50.626 ThaliTest[702:1097544] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 12:18:52.212 ThaliTest[702:1097544] Using UIWebView
,2016-12-13 12:18:52.221 ThaliTest[702:1097544] [CDVTimer][handleopenurl] 0.427961ms
,2016-12-13 12:18:52.232 ThaliTest[702:1097544] [CDVTimer][intentandnavigationfilter] 10.949016ms
2016-12-13 12:18:52.233 ThaliTest[702:1097544] [CDVTimer][gesturehandler] 0.451982ms
2016-12-13 12:18:52.234 ThaliTest[702:1097544] [CDVTimer][TotalPluginSta,rtup] 13.909996ms
,2016-12-13 12:18:58.210 ThaliTest[702:1097544] Resetting plugins due to page load.
,2016-12-13 12:19:01.884 ThaliTest[702:1097544] Finished load of: file:///var/mobile/Containers/Bundle/Application/7D712299-9D05-41E3-93E9-9DFFFCF02986/ThaliTest.app/www/index.html
,2016-12-13 12:19:02.075 ThaliTest[702:1097544] JXcore Cordova plugin initializing
,2016-12-13 12:19:02.076 ThaliTest[702:1097799] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 11:19:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 11:19:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 11:19:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-13 11:19:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 11:19:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 11:19:39 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.65016400814056
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
