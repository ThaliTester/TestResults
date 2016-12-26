#### Test 993933123c9286c_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CEF9EBD5-099B-43C0-81D4-A7046C09F71C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/CEF9EBD5-099B-43C0-81D4-A7046C09F71C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/456B60F2-14B0-4F7D-8085-22FDD2D55D67/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54774"
,(lldb)     command script import "/tmp/CEF9EBD5-099B-43C0-81D4-A7046C09F71C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 00:21:58.707 ThaliTest[1456:3108753] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9DD8CEEC-8AB8-4A64-949C-9FE0455BB3BC/Library/Cookies/Cookies.binarycookies
,2016-12-27 00:21:58.818 ThaliTest[1456:3108753] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-27 00:21:58.819 ThaliTest[1456:3108753] Multi-tasking -> Device: YES, App: YES
,2016-12-27 00:21:58.845 ThaliTest[1456:3108753] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 00:22:00.315 ThaliTest[1456:3108753] Using UIWebView
,2016-12-27 00:22:00.321 ThaliTest[1456:3108753] [CDVTimer][handleopenurl] 0.420988ms
,2016-12-27 00:22:00.328 ThaliTest[1456:3108753] [CDVTimer][intentandnavigationfilter] 6.358027ms
2016-12-27 00:22:00.328 ThaliTest[1456:3108753] [CDVTimer][gesturehandler] 0.198007ms
2016-12-27 00:22:00.328 ThaliTest[1456:3108753] [CDVTimer][TotalPluginS,tartup] 8.285999ms
,2016-12-27 00:22:06.724 ThaliTest[1456:3108753] Resetting plugins due to page load.
,2016-12-27 00:22:09.858 ThaliTest[1456:3108753] Finished load of: file:///var/mobile/Containers/Bundle/Application/456B60F2-14B0-4F7D-8085-22FDD2D55D67/ThaliTest.app/www/index.html
,2016-12-27 00:22:10.175 ThaliTest[1456:3108753] JXcore Cordova plugin initializing
,2016-12-27 00:22:10.176 ThaliTest[1456:3108973] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 23:22:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 23:22:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 23:22:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-26 23:22:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 23:22:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 23:22:48 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.15071803331375
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
