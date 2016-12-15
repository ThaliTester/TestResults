#### Test 98149861816c514_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/3A6D4D2B-72A3-49A3-8AB6-5A06722FB46F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/3A6D4D2B-72A3-49A3-8AB6-5A06722FB46F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98149861816c514/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/3A01EA59-4779-4495-BDC4-63A6E5BA542E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51256"
,(lldb)     command script import "/tmp/3A6D4D2B-72A3-49A3-8AB6-5A06722FB46F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-15 18:50:09.986 ThaliTest[846:1403910] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/47C912B9-2234-4ED5-9ED5-0F834A7B771E/Library/Cookies/Cookies.binarycookies
,2016-12-15 18:50:10.333 ThaliTest[846:1403910] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-15 18:50:10.335 ThaliTest[846:1403910] Multi-tasking -> Device: YES, App: YES
,2016-12-15 18:50:10.354 ThaliTest[846:1403910] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-15 18:50:12.452 ThaliTest[846:1403910] Using UIWebView
,2016-12-15 18:50:12.459 ThaliTest[846:1403910] [CDVTimer][handleopenurl] 0.355959ms
,2016-12-15 18:50:12.466 ThaliTest[846:1403910] [CDVTimer][intentandnavigationfilter] 6.389022ms
,2016-12-15 18:50:12.467 ThaliTest[846:1403910] [CDVTimer][gesturehandler] 0.275016ms
,2016-12-15 18:50:12.467 ThaliTest[846:1403910] [CDVTimer][TotalPluginStartup] 8.598983ms
,2016-12-15 18:50:19.505 ThaliTest[846:1403910] Resetting plugins due to page load.
,2016-12-15 18:50:22.752 ThaliTest[846:1403910] Finished load of: file:///var/mobile/Containers/Bundle/Application/3A01EA59-4779-4495-BDC4-63A6E5BA542E/ThaliTest.app/www/index.html
,2016-12-15 18:50:22.971 ThaliTest[846:1403910] JXcore Cordova plugin initializing
,2016-12-15 18:50:22.972 ThaliTest[846:1404140] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-15 17:50:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-15 17:50:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-15 17:50:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-15 17:50:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-15 17:50:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-15 17:50:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.54143399000168
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
