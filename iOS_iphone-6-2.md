#### Test 102271039a5a4541_iOS_iphone-6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7BE8EC01-593B-4502-82D0-CFEC63B724FC/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/7BE8EC01-593B-4502-82D0-CFEC63B724FC/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102271039a5a4541/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/3538F085-F895-4485-B260-7F483025024B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63961"
,(lldb)     command script import "/tmp/7BE8EC01-593B-4502-82D0-CFEC63B724FC/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-24 18:13:57.053 ThaliTest[4415:1866384] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5CA1C1CD-8EA1-451D-A969-3937574DB15F/Library/Cookies/Cookies.binarycookies
,2017-01-24 18:13:57.100 ThaliTest[4415:1866384] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-24 18:13:57.101 ThaliTest[4415:1866384] Multi-tasking -> Device: YES, App: YES
,2017-01-24 18:13:57.118 ThaliTest[4415:1866384] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-24 18:13:57.436 ThaliTest[4415:1866384] Using UIWebView
2017-01-24 18:13:57.439 ThaliTest[4415:1866384] [CDVTimer][handleopenurl] 0.156999ms
,2017-01-24 18:13:57.445 ThaliTest[4415:1866384] [CDVTimer][intentandnavigationfilter] 5.369008ms
2017-01-24 18:13:57.445 ThaliTest[4415:1866384] [CDVTimer][gesturehandler] 0.155032ms
2017-01-24 18:13:57.445 ThaliTest[4415:1866384] [CDVTimer][TotalPluginStartup] 6.461024ms
,2017-01-24 18:14:03.524 ThaliTest[4415:1866384] Resetting plugins due to page load.
,2017-01-24 18:14:03.887 ThaliTest[4415:1866384] Finished load of: file:///var/containers/Bundle/Application/3538F085-F895-4485-B260-7F483025024B/ThaliTest.app/www/index.html
,2017-01-24 18:14:04.252 ThaliTest[4415:1866384] JXcore Cordova plugin initializing
,2017-01-24 18:14:04.252 ThaliTest[4415:1866576] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-24 17:14:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-24 17:14:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-24 17:14:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-24 17:14:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-24 17:14:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-24 17:14:40 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.7007640004158
**,**TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
