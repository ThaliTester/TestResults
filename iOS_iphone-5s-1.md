#### Test 99529739424d9f5_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/37D6C28F-38DB-431C-8384-9BC305A74AAE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/37D6C28F-38DB-431C-8384-9BC305A74AAE/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99529739424d9f5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FD6ED28F-2372-46DB-A5F5-F54D6824117A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57723"
,(lldb)     command script import "/tmp/37D6C28F-38DB-431C-8384-9BC305A74AAE/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-28 11:23:34.910 ThaliTest[1575:3337678] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D750AE5E-3556-47E6-82B7-894D9A8DCECE/Library/Cookies/Cookies.binarycookies
,2016-12-28 11:23:35.036 ThaliTest[1575:3337678] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-28 11:23:35.038 ThaliTest[1575:3337678] Multi-tasking -> Device: YES, App: YES
,2016-12-28 11:23:35.059 ThaliTest[1575:3337678] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-28 11:23:36.604 ThaliTest[1575:3337678] Using UIWebView
,2016-12-28 11:23:36.613 ThaliTest[1575:3337678] [CDVTimer][handleopenurl] 0.413001ms
,2016-12-28 11:23:36.623 ThaliTest[1575:3337678] [CDVTimer][intentandnavigationfilter] 10.113001ms
2016-12-28 11:23:36.624 ThaliTest[1575:3337678] [CDVTimer][gesturehandler] 0.425994ms
2016-12-28 11:23:36.625 ThaliTest[1575:3337678] [CDVTimer][TotalPlugin,Startup] 12.880981ms
,2016-12-28 11:23:42.528 ThaliTest[1575:3337678] Resetting plugins due to page load.
,2016-12-28 11:23:45.933 ThaliTest[1575:3337678] Finished load of: file:///var/mobile/Containers/Bundle/Application/FD6ED28F-2372-46DB-A5F5-F54D6824117A/ThaliTest.app/www/index.html
,2016-12-28 11:23:46.230 ThaliTest[1575:3337678] JXcore Cordova plugin initializing
,2016-12-28 11:23:46.231 ThaliTest[1575:3337886] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-28 10:23:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-28 10:23:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-28 10:23:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-28 10:23:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-28 10:23:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-28 10:24:24 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.84054201841354
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
