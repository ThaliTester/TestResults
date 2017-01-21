#### Test 102585911579949a_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/FB886B65-06DB-463F-9A56-FA18C30C7E7D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FB886B65-06DB-463F-9A56-FA18C30C7E7D/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102585911579949a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E934D97D-9AC8-497F-AD85-9867E2B30FE5/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62949"
,(lldb)     command script import "/tmp/FB886B65-06DB-463F-9A56-FA18C30C7E7D/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-21 16:59:35.580 ThaliTest[2647:6561417] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E3202DC0-C0D1-4D0F-83A9-F4CF6D682131/Library/Cookies/Cookies.binarycookies
,2017-01-21 16:59:35.651 ThaliTest[2647:6561417] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-21 16:59:35.653 ThaliTest[2647:6561417] Multi-tasking -> Device: YES, App: YES
,2017-01-21 16:59:35.670 ThaliTest[2647:6561417] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-21 16:59:36.521 ThaliTest[2647:6561417] Using UIWebView
2017-01-21 16:59:36.524 ThaliTest[2647:6561417] [CDVTimer][handleopenurl] 0.160038ms
2017-01-21 16:59:36.529 ThaliTest[2647:6561417] [CDVTimer][intentandnavigationfilter] 4.429996ms
2017-01,-21 16:59:36.529 ThaliTest[2647:6561417] [CDVTimer][gesturehandler] 0.159025ms
2017-01-21 16:59:36.530 ThaliTest[2647:6561417] [CDVTimer][TotalPluginStartup] 5.470991ms
,2017-01-21 16:59:39.785 ThaliTest[2647:6561417] Resetting plugins due to page load.
,2017-01-21 16:59:41.467 ThaliTest[2647:6561417] Finished load of: file:///var/mobile/Containers/Bundle/Application/E934D97D-9AC8-497F-AD85-9867E2B30FE5/ThaliTest.app/www/index.html
,2017-01-21 16:59:41.669 ThaliTest[2647:6561417] JXcore Cordova plugin initializing
,2017-01-21 16:59:41.670 ThaliTest[2647:6561587] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-21 15:59:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-21 15:59:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-21 15:59:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-21 15:59:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-21 15:59:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-21 16:00:21 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.06196200847626
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
