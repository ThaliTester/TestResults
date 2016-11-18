#### Test 944077483e9c5d2_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/0BE35884-CAE8-45A0-A898-C14BCD07153C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0BE35884-CAE8-45A0-A898-C14BCD07153C/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/944077483e9c5d2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/9D22F0D2-0BDA-4B3D-A70F-3E407ACDCAED/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56397"
,(lldb)     command script import "/tmp/0BE35884-CAE8-45A0-A898-C14BCD07153C/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 19:19:40.560 ThaliTest[5800:12568645] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/470704DE-3C38-4B23-8566-1FA1BC3E4973/Library/Cookies/Cookies.binarycookies
,2016-11-18 19:19:40.805 ThaliTest[5800:12568645] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 19:19:40.806 ThaliTest[5800:12568645] Multi-tasking -> Device: YES, App: YES
,2016-11-18 19:19:40.818 ThaliTest[5800:12568645] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 19:19:41.681 ThaliTest[5800:12568645] Using UIWebView
,2016-11-18 19:19:41.684 ThaliTest[5800:12568645] [CDVTimer][handleopenurl] 0.093043ms
,2016-11-18 19:19:41.686 ThaliTest[5800:12568645] [CDVTimer][intentandnavigationfilter] 1.901984ms
2016-11-18 19:19:41.686 ThaliTest[5800:12568645] [CDVTimer][gesturehandler] 0.086010ms
2016-11-18 19:19:41.686 ThaliTest[5800:12568645] [CDVTimer][TotalPluginStartup] 2.499998ms
,2016-11-18 19:19:44.925 ThaliTest[5800:12568645] Resetting plugins due to page load.
,2016-11-18 19:19:46.404 ThaliTest[5800:12568645] Finished load of: file:///var/mobile/Containers/Bundle/Application/9D22F0D2-0BDA-4B3D-A70F-3E407ACDCAED/ThaliTest.app/www/index.html
,2016-11-18 19:19:46.547 ThaliTest[5800:12568645] JXcore Cordova plugin initializing
,2016-11-18 19:19:46.548 ThaliTest[5800:12568805] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 18:19:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 18:19:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 18:19:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 18:19:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-18 18:19:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-18 18:20:30 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  116
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  35.07925802469254
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
