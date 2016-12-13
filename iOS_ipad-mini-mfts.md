#### Test 9781689977f4746_iOS_ipad-mini-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/4FD88B2D-C650-45FB-8131-14D770FF68BE/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'
,Executing commands in '/tmp/4FD88B2D-C650-45FB-8131-14D770FF68BE/fruitstrap-lldb-prep-cmds-83aab4e7f1dde3becec287ac4c44362439d2595b'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/9781689977f4746/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C7DA1E34-DA6F-410F-BD21-94A3E97DC300/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56819"
,(lldb)     command script import "/tmp/4FD88B2D-C650-45FB-8131-14D770FF68BE/fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.py"
,(lldb)     command script add -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_83aab4e7f1dde3becec287ac4c44362439d2595b.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-13 20:44:47.020 ThaliTest[516:1084369] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C37F3786-E1C4-4FB4-BEE3-CB741B2D463F/Library/Cookies/Cookies.binarycookies
,2016-12-13 20:44:47.172 ThaliTest[516:1084369] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-13 20:44:47.175 ThaliTest[516:1084369] Multi-tasking -> Device: YES, App: YES
,2016-12-13 20:44:47.202 ThaliTest[516:1084369] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-13 20:44:47.875 ThaliTest[516:1084369] Using UIWebView
,2016-12-13 20:44:47.884 ThaliTest[516:1084369] [CDVTimer][handleopenurl] 0.367045ms
,2016-12-13 20:44:47.892 ThaliTest[516:1084369] [CDVTimer][intentandnavigationfilter] 7.723033ms
2016-12-13 20:44:47.893 ThaliTest[516:1084369] [CDVTimer][gesturehandler] 0.343025ms
2016-12-13 20:44:47.893 ThaliTest[516:1084369] [CDVTimer][TotalPluginStartup] 9.796977ms
,2016-12-13 20:44:57.155 ThaliTest[516:1084369] Resetting plugins due to page load.
,2016-12-13 20:44:57.863 ThaliTest[516:1084369] Finished load of: file:///var/containers/Bundle/Application/C7DA1E34-DA6F-410F-BD21-94A3E97DC300/ThaliTest.app/www/index.html
,2016-12-13 20:44:58.096 ThaliTest[516:1084369] JXcore Cordova plugin initializing
,2016-12-13 20:44:58.097 ThaliTest[516:1084548] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-13 19:45:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-13 19:45:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-13 19:45:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","bssid":"f0:f2:6d:22:99:3e","wifi":"on","bluetoothLowEnergy":"on","bluetooth":"on","ssid":"NG700_GUEST"}'
,2016-12-13 19:45:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-13 19:45:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-13 19:46:05 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  30.48671895265579
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
