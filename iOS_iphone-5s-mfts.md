#### Test 993933123c9286c_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/782955BA-C7AA-4697-AF32-C9276082020B/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/782955BA-C7AA-4697-AF32-C9276082020B/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/993933123c9286c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6A99A9E8-2033-4295-ADBC-7D7499833F24/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54772"
,(lldb)     command script import "/tmp/782955BA-C7AA-4697-AF32-C9276082020B/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 00:21:54.296 ThaliTest[1221:2392337] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/45A7A6CB-2518-431E-A815-B490EBAE60CD/Library/Cookies/Cookies.binarycookies
,2016-12-27 00:21:54.350 ThaliTest[1221:2392337] Apache Cordova native platform version 4.3.1 is starting.
2016-12-27 00:21:54.351 ThaliTest[1221:2392337] Multi-tasking -> Device: YES, App: YES
2016-12-27 00:21:54.367 ThaliTest[1221:2392337] 

Started b,ackup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 00:21:54.676 ThaliTest[1221:2392337] Using UIWebView
2016-12-27 00:21:54.679 ThaliTest[1221:2392337] [CDVTimer][handleopenurl] 0.147998ms
,2016-12-27 00:21:54.683 ThaliTest[1221:2392337] [CDVTimer][intentandnavigationfilter] 4.427016ms
2016-12-27 00:21:54.684 ThaliTest[1221:2392337] [CDVTimer][gesturehandler] 0.149965ms
2016-12-27 00:21:54.684 ThaliTest[1221:2392337] [CDVTimer][TotalPluginStartup] 5.451977ms
,2016-12-27 00:21:58.445 ThaliTest[1221:2392337] Resetting plugins due to page load.
,2016-12-27 00:21:58.743 ThaliTest[1221:2392337] Finished load of: file:///var/containers/Bundle/Application/6A99A9E8-2033-4295-ADBC-7D7499833F24/ThaliTest.app/www/index.html
,2016-12-27 00:21:59.216 ThaliTest[1221:2392337] JXcore Cordova plugin initializing
2016-12-27 00:21:59.217 ThaliTest[1221:2392505] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-26 23:22:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-26 23:22:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-26 23:22:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-26 23:22:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-26 23:22:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-26 23:22:41 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.29337197542191
*,***TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
,appEnteredForeground wasn't registered
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
appEnteringBackground wasn't registered

```
