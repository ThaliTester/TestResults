#### Test 983548825638cdd_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/DAEFD05B-336A-4D77-A6F6-8E46FA11CFA8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/DAEFD05B-336A-4D77-A6F6-8E46FA11CFA8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/983548825638cdd/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/06D32FD1-A723-4292-81FD-303B5799D322/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57985"
,(lldb)     command script import "/tmp/DAEFD05B-336A-4D77-A6F6-8E46FA11CFA8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-19 14:12:09.257 ThaliTest[1059:1992024] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E53379AF-21AB-4A07-B4D8-B0205434F747/Library/Cookies/Cookies.binarycookies
,2016-12-19 14:12:09.368 ThaliTest[1059:1992024] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-19 14:12:09.370 ThaliTest[1059:1992024] Multi-tasking -> Device: YES, App: YES
,2016-12-19 14:12:09.392 ThaliTest[1059:1992024] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-19 14:12:11.096 ThaliTest[1059:1992024] Using UIWebView
,2016-12-19 14:12:11.105 ThaliTest[1059:1992024] [CDVTimer][handleopenurl] 0.429988ms
,2016-12-19 14:12:11.115 ThaliTest[1059:1992024] [CDVTimer][intentandnavigationfilter] 9.045959ms
2016-12-19 14:12:11.115 ThaliTest[1059:1992024] [CDVTimer][gesturehandler] 0.380039ms
2016-12-19 14:12:11.116 ThaliTest[1059:1992024] [CDVTimer][TotalPluginStartup] 11.852980ms
,2016-12-19 14:12:18.388 ThaliTest[1059:1992024] Resetting plugins due to page load.
,2016-12-19 14:12:23.161 ThaliTest[1059:1992024] Finished load of: file:///var/mobile/Containers/Bundle/Application/06D32FD1-A723-4292-81FD-303B5799D322/ThaliTest.app/www/index.html
,2016-12-19 14:12:23.479 ThaliTest[1059:1992024] JXcore Cordova plugin initializing
,2016-12-19 14:12:23.481 ThaliTest[1059:1992267] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-19 13:12:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-19 13:12:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-19 13:12:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-19 13:12:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-19 13:12:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-19 13:13:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  23.70783895254135
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
