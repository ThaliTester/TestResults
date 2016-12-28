#### Test 9953060646c88db_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/E14A775E-3B38-4FED-938D-6D7CF7870439/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/E14A775E-3B38-4FED-938D-6D7CF7870439/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9953060646c88db/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D87FE76B-3B42-44A3-8F8C-3F9090D4AB97/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59062"
,(lldb)     command script import "/tmp/E14A775E-3B38-4FED-938D-6D7CF7870439/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 11:52:07.372 ThaliTest[1584:3342511] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D3632A4E-CCB6-40E0-A69B-90CAEF5EEC7C/Library/Cookies/Cookies.binarycookies
,2016-12-28 11:52:07.494 ThaliTest[1584:3342511] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 11:52:07.496 ThaliTest[1584:3342511] Multi-tasking -> Device: YES, App: YES
,2016-12-28 11:52:07.518 ThaliTest[1584:3342511] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 11:52:08.951 ThaliTest[1584:3342511] Using UIWebView
,2016-12-28 11:52:08.960 ThaliTest[1584:3342511] [CDVTimer][handleopenurl] 0.649035ms
,2016-12-28 11:52:08.971 ThaliTest[1584:3342511] [CDVTimer][intentandnavigationfilter] 10.406971ms
2016-12-28 11:52:08.972 ThaliTest[1584:3342511] [CDVTimer][gesturehandler] 0.379980ms
2016-12-28 11:52:08.973 ThaliTest[1584:3342511] [CDVTimer][TotalPlugin,Startup] 13.415039ms
,2016-12-28 11:52:14.789 ThaliTest[1584:3342511] Resetting plugins due to page load.
,2016-12-28 11:52:18.270 ThaliTest[1584:3342511] Finished load of: file:///var/mobile/Containers/Bundle/Application/D87FE76B-3B42-44A3-8F8C-3F9090D4AB97/ThaliTest.app/www/index.html
,2016-12-28 11:52:18.574 ThaliTest[1584:3342511] JXcore Cordova plugin initializing
,2016-12-28 11:52:18.575 ThaliTest[1584:3342725] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 10:52:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 10:52:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 10:52:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-28 10:52:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 10:52:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 10:52:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.41745096445084
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
