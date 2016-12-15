#### Test 97727103c899188_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/97727103c899188/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/27D382B0-C55B-4F6D-88B0-1E8EEC7F0574/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/27D382B0-C55B-4F6D-88B0-1E8EEC7F0574/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/97727103c899188/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/97727103c899188/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/31ED9F34-D753-4B19-B0CE-7A656BB822C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64293"
,(lldb)     command script import "/tmp/27D382B0-C55B-4F6D-88B0-1E8EEC7F0574/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-15 11:44:12.946 ThaliTest[843:1391164] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/BF8A5807-6194-48C5-9284-509A206AC841/Library/Cookies/Cookies.binarycookies
,2016-12-15 11:44:13.071 ThaliTest[843:1391164] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 11:44:13.073 ThaliTest[843:1391164] Multi-tasking -> Device: YES, App: YES
,2016-12-15 11:44:13.102 ThaliTest[843:1391164] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 11:44:14.681 ThaliTest[843:1391164] Using UIWebView
,2016-12-15 11:44:14.692 ThaliTest[843:1391164] [CDVTimer][handleopenurl] 0.460029ms
,2016-12-15 11:44:14.703 ThaliTest[843:1391164] [CDVTimer][intentandnavigationfilter] 10.932028ms
2016-12-15 11:44:14.704 ThaliTest[843:1391164] [CDVTimer][gesturehandler] 0.383019ms
2016-12-15 11:44:14.705 ThaliTest[843:1391164] [CDVTimer][TotalPluginSta,rtup] 13.742983ms
,2016-12-15 11:44:20.723 ThaliTest[843:1391164] Resetting plugins due to page load.
,2016-12-15 11:44:23.949 ThaliTest[843:1391164] Finished load of: file:///var/mobile/Containers/Bundle/Application/31ED9F34-D753-4B19-B0CE-7A656BB822C4/ThaliTest.app/www/index.html
,2016-12-15 11:44:24.244 ThaliTest[843:1391164] JXcore Cordova plugin initializing
,2016-12-15 11:44:24.246 ThaliTest[843:1391423] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 10:44:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 10:44:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 10:44:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-15 10:44:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 10:44:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-15 10:45:02 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.57613199949265
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
