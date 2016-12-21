#### Test 98912682a6d9d3f_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping iPhone 6 (GSM) 'iphone-6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPad mini 'ipad-mini-mfts' (83aab4e7f1dde3becec287ac4c44362439d2595b).
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/F88BD756-4377-4EE9-B9F4-1CAB14879E47/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/F88BD756-4377-4EE9-B9F4-1CAB14879E47/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/98912682a6d9d3f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/7D782AB3-1454-49AF-8004-87A44AEC2FD8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59232"
,(lldb)     command script import "/tmp/F88BD756-4377-4EE9-B9F4-1CAB14879E47/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-12-21 19:26:01.170 ThaliTest[1147:2261806] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5ADFA6D8-E2F8-4EC6-A906-6F252A51E854/Library/Cookies/Cookies.binarycookies
,2016-12-21 19:26:01.516 ThaliTest[1147:2261806] Apache Cordova native platform version 4.3.1 is starting.
,2016-12-21 19:26:01.518 ThaliTest[1147:2261806] Multi-tasking -> Device: YES, App: YES
,2016-12-21 19:26:01.537 ThaliTest[1147:2261806] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-12-21 19:26:03.569 ThaliTest[1147:2261806] Using UIWebView
,2016-12-21 19:26:03.576 ThaliTest[1147:2261806] [CDVTimer][handleopenurl] 0.339985ms
,2016-12-21 19:26:03.583 ThaliTest[1147:2261806] [CDVTimer][intentandnavigationfilter] 6.301999ms
,2016-12-21 19:26:03.584 ThaliTest[1147:2261806] [CDVTimer][gesturehandler] 0.276983ms
,2016-12-21 19:26:03.584 ThaliTest[1147:2261806] [CDVTimer][TotalPluginStartup] 8.454025ms
,2016-12-21 19:26:10.628 ThaliTest[1147:2261806] Resetting plugins due to page load.
,2016-12-21 19:26:14.492 ThaliTest[1147:2261806] Finished load of: file:///var/mobile/Containers/Bundle/Application/7D782AB3-1454-49AF-8004-87A44AEC2FD8/ThaliTest.app/www/index.html
,2016-12-21 19:26:14.700 ThaliTest[1147:2261806] JXcore Cordova plugin initializing
,2016-12-21 19:26:14.701 ThaliTest[1147:2262031] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-12-21 18:26:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-12-21 18:26:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-12-21 18:26:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-12-21 18:26:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-12-21 18:26:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-12-21 18:26:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.86938005685806
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
