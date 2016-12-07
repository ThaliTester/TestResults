#### Test 95321062fff4ed0_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/8B09D2B5-2130-4983-AA64-39313E6CBF27/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/8B09D2B5-2130-4983-AA64-39313E6CBF27/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/86E92B1A-B28F-4943-A48F-CFC4D847413A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57309"
,(lldb)     command script import "/tmp/8B09D2B5-2130-4983-AA64-39313E6CBF27/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 18:31:58.669 ThaliTest[360:149041] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/32FCB904-E0F6-4D02-B7B6-5E92886B714D/Library/Cookies/Cookies.binarycookies
,2016-12-07 18:31:58.750 ThaliTest[360:149041] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 18:31:58.752 ThaliTest[360:149041] Multi-tasking -> Device: YES, App: YES
,2016-12-07 18:31:58.773 ThaliTest[360:149041] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 18:31:59.250 ThaliTest[360:149041] Using UIWebView
,2016-12-07 18:31:59.260 ThaliTest[360:149041] [CDVTimer][handleopenurl] 0.316024ms
,2016-12-07 18:31:59.268 ThaliTest[360:149041] [CDVTimer][intentandnavigationfilter] 8.264959ms
2016-12-07 18:31:59.269 ThaliTest[360:149041] [CDVTimer][gesturehandler] 0.319004ms
2016-12-07 18:31:59.269 ThaliTest[360:149041] [CDVTimer][TotalPluginStartup,] 10.564029ms
,2016-12-07 18:32:05.197 ThaliTest[360:149041] Resetting plugins due to page load.
,2016-12-07 18:32:05.500 ThaliTest[360:149041] Finished load of: file:///var/containers/Bundle/Application/86E92B1A-B28F-4943-A48F-CFC4D847413A/ThaliTest.app/www/index.html
,2016-12-07 18:32:05.834 ThaliTest[360:149041] JXcore Cordova plugin initializing
,2016-12-07 18:32:05.835 ThaliTest[360:149249] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 17:32:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 17:32:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 17:32:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 17:32:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 17:32:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 17:32:42 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.62301999330521
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
