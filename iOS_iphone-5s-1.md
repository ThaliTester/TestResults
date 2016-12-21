#### Test 98912682a6d9d3f_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/1970F1D6-AB3C-438A-B5A6-4400D7ABC444/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1970F1D6-AB3C-438A-B5A6-4400D7ABC444/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/509D581C-6412-4837-AA26-4B05B2A841E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59230"
,(lldb)     command script import "/tmp/1970F1D6-AB3C-438A-B5A6-4400D7ABC444/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-21 19:25:50.224 ThaliTest[1182:2325259] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F6849B81-11E0-48C4-97D0-E52A8ECBCC72/Library/Cookies/Cookies.binarycookies
,2016-12-21 19:25:50.348 ThaliTest[1182:2325259] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-21 19:25:50.350 ThaliTest[1182:2325259] Multi-tasking -> Device: YES, App: YES
,2016-12-21 19:25:50.372 ThaliTest[1182:2325259] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-21 19:25:51.854 ThaliTest[1182:2325259] Using UIWebView
,2016-12-21 19:25:51.862 ThaliTest[1182:2325259] [CDVTimer][handleopenurl] 0.584006ms
,2016-12-21 19:25:51.874 ThaliTest[1182:2325259] [CDVTimer][intentandnavigationfilter] 10.490954ms
2016-12-21 19:25:51.875 ThaliTest[1182:2325259] [CDVTimer][gesturehandler] 0.394046ms
2016-12-21 19:25:51.875 ThaliTest[1182:2325259] [CDVTimer][TotalPluginStartup] 13.458014ms
,2016-12-21 19:25:57.440 ThaliTest[1182:2325259] Resetting plugins due to page load.
,2016-12-21 19:26:00.570 ThaliTest[1182:2325259] Finished load of: file:///var/mobile/Containers/Bundle/Application/509D581C-6412-4837-AA26-4B05B2A841E2/ThaliTest.app/www/index.html
,2016-12-21 19:26:00.758 ThaliTest[1182:2325259] JXcore Cordova plugin initializing
,2016-12-21 19:26:00.759 ThaliTest[1182:2325507] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-21 18:26:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-21 18:26:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-21 18:26:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-21 18:26:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-21 18:26:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-21 18:26:38 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.93504899740219
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
