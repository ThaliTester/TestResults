#### Test 977271034c6c8cc_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/399BFA98-4BD9-4B87-9F70-EC206A5FDD22/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/399BFA98-4BD9-4B87-9F70-EC206A5FDD22/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/977271034c6c8cc/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E886311C-996C-49AC-B187-983CB9EECC74/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52725"
,(lldb)     command script import "/tmp/399BFA98-4BD9-4B87-9F70-EC206A5FDD22/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 12:18:55.497 ThaliTest[581:796598] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/94CA5967-C7AC-47A0-B5AA-DDBA42F924AA/Library/Cookies/Cookies.binarycookies
,2016-12-13 12:18:55.604 ThaliTest[581:796598] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 12:18:55.607 ThaliTest[581:796598] Multi-tasking -> Device: YES, App: YES
,2016-12-13 12:18:55.628 ThaliTest[581:796598] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 12:18:55.979 ThaliTest[581:796598] Using UIWebView
,2016-12-13 12:18:55.984 ThaliTest[581:796598] [CDVTimer][handleopenurl] 0.436008ms
,2016-12-13 12:18:55.992 ThaliTest[581:796598] [CDVTimer][intentandnavigationfilter] 6.980956ms
2016-12-13 12:18:55.992 ThaliTest[581:796598] [CDVTimer][gesturehandler] 0.267029ms
2016-12-13 12:18:55.993 ThaliTest[581:796598] [CDVTimer][TotalPluginStartup,] 9.020030ms
,2016-12-13 12:19:02.829 ThaliTest[581:796598] Resetting plugins due to page load.
,2016-12-13 12:19:03.297 ThaliTest[581:796598] Finished load of: file:///var/containers/Bundle/Application/E886311C-996C-49AC-B187-983CB9EECC74/ThaliTest.app/www/index.html
,2016-12-13 12:19:03.699 ThaliTest[581:796598] JXcore Cordova plugin initializing
,2016-12-13 12:19:03.700 ThaliTest[581:796799] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 11:19:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 11:19:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 11:19:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 11:19:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 11:19:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 11:19:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.7084059715271
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
