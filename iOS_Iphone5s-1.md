#### Test 94407748f58d03e_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/14CCD35F-FD53-488A-84C2-5FC4E803F0A8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/14CCD35F-FD53-488A-84C2-5FC4E803F0A8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/94407748f58d03e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7605AD4D-6EFB-4C58-9C2B-C319DDE9F579/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52844"
,(lldb)     command script import "/tmp/14CCD35F-FD53-488A-84C2-5FC4E803F0A8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 15:33:17.668 ThaliTest[6086:15512106] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3BBEB0E4-5751-4360-B617-DBFB2B5FBF17/Library/Cookies/Cookies.binarycookies
,2016-11-21 15:33:17.778 ThaliTest[6086:15512106] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 15:33:17.780 ThaliTest[6086:15512106] Multi-tasking -> Device: YES, App: YES
,2016-11-21 15:33:17.801 ThaliTest[6086:15512106] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 15:33:19.181 ThaliTest[6086:15512106] Using UIWebView
,2016-11-21 15:33:19.190 ThaliTest[6086:15512106] [CDVTimer][handleopenurl] 0.624955ms
,2016-11-21 15:33:19.198 ThaliTest[6086:15512106] [CDVTimer][intentandnavigationfilter] 8.199990ms
2016-11-21 15:33:19.199 ThaliTest[6086:15512106] [CDVTimer][gesturehandler] 0.433028ms
2016-11-21 15:33:19.200 ThaliTest[6086:15512106] [CDVTimer][TotalPlug,inStartup] 11.081994ms
,2016-11-21 15:33:25.072 ThaliTest[6086:15512106] Resetting plugins due to page load.
,2016-11-21 15:33:28.491 ThaliTest[6086:15512106] Finished load of: file:///var/mobile/Containers/Bundle/Application/7605AD4D-6EFB-4C58-9C2B-C319DDE9F579/ThaliTest.app/www/index.html
,2016-11-21 15:33:28.795 ThaliTest[6086:15512106] JXcore Cordova plugin initializing
,2016-11-21 15:33:28.797 ThaliTest[6086:15512331] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 14:33:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 14:33:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 14:33:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 14:33:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 14:33:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-21 14:34:21 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  40.05357098579407
F,ailed to execute UT.
2016-11-21 14:34:21 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered

```
