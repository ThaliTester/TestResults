#### Test 8962479671c5ab8_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/7C73AE4C-6BB0-4D3C-B08A-E0DFEC380A21/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/7C73AE4C-6BB0-4D3C-B08A-E0DFEC380A21/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8962479671c5ab8/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/53942500-DB9F-4684-BC17-857F9408FC2C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49246"
,(lldb)     command script import "/tmp/7C73AE4C-6BB0-4D3C-B08A-E0DFEC380A21/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-11-04 14:14:47.427 ThaliTest[5070:10760610] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/D5A29F10-1C26-45DF-A8D5-0CC02E52A999/Library/Cookies/Cookies.binarycookies
,2016-11-04 14:14:47.791 ThaliTest[5070:10760610] Apache Cordova native platform version 4.2.1 is starting.
,2016-11-04 14:14:47.792 ThaliTest[5070:10760610] Multi-tasking -> Device: YES, App: YES
,2016-11-04 14:14:47.811 ThaliTest[5070:10760610] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://develope,r.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-11-04 14:14:49.675 ThaliTest[5070:10760610] Using UIWebView
,2016-11-04 14:14:49.685 ThaliTest[5070:10760610] [CDVTimer][handleopenurl] 0.376999ms
,2016-11-04 14:14:49.693 ThaliTest[5070:10760610] [CDVTimer][intentandnavigationfilter] 6.906986ms
,2016-11-04 14:14:49.694 ThaliTest[5070:10760610] [CDVTimer][gesturehandler] 0.294030ms
,2016-11-04 14:14:49.694 ThaliTest[5070:10760610] [CDVTimer][TotalPluginStartup] 9.206951ms
,2016-11-04 14:14:56.344 ThaliTest[5070:10760610] Resetting plugins due to page load.
,2016-11-04 14:14:59.940 ThaliTest[5070:10760610] Finished load of: file:///var/mobile/Containers/Bundle/Application/53942500-DB9F-4684-BC17-857F9408FC2C/ThaliTest.app/www/index.html
,2016-11-04 14:15:00.123 ThaliTest[5070:10760610] JXcore Cordova plugin initializing
,2016-11-04 14:15:00.124 ThaliTest[5070:10760918] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-11-04 13:15:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2016-11-04 13:15:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2016-11-04 13:15:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"ssid":"NG700","bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}'
2016-11-04 13:15:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2016-11-04 13:15:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,2016-11-04 13:15:46 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  116
Number of passed tests:  116
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  36.39856195449829
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
