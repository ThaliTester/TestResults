#### Test 83627337ae40023_iOS_Iphone5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/B65D62C4-E31C-453C-9DD8-9F75A413BC9A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/B65D62C4-E31C-453C-9DD8-9F75A413BC9A/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83627337ae40023/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/87168B69-051B-439F-ADD8-D8FB64F127A4/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55816"
,(lldb)     command script import "/tmp/B65D62C4-E31C-453C-9DD8-9F75A413BC9A/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 22:52:56.458 ThaliTest[2178:4633427] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/106170F4-CD4D-4A83-B98A-1EFF11DD82F9/Library/Cookies/Cookies.binarycookies
,2016-09-13 22:52:56.866 ThaliTest[2178:4633427] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 22:52:56.868 ThaliTest[2178:4633427] Multi-tasking -> Device: YES, App: YES
,2016-09-13 22:52:56.893 ThaliTest[2178:4633427] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer,.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 22:52:58.648 ThaliTest[2178:4633427] Using UIWebView
,2016-09-13 22:52:58.656 ThaliTest[2178:4633427] [CDVTimer][handleopenurl] 0.788033ms
,2016-09-13 22:52:58.665 ThaliTest[2178:4633427] [CDVTimer][intentandnavigationfilter] 8.109987ms
2016-09-13 22:52:58.666 ThaliTest[2178:4633427] [CDVTimer][gesturehandler] 0.443995ms
2016-09-13 22:52:58.666 ThaliTest[2178:4633427] [CDVTimer][TotalPluginS,tartup] 11.188030ms
,2016-09-13 22:53:05.640 ThaliTest[2178:4633427] Resetting plugins due to page load.
,2016-09-13 22:53:09.048 ThaliTest[2178:4633427] Finished load of: file:///var/mobile/Containers/Bundle/Application/87168B69-051B-439F-ADD8-D8FB64F127A4/ThaliTest.app/www/index.html
,2016-09-13 22:53:09.297 ThaliTest[2178:4633427] JXcore Cordova plugin initializing
,2016-09-13 22:53:09.298 ThaliTest[2178:4633661] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 22:53:17.413 ThaliTest[2178:4633661] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-13 22:53:17.414 ThaliTest[2178:4633661] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 22:53:17.415 ThaliTest[2178:4633661] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-13 22:53:17.417 ThaliTest[2178:4633661] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
