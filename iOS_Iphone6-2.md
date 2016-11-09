#### Test 896247965a92e74_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/2C87F36C-E8FC-4EAC-BA09-6410303481AF/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/2C87F36C-E8FC-4EAC-BA09-6410303481AF/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DADBB012-80D9-4F79-995A-BEA24A42264C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62047"
,(lldb)     command script import "/tmp/2C87F36C-E8FC-4EAC-BA09-6410303481AF/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 05:57:35.252 ThaliTest[3213:7177682] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CFA4F3BF-478B-464A-987B-439B8A2DA612/Library/Cookies/Cookies.binarycookies
,2016-11-09 05:57:35.301 ThaliTest[3213:7177682] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 05:57:35.303 ThaliTest[3213:7177682] Multi-tasking -> Device: YES, App: YES
,2016-11-09 05:57:35.320 ThaliTest[3213:7177682] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 05:57:35.633 ThaliTest[3213:7177682] Using UIWebView
,2016-11-09 05:57:35.637 ThaliTest[3213:7177682] [CDVTimer][handleopenurl] 0.196040ms
,2016-11-09 05:57:35.641 ThaliTest[3213:7177682] [CDVTimer][intentandnavigationfilter] 3.757000ms
2016-11-09 05:57:35.641 ThaliTest[3213:7177682] [CDVTimer][gesturehandler] 0.169039ms
2016-11-09 05:57:35.641 ThaliTest[3213:7177682] [CDVTimer][TotalPluginStartup] 4.934013ms
,2016-11-09 05:57:41.004 ThaliTest[3213:7177682] Resetting plugins due to page load.
,2016-11-09 05:57:41.299 ThaliTest[3213:7177682] Finished load of: file:///var/containers/Bundle/Application/DADBB012-80D9-4F79-995A-BEA24A42264C/ThaliTest.app/www/index.html
,2016-11-09 05:57:41.633 ThaliTest[3213:7177682] JXcore Cordova plugin initializing
,2016-11-09 05:57:41.634 ThaliTest[3213:7177890] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 13:57:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 13:57:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 13:57:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 13:57:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 13:57:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-09 13:58:17 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.92336601018906
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
