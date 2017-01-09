#### Test 996748488b0f149_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/158099EA-BB0E-404E-AE75-1B0FA889520F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/158099EA-BB0E-404E-AE75-1B0FA889520F/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/996748488b0f149/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0408776F-FB90-41AF-82CA-D2FF896AC05C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54033"
,(lldb)     command script import "/tmp/158099EA-BB0E-404E-AE75-1B0FA889520F/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-09 12:54:18.882 ThaliTest[1817:4074184] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4480889E-81CD-41CE-8FC6-0EDF4FBE92DC/Library/Cookies/Cookies.binarycookies
,2017-01-09 12:54:18.931 ThaliTest[1817:4074184] Apache Cordova native platform version 4.3.1 is starting.
2017-01-09 12:54:18.933 ThaliTest[1817:4074184] Multi-tasking -> Device: YES, App: YES
,2017-01-09 12:54:18.956 ThaliTest[1817:4074184] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-09 12:54:19.213 ThaliTest[1817:4074184] Using UIWebView
2017-01-09 12:54:19.216 ThaliTest[1817:4074184] [CDVTimer][handleopenurl] 0.144005ms
,2017-01-09 12:54:19.220 ThaliTest[1817:4074184] [CDVTimer][intentandnavigationfilter] 4.366994ms
2017-01-09 12:54:19.221 ThaliTest[1817:4074184] [CDVTimer][gesturehandler] 0.144958ms
2017-01-09 12:54:19.221 ThaliTest[1817:4074184] [CDVTimer][TotalPluginStartup] 5.315006ms
,2017-01-09 12:54:22.503 ThaliTest[1817:4074184] Resetting plugins due to page load.
,2017-01-09 12:54:22.778 ThaliTest[1817:4074184] Finished load of: file:///var/containers/Bundle/Application/0408776F-FB90-41AF-82CA-D2FF896AC05C/ThaliTest.app/www/index.html
,2017-01-09 12:54:23.174 ThaliTest[1817:4074184] JXcore Cordova plugin initializing
,2017-01-09 12:54:23.175 ThaliTest[1817:4074337] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-09 11:54:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-09 11:54:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-09 11:54:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2017-01-09 11:54:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-09 11:54:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-09 11:55:00 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.26246798038483
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
