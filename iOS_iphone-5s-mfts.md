#### Test 1006908264485454_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F43E4C09-020C-412B-AC23-1D17129C56AC/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/F43E4C09-020C-412B-AC23-1D17129C56AC/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1006908264485454/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7B3B62A5-E0D9-4A3F-A0F2-E192828EAEC2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57301"
,(lldb)     command script import "/tmp/F43E4C09-020C-412B-AC23-1D17129C56AC/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-09 15:40:34.892 ThaliTest[1832:4091542] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/1EBCB5B5-0462-4CB6-8551-99ABD5656B46/Library/Cookies/Cookies.binarycookies
,2017-01-09 15:40:34.952 ThaliTest[1832:4091542] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-09 15:40:34.953 ThaliTest[1832:4091542] Multi-tasking -> Device: YES, App: YES
,2017-01-09 15:40:34.972 ThaliTest[1832:4091542] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-09 15:40:35.232 ThaliTest[1832:4091542] Using UIWebView
,2017-01-09 15:40:35.235 ThaliTest[1832:4091542] [CDVTimer][handleopenurl] 0.152051ms
,2017-01-09 15:40:35.239 ThaliTest[1832:4091542] [CDVTimer][intentandnavigationfilter] 4.317999ms
2017-01-09 15:40:35.240 ThaliTest[1832:4091542] [CDVTimer][gesturehandler] 0.146031ms
2017-01-09 15:40:35.240 ThaliTest[1832:4091542] [CDVTimer][TotalPluginStartup] 5.364001ms
,2017-01-09 15:40:38.667 ThaliTest[1832:4091542] Resetting plugins due to page load.
,2017-01-09 15:40:38.940 ThaliTest[1832:4091542] Finished load of: file:///var/containers/Bundle/Application/7B3B62A5-E0D9-4A3F-A0F2-E192828EAEC2/ThaliTest.app/www/index.html
,2017-01-09 15:40:39.339 ThaliTest[1832:4091542] JXcore Cordova plugin initializing
2017-01-09 15:40:39.339 ThaliTest[1832:4091707] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-01-09 14:40:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-01-09 14:40:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-09 14:40:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-09 14:41:17 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  24.6351330280304
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
