#### Test 95321062fff4ed0_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/06B0BB2B-261E-45B1-B086-5E0E2D365CCF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/06B0BB2B-261E-45B1-B086-5E0E2D365CCF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/95321062fff4ed0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8877CD11-EF55-4B30-AEAC-197BBFA8132D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57314"
,(lldb)     command script import "/tmp/06B0BB2B-261E-45B1-B086-5E0E2D365CCF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 18:32:05.203 ThaliTest[439:307856] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/385C466E-2827-406D-9579-D8F483FE06D2/Library/Cookies/Cookies.binarycookies
,2016-12-07 18:32:05.315 ThaliTest[439:307856] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 18:32:05.317 ThaliTest[439:307856] Multi-tasking -> Device: YES, App: YES
,2016-12-07 18:32:05.340 ThaliTest[439:307856] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 18:32:07.128 ThaliTest[439:307856] Using UIWebView
,2016-12-07 18:32:07.137 ThaliTest[439:307856] [CDVTimer][handleopenurl] 0.455976ms
,2016-12-07 18:32:07.147 ThaliTest[439:307856] [CDVTimer][intentandnavigationfilter] 9.402037ms
2016-12-07 18:32:07.148 ThaliTest[439:307856] [CDVTimer][gesturehandler] 0.851989ms
2016-12-07 18:32:07.149 ThaliTest[439:307856] [CDVTimer][TotalPluginStartup] 12.867033ms
,2016-12-07 18:32:14.258 ThaliTest[439:307856] Resetting plugins due to page load.
,2016-12-07 18:32:17.957 ThaliTest[439:307856] Finished load of: file:///var/mobile/Containers/Bundle/Application/8877CD11-EF55-4B30-AEAC-197BBFA8132D/ThaliTest.app/www/index.html
,2016-12-07 18:32:18.273 ThaliTest[439:307856] JXcore Cordova plugin initializing
,2016-12-07 18:32:18.274 ThaliTest[439:308067] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 17:32:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 17:32:56 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.47790002822876
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
