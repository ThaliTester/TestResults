#### Test 937653172c2e8c7_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/4092E3B0-BEFE-43C7-8BD2-E093FD6FAB48/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/4092E3B0-BEFE-43C7-8BD2-E093FD6FAB48/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/937653172c2e8c7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3AAFF3CC-45ED-46BC-8A04-09BC9422E294/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51263"
,(lldb)     command script import "/tmp/4092E3B0-BEFE-43C7-8BD2-E093FD6FAB48/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 11:51:46.434 ThaliTest[5861:14856891] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4B2A0E24-012D-4646-B170-C03A54EDCC47/Library/Cookies/Cookies.binarycookies
,2016-11-17 11:51:46.495 ThaliTest[5861:14856891] Apache Cordova native platform version 4.2.1 is starting.
2016-11-17 11:51:46.496 ThaliTest[5861:14856891] Multi-tasking -> Device: YES, App: YES
,2016-11-17 11:51:46.514 ThaliTest[5861:14856891] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 11:51:47.309 ThaliTest[5861:14856891] Using UIWebView
,2016-11-17 11:51:47.313 ThaliTest[5861:14856891] [CDVTimer][handleopenurl] 0.169039ms
2016-11-17 11:51:47.316 ThaliTest[5861:14856891] [CDVTimer][intentandnavigationfilter] 2.736032ms
2016-11-17 11:51:47.317 ThaliTest[5861:14856891] [CDVTimer][gesturehan,dler] 0.138998ms
2016-11-17 11:51:47.317 ThaliTest[5861:14856891] [CDVTimer][TotalPluginStartup] 3.693044ms
,2016-11-17 11:51:50.466 ThaliTest[5861:14856891] Resetting plugins due to page load.
,2016-11-17 11:51:52.163 ThaliTest[5861:14856891] Finished load of: file:///var/mobile/Containers/Bundle/Application/3AAFF3CC-45ED-46BC-8A04-09BC9422E294/ThaliTest.app/www/index.html
,2016-11-17 11:51:52.352 ThaliTest[5861:14856891] JXcore Cordova plugin initializing
,2016-11-17 11:51:52.353 ThaliTest[5861:14857066] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 10:52:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 10:52:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 10:52:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 10:52:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 10:52:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-17 10:52:30 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.23704600334167
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
