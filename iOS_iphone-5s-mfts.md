#### Test 978514903f1da2e_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CF31E919-16DA-40AD-8BA4-9BA466F4A5BF/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/CF31E919-16DA-40AD-8BA4-9BA466F4A5BF/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/978514903f1da2e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7C5B185E-4B7E-4FF2-8650-385EC307046C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59849"
,(lldb)     command script import "/tmp/CF31E919-16DA-40AD-8BA4-9BA466F4A5BF/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-14 00:09:12.020 ThaliTest[614:853072] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0C7F454C-DF7F-44E5-B79D-530F282CBB11/Library/Cookies/Cookies.binarycookies
,2016-12-14 00:09:12.112 ThaliTest[614:853072] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-14 00:09:12.114 ThaliTest[614:853072] Multi-tasking -> Device: YES, App: YES
,2016-12-14 00:09:12.133 ThaliTest[614:853072] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-14 00:09:12.604 ThaliTest[614:853072] Using UIWebView
2016-12-14 00:09:12.616 ThaliTest[614:853072] [CDVTimer][handleopenurl] 0.389993ms
,2016-12-14 00:09:12.627 ThaliTest[614:853072] [CDVTimer][intentandnavigationfilter] 10.541975ms
2016-12-14 00:09:12.628 ThaliTest[614:853072] [CDVTimer][gesturehandler] 0.403047ms
2016-12-14 00:09:12.629 ThaliTest[614:853072] [CDVTimer][TotalPluginStartup] 13.734996ms
,2016-12-14 00:09:19.269 ThaliTest[614:853072] Resetting plugins due to page load.
,2016-12-14 00:09:19.742 ThaliTest[614:853072] Finished load of: file:///var/containers/Bundle/Application/7C5B185E-4B7E-4FF2-8650-385EC307046C/ThaliTest.app/www/index.html
,2016-12-14 00:09:20.146 ThaliTest[614:853072] JXcore Cordova plugin initializing
,2016-12-14 00:09:20.147 ThaliTest[614:853258] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 23:09:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 23:09:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 23:09:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 23:09:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 23:09:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 23:09:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.68851298093796
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
