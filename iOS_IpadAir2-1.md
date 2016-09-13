#### Test 8362733795b1a33_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/FCC6E84C-BF63-4757-AD01-55449E0C1E5A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/FCC6E84C-BF63-4757-AD01-55449E0C1E5A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8362733795b1a33/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/C6E1FBAA-F3B0-4C02-B4E1-6AED5D4FB7C9/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64821"
,(lldb)     command script import "/tmp/FCC6E84C-BF63-4757-AD01-55449E0C1E5A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-13 16:07:57.451 ThaliTest[2230:4289887] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/0D92FCA6-FA19-4739-ACE5-5C74AE3B7AB2/Library/Cookies/Cookies.binarycookies
,2016-09-13 16:07:57.878 ThaliTest[2230:4289887] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-13 16:07:57.879 ThaliTest[2230:4289887] Multi-tasking -> Device: YES, App: YES
,2016-09-13 16:07:57.896 ThaliTest[2230:4289887] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-13 16:07:59.739 ThaliTest[2230:4289887] Using UIWebView
,2016-09-13 16:07:59.746 ThaliTest[2230:4289887] [CDVTimer][handleopenurl] 0.396013ms
,2016-09-13 16:07:59.753 ThaliTest[2230:4289887] [CDVTimer][intentandnavigationfilter] 6.947994ms
,2016-09-13 16:07:59.754 ThaliTest[2230:4289887] [CDVTimer][gesturehandler] 0.339985ms
2016-09-13 16:07:59.754 ThaliTest[2230:4289887] [CDVTimer][TotalPluginStartup] 9.591997ms
,2016-09-13 16:08:05.867 ThaliTest[2230:4289887] Resetting plugins due to page load.
,2016-09-13 16:08:09.489 ThaliTest[2230:4289887] Finished load of: file:///var/mobile/Containers/Bundle/Application/C6E1FBAA-F3B0-4C02-B4E1-6AED5D4FB7C9/ThaliTest.app/www/index.html
,2016-09-13 16:08:09.693 ThaliTest[2230:4289887] JXcore Cordova plugin initializing
,2016-09-13 16:08:09.693 ThaliTest[2230:4290130] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-13 16:08:15.818 ThaliTest[2230:4290130] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-13 16:08:15.819 ThaliTest[2230:4290130] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-13 16:08:15.819 ThaliTest[2230:4290130] jxcore: didRegisterToNative networkChanged
DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
2016-09-13 16:08:15.820 ThaliTest[2230:4290130] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
