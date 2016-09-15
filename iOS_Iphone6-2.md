#### Test 83276082e94149a_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4673DF46-3EFC-41C9-905B-3304613388E0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/4673DF46-3EFC-41C9-905B-3304613388E0/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/382ED1AF-E27B-466F-A599-B951224A9920/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57735"
,(lldb)     command script import "/tmp/4673DF46-3EFC-41C9-905B-3304613388E0/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 06:32:47.798 ThaliTest[853:887765] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/B3DB25F2-62F2-46E7-A8C3-A6DD32AE136E/Library/Cookies/Cookies.binarycookies
,2016-09-15 06:32:48.096 ThaliTest[853:887765] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 06:32:48.097 ThaliTest[853:887765] Multi-tasking -> Device: YES, App: YES
,2016-09-15 06:32:48.123 ThaliTest[853:887765] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 06:32:48.642 ThaliTest[853:887765] Using UIWebView
,2016-09-15 06:32:48.653 ThaliTest[853:887765] [CDVTimer][handleopenurl] 0.376999ms
,2016-09-15 06:32:48.661 ThaliTest[853:887765] [CDVTimer][intentandnavigationfilter] 7.174969ms
2016-09-15 06:32:48.662 ThaliTest[853:887765] [CDVTimer][gesturehandler] 0.355005ms
2016-09-15 06:32:48.662 ThaliTest[853:887765] [CDVTimer][TotalPluginStartup] 9.522021ms
,2016-09-15 06:32:54.455 ThaliTest[853:887765] Resetting plugins due to page load.
,2016-09-15 06:32:54.975 ThaliTest[853:887765] Finished load of: file:///var/containers/Bundle/Application/382ED1AF-E27B-466F-A599-B951224A9920/ThaliTest.app/www/index.html
,2016-09-15 06:32:55.371 ThaliTest[853:887765] JXcore Cordova plugin initializing
,2016-09-15 06:32:55.372 ThaliTest[853:887951] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 06:33:01.917 ThaliTest[853:887951] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-15 06:33:01.918 ThaliTest[853:887951] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 06:33:01.918 ThaliTest[853:887951] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 06:33:01.920 ThaliTest[853:887951] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
