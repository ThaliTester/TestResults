#### Test 83276082e94149a_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/3A5D937B-EDC6-43CF-8F7C-8CC3D058494F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/3A5D937B-EDC6-43CF-8F7C-8CC3D058494F/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/B1D27939-9139-4BEF-A043-65218382ED42/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57739"
,(lldb)     command script import "/tmp/3A5D937B-EDC6-43CF-8F7C-8CC3D058494F/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 15:32:50.045 ThaliTest[2372:4902284] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C5ED670E-115E-49D9-9833-05139892978C/Library/Cookies/Cookies.binarycookies
,2016-09-15 15:32:50.481 ThaliTest[2372:4902284] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 15:32:50.482 ThaliTest[2372:4902284] Multi-tasking -> Device: YES, App: YES
,2016-09-15 15:32:50.503 ThaliTest[2372:4902284] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 15:32:52.116 ThaliTest[2372:4902284] Using UIWebView
,2016-09-15 15:32:52.124 ThaliTest[2372:4902284] [CDVTimer][handleopenurl] 0.487983ms
,2016-09-15 15:32:52.133 ThaliTest[2372:4902284] [CDVTimer][intentandnavigationfilter] 8.102000ms
2016-09-15 15:32:52.134 ThaliTest[2372:4902284] [CDVTimer][gesturehandler] 0.366986ms
2016-09-15 15:32:52.134 ThaliTest[2372:4902284] [CDVTimer][TotalPluginS,tartup] 10.730028ms
,2016-09-15 15:32:58.860 ThaliTest[2372:4902284] Resetting plugins due to page load.
,2016-09-15 15:33:02.276 ThaliTest[2372:4902284] Finished load of: file:///var/mobile/Containers/Bundle/Application/B1D27939-9139-4BEF-A043-65218382ED42/ThaliTest.app/www/index.html
,2016-09-15 15:33:02.464 ThaliTest[2372:4902284] JXcore Cordova plugin initializing
,2016-09-15 15:33:02.465 ThaliTest[2372:4902566] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 15:33:10.588 ThaliTest[2372:4902566] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 15:33:10.588 ThaliTest[2372:4902566] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 15:33:10.589 ThaliTest[2372:4,902566] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 15:33:10.592 ThaliTest[2372:4902566] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
