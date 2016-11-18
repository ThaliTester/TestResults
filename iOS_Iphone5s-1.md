#### Test 93371269c81e6ec_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/B3136093-36FE-468E-816C-91456397BAB8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B3136093-36FE-468E-816C-91456397BAB8/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/93371269c81e6ec/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/CB5436B6-339C-4573-BE91-5811A9E5E6C4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57410"
,(lldb)     command script import "/tmp/B3136093-36FE-468E-816C-91456397BAB8/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 19:44:26.710 ThaliTest[5974:15065172] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/64CD8354-3365-4765-ADEA-8F05321AAE0E/Library/Cookies/Cookies.binarycookies
,2016-11-18 19:44:26.769 ThaliTest[5974:15065172] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 19:44:26.771 ThaliTest[5974:15065172] Multi-tasking -> Device: YES, App: YES
,2016-11-18 19:44:26.792 ThaliTest[5974:15065172] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 19:44:27.577 ThaliTest[5974:15065172] Using UIWebView
,2016-11-18 19:44:27.581 ThaliTest[5974:15065172] [CDVTimer][handleopenurl] 1.156986ms
,2016-11-18 19:44:27.585 ThaliTest[5974:15065172] [CDVTimer][intentandnavigationfilter] 3.759980ms
2016-11-18 19:44:27.585 ThaliTest[5974:15065172] [CDVTimer][gesturehandler] 0.138998ms
2016-11-18 19:44:27.586 ThaliTest[5974:15065172] [CDVTimer][TotalPlug,inStartup] 5.737960ms
,2016-11-18 19:44:30.631 ThaliTest[5974:15065172] Resetting plugins due to page load.
,2016-11-18 19:44:32.266 ThaliTest[5974:15065172] Finished load of: file:///var/mobile/Containers/Bundle/Application/CB5436B6-339C-4573-BE91-5811A9E5E6C4/ThaliTest.app/www/index.html
,2016-11-18 19:44:32.454 ThaliTest[5974:15065172] JXcore Cordova plugin initializing
,2016-11-18 19:44:32.456 ThaliTest[5974:15065335] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 18:44:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-18 18:44:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-18 18:44:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 18:44:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-18 18:44:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,failed - Unexpected connect received in file: Optional("/Users/thali/Github/ThaliTest/plugins/org.thaliproject.p2p/lib/ios/ThaliCore/ThaliCoreTests/Utils/MultipeerConnectHelper.swift"), line: 39
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-18 18:45:09 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
,Number of passed tests:  115
Number of failed tests:  1
,Number of ignored tests:  0
Total duration:  23.79828995466232
Failed to execute UT.
,2016-11-18 18:45:09 - DEBUG UnitTest_app: 'Failed to execute UT.'
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
