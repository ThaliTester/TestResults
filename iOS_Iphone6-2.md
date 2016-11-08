#### Test 896247960fcbde9_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/DBB8D3A9-EE60-4ECF-8D9D-F24D3E81E482/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/DBB8D3A9-EE60-4ECF-8D9D-F24D3E81E482/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247960fcbde9/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/F35024B4-CE29-4F46-8524-33E0E3BA379C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64559"
,(lldb)     command script import "/tmp/DBB8D3A9-EE60-4ECF-8D9D-F24D3E81E482/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2016-11-08 02:17:06.519 ThaliTest[3116:7025787] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A08CD744-7A56-4F08-82BA-8D33E3ABB949/Library/Cookies/Cookies.binarycookies
,2016-11-08 02:17:06.567 ThaliTest[3116:7025787] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-08 02:17:06.568 ThaliTest[3116:7025787] Multi-tasking -> Device: YES, App: YES
,2016-11-08 02:17:06.581 ThaliTest[3116:7025787] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-08 02:17:07.012 ThaliTest[3116:7025787] Using UIWebView
2016-11-08 02:17:07.018 ThaliTest[3116:7025787] [CDVTimer][handleopenurl] 0.384033ms
,2016-11-08 02:17:07.027 ThaliTest[3116:7025787] [CDVTimer][intentandnavigationfilter] 8.284986ms
2016-11-08 02:17:07.028 ThaliTest[3116:7025787] [CDVTimer][gesturehandler] 0.310957ms
2016-11-08 02:17:07.028 ThaliTest[3116:7025787] [CDVTimer][TotalPluginS,tartup] 10.493994ms
,2016-11-08 02:17:12.978 ThaliTest[3116:7025787] Resetting plugins due to page load.
,2016-11-08 02:17:13.428 ThaliTest[3116:7025787] Finished load of: file:///var/containers/Bundle/Application/F35024B4-CE29-4F46-8524-33E0E3BA379C/ThaliTest.app/www/index.html
,2016-11-08 02:17:13.772 ThaliTest[3116:7025787] JXcore Cordova plugin initializing
,2016-11-08 02:17:13.773 ThaliTest[3116:7025972] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-08 10:17:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-08 10:17:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-08 10:17:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-08 10:17:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-08 10:17:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
,Optional(false)
,Optional(false)
Optional(true)
,2016-11-08 10:17:51 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  26.62613600492477
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
