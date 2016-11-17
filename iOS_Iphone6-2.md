#### Test 937653176a1f39f_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/937653176a1f39f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/9FA661DA-7387-499B-9920-C8E61355F3EB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/9FA661DA-7387-499B-9920-C8E61355F3EB/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/937653176a1f39f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/937653176a1f39f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EEB99E4B-8E01-44BD-8993-C595D8E11ADC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49383"
,(lldb)     command script import "/tmp/9FA661DA-7387-499B-9920-C8E61355F3EB/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-17 02:01:06.133 ThaliTest[3596:8166464] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3EC16674-7FA8-41CE-AD57-60E79156E850/Library/Cookies/Cookies.binarycookies
,2016-11-17 02:01:06.223 ThaliTest[3596:8166464] Apache Cordova native platform version 4.2.1 is starting.
2016-11-17 02:01:06.225 ThaliTest[3596:8166464] Multi-tasking -> Device: YES, App: YES
,2016-11-17 02:01:06.249 ThaliTest[3596:8166464] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-17 02:01:06.766 ThaliTest[3596:8166464] Using UIWebView
2016-11-17 02:01:06.773 ThaliTest[3596:8166464] [CDVTimer][handleopenurl] 1.200020ms
2016-11-17 02:01:06.780 ThaliTest[3596:8166464] [CDVTimer][intentandnavigationfilter] 6.841004ms
,2016-11-17 02:01:06.782 ThaliTest[3596:8166464] [CDVTimer][gesturehandler] 0.274003ms
,2016-11-17 02:01:06.782 ThaliTest[3596:8166464] [CDVTimer][TotalPluginStartup] 10.800958ms
,2016-11-17 02:01:13.641 ThaliTest[3596:8166464] Resetting plugins due to page load.
,2016-11-17 02:01:14.030 ThaliTest[3596:8166464] Finished load of: file:///var/containers/Bundle/Application/EEB99E4B-8E01-44BD-8993-C595D8E11ADC/ThaliTest.app/www/index.html
,2016-11-17 02:01:14.369 ThaliTest[3596:8166464] JXcore Cordova plugin initializing
,2016-11-17 02:01:14.370 ThaliTest[3596:8166692] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-17 10:01:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-17 10:01:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-17 10:01:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-17 10:01:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-17 10:01:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Asynchronous wait failed: Exceeded timeout of 15 seconds, with unfulfilled expectations: "Advertiser's fake node server received a message". in file: Optional("<unknown>"), line: 0
,2016-11-17 10:02:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  115
Number of failed tests:  1
Number of ignored tests:  0
Total duration:  39.0115020275116
Fa,iled to execute UT.
2016-11-17 10:02:03 - DEBUG UnitTest_app: 'Failed to execute UT.'
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered

```
