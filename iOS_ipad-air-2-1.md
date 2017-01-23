#### Test 102585911d0c1950_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/A85711D2-D4EB-4E0A-91D5-F4DCE8FAAE9F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/A85711D2-D4EB-4E0A-91D5-F4DCE8FAAE9F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/102585911d0c1950/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FBC76021-1557-40E1-959D-ABD96C514E71/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52105"
,(lldb)     command script import "/tmp/A85711D2-D4EB-4E0A-91D5-F4DCE8FAAE9F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2017-01-23 15:33:39.064 ThaliTest[2672:6936267] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B698DE8D-F333-4793-8ACE-EA86180BAF44/Library/Cookies/Cookies.binarycookies
,2017-01-23 15:33:39.307 ThaliTest[2672:6936267] Apache Cordova native platform version 4.3.1 is starting.
,2017-01-23 15:33:39.308 ThaliTest[2672:6936267] Multi-tasking -> Device: YES, App: YES
,2017-01-23 15:33:39.319 ThaliTest[2672:6936267] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2017-01-23 15:33:40.193 ThaliTest[2672:6936267] Using UIWebView
,2017-01-23 15:33:40.195 ThaliTest[2672:6936267] [CDVTimer][handleopenurl] 0.106990ms
,2017-01-23 15:33:40.197 ThaliTest[2672:6936267] [CDVTimer][intentandnavigationfilter] 1.902997ms
,2017-01-23 15:33:40.197 ThaliTest[2672:6936267] [CDVTimer][gesturehandler] 0.088990ms
2017-01-23 15:33:40.197 ThaliTest[2672:6936267] [CDVTimer][TotalPluginStartup] 2.544999ms
,2017-01-23 15:33:43.372 ThaliTest[2672:6936267] Resetting plugins due to page load.
,2017-01-23 15:33:44.820 ThaliTest[2672:6936267] Finished load of: file:///var/mobile/Containers/Bundle/Application/FBC76021-1557-40E1-959D-ABD96C514E71/ThaliTest.app/www/index.html
,2017-01-23 15:33:44.958 ThaliTest[2672:6936267] JXcore Cordova plugin initializing
,2017-01-23 15:33:44.959 ThaliTest[2672:6936449] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-01-23 14:33:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-01-23 14:33:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-01-23 14:33:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2017-01-23 14:33:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-01-23 14:33:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2017-01-23 14:34:21 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.55005699396133
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
