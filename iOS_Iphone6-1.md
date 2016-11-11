#### Test 93390913232c8a0_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/5D93C6F6-9D2D-4735-B5B9-80694E959339/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5D93C6F6-9D2D-4735-B5B9-80694E959339/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93390913232c8a0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/FD3E128B-27BF-4183-B224-09B4CAC2481A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54435"
,(lldb)     command script import "/tmp/5D93C6F6-9D2D-4735-B5B9-80694E959339/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-11 21:57:59.917 ThaliTest[3339:8381964] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4AF1803D-8A1D-4D86-87A1-0A2AC737B9FD/Library/Cookies/Cookies.binarycookies
,2016-11-11 21:57:59.997 ThaliTest[3339:8381964] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-11 21:57:59.998 ThaliTest[3339:8381964] Multi-tasking -> Device: YES, App: YES
,2016-11-11 21:58:00.025 ThaliTest[3339:8381964] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-11 21:58:00.327 ThaliTest[3339:8381964] Using UIWebView
,2016-11-11 21:58:00.331 ThaliTest[3339:8381964] [CDVTimer][handleopenurl] 0.198007ms
,2016-11-11 21:58:00.335 ThaliTest[3339:8381964] [CDVTimer][intentandnavigationfilter] 3.560960ms
2016-11-11 21:58:00.335 ThaliTest[3339:8381964] [CDVTimer][gesturehandler] 0.137985ms
2016-11-11 21:58:00.335 ThaliTest[3339:8381964] [CDVTimer][TotalPluginStartup] 4.681051ms
,2016-11-11 21:58:05.319 ThaliTest[3339:8381964] Resetting plugins due to page load.
,2016-11-11 21:58:05.625 ThaliTest[3339:8381964] Finished load of: file:///var/containers/Bundle/Application/FD3E128B-27BF-4183-B224-09B4CAC2481A/ThaliTest.app/www/index.html
,2016-11-11 21:58:05.968 ThaliTest[3339:8381964] JXcore Cordova plugin initializing
,2016-11-11 21:58:05.969 ThaliTest[3339:8382169] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-11 20:58:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-11 20:58:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-11 20:58:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-11 20:58:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-11 20:58:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-11 20:58:42 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.10771000385284
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
