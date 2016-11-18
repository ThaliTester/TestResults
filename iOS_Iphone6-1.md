#### Test 9215228616bd023_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9215228616bd023/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/D40CC582-F3A3-426E-8B67-6E1BCD12D21C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/D40CC582-F3A3-426E-8B67-6E1BCD12D21C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9215228616bd023/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9215228616bd023/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9C72376F-934E-4729-A32A-7254E5BC05F4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60363"
,(lldb)     command script import "/tmp/D40CC582-F3A3-426E-8B67-6E1BCD12D21C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 13:30:36.386 ThaliTest[3663:9302874] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D11E163-5538-4F0D-A1C0-0EABE2146356/Library/Cookies/Cookies.binarycookies
,2016-11-18 13:30:36.428 ThaliTest[3663:9302874] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 13:30:36.429 ThaliTest[3663:9302874] Multi-tasking -> Device: YES, App: YES
,2016-11-18 13:30:36.441 ThaliTest[3663:9302874] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 13:30:36.712 ThaliTest[3663:9302874] Using UIWebView
,2016-11-18 13:30:36.715 ThaliTest[3663:9302874] [CDVTimer][handleopenurl] 0.154018ms
,2016-11-18 13:30:36.718 ThaliTest[3663:9302874] [CDVTimer][intentandnavigationfilter] 2.703965ms
2016-11-18 13:30:36.718 ThaliTest[3663:9302874] [CDVTimer][gesturehandler] 0.120997ms
2016-11-18 13:30:36.718 ThaliTest[3663:9302874] [CDVTimer][TotalPluginStartup] 3.629982ms
,2016-11-18 13:30:41.919 ThaliTest[3663:9302874] Resetting plugins due to page load.
,2016-11-18 13:30:42.360 ThaliTest[3663:9302874] Finished load of: file:///var/containers/Bundle/Application/9C72376F-934E-4729-A32A-7254E5BC05F4/ThaliTest.app/www/index.html
,2016-11-18 13:30:42.764 ThaliTest[3663:9302874] JXcore Cordova plugin initializing
,2016-11-18 13:30:42.765 ThaliTest[3663:9303033] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 12:30:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 12:30:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 12:30:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-18 12:30:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 12:30:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 12:30:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-18 12:31:17 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.78903698921204
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
