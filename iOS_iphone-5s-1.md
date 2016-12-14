#### Test 912434544e24a36_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/912434544e24a36/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/7BB446AD-0237-46F6-994C-7722868B3BD4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/7BB446AD-0237-46F6-994C-7722868B3BD4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/912434544e24a36/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/912434544e24a36/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/2D00CDFD-A95A-45B9-A69B-BC0E64780BBA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58325"
,(lldb)     command script import "/tmp/7BB446AD-0237-46F6-994C-7722868B3BD4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 17:00:32.509 ThaliTest[791:1275215] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1AFCA266-2020-47A2-8F6A-96409CC6192C/Library/Cookies/Cookies.binarycookies
,2016-12-14 17:00:32.626 ThaliTest[791:1275215] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 17:00:32.628 ThaliTest[791:1275215] Multi-tasking -> Device: YES, App: YES
,2016-12-14 17:00:32.651 ThaliTest[791:1275215] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 17:00:34.057 ThaliTest[791:1275215] Using UIWebView
,2016-12-14 17:00:34.066 ThaliTest[791:1275215] [CDVTimer][handleopenurl] 0.410974ms
,2016-12-14 17:00:34.076 ThaliTest[791:1275215] [CDVTimer][intentandnavigationfilter] 10.239005ms
2016-12-14 17:00:34.077 ThaliTest[791:1275215] [CDVTimer][gesturehandler] 0.371993ms
2016-12-14 17:00:34.078 ThaliTest[791:1275215] [CDVTimer][TotalPluginSta,rtup] 13.105989ms
,2016-12-14 17:00:39.665 ThaliTest[791:1275215] Resetting plugins due to page load.
,2016-12-14 17:00:43.095 ThaliTest[791:1275215] Finished load of: file:///var/mobile/Containers/Bundle/Application/2D00CDFD-A95A-45B9-A69B-BC0E64780BBA/ThaliTest.app/www/index.html
,2016-12-14 17:00:43.400 ThaliTest[791:1275215] JXcore Cordova plugin initializing
,2016-12-14 17:00:43.401 ThaliTest[791:1275432] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-14 16:00:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-14 16:00:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-14 16:00:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-14 16:00:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-14 16:00:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-14 16:01:21 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.37222200632095
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
