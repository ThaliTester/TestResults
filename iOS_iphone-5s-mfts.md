#### Test 103295431c2804f2_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/D3FE2E02-932D-481D-9CAA-3A35F910BA2D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/D3FE2E02-932D-481D-9CAA-3A35F910BA2D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/103295431c2804f2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6DF69D62-01B6-4399-B2ED-6B16AA9903A4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57438"
,(lldb)     command script import "/tmp/D3FE2E02-932D-481D-9CAA-3A35F910BA2D/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-26 13:41:10.177 ThaliTest[800:1787521] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/914EF230-DFC4-4F54-92D9-2EC08EFAC004/Library/Cookies/Cookies.binarycookies
,2017-01-26 13:41:10.228 ThaliTest[800:1787521] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-26 13:41:10.229 ThaliTest[800:1787521] Multi-tasking -> Device: YES, App: YES
,2017-01-26 13:41:10.245 ThaliTest[800:1787521] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-26 13:41:10.573 ThaliTest[800:1787521] Using UIWebView
,2017-01-26 13:41:10.578 ThaliTest[800:1787521] [CDVTimer][handleopenurl] 0.203013ms
,2017-01-26 13:41:10.584 ThaliTest[800:1787521] [CDVTimer][intentandnavigationfilter] 6.069005ms
2017-01-26 13:41:10.585 ThaliTest[800:1787521] [CDVTimer][gesturehandler] 0.209033ms
2017-01-26 13:41:10.585 ThaliTest[800:1787521] [CDVTimer][TotalPluginStartup] 7.497013ms
,2017-01-26 13:41:16.920 ThaliTest[800:1787521] Resetting plugins due to page load.
,2017-01-26 13:41:17.377 ThaliTest[800:1787521] Finished load of: file:///var/containers/Bundle/Application/6DF69D62-01B6-4399-B2ED-6B16AA9903A4/ThaliTest.app/www/index.html
,2017-01-26 13:41:17.828 ThaliTest[800:1787521] JXcore Cordova plugin initializing
,2017-01-26 13:41:17.829 ThaliTest[800:1787714] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-26 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-26 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-26 12:41:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-26 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-26 12:41:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-26 12:41:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  24.41143500804901
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
