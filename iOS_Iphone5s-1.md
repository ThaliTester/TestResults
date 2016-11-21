#### Test 94626375b5fe2b0_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/08EA7745-3D34-48FE-9904-5B4AA3D16108/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/08EA7745-3D34-48FE-9904-5B4AA3D16108/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/94626375b5fe2b0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/FE4E694A-BB32-427B-A937-FEA71A205296/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61071"
,(lldb)     command script import "/tmp/08EA7745-3D34-48FE-9904-5B4AA3D16108/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-21 17:38:00.970 ThaliTest[6130:15532242] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5F26A61B-6D77-4793-98C4-DB4734F29895/Library/Cookies/Cookies.binarycookies
,2016-11-21 17:38:01.086 ThaliTest[6130:15532242] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-21 17:38:01.088 ThaliTest[6130:15532242] Multi-tasking -> Device: YES, App: YES
,2016-11-21 17:38:01.114 ThaliTest[6130:15532242] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-21 17:38:02.731 ThaliTest[6130:15532242] Using UIWebView
,2016-11-21 17:38:02.744 ThaliTest[6130:15532242] [CDVTimer][handleopenurl] 0.472009ms
,2016-11-21 17:38:02.753 ThaliTest[6130:15532242] [CDVTimer][intentandnavigationfilter] 8.412004ms
2016-11-21 17:38:02.754 ThaliTest[6130:15532242] [CDVTimer][gesturehandler] 0.388980ms
2016-11-21 17:38:02.754 ThaliTest[6130:15532242] [CDVTimer][TotalPlug,inStartup] 11.146963ms
,2016-11-21 17:38:08.743 ThaliTest[6130:15532242] Resetting plugins due to page load.
,2016-11-21 17:38:12.150 ThaliTest[6130:15532242] Finished load of: file:///var/mobile/Containers/Bundle/Application/FE4E694A-BB32-427B-A937-FEA71A205296/ThaliTest.app/www/index.html
,2016-11-21 17:38:12.449 ThaliTest[6130:15532242] JXcore Cordova plugin initializing
,2016-11-21 17:38:12.450 ThaliTest[6130:15532455] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-21 16:38:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-21 16:38:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-21 16:38:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-21 16:38:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-21 16:38:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-21 16:38:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2016-11-21 16:38:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-21 16:38:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  25.04614996910095
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
