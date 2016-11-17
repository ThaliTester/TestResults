#### Test 9378027201b8727_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9378027201b8727/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/417E6788-61A9-4281-AEF4-C27418466435/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/417E6788-61A9-4281-AEF4-C27418466435/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9378027201b8727/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9378027201b8727/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/A3D5FEB0-5EFF-44E2-A975-35675C4D85CB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64230"
,(lldb)     command script import "/tmp/417E6788-61A9-4281-AEF4-C27418466435/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 09:40:47.756 ThaliTest[5833:14837801] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/6C48009E-EC15-42DE-816D-D7A4B898788E/Library/Cookies/Cookies.binarycookies
,2016-11-17 09:40:47.819 ThaliTest[5833:14837801] Apache Cordova native platform version 4.2.1 is starting.
2016-11-17 09:40:47.820 ThaliTest[5833:14837801] Multi-tasking -> Device: YES, App: YES
,2016-11-17 09:40:47.839 ThaliTest[5833:14837801] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 09:40:48.596 ThaliTest[5833:14837801] Using UIWebView
2016-11-17 09:40:48.599 ThaliTest[5833:14837801] [CDVTimer][handleopenurl] 0.167012ms
2016-11-17 09:40:48.602 ThaliTest[5833:14837801] [CDVTimer][intentandnavigationfilter] 2.802968ms
2016-11-17 09:40:48.602 ThaliTest[5833:14837801] [CDVTimer][gesturehandler] 0.149012ms
2016-11-17 09:40:48.602 ThaliTest[5833:14837801] [CDVTimer][TotalPluginStartup] 3.749013ms
,2016-11-17 09:40:51.647 ThaliTest[5833:14837801] Resetting plugins due to page load.
,2016-11-17 09:40:53.190 ThaliTest[5833:14837801] Finished load of: file:///var/mobile/Containers/Bundle/Application/A3D5FEB0-5EFF-44E2-A975-35675C4D85CB/ThaliTest.app/www/index.html
,2016-11-17 09:40:53.483 ThaliTest[5833:14837801] JXcore Cordova plugin initializing
,2016-11-17 09:40:53.484 ThaliTest[5833:14837959] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 08:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 08:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 08:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 08:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 08:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-17 08:41:29 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.52894198894501
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
