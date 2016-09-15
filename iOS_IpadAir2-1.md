#### Test 83276082e94149a_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/CE170500-ED3B-48FE-8007-15ED3624CEEE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CE170500-ED3B-48FE-8007-15ED3624CEEE/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082e94149a/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/6BF320CD-64EC-438C-AD59-7206D8FA749B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57738"
,(lldb)     command script import "/tmp/CE170500-ED3B-48FE-8007-15ED3624CEEE/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 15:32:54.950 ThaliTest[2463:4554800] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/01EB3107-6EDA-48F0-9E37-AB6A3BD111DD/Library/Cookies/Cookies.binarycookies
,2016-09-15 15:32:55.235 ThaliTest[2463:4554800] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 15:32:55.236 ThaliTest[2463:4554800] Multi-tasking -> Device: YES, App: YES
,2016-09-15 15:32:55.251 ThaliTest[2463:4554800] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 15:32:57.117 ThaliTest[2463:4554800] Using UIWebView
,2016-09-15 15:32:57.124 ThaliTest[2463:4554800] [CDVTimer][handleopenurl] 0.370026ms
,2016-09-15 15:32:57.131 ThaliTest[2463:4554800] [CDVTimer][intentandnavigationfilter] 6.567001ms
,2016-09-15 15:32:57.132 ThaliTest[2463:4554800] [CDVTimer][gesturehandler] 0.317991ms
,2016-09-15 15:32:57.132 ThaliTest[2463:4554800] [CDVTimer][TotalPluginStartup] 8.780003ms
,2016-09-15 15:33:05.289 ThaliTest[2463:4554800] Resetting plugins due to page load.
,2016-09-15 15:33:09.739 ThaliTest[2463:4554800] Finished load of: file:///var/mobile/Containers/Bundle/Application/6BF320CD-64EC-438C-AD59-7206D8FA749B/ThaliTest.app/www/index.html
,2016-09-15 15:33:09.928 ThaliTest[2463:4554800] JXcore Cordova plugin initializing
,2016-09-15 15:33:09.929 ThaliTest[2463:4555083] JXcore instance initializing
,Initializing JXcore engine
,JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm
,JXcore Cordova bridge is ready!
JXcore engine is started
,2016-09-15 15:33:16.112 ThaliTest[2463:4555083] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-15 15:33:16.112 ThaliTest[2463:4555083] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-15 15:33:16.113 ThaliTest[2463:4555083] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"off"}
,2016-09-15 15:33:16.114 ThaliTest[2463:4555083] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
