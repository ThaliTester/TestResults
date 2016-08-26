#### Test 79896569fbe8035_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/C59D0350-4380-4806-A276-FC4D73572EA3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/C59D0350-4380-4806-A276-FC4D73572EA3/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79896569fbe8035/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B555A0CA-1C2A-4A0A-90C6-C60038BB104E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59867"
,(lldb)     command script import "/tmp/C59D0350-4380-4806-A276-FC4D73572EA3/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-26 21:51:57.075 ThaliTest[1135:2031462] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/93EFA5CD-9333-4618-A7D6-7151AEBA11BA/Library/Cookies/Cookies.binarycookies
,2016-08-26 21:51:57.425 ThaliTest[1135:2031462] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-26 21:51:57.426 ThaliTest[1135:2031462] Multi-tasking -> Device: YES, App: YES
,2016-08-26 21:51:57.443 ThaliTest[1135:2031462] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-26 21:51:59.328 ThaliTest[1135:2031462] Using UIWebView
,2016-08-26 21:51:59.335 ThaliTest[1135:2031462] [CDVTimer][handleopenurl] 0.415027ms
,2016-08-26 21:51:59.343 ThaliTest[1135:2031462] [CDVTimer][intentandnavigationfilter] 7.615983ms
,2016-08-26 21:51:59.344 ThaliTest[1135:2031462] [CDVTimer][gesturehandler] 0.386000ms
,2016-08-26 21:51:59.344 ThaliTest[1135:2031462] [CDVTimer][TotalPluginStartup] 10.266006ms
,2016-08-26 21:52:06.584 ThaliTest[1135:2031462] Resetting plugins due to page load.
,2016-08-26 21:52:10.243 ThaliTest[1135:2031462] Finished load of: file:///var/mobile/Containers/Bundle/Application/B555A0CA-1C2A-4A0A-90C6-C60038BB104E/ThaliTest.app/www/index.html
,2016-08-26 21:52:10.478 ThaliTest[1135:2031462] JXcore Cordova plugin initializing
,2016-08-26 21:52:10.479 ThaliTest[1135:2031697] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
,DEBUG thaliMobileNativeWrapper: networkChanged: {}
DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,*Native tests were executed*
Total number of executed tests:  5
,Number of passed tests:  5
,Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  0.006655991077423096
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
