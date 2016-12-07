#### Test 962930629a6bd77_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/962930629a6bd77/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/677A9FFB-F99D-41DD-B0F1-C1CBDB172D13/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/677A9FFB-F99D-41DD-B0F1-C1CBDB172D13/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/962930629a6bd77/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/962930629a6bd77/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/4CC54F8E-43EA-4037-93F4-3BB62E6E1458/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52856"
,(lldb)     command script import "/tmp/677A9FFB-F99D-41DD-B0F1-C1CBDB172D13/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-07 16:22:10.193 ThaliTest[347:154651] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/F70A9826-4AD6-49E4-97A0-8582F31DF0FD/Library/Cookies/Cookies.binarycookies
,2016-12-07 16:22:10.241 ThaliTest[347:154651] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-07 16:22:10.242 ThaliTest[347:154651] Multi-tasking -> Device: YES, App: YES
,2016-12-07 16:22:10.256 ThaliTest[347:154651] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-07 16:22:10.614 ThaliTest[347:154651] Using UIWebView
,2016-12-07 16:22:10.619 ThaliTest[347:154651] [CDVTimer][handleopenurl] 0.322998ms
,2016-12-07 16:22:10.627 ThaliTest[347:154651] [CDVTimer][intentandnavigationfilter] 6.802976ms
2016-12-07 16:22:10.627 ThaliTest[347:154651] [CDVTimer][gesturehandler] 0.257015ms
2016-12-07 16:22:10.628 ThaliTest[347:154651] [CDVTimer][TotalPluginStartup] 8.700013ms
,2016-12-07 16:22:16.549 ThaliTest[347:154651] Resetting plugins due to page load.
,2016-12-07 16:22:17.144 ThaliTest[347:154651] Finished load of: file:///var/containers/Bundle/Application/4CC54F8E-43EA-4037-93F4-3BB62E6E1458/ThaliTest.app/www/index.html
,2016-12-07 16:22:17.575 ThaliTest[347:154651] JXcore Cordova plugin initializing
,2016-12-07 16:22:17.576 ThaliTest[347:154836] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-07 15:22:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-07 15:22:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-07 15:22:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-07 15:22:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-07 15:22:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-12-07 15:22:54 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  24.40689998865128
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
,appEnteringBackground wasn't registered

```
