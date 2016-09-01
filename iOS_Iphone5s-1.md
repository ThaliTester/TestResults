#### Test 8359176442466a2_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8359176442466a2/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/0F601569-0F13-4576-80AE-BD27339065B9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0F601569-0F13-4576-80AE-BD27339065B9/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8359176442466a2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8359176442466a2/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/8196790E-71C4-4585-8B72-26F7427988D9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60815"
,(lldb)     command script import "/tmp/0F601569-0F13-4576-80AE-BD27339065B9/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,2016-09-01 11:13:49.469 ThaliTest[1423:2832909] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C472DF5F-9AAE-47E7-BD56-47DD2DFFE4B9/Library/Cookies/Cookies.binarycookies
,2016-09-01 11:13:49.902 ThaliTest[1423:2832909] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-01 11:13:49.903 ThaliTest[1423:2832909] Multi-tasking -> Device: YES, App: YES
,2016-09-01 11:13:49.928 ThaliTest[1423:2832909] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-01 11:13:51.473 ThaliTest[1423:2832909] Using UIWebView
,2016-09-01 11:13:51.484 ThaliTest[1423:2832909] [CDVTimer][handleopenurl] 0.464976ms
,2016-09-01 11:13:51.492 ThaliTest[1423:2832909] [CDVTimer][intentandnavigationfilter] 7.862985ms
2016-09-01 11:13:51.493 ThaliTest[1423:2832909] [CDVTimer][gesturehandler] 0.381947ms
2016-09-01 11:13:51.494 ThaliTest[1423:2832909] [CDVTimer][TotalPluginS,tartup] 10.652959ms
,2016-09-01 11:13:57.332 ThaliTest[1423:2832909] Resetting plugins due to page load.
,2016-09-01 11:14:00.229 ThaliTest[1423:2832909] Finished load of: file:///var/mobile/Containers/Bundle/Application/8196790E-71C4-4585-8B72-26F7427988D9/ThaliTest.app/www/index.html
,2016-09-01 11:14:00.404 ThaliTest[1423:2832909] JXcore Cordova plugin initializing
,2016-09-01 11:14:00.404 ThaliTest[1423:2833162] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-01 11:14:08.529 ThaliTest[1423:2833162] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-01 11:14:08.529 ThaliTest[1423:2833162] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-01 11:14:08.530 ThaliTest[1423:2833162] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-01 11:14:08.533 ThaliTest[1423:2833162] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-01 11:14:08.920 ThaliTest[1423:2833162] jxcore: executeNativeTests: success
,*Native tests were executed*
,Total number of executed tests:  2
,Number of passed tests:  2
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  0.005464017391204834
,****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
