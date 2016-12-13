#### Test 978514903f1da2e_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/088AB0B6-3101-446F-9120-91585B2DF3E0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/088AB0B6-3101-446F-9120-91585B2DF3E0/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5D4DB79D-2D8A-4FCF-AAB4-BF890827EF5B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59845"
,(lldb)     command script import "/tmp/088AB0B6-3101-446F-9120-91585B2DF3E0/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 00:09:01.763 ThaliTest[741:1171660] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C853576A-77A5-4D0D-8C85-A683C0604816/Library/Cookies/Cookies.binarycookies
,2016-12-14 00:09:01.880 ThaliTest[741:1171660] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 00:09:01.882 ThaliTest[741:1171660] Multi-tasking -> Device: YES, App: YES
,2016-12-14 00:09:01.907 ThaliTest[741:1171660] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 00:09:03.292 ThaliTest[741:1171660] Using UIWebView
,2016-12-14 00:09:03.300 ThaliTest[741:1171660] [CDVTimer][handleopenurl] 0.410974ms
,2016-12-14 00:09:03.311 ThaliTest[741:1171660] [CDVTimer][intentandnavigationfilter] 10.010004ms
2016-12-14 00:09:03.312 ThaliTest[741:1171660] [CDVTimer][gesturehandler] 0.386000ms
2016-12-14 00:09:03.312 ThaliTest[741:1171660] [CDVTimer][TotalPluginSta,rtup] 12.782037ms
,2016-12-14 00:09:08.917 ThaliTest[741:1171660] Resetting plugins due to page load.
,2016-12-14 00:09:12.040 ThaliTest[741:1171660] Finished load of: file:///var/mobile/Containers/Bundle/Application/5D4DB79D-2D8A-4FCF-AAB4-BF890827EF5B/ThaliTest.app/www/index.html
,2016-12-14 00:09:12.357 ThaliTest[741:1171660] JXcore Cordova plugin initializing
,2016-12-14 00:09:12.359 ThaliTest[741:1171900] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 23:09:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 23:09:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 23:09:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-13 23:09:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 23:09:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-12-13 23:09:50 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.90585404634476
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
