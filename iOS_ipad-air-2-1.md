#### Test 97920233248158d_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/AD0F04E5-ACCE-4C3E-8FF0-808A5E5CF751/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AD0F04E5-ACCE-4C3E-8FF0-808A5E5CF751/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/97920233248158d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/E817C144-EE59-4E8E-8714-5793BADF7BDF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56667"
,(lldb)     command script import "/tmp/AD0F04E5-ACCE-4C3E-8FF0-808A5E5CF751/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 15:09:53.486 ThaliTest[763:1236818] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7E24DF13-0A70-40B6-98CC-9187E26C8749/Library/Cookies/Cookies.binarycookies
,2016-12-14 15:09:53.820 ThaliTest[763:1236818] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 15:09:53.821 ThaliTest[763:1236818] Multi-tasking -> Device: YES, App: YES
,2016-12-14 15:09:53.837 ThaliTest[763:1236818] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 15:09:55.706 ThaliTest[763:1236818] Using UIWebView
,2016-12-14 15:09:55.713 ThaliTest[763:1236818] [CDVTimer][handleopenurl] 0.432968ms
,2016-12-14 15:09:55.720 ThaliTest[763:1236818] [CDVTimer][intentandnavigationfilter] 7.330954ms
,2016-12-14 15:09:55.721 ThaliTest[763:1236818] [CDVTimer][gesturehandler] 0.338972ms
2016-12-14 15:09:55.722 ThaliTest[763:1236818] [CDVTimer][TotalPluginStartup] 9.853005ms
,2016-12-14 15:10:02.419 ThaliTest[763:1236818] Resetting plugins due to page load.
,2016-12-14 15:10:06.190 ThaliTest[763:1236818] Finished load of: file:///var/mobile/Containers/Bundle/Application/E817C144-EE59-4E8E-8714-5793BADF7BDF/ThaliTest.app/www/index.html
,2016-12-14 15:10:06.420 ThaliTest[763:1236818] JXcore Cordova plugin initializing
,2016-12-14 15:10:06.421 ThaliTest[763:1237053] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-14 14:10:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-14 14:10:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-14 14:10:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-14 14:10:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-14 14:10:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-14 14:10:42 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.28349995613098
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
