#### Test 9357216729ac2d0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/90C25D0A-613B-47F8-A665-BDD5A155AACD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/90C25D0A-613B-47F8-A665-BDD5A155AACD/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9357216729ac2d0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/DD8C2CB1-BA93-45EA-BAE4-8F999DC29116/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52314"
,(lldb)     command script import "/tmp/90C25D0A-613B-47F8-A665-BDD5A155AACD/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 12:16:25.671 ThaliTest[5869:14860079] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EFBEC28A-5D63-44D3-B196-B94F0C687ABF/Library/Cookies/Cookies.binarycookies
,2016-11-17 12:16:25.733 ThaliTest[5869:14860079] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 12:16:25.735 ThaliTest[5869:14860079] Multi-tasking -> Device: YES, App: YES
,2016-11-17 12:16:25.751 ThaliTest[5869:14860079] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 12:16:26.542 ThaliTest[5869:14860079] Using UIWebView
2016-11-17 12:16:26.545 ThaliTest[5869:14860079] [CDVTimer][handleopenurl] 0.169992ms
2016-11-17 12:16:26.548 ThaliTest[5869:14860079] [CDVTimer][intentandnavigationfilter] 2.777994ms
,2016-11-17 12:16:26.549 ThaliTest[5869:14860079] [CDVTimer][gesturehandler] 1.276970ms
2016-11-17 12:16:26.549 ThaliTest[5869:14860079] [CDVTimer][TotalPluginStartup] 4.933000ms
,2016-11-17 12:16:29.558 ThaliTest[5869:14860079] Resetting plugins due to page load.
,2016-11-17 12:16:31.207 ThaliTest[5869:14860079] Finished load of: file:///var/mobile/Containers/Bundle/Application/DD8C2CB1-BA93-45EA-BAE4-8F999DC29116/ThaliTest.app/www/index.html
,2016-11-17 12:16:31.400 ThaliTest[5869:14860079] JXcore Cordova plugin initializing
,2016-11-17 12:16:31.401 ThaliTest[5869:14860256] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 11:16:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-17 11:16:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 11:16:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 11:16:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-17 11:16:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-17 11:17:09 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.84358602762222
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
