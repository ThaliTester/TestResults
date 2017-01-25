#### Test 10307209017d2aad_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,(lldb) command source -s 0 '/tmp/9C77A684-A36C-4BFB-8A9E-4055626B4306/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/9C77A684-A36C-4BFB-8A9E-4055626B4306/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/10307209017d2aad/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/D69232F3-F133-42CC-B65D-2228A9A006BC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50025"
,(lldb)     command script import "/tmp/9C77A684-A36C-4BFB-8A9E-4055626B4306/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,success
,(lldb)     autoexit
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 09:43:16.342 ThaliTest[2785:7203855] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/160728A9-9AB6-4345-8684-2C412AC8B675/Library/Cookies/Cookies.binarycookies
,2017-01-25 09:43:16.560 ThaliTest[2785:7203855] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-25 09:43:16.561 ThaliTest[2785:7203855] Multi-tasking -> Device: YES, App: YES
,2017-01-25 09:43:16.574 ThaliTest[2785:7203855] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-25 09:43:17.413 ThaliTest[2785:7203855] Using UIWebView
,2017-01-25 09:43:17.415 ThaliTest[2785:7203855] [CDVTimer][handleopenurl] 0.096023ms
,2017-01-25 09:43:17.417 ThaliTest[2785:7203855] [CDVTimer][intentandnavigationfilter] 1.803994ms
2017-01-25 09:43:17.417 ThaliTest[2785:7203855] [CDVTimer][gesturehandler] 0.077009ms
2017-01-25 09:43:17.417 ThaliTest[2785:7203855] [CDVTimer][TotalPluginStartup] 2.402961ms
,2017-01-25 09:43:20.555 ThaliTest[2785:7203855] Resetting plugins due to page load.
,2017-01-25 09:43:22.016 ThaliTest[2785:7203855] Finished load of: file:///var/mobile/Containers/Bundle/Application/D69232F3-F133-42CC-B65D-2228A9A006BC/ThaliTest.app/www/index.html
,2017-01-25 09:43:22.156 ThaliTest[2785:7203855] JXcore Cordova plugin initializing
,2017-01-25 09:43:22.157 ThaliTest[2785:7204038] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 08:43:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-25 08:43:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-25 08:43:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-25 08:43:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-25 08:43:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,2017-01-25 08:43:58 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  25.35064202547073
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
