#### Test 99530606e7215e5_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/2B6F8A2A-C0F8-4AE8-B241-7C71E5BC3765/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/2B6F8A2A-C0F8-4AE8-B241-7C71E5BC3765/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/7CAC5494-316B-4792-93C9-E8D65F9294EF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60312"
,(lldb)     command script import "/tmp/2B6F8A2A-C0F8-4AE8-B241-7C71E5BC3765/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
(lldb)     autoexit
,2017-01-03 14:55:10.029 ThaliTest[1605:3328033] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DFD36C7B-8129-447D-AF62-8D84DA51E6AD/Library/Cookies/Cookies.binarycookies
,2017-01-03 14:55:10.085 ThaliTest[1605:3328033] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 14:55:10.086 ThaliTest[1605:3328033] Multi-tasking -> Device: YES, App: YES
,2017-01-03 14:55:10.102 ThaliTest[1605:3328033] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 14:55:10.354 ThaliTest[1605:3328033] Using UIWebView
,2017-01-03 14:55:10.357 ThaliTest[1605:3328033] [CDVTimer][handleopenurl] 0.338972ms
,2017-01-03 14:55:10.361 ThaliTest[1605:3328033] [CDVTimer][intentandnavigationfilter] 4.141033ms
2017-01-03 14:55:10.362 ThaliTest[1605:3328033] [CDVTimer][gesturehandler] 0.141025ms
2017-01-03 14:55:10.362 ThaliTest[1605:3328033] [CDVTimer][TotalPluginS,tartup] 5.355000ms
,2017-01-03 14:55:13.699 ThaliTest[1605:3328033] Resetting plugins due to page load.
,2017-01-03 14:55:13.983 ThaliTest[1605:3328033] Finished load of: file:///var/containers/Bundle/Application/7CAC5494-316B-4792-93C9-E8D65F9294EF/ThaliTest.app/www/index.html
,2017-01-03 14:55:14.369 ThaliTest[1605:3328033] JXcore Cordova plugin initializing
,2017-01-03 14:55:14.370 ThaliTest[1605:3328201] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 13:55:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-03 13:55:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 13:55:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700_GUEST","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e"}'
,2017-01-03 13:55:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-03 13:55:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2017-01-03 13:55:51 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.74059998989105
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
