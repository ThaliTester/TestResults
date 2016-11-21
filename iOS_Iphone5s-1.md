#### Test 935721679a8c53b_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721679a8c53b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/03C9A485-B77B-49BA-B2D6-31936F5AA557/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/03C9A485-B77B-49BA-B2D6-31936F5AA557/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721679a8c53b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721679a8c53b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CAA8AEBC-AF4B-4EFF-88B9-A3E6C3D64E53/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59614"
,(lldb)     command script import "/tmp/03C9A485-B77B-49BA-B2D6-31936F5AA557/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 17:13:30.870 ThaliTest[6119:15528813] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D1BC2CC0-9E60-418B-90BA-7D7DF0883E06/Library/Cookies/Cookies.binarycookies
,2016-11-21 17:13:30.982 ThaliTest[6119:15528813] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 17:13:30.984 ThaliTest[6119:15528813] Multi-tasking -> Device: YES, App: YES
,2016-11-21 17:13:31.004 ThaliTest[6119:15528813] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 17:13:32.668 ThaliTest[6119:15528813] Using UIWebView
,2016-11-21 17:13:32.677 ThaliTest[6119:15528813] [CDVTimer][handleopenurl] 1.827955ms
,2016-11-21 17:13:32.686 ThaliTest[6119:15528813] [CDVTimer][intentandnavigationfilter] 8.276999ms
2016-11-21 17:13:32.687 ThaliTest[6119:15528813] [CDVTimer][gesturehandler] 0.366986ms
2016-11-21 17:13:32.687 ThaliTest[6119:15528813] [CDVTimer][TotalPlug,inStartup] 12.419999ms
,2016-11-21 17:13:39.239 ThaliTest[6119:15528813] Resetting plugins due to page load.
,2016-11-21 17:13:43.644 ThaliTest[6119:15528813] Finished load of: file:///var/mobile/Containers/Bundle/Application/CAA8AEBC-AF4B-4EFF-88B9-A3E6C3D64E53/ThaliTest.app/www/index.html
,2016-11-21 17:13:43.953 ThaliTest[6119:15528813] JXcore Cordova plugin initializing
,2016-11-21 17:13:43.954 ThaliTest[6119:15529017] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 16:13:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 16:13:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 16:13:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 16:13:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 16:13:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 16:14:21 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.37039697170258
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
