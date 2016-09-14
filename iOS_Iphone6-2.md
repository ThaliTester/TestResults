#### Test 836273377282b4e_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/836273377282b4e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/189ED4D4-C49A-4DB9-8B7A-96E91B8394A9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/189ED4D4-C49A-4DB9-8B7A-96E91B8394A9/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/836273377282b4e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/836273377282b4e/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/BE766F0B-44A5-41D4-814A-0796291C0610/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56144"
,(lldb)     command script import "/tmp/189ED4D4-C49A-4DB9-8B7A-96E91B8394A9/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-14 08:59:05.238 ThaliTest[712:773716] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/5EB94A67-E203-4A7B-8230-808ED0B20703/Library/Cookies/Cookies.binarycookies
,2016-09-14 08:59:05.581 ThaliTest[712:773716] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-14 08:59:05.583 ThaliTest[712:773716] Multi-tasking -> Device: YES, App: YES
,2016-09-14 08:59:05.609 ThaliTest[712:773716] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-14 08:59:06.144 ThaliTest[712:773716] Using UIWebView
,2016-09-14 08:59:06.150 ThaliTest[712:773716] [CDVTimer][handleopenurl] 0.385046ms
,2016-09-14 08:59:06.158 ThaliTest[712:773716] [CDVTimer][intentandnavigationfilter] 7.620037ms
2016-09-14 08:59:06.159 ThaliTest[712:773716] [CDVTimer][gesturehandler] 0.294030ms
2016-09-14 08:59:06.159 ThaliTest[712:773716] [CDVTimer][TotalPluginStartup,] 9.750962ms
,2016-09-14 08:59:11.762 ThaliTest[712:773716] Resetting plugins due to page load.
,2016-09-14 08:59:12.232 ThaliTest[712:773716] Finished load of: file:///var/containers/Bundle/Application/BE766F0B-44A5-41D4-814A-0796291C0610/ThaliTest.app/www/index.html
,2016-09-14 08:59:12.632 ThaliTest[712:773716] JXcore Cordova plugin initializing
,2016-09-14 08:59:12.633 ThaliTest[712:773910] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-14 08:59:19.236 ThaliTest[712:773910] jxcore: didRegisterToNative peerAvailabilityChanged
2016-09-14 08:59:19.236 ThaliTest[712:773910] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
2016-09-14 08:59:19.237 ThaliTest[712:773910] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-14 08:59:19.239 ThaliTest[712:773910] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
