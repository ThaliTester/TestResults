#### Test 935721672bafbe2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/81D8D4DD-6C47-4962-ACAB-02668CDE1537/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/81D8D4DD-6C47-4962-ACAB-02668CDE1537/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721672bafbe2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3EC5A12D-5647-4B1A-A6EE-46CFB368B453/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58179"
,(lldb)     command script import "/tmp/81D8D4DD-6C47-4962-ACAB-02668CDE1537/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-21 16:48:30.580 ThaliTest[6112:15524046] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6D80C31D-47E0-4205-B980-F8054C13B538/Library/Cookies/Cookies.binarycookies
,2016-11-21 16:48:30.700 ThaliTest[6112:15524046] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 16:48:30.702 ThaliTest[6112:15524046] Multi-tasking -> Device: YES, App: YES
,2016-11-21 16:48:30.728 ThaliTest[6112:15524046] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 16:48:32.338 ThaliTest[6112:15524046] Using UIWebView
,2016-11-21 16:48:32.347 ThaliTest[6112:15524046] [CDVTimer][handleopenurl] 0.490010ms
,2016-11-21 16:48:32.356 ThaliTest[6112:15524046] [CDVTimer][intentandnavigationfilter] 8.252025ms
2016-11-21 16:48:32.357 ThaliTest[6112:15524046] [CDVTimer][gesturehandler] 0.386000ms
2016-11-21 16:48:32.357 ThaliTest[6112:15524046] [CDVTimer][TotalPlug,inStartup] 11.004984ms
,2016-11-21 16:48:36.680 ThaliTest[6112:15524046] Resetting plugins due to page load.
,2016-11-21 16:48:40.037 ThaliTest[6112:15524046] Finished load of: file:///var/mobile/Containers/Bundle/Application/3EC5A12D-5647-4B1A-A6EE-46CFB368B453/ThaliTest.app/www/index.html
,2016-11-21 16:48:40.335 ThaliTest[6112:15524046] JXcore Cordova plugin initializing
,2016-11-21 16:48:40.336 ThaliTest[6112:15525661] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 15:48:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 15:48:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 15:48:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 15:48:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 15:48:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 15:49:17 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.39206099510193
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
