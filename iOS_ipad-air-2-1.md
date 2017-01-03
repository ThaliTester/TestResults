#### Test 99530606e7215e5_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/70FC5E5A-E62F-4BA6-A95E-EF274D14C618/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/70FC5E5A-E62F-4BA6-A95E-EF274D14C618/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/99530606e7215e5/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/097BF47F-C712-49D9-B637-D99E7ABC4B38/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60306"
,(lldb)     command script import "/tmp/70FC5E5A-E62F-4BA6-A95E-EF274D14C618/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-03 14:54:58.614 ThaliTest[1852:4145603] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/A3C56C10-EE04-4ED6-84B2-68EF2B0BBCC5/Library/Cookies/Cookies.binarycookies
,2017-01-03 14:54:58.835 ThaliTest[1852:4145603] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-03 14:54:58.836 ThaliTest[1852:4145603] Multi-tasking -> Device: YES, App: YES
,2017-01-03 14:54:58.848 ThaliTest[1852:4145603] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-03 14:54:59.686 ThaliTest[1852:4145603] Using UIWebView
,2017-01-03 14:54:59.688 ThaliTest[1852:4145603] [CDVTimer][handleopenurl] 0.120997ms
,2017-01-03 14:54:59.690 ThaliTest[1852:4145603] [CDVTimer][intentandnavigationfilter] 1.871049ms
2017-01-03 14:54:59.691 ThaliTest[1852:4145603] [CDVTimer][gesturehandler] 0.078976ms
2017-01-03 14:54:59.691 ThaliTest[1852:4145603] [CDVTimer][TotalPluginS,tartup] 2.497017ms
,2017-01-03 14:55:02.914 ThaliTest[1852:4145603] Resetting plugins due to page load.
,2017-01-03 14:55:04.387 ThaliTest[1852:4145603] Finished load of: file:///var/mobile/Containers/Bundle/Application/097BF47F-C712-49D9-B637-D99E7ABC4B38/ThaliTest.app/www/index.html
,2017-01-03 14:55:04.526 ThaliTest[1852:4145603] JXcore Cordova plugin initializing
2017-01-03 14:55:04.527 ThaliTest[1852:4145797] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-03 13:55:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-03 13:55:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-03 13:55:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-03 13:55:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-03 13:55:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-03 13:55:41 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  27.43828803300858
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
