#### Test 921522864f1c710_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/F7CF90F4-603E-4F63-AFDA-B0172D2DE048/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F7CF90F4-603E-4F63-AFDA-B0172D2DE048/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/921522864f1c710/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/03F1745A-B0A8-4389-9E7F-48AD9D05EF9F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63239"
,(lldb)     command script import "/tmp/F7CF90F4-603E-4F63-AFDA-B0172D2DE048/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-18 14:30:45.207 ThaliTest[5939:15027721] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2C0389CB-B608-4601-8BF3-B703E42DA9BE/Library/Cookies/Cookies.binarycookies
,2016-11-18 14:30:45.268 ThaliTest[5939:15027721] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-18 14:30:45.270 ThaliTest[5939:15027721] Multi-tasking -> Device: YES, App: YES
,2016-11-18 14:30:45.289 ThaliTest[5939:15027721] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-18 14:30:46.111 ThaliTest[5939:15027721] Using UIWebView
,2016-11-18 14:30:46.116 ThaliTest[5939:15027721] [CDVTimer][handleopenurl] 0.184000ms
,2016-11-18 14:30:46.119 ThaliTest[5939:15027721] [CDVTimer][intentandnavigationfilter] 2.906024ms
2016-11-18 14:30:46.119 ThaliTest[5939:15027721] [CDVTimer][gesturehandler] 0.153005ms
2016-11-18 14:30:46.119 ThaliTest[5939:15027721] [CDVTimer][TotalPluginStartup] 4.105031ms
,2016-11-18 14:30:49.301 ThaliTest[5939:15027721] Resetting plugins due to page load.
,2016-11-18 14:30:50.970 ThaliTest[5939:15027721] Finished load of: file:///var/mobile/Containers/Bundle/Application/03F1745A-B0A8-4389-9E7F-48AD9D05EF9F/ThaliTest.app/www/index.html
,2016-11-18 14:30:51.167 ThaliTest[5939:15027721] JXcore Cordova plugin initializing
2016-11-18 14:30:51.168 ThaliTest[5939:15027895] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-18 13:31:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-18 13:31:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-18 13:31:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2016-11-18 13:31:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-18 13:31:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-18 13:31:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-18 13:31:27 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  23.13195300102234
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
