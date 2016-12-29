#### Test 996810527fc9b76_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/996810527fc9b76/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/4BE25E33-9E3A-4807-BAFF-7891CF45622D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4BE25E33-9E3A-4807-BAFF-7891CF45622D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/996810527fc9b76/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/996810527fc9b76/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/923D7757-0DA3-4679-BB16-DB4912DAD5F0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51806"
,(lldb)     command script import "/tmp/4BE25E33-9E3A-4807-BAFF-7891CF45622D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 19:18:20.362 ThaliTest[1701:3548211] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/14AE648A-713A-4458-A6E5-A608BCC68C72/Library/Cookies/Cookies.binarycookies
,2016-12-29 19:18:20.472 ThaliTest[1701:3548211] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 19:18:20.474 ThaliTest[1701:3548211] Multi-tasking -> Device: YES, App: YES
,2016-12-29 19:18:20.497 ThaliTest[1701:3548211] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 19:18:21.839 ThaliTest[1701:3548211] Using UIWebView
,2016-12-29 19:18:21.847 ThaliTest[1701:3548211] [CDVTimer][handleopenurl] 0.589013ms
,2016-12-29 19:18:21.858 ThaliTest[1701:3548211] [CDVTimer][intentandnavigationfilter] 9.520948ms
,2016-12-29 19:18:21.859 ThaliTest[1701:3548211] [CDVTimer][gesturehandler] 0.835001ms
2016-12-29 19:18:21.859 ThaliTest[1701:3548211] [CDVTimer][TotalPluginStartup] 12.995005ms
,2016-12-29 19:18:28.926 ThaliTest[1701:3548211] Resetting plugins due to page load.
,2016-12-29 19:18:33.252 ThaliTest[1701:3548211] Finished load of: file:///var/mobile/Containers/Bundle/Application/923D7757-0DA3-4679-BB16-DB4912DAD5F0/ThaliTest.app/www/index.html
,2016-12-29 19:18:33.565 ThaliTest[1701:3548211] JXcore Cordova plugin initializing
,2016-12-29 19:18:33.566 ThaliTest[1701:3548425] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 18:18:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 18:18:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 18:18:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-29 18:18:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 18:18:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-29 18:19:12 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.73949199914932
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
