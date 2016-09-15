#### Test 83276082d331142_iOS_Iphone6-2 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6 (GSM) 'Iphone6-2' (7ed231f0829a4ace34162e6c18308bcd995bc25a) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'Iphone5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/14F7E6B6-04D6-4E36-97BF-148549245C4A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'
,Executing commands in '/tmp/14F7E6B6-04D6-4E36-97BF-148549245C4A/fruitstrap-lldb-prep-cmds-7ed231f0829a4ace34162e6c18308bcd995bc25a'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/9.3 (13E230)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/83276082d331142/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B47C51A8-E1FB-4C46-B5E7-6D7AAB665640/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49928"
,(lldb)     command script import "/tmp/14F7E6B6-04D6-4E36-97BF-148549245C4A/fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.py"
,(lldb)     command script add -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_7ed231f0829a4ace34162e6c18308bcd995bc25a.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-09-15 04:29:30.930 ThaliTest[824:875028] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/2E166BB4-C5B0-4AD5-81B5-82C2A217D615/Library/Cookies/Cookies.binarycookies
,2016-09-15 04:29:31.258 ThaliTest[824:875028] Apache Cordova native platform version 4.1.1 is starting.
,2016-09-15 04:29:31.260 ThaliTest[824:875028] Multi-tasking -> Device: YES, App: YES
,2016-09-15 04:29:31.285 ThaliTest[824:875028] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.a,pple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-09-15 04:29:31.808 ThaliTest[824:875028] Using UIWebView
,2016-09-15 04:29:31.814 ThaliTest[824:875028] [CDVTimer][handleopenurl] 0.398993ms
,2016-09-15 04:29:31.822 ThaliTest[824:875028] [CDVTimer][intentandnavigationfilter] 7.148981ms
2016-09-15 04:29:31.823 ThaliTest[824:875028] [CDVTimer][gesturehandler] 0.333011ms
2016-09-15 04:29:31.823 ThaliTest[824:875028] [CDVTimer][TotalPluginStartup] 9.361029ms
,2016-09-15 04:29:37.612 ThaliTest[824:875028] Resetting plugins due to page load.
,2016-09-15 04:29:38.070 ThaliTest[824:875028] Finished load of: file:///var/containers/Bundle/Application/B47C51A8-E1FB-4C46-B5E7-6D7AAB665640/ThaliTest.app/www/index.html
,2016-09-15 04:29:38.467 ThaliTest[824:875028] JXcore Cordova plugin initializing
2016-09-15 04:29:38.468 ThaliTest[824:875225] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2016-09-15 04:29:45.017 ThaliTest[824:875225] jxcore: didRegisterToNative peerAvailabilityChanged
,2016-09-15 04:29:45.018 ThaliTest[824:875225] jxcore: didRegisterToNative discoveryAdvertisingStateUpdateNonTCP
,2016-09-15 04:29:45.018 ThaliTest[824:875225] jxcore: didRegisterToNative networkChanged
,DEBUG thaliMobileNativeWrapper: networkChanged: {"wifi":"on","bluetoothLowEnergy":"off","cellular":"doNotCare","bluetooth":"on"}
,2016-09-15 04:29:45.020 ThaliTest[824:875225] jxcore: didRegisterToNative incomingConnectionToPortNumberFailed
,Unit Test app is loaded

```
