#### Test 9772710378c4b3e_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/6A334752-8CB2-406C-AA70-53FFC6C148A9/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/6A334752-8CB2-406C-AA70-53FFC6C148A9/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9772710378c4b3e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/40FF76D4-ED0E-4077-8E01-CE87E8B96B7A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54420"
,(lldb)     command script import "/tmp/6A334752-8CB2-406C-AA70-53FFC6C148A9/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 13:34:04.435 ThaliTest[590:803746] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B762F742-9055-4141-BFCA-4AC575479356/Library/Cookies/Cookies.binarycookies
,2016-12-13 13:34:04.489 ThaliTest[590:803746] Apache Cordova native platform version 4.3.1 is starting.
2016-12-13 13:34:04.490 ThaliTest[590:803746] Multi-tasking -> Device: YES, App: YES
,2016-12-13 13:34:04.506 ThaliTest[590:803746] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 13:34:04.848 ThaliTest[590:803746] Using UIWebView
,2016-12-13 13:34:04.854 ThaliTest[590:803746] [CDVTimer][handleopenurl] 0.217974ms
,2016-12-13 13:34:04.860 ThaliTest[590:803746] [CDVTimer][intentandnavigationfilter] 5.771995ms
2016-12-13 13:34:04.860 ThaliTest[590:803746] [CDVTimer][gesturehandler] 0.190020ms
2016-12-13 13:34:04.861 ThaliTest[590:803746] [CDVTimer][TotalPluginStartup] 7.203043ms
,2016-12-13 13:34:11.541 ThaliTest[590:803746] Resetting plugins due to page load.
,2016-12-13 13:34:12.218 ThaliTest[590:803746] Finished load of: file:///var/containers/Bundle/Application/40FF76D4-ED0E-4077-8E01-CE87E8B96B7A/ThaliTest.app/www/index.html
,2016-12-13 13:34:12.642 ThaliTest[590:803746] JXcore Cordova plugin initializing
,2016-12-13 13:34:12.643 ThaliTest[590:803969] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 12:34:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 12:34:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 12:34:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-13 12:34:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 12:34:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-13 12:34:49 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.74301999807358
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
