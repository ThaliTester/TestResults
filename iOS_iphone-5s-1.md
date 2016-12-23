#### Test 992828382af0ec7_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992828382af0ec7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/B6744CDA-D0C0-4EAD-B216-DCAED73448D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B6744CDA-D0C0-4EAD-B216-DCAED73448D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992828382af0ec7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992828382af0ec7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/AB6E7C17-C07A-41B8-BC66-3CC7E243D269/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59223"
,(lldb)     command script import "/tmp/B6744CDA-D0C0-4EAD-B216-DCAED73448D4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-23 23:01:45.381 ThaliTest[1297:2648519] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/77EC838D-4004-45A0-A676-54B278A5B248/Library/Cookies/Cookies.binarycookies
,2016-12-23 23:01:45.995 ThaliTest[1297:2648519] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-23 23:01:45.996 ThaliTest[1297:2648519] Multi-tasking -> Device: YES, App: YES
,2016-12-23 23:01:46.018 ThaliTest[1297:2648519] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-23 23:01:47.501 ThaliTest[1297:2648519] Using UIWebView
,2016-12-23 23:01:47.509 ThaliTest[1297:2648519] [CDVTimer][handleopenurl] 0.410974ms
,2016-12-23 23:01:47.520 ThaliTest[1297:2648519] [CDVTimer][intentandnavigationfilter] 9.980977ms
2016-12-23 23:01:47.521 ThaliTest[1297:2648519] [CDVTimer][gesturehandler] 0.384986ms
2016-12-23 23:01:47.521 ThaliTest[1297:2648519] [CDVTimer][TotalPluginStartup] 12.739003ms
,2016-12-23 23:01:53.612 ThaliTest[1297:2648519] Resetting plugins due to page load.
,2016-12-23 23:01:56.700 ThaliTest[1297:2648519] Finished load of: file:///var/mobile/Containers/Bundle/Application/AB6E7C17-C07A-41B8-BC66-3CC7E243D269/ThaliTest.app/www/index.html
,2016-12-23 23:01:56.948 ThaliTest[1297:2648519] JXcore Cordova plugin initializing
,2016-12-23 23:01:56.950 ThaliTest[1297:2648722] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-23 22:02:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-23 22:02:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-23 22:02:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-23 22:02:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-23 22:02:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-23 22:02:34 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.37059998512268
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
