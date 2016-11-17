#### Test 9376531757daca3_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9376531757daca3/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/C65C7DC7-9F67-48EC-9077-2D2E37FE355E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/C65C7DC7-9F67-48EC-9077-2D2E37FE355E/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9376531757daca3/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9376531757daca3/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0949A9DB-A84F-4E91-AB35-09850B6CBD0B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57354"
,(lldb)     command script import "/tmp/C65C7DC7-9F67-48EC-9077-2D2E37FE355E/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 14:12:35.802 ThaliTest[3619:9168203] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2B026773-1E3A-401A-AD09-695C98AC3F50/Library/Cookies/Cookies.binarycookies
,2016-11-17 14:12:35.881 ThaliTest[3619:9168203] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-17 14:12:35.884 ThaliTest[3619:9168203] Multi-tasking -> Device: YES, App: YES
,2016-11-17 14:12:35.906 ThaliTest[3619:9168203] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 14:12:36.236 ThaliTest[3619:9168203] Using UIWebView
,2016-11-17 14:12:36.241 ThaliTest[3619:9168203] [CDVTimer][handleopenurl] 0.342011ms
,2016-11-17 14:12:36.246 ThaliTest[3619:9168203] [CDVTimer][intentandnavigationfilter] 4.610956ms
2016-11-17 14:12:36.247 ThaliTest[3619:9168203] [CDVTimer][gesturehandler] 0.181019ms
2016-11-17 14:12:36.247 ThaliTest[3619:9168203] [CDVTimer][TotalPluginStartup] 6.240010ms
,2016-11-17 14:12:41.468 ThaliTest[3619:9168203] Resetting plugins due to page load.
,2016-11-17 14:12:41.801 ThaliTest[3619:9168203] Finished load of: file:///var/containers/Bundle/Application/0949A9DB-A84F-4E91-AB35-09850B6CBD0B/ThaliTest.app/www/index.html
,2016-11-17 14:12:42.131 ThaliTest[3619:9168203] JXcore Cordova plugin initializing
,2016-11-17 14:12:42.131 ThaliTest[3619:9168365] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 13:12:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 13:12:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 13:12:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 13:12:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 13:12:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-17 13:13:17 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.58569604158401
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
