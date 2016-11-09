#### Test 89624796ae60baf_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/89624796ae60baf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/CB792186-FDBC-4722-8F33-DFC104EB104F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/CB792186-FDBC-4722-8F33-DFC104EB104F/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/89624796ae60baf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/89624796ae60baf/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8A8BF921-B7BD-4CFD-8B2F-569517360643/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62965"
,(lldb)     command script import "/tmp/CB792186-FDBC-4722-8F33-DFC104EB104F/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 06:17:17.333 ThaliTest[3221:7180926] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/CA2F907E-A8A8-4266-BC42-2D9CD2C573D0/Library/Cookies/Cookies.binarycookies
,2016-11-09 06:17:17.413 ThaliTest[3221:7180926] Apache Cordova native platform version 4.2.1 is starting.
2016-11-09 06:17:17.414 ThaliTest[3221:7180926] Multi-tasking -> Device: YES, App: YES
,2016-11-09 06:17:17.437 ThaliTest[3221:7180926] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 06:17:18.057 ThaliTest[3221:7180926] Using UIWebView
,2016-11-09 06:17:18.067 ThaliTest[3221:7180926] [CDVTimer][handleopenurl] 0.414968ms
,2016-11-09 06:17:18.074 ThaliTest[3221:7180926] [CDVTimer][intentandnavigationfilter] 6.856024ms
2016-11-09 06:17:18.075 ThaliTest[3221:7180926] [CDVTimer][gesturehandler] 0.340998ms
2016-11-09 06:17:18.075 ThaliTest[3221:7180926] [CDVTimer][TotalPluginS,tartup] 9.268999ms
,2016-11-09 06:17:24.779 ThaliTest[3221:7180926] Resetting plugins due to page load.
,2016-11-09 06:17:25.418 ThaliTest[3221:7180926] Finished load of: file:///var/containers/Bundle/Application/8A8BF921-B7BD-4CFD-8B2F-569517360643/ThaliTest.app/www/index.html
,2016-11-09 06:17:25.834 ThaliTest[3221:7180926] JXcore Cordova plugin initializing
,2016-11-09 06:17:25.835 ThaliTest[3221:7181105] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 14:17:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-09 14:17:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 14:17:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-09 14:17:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-09 14:17:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-09 14:18:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  23.90911799669266
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
