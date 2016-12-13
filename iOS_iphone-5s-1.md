#### Test 9781689977f4746_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/1FFD42D8-9CED-4439-85C6-F2CC965C039A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1FFD42D8-9CED-4439-85C6-F2CC965C039A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1EDFCC59-FE09-4B08-BBAC-24750EE197DC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57054"
,(lldb)     command script import "/tmp/1FFD42D8-9CED-4439-85C6-F2CC965C039A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 20:45:37.715 ThaliTest[730:1150374] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0CC2A895-482B-4889-8DC4-99AC56E69AAD/Library/Cookies/Cookies.binarycookies
,2016-12-13 20:45:37.834 ThaliTest[730:1150374] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 20:45:37.835 ThaliTest[730:1150374] Multi-tasking -> Device: YES, App: YES
,2016-12-13 20:45:37.853 ThaliTest[730:1150374] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 20:45:39.407 ThaliTest[730:1150374] Using UIWebView
,2016-12-13 20:45:39.415 ThaliTest[730:1150374] [CDVTimer][handleopenurl] 0.438988ms
,2016-12-13 20:45:39.426 ThaliTest[730:1150374] [CDVTimer][intentandnavigationfilter] 10.231018ms
2016-12-13 20:45:39.427 ThaliTest[730:1150374] [CDVTimer][gesturehandler] 0.386000ms
2016-12-13 20:45:39.428 ThaliTest[730:1150374] [CDVTimer][TotalPluginSta,rtup] 13.031006ms
,2016-12-13 20:45:44.926 ThaliTest[730:1150374] Resetting plugins due to page load.
,2016-12-13 20:45:48.318 ThaliTest[730:1150374] Finished load of: file:///var/mobile/Containers/Bundle/Application/1EDFCC59-FE09-4B08-BBAC-24750EE197DC/ThaliTest.app/www/index.html
,2016-12-13 20:45:48.626 ThaliTest[730:1150374] JXcore Cordova plugin initializing
,2016-12-13 20:45:48.627 ThaliTest[730:1150586] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 19:46:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 19:46:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 19:46:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-13 19:46:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 19:46:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 19:46:25 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.32963597774506
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
