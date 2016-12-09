#### Test 9732732894937d3_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/AF84D5D0-D2D0-4D9F-8064-711ACEBD243A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/AF84D5D0-D2D0-4D9F-8064-711ACEBD243A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9732732894937d3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/BAED63AB-1D29-443A-91B4-0CD12DF390C5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61903"
,(lldb)     command script import "/tmp/AF84D5D0-D2D0-4D9F-8064-711ACEBD243A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-09 16:50:36.768 ThaliTest[528:569111] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/581433DF-36BB-4EB1-84B0-6EC6113F1732/Library/Cookies/Cookies.binarycookies
,2016-12-09 16:50:36.894 ThaliTest[528:569111] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-09 16:50:36.896 ThaliTest[528:569111] Multi-tasking -> Device: YES, App: YES
,2016-12-09 16:50:36.919 ThaliTest[528:569111] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-09 16:50:38.369 ThaliTest[528:569111] Using UIWebView
,2016-12-09 16:50:38.380 ThaliTest[528:569111] [CDVTimer][handleopenurl] 0.447035ms
,2016-12-09 16:50:38.391 ThaliTest[528:569111] [CDVTimer][intentandnavigationfilter] 10.490000ms
,2016-12-09 16:50:38.392 ThaliTest[528:569111] [CDVTimer][gesturehandler] 0.811994ms
2016-12-09 16:50:38.393 ThaliTest[528:569111] [CDVTimer][TotalPluginStartup] 13.782024ms
,2016-12-09 16:50:44.277 ThaliTest[528:569111] Resetting plugins due to page load.
,2016-12-09 16:50:47.586 ThaliTest[528:569111] Finished load of: file:///var/mobile/Containers/Bundle/Application/BAED63AB-1D29-443A-91B4-0CD12DF390C5/ThaliTest.app/www/index.html
,2016-12-09 16:50:47.897 ThaliTest[528:569111] JXcore Cordova plugin initializing
,2016-12-09 16:50:47.898 ThaliTest[528:569326] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-09 15:51:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-09 15:51:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-09 15:51:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-09 15:51:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-09 15:51:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-09 15:51:26 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.26179999113083
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
