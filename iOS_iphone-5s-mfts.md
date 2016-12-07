#### Test 96524298edd5c74_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/08D4378A-A4EF-472F-9489-FA5954E490DD/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/08D4378A-A4EF-472F-9489-FA5954E490DD/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/96524298edd5c74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A06B1102-68D6-4C00-815A-45E7152ED85E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60877"
,(lldb)     command script import "/tmp/08D4378A-A4EF-472F-9489-FA5954E490DD/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 12:51:09.717 ThaliTest[311:132187] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/419F22AD-C667-4707-81E8-610802A6CBA3/Library/Cookies/Cookies.binarycookies
,2016-12-07 12:51:09.827 ThaliTest[311:132187] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 12:51:09.829 ThaliTest[311:132187] Multi-tasking -> Device: YES, App: YES
,2016-12-07 12:51:09.851 ThaliTest[311:132187] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 12:51:10.306 ThaliTest[311:132187] Using UIWebView
,2016-12-07 12:51:10.315 ThaliTest[311:132187] [CDVTimer][handleopenurl] 0.577986ms
,2016-12-07 12:51:10.325 ThaliTest[311:132187] [CDVTimer][intentandnavigationfilter] 9.074032ms
2016-12-07 12:51:10.325 ThaliTest[311:132187] [CDVTimer][gesturehandler] 0.361979ms
2016-12-07 12:51:10.326 ThaliTest[311:132187] [CDVTimer][TotalPluginStartup,] 11.943996ms
,2016-12-07 12:51:16.589 ThaliTest[311:132187] Resetting plugins due to page load.
,2016-12-07 12:51:16.923 ThaliTest[311:132187] Finished load of: file:///var/containers/Bundle/Application/A06B1102-68D6-4C00-815A-45E7152ED85E/ThaliTest.app/www/index.html
,2016-12-07 12:51:17.324 ThaliTest[311:132187] JXcore Cordova plugin initializing
,2016-12-07 12:51:17.325 ThaliTest[311:132410] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 11:51:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 11:51:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 11:51:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-07 11:51:56 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.55754601955414
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
