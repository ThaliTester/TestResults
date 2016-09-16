#### Test 8504691131acdd6_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/37F82492-A82B-478B-95C6-A0DB132FF19B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/37F82492-A82B-478B-95C6-A0DB132FF19B/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/8504691131acdd6/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D7DEDA4D-A9AA-4D97-B3C4-04D3BCF5D43F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64743"
,(lldb)     command script import "/tmp/37F82492-A82B-478B-95C6-A0DB132FF19B/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-16 03:16:13.802 ThaliTest[930:987981] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/DEF7B4B3-9102-4515-90DE-9D7156A6DF81/Library/Cookies/Cookies.binarycookies
,2016-09-16 03:16:14.125 ThaliTest[930:987981] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-16 03:16:14.126 ThaliTest[930:987981] Multi-tasking -> Device: YES, App: YES
,2016-09-16 03:16:14.151 ThaliTest[930:987981] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-16 03:16:14.699 ThaliTest[930:987981] Using UIWebView
,2016-09-16 03:16:14.708 ThaliTest[930:987981] [CDVTimer][handleopenurl] 0.384986ms
,2016-09-16 03:16:14.716 ThaliTest[930:987981] [CDVTimer][intentandnavigationfilter] 7.058978ms
2016-09-16 03:16:14.716 ThaliTest[930:987981] [CDVTimer][gesturehandler] 0.316024ms
2016-09-16 03:16:14.717 ThaliTest[930:987981] [CDVTimer][TotalPluginStartup,] 9.454012ms
,2016-09-16 03:16:20.616 ThaliTest[930:987981] Resetting plugins due to page load.
,2016-09-16 03:16:21.084 ThaliTest[930:987981] Finished load of: file:///var/containers/Bundle/Application/D7DEDA4D-A9AA-4D97-B3C4-04D3BCF5D43F/ThaliTest.app/www/index.html
,2016-09-16 03:16:21.482 ThaliTest[930:987981] JXcore Cordova plugin initializing
,2016-09-16 03:16:21.482 ThaliTest[930:988164] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-16 03:16:27.993 ThaliTest[930:988164] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-16 03:16:27.993 ThaliTest[930:988164] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-16 03:16:27.994 ThaliTest[930:988164] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-16 03:16:27.996 ThaliTest[930:988164] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,2016-09-16 03:16:28.388 ThaliTest[930:988164] jxcore: executeNativeTests: success
*Native tests were executed*
Total number of executed tests:  2
Number of passed tests:  2
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  0.004,104018211364746
****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****

```
