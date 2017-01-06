#### Test 10045281117fe266_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10045281117fe266/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/A1275FA4-75B5-4566-BADF-141EE9265C93/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A1275FA4-75B5-4566-BADF-141EE9265C93/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10045281117fe266/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10045281117fe266/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8BFE8CBF-427F-4786-995B-C562FB7B0EB5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64723"
,(lldb)     command script import "/tmp/A1275FA4-75B5-4566-BADF-141EE9265C93/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-06 14:02:48.435 ThaliTest[2020:4678813] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C5AA1E60-AB5C-426F-9FE2-CB76E2EDFA4B/Library/Cookies/Cookies.binarycookies
,2017-01-06 14:02:48.505 ThaliTest[2020:4678813] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-06 14:02:48.507 ThaliTest[2020:4678813] Multi-tasking -> Device: YES, App: YES
,2017-01-06 14:02:48.523 ThaliTest[2020:4678813] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-06 14:02:49.350 ThaliTest[2020:4678813] Using UIWebView
,2017-01-06 14:02:49.353 ThaliTest[2020:4678813] [CDVTimer][handleopenurl] 0.165999ms
,2017-01-06 14:02:49.358 ThaliTest[2020:4678813] [CDVTimer][intentandnavigationfilter] 4.266977ms
2017-01-06 14:02:49.358 ThaliTest[2020:4678813] [CDVTimer][gesturehandler] 0.162005ms
2017-01-06 14:02:49.358 ThaliTest[2020:4678813] [CDVTimer][TotalPluginS,tartup] 5.402029ms
,2017-01-06 14:02:52.551 ThaliTest[2020:4678813] Resetting plugins due to page load.
,2017-01-06 14:02:54.330 ThaliTest[2020:4678813] Finished load of: file:///var/mobile/Containers/Bundle/Application/8BFE8CBF-427F-4786-995B-C562FB7B0EB5/ThaliTest.app/www/index.html
,2017-01-06 14:02:54.341 ThaliTest[2020:4678813] JXcore Cordova plugin initializing
2017-01-06 14:02:54.342 ThaliTest[2020:4678965] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-06 13:03:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-06 13:03:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-06 13:03:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-06 13:03:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-06 13:03:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-06 13:03:31 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  22.77015602588654
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
