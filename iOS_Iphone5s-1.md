#### Test 75789268514fc25_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/75789268514fc25/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,(lldb) command source -s 0 '/tmp/232AD6BA-6802-47A2-B82A-F450DF413F9F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/232AD6BA-6802-47A2-B82A-F450DF413F9F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/75789268514fc25/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/75789268514fc25/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/30489AD2-B77D-4DDA-B901-575A9F09A04B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53104"
,(lldb)     command script import "/tmp/232AD6BA-6802-47A2-B82A-F450DF413F9F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-07-15 15:19:14.714 ThaliTest[353:412769] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DEA9E4F4-B013-4AE9-AFFA-301E85873F7A/Library/Cookies/Cookies.binarycookies
,2016-07-15 15:19:15.106 ThaliTest[353:412769] Apache Cordova native platform version 4.1.1 is starting.
,2016-07-15 15:19:15.107 ThaliTest[353:412769] Multi-tasking -> Device: YES, App: YES
,2016-07-15 15:19:15.129 ThaliTest[353:412769] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-07-15 15:19:16.916 ThaliTest[353:412769] Using UIWebView
,2016-07-15 15:19:16.924 ThaliTest[353:412769] [CDVTimer][handleopenurl] 0.657976ms
,2016-07-15 15:19:16.933 ThaliTest[353:412769] [CDVTimer][intentandnavigationfilter] 8.598983ms
2016-07-15 15:19:16.934 ThaliTest[353:412769] [CDVTimer][gesturehandler] 0.427961ms
2016-07-15 15:19:16.934 ThaliTest[353:412769] [CDVTimer][TotalPluginStartup,] 11.534989ms
,2016-07-15 15:19:24.359 ThaliTest[353:412769] Resetting plugins due to page load.
,2016-07-15 15:19:28.406 ThaliTest[353:412769] Finished load of: file:///var/mobile/Containers/Bundle/Application/30489AD2-B77D-4DDA-B901-575A9F09A04B/ThaliTest.app/www/index.html
,2016-07-15 15:19:28.651 ThaliTest[353:412769] JXcore Cordova plugin initializing
,2016-07-15 15:19:28.652 ThaliTest[353:412988] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-07-15 15:19:37.729 ThaliTest[353:412988] jxcore: didRegisterToNative peerAvailabilityChanged
2016-07-15 15:19:37.729 ThaliTest[353:412988] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-07-15 15:19:37.730 ThaliTest[353:412988] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-07-15 15:19:37.732 ThaliTest[353:412988] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-07-15 15:19:38.094 ThaliTest[353:412988] Native method ExecuteNativeTests not found.

```
