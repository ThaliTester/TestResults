#### Test 8326889373d8814_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/5D634B18-5A85-484D-A679-4A910D8DC986/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/5D634B18-5A85-484D-A679-4A910D8DC986/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8326889373d8814/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/F49E0564-0A8F-4915-8DCF-5CC26EF79510/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:61516"
,(lldb)     command script import "/tmp/5D634B18-5A85-484D-A679-4A910D8DC986/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-23 16:42:24.872 ThaliTest[3215:5602479] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/67949B9E-D8F3-40F3-A932-7D40B18ECE5F/Library/Cookies/Cookies.binarycookies
,2016-09-23 16:42:25.192 ThaliTest[3215:5602479] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-23 16:42:25.192 ThaliTest[3215:5602479] Multi-tasking -> Device: YES, App: YES
,2016-09-23 16:42:25.208 ThaliTest[3215:5602479] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-23 16:42:26.940 ThaliTest[3215:5602479] Using UIWebView
,2016-09-23 16:42:26.947 ThaliTest[3215:5602479] [CDVTimer][handleopenurl] 0.352025ms
,2016-09-23 16:42:26.954 ThaliTest[3215:5602479] [CDVTimer][intentandnavigationfilter] 6.366968ms
,2016-09-23 16:42:26.955 ThaliTest[3215:5602479] [CDVTimer][gesturehandler] 0.271976ms
,2016-09-23 16:42:26.955 ThaliTest[3215:5602479] [CDVTimer][TotalPluginStartup] 8.560002ms
,2016-09-23 16:42:33.272 ThaliTest[3215:5602479] Resetting plugins due to page load.
,2016-09-23 16:42:36.283 ThaliTest[3215:5602479] Finished load of: file:///var/mobile/Containers/Bundle/Application/F49E0564-0A8F-4915-8DCF-5CC26EF79510/ThaliTest.app/www/index.html
,2016-09-23 16:42:36.489 ThaliTest[3215:5602479] JXcore Cordova plugin initializing
,2016-09-23 16:42:36.489 ThaliTest[3215:5602728] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetooth":"off","wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bssid":"f4:f2:6d:22:99:3e"}
,DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,received session: <ThaliCore.Session: 0x15f660a00>
,Optional("9869C920-F096-4753-B303-16BCEECFCEBB")
,nil
,nil
,Optional("7F3A6493-645B-46EB-8CCF-12573809CF80")
,Optional("9F7B6D20-8BB9-42A5-A23D-A35A6F4BE031")
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,*Native tests were executed*
Total number of executed tests:  55
,Number of passed tests:  55
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  19.17569696903229
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
