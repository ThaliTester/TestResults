#### Test 935721679a8c53b_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/935721679a8c53b/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/86C02051-5ED0-41A8-998A-76215451FD9F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/86C02051-5ED0-41A8-998A-76215451FD9F/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/935721679a8c53b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/935721679a8c53b/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/52088824-3F2B-4E5D-94FC-5635FEB3E9B2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59610"
,(lldb)     command script import "/tmp/86C02051-5ED0-41A8-998A-76215451FD9F/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 17:13:16.093 ThaliTest[3827:9750177] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/9BE0FBB0-9E8D-4717-BCA1-E1F48F6196E7/Library/Cookies/Cookies.binarycookies
,2016-11-21 17:13:16.162 ThaliTest[3827:9750177] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 17:13:16.163 ThaliTest[3827:9750177] Multi-tasking -> Device: YES, App: YES
,2016-11-21 17:13:16.181 ThaliTest[3827:9750177] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 17:13:16.603 ThaliTest[3827:9750177] Using UIWebView
,2016-11-21 17:13:16.610 ThaliTest[3827:9750177] [CDVTimer][handleopenurl] 0.373006ms
,2016-11-21 17:13:16.617 ThaliTest[3827:9750177] [CDVTimer][intentandnavigationfilter] 6.793976ms
2016-11-21 17:13:16.618 ThaliTest[3827:9750177] [CDVTimer][gesturehandler] 0.268996ms
2016-11-21 17:13:16.618 ThaliTest[3827:9750177] [CDVTimer][TotalPluginS,tartup] 9.014010ms
,2016-11-21 17:13:22.164 ThaliTest[3827:9750177] Resetting plugins due to page load.
,2016-11-21 17:13:22.536 ThaliTest[3827:9750177] Finished load of: file:///var/containers/Bundle/Application/52088824-3F2B-4E5D-94FC-5635FEB3E9B2/ThaliTest.app/www/index.html
,2016-11-21 17:13:22.871 ThaliTest[3827:9750177] JXcore Cordova plugin initializing
,2016-11-21 17:13:22.871 ThaliTest[3827:9750352] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 16:13:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 16:13:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 16:13:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 16:13:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 16:13:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 16:13:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.73297101259232
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
