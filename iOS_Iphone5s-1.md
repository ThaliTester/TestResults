#### Test 896247965a92e74_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F146F3AB-CD1F-47C6-AA76-5657ABC0F196/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F146F3AB-CD1F-47C6-AA76-5657ABC0F196/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/896247965a92e74/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/616F8366-2324-475F-BBC2-ADE8E53A4DE2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61955"
,(lldb)     command script import "/tmp/F146F3AB-CD1F-47C6-AA76-5657ABC0F196/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-09 14:57:07.330 ThaliTest[5423:13665804] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/EEE509B7-E8CA-478E-B078-957B46D0EF64/Library/Cookies/Cookies.binarycookies
,2016-11-09 14:57:07.836 ThaliTest[5423:13665804] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-09 14:57:07.837 ThaliTest[5423:13665804] Multi-tasking -> Device: YES, App: YES
,2016-11-09 14:57:07.857 ThaliTest[5423:13665804] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-09 14:57:08.657 ThaliTest[5423:13665804] Using UIWebView
,2016-11-09 14:57:08.660 ThaliTest[5423:13665804] [CDVTimer][handleopenurl] 0.169992ms
2016-11-09 14:57:08.664 ThaliTest[5423:13665804] [CDVTimer][intentandnavigationfilter] 2.837002ms
2016-11-09 14:57:08.664 ThaliTest[5423:13665804] [CDVTimer][gesturehan,dler] 0.124037ms
2016-11-09 14:57:08.664 ThaliTest[5423:13665804] [CDVTimer][TotalPluginStartup] 4.583001ms
,2016-11-09 14:57:11.824 ThaliTest[5423:13665804] Resetting plugins due to page load.
,2016-11-09 14:57:13.285 ThaliTest[5423:13665804] Finished load of: file:///var/mobile/Containers/Bundle/Application/616F8366-2324-475F-BBC2-ADE8E53A4DE2/ThaliTest.app/www/index.html
,2016-11-09 14:57:13.470 ThaliTest[5423:13665804] JXcore Cordova plugin initializing
2016-11-09 14:57:13.470 ThaliTest[5423:13665981] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-09 13:57:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-09 13:57:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-09 13:57:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"on","wifi":"on","bluetoothLowEnergy":"on","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-09 13:57:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-09 13:57:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
Optional(false)
Optional(true)
,2016-11-09 13:57:51 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  25.29359197616577
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
