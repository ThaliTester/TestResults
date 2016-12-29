#### Test 992473934db55e8_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/91A86444-625C-44CA-AC39-1097429E9508/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/91A86444-625C-44CA-AC39-1097429E9508/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/992473934db55e8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8EDD404B-A1BD-466B-8E9D-11D82F127FCF/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61467"
,(lldb)     command script import "/tmp/91A86444-625C-44CA-AC39-1097429E9508/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-29 14:07:04.656 ThaliTest[1622:3404053] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/4E93B461-2256-4B9A-8A6F-3B32656840FB/Library/Cookies/Cookies.binarycookies
,2016-12-29 14:07:05.011 ThaliTest[1622:3404053] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-29 14:07:05.013 ThaliTest[1622:3404053] Multi-tasking -> Device: YES, App: YES
,2016-12-29 14:07:05.032 ThaliTest[1622:3404053] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-29 14:07:06.988 ThaliTest[1622:3404053] Using UIWebView
,2016-12-29 14:07:06.997 ThaliTest[1622:3404053] [CDVTimer][handleopenurl] 0.351012ms
,2016-12-29 14:07:07.005 ThaliTest[1622:3404053] [CDVTimer][intentandnavigationfilter] 7.128000ms
,2016-12-29 14:07:07.006 ThaliTest[1622:3404053] [CDVTimer][gesturehandler] 0.321984ms
,2016-12-29 14:07:07.006 ThaliTest[1622:3404053] [CDVTimer][TotalPluginStartup] 9.411991ms
,2016-12-29 14:07:13.343 ThaliTest[1622:3404053] Resetting plugins due to page load.
,2016-12-29 14:07:16.249 ThaliTest[1622:3404053] Finished load of: file:///var/mobile/Containers/Bundle/Application/8EDD404B-A1BD-466B-8E9D-11D82F127FCF/ThaliTest.app/www/index.html
,2016-12-29 14:07:16.521 ThaliTest[1622:3404053] JXcore Cordova plugin initializing
,2016-12-29 14:07:16.522 ThaliTest[1622:3404251] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-29 13:07:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-29 13:07:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-29 13:07:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-12-29 13:07:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-29 13:07:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-29 13:07:53 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  27.06146401166916
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
