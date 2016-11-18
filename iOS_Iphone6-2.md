#### Test 921522864f1c710_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/7CBE6C0F-BE3E-4857-9388-086A185F9741/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/7CBE6C0F-BE3E-4857-9388-086A185F9741/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B0705144-42D1-4A61-9BCD-9C6C420D82A6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63297"
,(lldb)     command script import "/tmp/7CBE6C0F-BE3E-4857-9388-086A185F9741/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 05:31:12.387 ThaliTest[3685:8318073] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EBE30E8D-A84A-4678-9EE6-C4900690F626/Library/Cookies/Cookies.binarycookies
,2016-11-18 05:31:12.426 ThaliTest[3685:8318073] Apache Cordova native platform version 4.2.1 is starting.
2016-11-18 05:31:12.427 ThaliTest[3685:8318073] Multi-tasking -> Device: YES, App: YES
,2016-11-18 05:31:12.438 ThaliTest[3685:8318073] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 05:31:12.750 ThaliTest[3685:8318073] Using UIWebView
,2016-11-18 05:31:12.756 ThaliTest[3685:8318073] [CDVTimer][handleopenurl] 0.301003ms
,2016-11-18 05:31:12.759 ThaliTest[3685:8318073] [CDVTimer][intentandnavigationfilter] 3.453016ms
2016-11-18 05:31:12.760 ThaliTest[3685:8318073] [CDVTimer][gesturehandler] 0.137985ms
2016-11-18 05:31:12.760 ThaliTest[3685:8318073] [CDVTimer][TotalPluginStartup] 4.714966ms
,2016-11-18 05:31:18.599 ThaliTest[3685:8318073] Resetting plugins due to page load.
,2016-11-18 05:31:18.981 ThaliTest[3685:8318073] Finished load of: file:///var/containers/Bundle/Application/B0705144-42D1-4A61-9BCD-9C6C420D82A6/ThaliTest.app/www/index.html
,2016-11-18 05:31:19.344 ThaliTest[3685:8318073] JXcore Cordova plugin initializing
,2016-11-18 05:31:19.345 ThaliTest[3685:8318260] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 13:31:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 13:31:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 13:31:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-18 13:31:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 13:31:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 13:31:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-18 13:31:53 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.5278280377388
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
