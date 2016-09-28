#### Test 85046911b7c1908_iOS_Iphone6-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/85046911b7c1908/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a).
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/5EB5E607-B680-4638-9729-BA7A17176F7C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'
,Executing commands in '/tmp/5EB5E607-B680-4638-9729-BA7A17176F7C/fruitstrap-lldb-prep-cmds-2a65f58f9902a701b5c9a55b2befb18672927474'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.3.5 (13G36)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/85046911b7c1908/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/85046911b7c1908/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/DCCB7241-D07B-4EFD-93D7-EAD741C3BEB3/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65146"
,(lldb)     command script import "/tmp/5EB5E607-B680-4638-9729-BA7A17176F7C/fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.py"
,(lldb)     command script add -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_2a65f58f9902a701b5c9a55b2befb18672927474.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-28 11:20:25.828 ThaliTest[1612:2501774] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/51A855EB-565A-4AD9-B0F3-21F1008F0985/Library/Cookies/Cookies.binarycookies
,2016-09-28 11:20:25.899 ThaliTest[1612:2501774] Apache Cordova native platform version 4.2.1 is starting.
,2016-09-28 11:20:25.900 ThaliTest[1612:2501774] Multi-tasking -> Device: YES, App: YES
,2016-09-28 11:20:25.916 ThaliTest[1612:2501774] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-28 11:20:26.381 ThaliTest[1612:2501774] Using UIWebView
,2016-09-28 11:20:26.388 ThaliTest[1612:2501774] [CDVTimer][handleopenurl] 0.500977ms
,2016-09-28 11:20:26.395 ThaliTest[1612:2501774] [CDVTimer][intentandnavigationfilter] 6.787956ms
2016-09-28 11:20:26.396 ThaliTest[1612:2501774] [CDVTimer][gesturehandler] 0.265002ms
2016-09-28 11:20:26.396 ThaliTest[1612:2501774] [CDVTimer][TotalPluginS,tartup] 9.203970ms
,2016-09-28 11:20:31.862 ThaliTest[1612:2501774] Resetting plugins due to page load.
,2016-09-28 11:20:32.238 ThaliTest[1612:2501774] Finished load of: file:///var/containers/Bundle/Application/DCCB7241-D07B-4EFD-93D7-EAD741C3BEB3/ThaliTest.app/www/index.html
,2016-09-28 11:20:32.572 ThaliTest[1612:2501774] JXcore Cordova plugin initializing
,2016-09-28 11:20:32.572 ThaliTest[1612:2501945] JXcore instance initializing
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
,Optional(true)
Optional(false)
,Optional(false)
Optional(true)
,received session: <ThaliCore.Session: 0x125d51d30>
,Optional("28A81846-321E-447D-AFB7-F836B6711B1A")
nil
,nil
,Optional("1AED2276-DEFD-4BC9-AFFE-53F97074C868")
,Optional("E22C535D-4115-4258-9C20-CF7C0EC2BD06")
,*Native tests were executed*
Total number of executed tests:  56
,Number of passed tests:  56
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  13.18242102861404
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
