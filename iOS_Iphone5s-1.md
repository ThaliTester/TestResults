#### Test 8962479671c5ab8_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/352F4D16-846B-4005-AF39-D02E14546C51/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/352F4D16-846B-4005-AF39-D02E14546C51/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/1437A8F1-E2B3-4635-A36D-83C9897AF7F3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49248"
,(lldb)     command script import "/tmp/352F4D16-846B-4005-AF39-D02E14546C51/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-04 14:14:46.248 ThaliTest[5155:12849914] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/E0DC8A98-2642-448D-B9C9-7A39E95E7FA1/Library/Cookies/Cookies.binarycookies
,2016-11-04 14:14:46.364 ThaliTest[5155:12849914] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-04 14:14:46.366 ThaliTest[5155:12849914] Multi-tasking -> Device: YES, App: YES
,2016-11-04 14:14:46.391 ThaliTest[5155:12849914] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-04 14:14:47.933 ThaliTest[5155:12849914] Using UIWebView
,2016-11-04 14:14:47.941 ThaliTest[5155:12849914] [CDVTimer][handleopenurl] 0.627995ms
,2016-11-04 14:14:47.950 ThaliTest[5155:12849914] [CDVTimer][intentandnavigationfilter] 8.163989ms
2016-11-04 14:14:47.951 ThaliTest[5155:12849914] [CDVTimer][gesturehandler] 0.389040ms
2016-11-04 14:14:47.951 ThaliTest[5155:12849914] [CDVTimer][TotalPlug,inStartup] 11.266947ms
,2016-11-04 14:14:53.918 ThaliTest[5155:12849914] Resetting plugins due to page load.
,2016-11-04 14:14:57.578 ThaliTest[5155:12849914] Finished load of: file:///var/mobile/Containers/Bundle/Application/1437A8F1-E2B3-4635-A36D-83C9897AF7F3/ThaliTest.app/www/index.html
,2016-11-04 14:14:57.893 ThaliTest[5155:12849914] JXcore Cordova plugin initializing
,2016-11-04 14:14:57.894 ThaliTest[5155:12850120] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-04 13:15:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-04 13:15:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-04 13:15:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
,2016-11-04 13:15:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-04 13:15:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-04 13:15:37 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
,Total number of executed tests:  116
,Number of passed tests:  116
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  26.14528399705887
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
