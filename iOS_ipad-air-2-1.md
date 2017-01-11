#### Test 995727498cdcb4a_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/995727498cdcb4a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/D9906A0B-E0FD-4BD6-A43F-0C49D28B37D7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/D9906A0B-E0FD-4BD6-A43F-0C49D28B37D7/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/995727498cdcb4a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/995727498cdcb4a/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/EE3C1A7B-60FB-48E5-A1AE-62C99C1CB63E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63750"
,(lldb)     command script import "/tmp/D9906A0B-E0FD-4BD6-A43F-0C49D28B37D7/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-11 12:59:39.353 ThaliTest[2202:5393361] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/FC619048-7F29-4A72-B4C7-136D76AAE543/Library/Cookies/Cookies.binarycookies
,2017-01-11 12:59:39.596 ThaliTest[2202:5393361] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-11 12:59:39.597 ThaliTest[2202:5393361] Multi-tasking -> Device: YES, App: YES
,2017-01-11 12:59:39.609 ThaliTest[2202:5393361] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-11 12:59:40.440 ThaliTest[2202:5393361] Using UIWebView
,2017-01-11 12:59:40.442 ThaliTest[2202:5393361] [CDVTimer][handleopenurl] 0.097036ms
,2017-01-11 12:59:40.444 ThaliTest[2202:5393361] [CDVTimer][intentandnavigationfilter] 1.874030ms
2017-01-11 12:59:40.444 ThaliTest[2202:5393361] [CDVTimer][gesturehandler] 0.093043ms
2017-01-11 12:59:40.444 ThaliTest[2202:5393361] [CDVTimer][TotalPluginS,tartup] 2.483964ms
,2017-01-11 12:59:43.576 ThaliTest[2202:5393361] Resetting plugins due to page load.
,2017-01-11 12:59:45.017 ThaliTest[2202:5393361] Finished load of: file:///var/mobile/Containers/Bundle/Application/EE3C1A7B-60FB-48E5-A1AE-62C99C1CB63E/ThaliTest.app/www/index.html
,2017-01-11 12:59:45.155 ThaliTest[2202:5393361] JXcore Cordova plugin initializing
,2017-01-11 12:59:45.156 ThaliTest[2202:5393556] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-11 11:59:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-11 11:59:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-11 11:59:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-11 11:59:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-01-11 11:59:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-11 12:00:23 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  27.10421997308731
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
