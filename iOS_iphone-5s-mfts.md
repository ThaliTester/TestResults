#### Test 99374565572e946_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/46C53CAD-B5CA-4192-AC34-91AC422521C9/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/46C53CAD-B5CA-4192-AC34-91AC422521C9/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99374565572e946/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B2E9B359-FE8F-4A84-A215-86814D4FC2BB/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64641"
,(lldb)     command script import "/tmp/46C53CAD-B5CA-4192-AC34-91AC422521C9/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-27 14:15:45.906 ThaliTest[1275:2467083] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C8C94E3C-786D-4B35-87DA-9AEB2AA2FD78/Library/Cookies/Cookies.binarycookies
,2016-12-27 14:15:45.996 ThaliTest[1275:2467083] Apache Cordova native platform version 4.3.1 is starting.
2016-12-27 14:15:45.998 ThaliTest[1275:2467083] Multi-tasking -> Device: YES, App: YES
,2016-12-27 14:15:46.018 ThaliTest[1275:2467083] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-27 14:15:46.552 ThaliTest[1275:2467083] Using UIWebView
,2016-12-27 14:15:46.560 ThaliTest[1275:2467083] [CDVTimer][handleopenurl] 0.550985ms
,2016-12-27 14:15:46.570 ThaliTest[1275:2467083] [CDVTimer][intentandnavigationfilter] 9.460032ms
2016-12-27 14:15:46.571 ThaliTest[1275:2467083] [CDVTimer][gesturehandler] 0.360012ms
2016-12-27 14:15:46.572 ThaliTest[1275:2467083] [CDVTimer][TotalPluginS,tartup] 12.309015ms
,2016-12-27 14:15:52.975 ThaliTest[1275:2467083] Resetting plugins due to page load.
,2016-12-27 14:15:53.384 ThaliTest[1275:2467083] Finished load of: file:///var/containers/Bundle/Application/B2E9B359-FE8F-4A84-A215-86814D4FC2BB/ThaliTest.app/www/index.html
,2016-12-27 14:15:53.768 ThaliTest[1275:2467083] JXcore Cordova plugin initializing
,2016-12-27 14:15:53.769 ThaliTest[1275:2467257] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-27 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-27 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-27 13:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2016-12-27 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-27 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-27 13:16:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  26.6403129696846
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
