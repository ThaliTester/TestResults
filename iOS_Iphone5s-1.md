#### Test 83627337e0b549f_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/6F4F17B7-C5E2-4B75-98B7-0ABAAB94BDEF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6F4F17B7-C5E2-4B75-98B7-0ABAAB94BDEF/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337e0b549f/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/5DF80FA1-6894-4FD2-9F70-97DE74106F9F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57616"
,(lldb)     command script import "/tmp/6F4F17B7-C5E2-4B75-98B7-0ABAAB94BDEF/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 09:26:37.660 ThaliTest[2203:4701278] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/C286953C-CF1C-4485-ACDC-E0D8AB1BB9D3/Library/Cookies/Cookies.binarycookies
,2016-09-14 09:26:38.092 ThaliTest[2203:4701278] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 09:26:38.094 ThaliTest[2203:4701278] Multi-tasking -> Device: YES, App: YES
,2016-09-14 09:26:38.120 ThaliTest[2203:4701278] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 09:26:39.770 ThaliTest[2203:4701278] Using UIWebView
,2016-09-14 09:26:39.778 ThaliTest[2203:4701278] [CDVTimer][handleopenurl] 0.434995ms
,2016-09-14 09:26:39.787 ThaliTest[2203:4701278] [CDVTimer][intentandnavigationfilter] 8.226991ms
2016-09-14 09:26:39.788 ThaliTest[2203:4701278] [CDVTimer][gesturehandler] 0.397027ms
2016-09-14 09:26:39.788 ThaliTest[2203:4701278] [CDVTimer][TotalPluginS,tartup] 10.941982ms
,2016-09-14 09:26:46.287 ThaliTest[2203:4701278] Resetting plugins due to page load.
,2016-09-14 09:26:50.029 ThaliTest[2203:4701278] Finished load of: file:///var/mobile/Containers/Bundle/Application/5DF80FA1-6894-4FD2-9F70-97DE74106F9F/ThaliTest.app/www/index.html
,2016-09-14 09:26:50.272 ThaliTest[2203:4701278] JXcore Cordova plugin initializing
,2016-09-14 09:26:50.275 ThaliTest[2203:4701515] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 09:26:58.388 ThaliTest[2203:4701515] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-14 09:26:58.389 ThaliTest[2203:4701515] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 09:26:58.390 ThaliTest[2203:4701515] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 09:26:58.392 ThaliTest[2203:4701515] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
