#### Test 79763830e108614_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A93DAA37-1549-4E46-BA47-9AAE0F2485B4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A93DAA37-1549-4E46-BA47-9AAE0F2485B4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/79763830e108614/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C3EB15F4-96AE-49E0-B267-26EE294CF2CD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51255"
,(lldb)     command script import "/tmp/A93DAA37-1549-4E46-BA47-9AAE0F2485B4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-08-24 13:22:44.756 ThaliTest[775:1654265] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/3D9635E1-DB0F-4854-95F6-E79B81F1FD41/Library/Cookies/Cookies.binarycookies
,2016-08-24 13:22:45.127 ThaliTest[775:1654265] Apache Cordova native platform version 4.1.1 is starting.
,2016-08-24 13:22:45.128 ThaliTest[775:1654265] Multi-tasking -> Device: YES, App: YES
,2016-08-24 13:22:45.153 ThaliTest[775:1654265] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.,apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-08-24 13:22:47.173 ThaliTest[775:1654265] Using UIWebView
,2016-08-24 13:22:47.181 ThaliTest[775:1654265] [CDVTimer][handleopenurl] 0.585973ms
,2016-08-24 13:22:47.189 ThaliTest[775:1654265] [CDVTimer][intentandnavigationfilter] 7.969975ms
2016-08-24 13:22:47.190 ThaliTest[775:1654265] [CDVTimer][gesturehandler] 0.369966ms
2016-08-24 13:22:47.191 ThaliTest[775:1654265] [CDVTimer][TotalPluginStar,tup] 10.843992ms
,2016-08-24 13:22:53.639 ThaliTest[775:1654265] Resetting plugins due to page load.
,2016-08-24 13:22:57.208 ThaliTest[775:1654265] Finished load of: file:///var/mobile/Containers/Bundle/Application/C3EB15F4-96AE-49E0-B267-26EE294CF2CD/ThaliTest.app/www/index.html
,2016-08-24 13:22:57.463 ThaliTest[775:1654265] JXcore Cordova plugin initializing
,2016-08-24 13:22:57.465 ThaliTest[775:1654516] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-08-24 13:23:05.599 ThaliTest[775:1654516] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-08-24 13:23:05.600 ThaliTest[775:1654516] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-08-24 13:23:05.600 ThaliTest[775:1654516] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-08-24 13:23:05.602 ThaliTest[775:1654516] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-08-24 13:23:05.935 ThaliTest[775:1654516] Native method executeNativeTests not found.
Failed to execute UT.
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
